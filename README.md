# Pothole Detection Models

Here is a summary of the datasets, model weights files, and key performance metrics for the models in this repository.

### Datasets Used for Research
1.  **Balanced Ultralytics Hub Dataset** (`pothole-detection-merged-balanced-dataset-2`):
    - [Ultralytics Hub Dataset Link](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)
2.  **RDD-2022 Dataset**:
    - [Kaggle RDD-2022 Dataset Link](https://www.kaggle.com/datasets/aliabdelmenam/rdd-2022)
3.  **Custom Google Drive Dataset**:
    - [Google Drive Dataset Link](https://drive.google.com/file/d/1b1kpXADga39fd784VJLoHtXUFZFIIKQ5/view?usp=share_link)

### Performance Metrics Comparison

---

### 1. Balanced Ultralytics Hub Dataset Models
This section lists models trained on the **Balanced Ultralytics Hub Dataset** (`pothole-detection-merged-balanced-dataset`).

#### YOLOv8 Nano (YOLOv8n) Models

| Folder Name | Weights File | Epochs | mAP50 | mAP50-95 | Precision | Recall | Model/Hub Link |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| `yolov8n-300epoch-1280imgsz-balanced-ultralytics-dataset` | `yolov8n-300epoch.pt` | 300 (1280px) | **64.0%** | **37.4%** | **66.4%** | **65.5%** | [Ultralytics Hub](https://platform.ultralytics.com/palasuntharam-ponnampalam/example-project/yolov8n-300epoch) |
| `yolov8n-250epoch-1280imgsz-balanced-ultralytics-dataset` | `yolov8n-250-epoch.pt` | 250 (1280px) | 63.9% | 36.3% | 65.9% | 65.4% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam-2/pothole-detection/yolov8n-250-epoch) |
| `yolov8n-train-with-200-epoch` | `yolov8n-train-with-200-epoch.pt` | 200 (1280px) | 63.0% | 35.5% | 64.7% | 65.1% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam-2/pothole-detection/train-with-200-epoch) |
| `yolov8n-update-v1-balanced-ultralytics-dataset` | `yolov8n-update-v1.pt` | 100 | 60.5% | 34.6% | 63.4% | 62.2% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam-2/pothole-detection/yolov8n-update-v1) |
| `yolov8n-balanced-ultralytics-dataset` | `exp-2.pt` | 100 | 59.4% | 34.1% | 63.4% | 61.2% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam/pothole-detection/exp-2) |

#### YOLOv8 Small (YOLOv8s) Models

| Folder Name | Weights File | Epochs | mAP50 | mAP50-95 | Precision | Recall | Model/Hub Link |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| `yolov8s-250epoch-1280imgsz-balanced-ultralytics-dataset` | `yolov8s-250-epoch.pt` | 250 (1280px) | **68.9%** | 45.0% | 73.9% | 68.8% | [Ultralytics Hub](https://platform.ultralytics.com/paranitharan002/pothole-detection/yolov8s-250-epoch-3) |
| `yolov8s-350epoch-1280imgsz-balanced-ultralytics-dataset` | `yolov8s-350-epoch.pt` | 350 (1280px) | 68.8% | **45.9%** | **75.1%** | 68.3% | [Ultralytics Hub](https://platform.ultralytics.com/paranitharan002/pothole-detection/350-epoch) |
| `yolov8s-200epoch-1280imgsz-balanced-ultralytics-dataset` | `yolov8s-200-epoch.pt` | 200 (1280px) | 68.2% | 43.0% | 71.1% | **69.0%** | [Ultralytics Hub](https://platform.ultralytics.com/paranitharan002/pothole-detection/yolov8s-200) |
| `yolov8s-100epoch-balanced-ultralytics-dataset` | `yolov8s.pt` | 100 | 66.4% | 39.4% | 68.0% | 68.1% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam-2/pothole-detection/yolov8s) |
| `yolov8s-balanced-ultralytics-dataset` | `exp.pt` | 50 | 62.4% | 36.6% | 63.9% | 66.0% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam/pothole-detection/exp) |
| `yolov8s-960imgsz-balanced-ultralytics-dataset` | `exp.pt` | 100 (960px) | 51.5% | 27.6% | 56.9% | 53.2% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam-2/pothole-detection/exp) |

#### YOLOv8 Medium (YOLOv8m) Models

| Folder Name | Weights File | Epochs | mAP50 | mAP50-95 | Precision | Recall | Model/Hub Link |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| `yolov8m-balanced-ultralytics-dataset` | `yolov8m.pt` | 75 | **66.9%** | **43.5%** | **70.7%** | **69.2%** | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam-4/example-project/yolov8m) |

