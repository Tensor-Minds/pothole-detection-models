# Pothole Detection Models

Here is a summary of the datasets, model weights files, and key performance metrics for the models in this repository.

### Datasets Used for Research
1.  **Balanced Ultralytics Hub Dataset** (`pothole-detection-merged-balanced-dataset-2`):
    - [Ultralytics Hub Dataset Link](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset-2)
2.  **RDD-2022 Dataset**:
    - [Kaggle RDD-2022 Dataset Link](https://www.kaggle.com/datasets/aliabdelmenam/rdd-2022)
3.  **Custom Google Drive Dataset**:
    - [Google Drive Dataset Link](https://drive.google.com/file/d/1b1kpXADga39fd784VJLoHtXUFZFIIKQ5/view?usp=share_link)

### Performance Metrics Comparison

#### YOLOv8 Nano (YOLOv8n) Models

| Folder Name | Weights File | Dataset | Epochs | mAP50 | mAP50-95 | Precision | Recall | Model/Hub Link |
| :--- | :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| `yolov8n-balanced-ultralytics-dataset` | `exp-2.pt` | Balanced Hub Dataset | 100 | 59.4% | 34.1% | 63.4% | 61.2% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam/pothole-detection/exp-2) |
| `yolov8n-kaggle-RDD2022` | `models/best.pt` | RDD-2022 (Kaggle) | 50 | 60.2% | 33.1% | **65.0%** | 56.1% | Local Run |
| `yolov8n-update-v1-balanced-ultralytics-dataset` | `yolov8n-update-v1.pt` | Balanced Hub Dataset | 100 | 60.5% | 34.6% | 63.4% | 62.2% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam-2/pothole-detection/yolov8n-update-v1) |
| `yolov8n-train-with-200-epoch` | `yolov8n-train-with-200-epoch.pt` | Balanced Hub Dataset | 200 (1280px) | **63.0%** | **35.5%** | 64.7% | **65.1%** | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam-2/pothole-detection/train-with-200-epoch) |

#### YOLOv8 Small (YOLOv8s) Models

| Folder Name | Weights File | Dataset | Epochs | mAP50 | mAP50-95 | Precision | Recall | Model/Hub Link |
| :--- | :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| `yolov8s-balanced-ultralytics-dataset` | `exp.pt` | Balanced Hub Dataset | 50 | 62.4% | 36.6% | 63.9% | 66.0% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam/pothole-detection/exp) |
| `yolov8s-kaggle-RDD2022` | `models/best.pt` | RDD-2022 (Kaggle) | 50 | 64.3% | 35.9% | 66.5% | 59.9% | Local Run |
| `yolov8s-kaggle-RDD2022-and-drive-data` | `models/best.pt` | RDD-2022 + Drive | 50 | 64.0% | 35.4% | 69.2% | 58.8% | Local Run |
| `yolov8s-100epoch-balanced-ultralytics-dataset` | `yolov8s.pt` | Balanced Hub Dataset | 100 | **66.4%** | **39.4%** | **68.0%** | **68.1%** | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam-2/pothole-detection/yolov8s) |
| `yolov8s-960imgsz-balanced-ultralytics-dataset` | `exp.pt` | Balanced Hub Dataset | 100 (960px) | 51.5% | 27.6% | 56.9% | 53.2% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam-2/pothole-detection/exp) |

#### YOLOv26 Models

| Folder Name | Weights File | Dataset | Epochs | mAP50 | mAP50-95 | Precision | Recall | Model/Hub Link |
| :--- | :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| `yolov26n-balanced-ultralytics-dataset` | `yolo26n-training.pt` | Balanced Hub Dataset | 100 | 58.9% | 34.3% | 64.1% | 59.8% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam/pothole-detection/yolo26n-training) |

---

## Documenting Rules

To ensure consistency and ease of tracking for research, any new model training runs or model updates **MUST** follow these documentation rules:

1. **Update Root `README.md`**:
   - Any new models, modified epochs, or updated metrics must be added/updated in the appropriate table under the **Performance Metrics Comparison** section above (either the **YOLOv8 Nano**, **YOLOv8 Small**, or **YOLOv26** table, depending on the model type).
   - Include the correct folder name and the exact model weights file name (e.g., `exp.pt` or `models/best.pt`).
   - If a new dataset is introduced, document its name and link in the **Datasets Used for Research** section.

2. **Update Subfolder `Readme.md`**:
   - The directory-specific `Readme.md` file (e.g., `yolov8s-kaggle-RDD2022/Readme.md`) must be kept synchronized with the root file.
   - Detail the specific model weights file, the dataset details, and the local performance metrics table inside that folder's `Readme.md`.

3. **Validate Metric Accuracies**:
   - Ensure the metrics (mAP50, mAP50-95, Precision, Recall) match the final validation epochs from the training logs or the Ultralytics Hub platform.
   - Verify that all external dataset and model links are correct and accessible.