#### YOLO11 Nano (YOLO11n) Models

| Folder Name | Weights File | Epochs | mAP50 | mAP50-95 | Precision | Recall | Model/Hub Link |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| `yolo11n-50epoch-balanced-ultralytics-dataset` | `yolo11n-50epoch.pt` | 50 | **57.3%** | **32.2%** | **60.6%** | **59.8%** | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam/pothole-detection/volov11n-50epoch) |

#### YOLOv26 Nano (YOLOv26n) Models

| Folder Name | Weights File | Epochs | mAP50 | mAP50-95 | Precision | Recall | Model/Hub Link |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| `yolov26n-150epoch-1280imgsz-balanced-ultralytics-dataset` | `yolov26n-150epoch.pt` | 150 (1280px) | **64.3%** | **37.3%** | **66.5%** | **65.4%** | [Ultralytics Hub](https://platform.ultralytics.com/paranitharan002/pothole-detection/yolov26n-150epoch) |
| `yolov26n-balanced-ultralytics-dataset` | `yolo26n-training.pt` | 100 | 58.9% | 34.3% | 64.1% | 59.8% | [Ultralytics Hub](https://platform.ultralytics.com/paranietharan-palasuntharam/pothole-detection/yolo26n-training) |

#### YOLOv26 Small (YOLOv26s) Models

| Folder Name | Weights File | Epochs | mAP50 | mAP50-95 | Precision | Recall | Model/Hub Link |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| `yolov26s-balanced-ultralytics-dataset` | `yolov26s.pt` | 100 | **65.1%** | **41.1%** | **70.0%** | **67.3%** | [Ultralytics Hub](https://platform.ultralytics.com/ankayatchchelvi-palasuntharam/test-yolo-training/yolov26s) |

---

### 2. RDD-2022 (Kaggle) Dataset Models
This section lists models trained exclusively on the **RDD-2022 Dataset** (Kaggle).

#### YOLOv8 Nano (YOLOv8n) Models

| Folder Name | Weights File | Epochs | mAP50 | mAP50-95 | Precision | Recall | Model/Hub Link |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| `yolov8n-kaggle-RDD2022` | `models/best.pt` | 50 | **60.2%** | **33.1%** | **65.0%** | **56.1%** | Local Run |

#### YOLOv8 Small (YOLOv8s) Models

| Folder Name | Weights File | Epochs | mAP50 | mAP50-95 | Precision | Recall | Model/Hub Link |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| `yolov8s-kaggle-RDD2022` | `models/best.pt` | 50 | **64.3%** | **35.9%** | **66.5%** | **59.9%** | Local Run |

---

### 3. RDD-2022 + Custom Google Drive Dataset Models
This section lists models trained on the combined **RDD-2022 and Custom Google Drive datasets**.

#### YOLOv8 Small (YOLOv8s) Models

| Folder Name | Weights File | Epochs | mAP50 | mAP50-95 | Precision | Recall | Model/Hub Link |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| `yolov8s-kaggle-RDD2022-and-drive-data` | `models/best.pt` | 50 | **64.0%** | **35.4%** | **69.2%** | **58.8%** | Local Run |

---

## Documenting Rules

To ensure consistency and ease of tracking for research, any new model training runs or model updates **MUST** follow these documentation rules:

1. **Update Root `README.md`**:
   - Locate the correct dataset section under the **Performance Metrics Comparison** (either **Balanced Ultralytics Hub Dataset Models**, **RDD-2022 (Kaggle) Dataset Models**, or **RDD-2022 + Custom Google Drive Dataset Models**).
   - Add/update the model run in the appropriate table matching the model scale/version (e.g. YOLOv8 Nano, YOLOv8 Small, YOLOv8 Medium, YOLO11 Nano, YOLOv26 Nano, or YOLOv26 Small) under that dataset section.
   - **Order the models from best to worst** within each table based on their `mAP50` metric (with `mAP50-95` as a tiebreaker).
   - Include the correct folder name and the exact model weights file name (e.g., `exp.pt` or `models/best.pt`).
   - If a new dataset is introduced, document its name and link in the **Datasets Used for Research** section.

2. **Update Subfolder `Readme.md`**:
   - The directory-specific `Readme.md` file (e.g., `yolov8s-kaggle-RDD2022/Readme.md`) must be kept synchronized with the root file.
   - Detail the specific model weights file, the dataset details, and the local performance metrics table inside that folder's `Readme.md`.

3. **Validate Metric Accuracies**:
   - Ensure the metrics (mAP50, mAP50-95, Precision, Recall) match the final validation epochs from the training logs or the Ultralytics Hub platform.
   - Verify that all external dataset and model links are correct and accessible.