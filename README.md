# Pothole Detection Models

Here is a summary of the dataset links, weights files, and key performance metrics for the models in this repository.

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset-2`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset-2)

### Performance Metrics Comparison

| Model | Weights File | Epochs | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| **YOLOv8n** (`yolov8n-balanced-kaggle-dataset`) | `exp-2.pt` | 100 | 59.4% | 34.1% | 63.4% | 61.2% | [Ultralytics Hub Link](https://platform.ultralytics.com/paranietharan-palasuntharam/pothole-detection/exp-2) |
| **YOLOv8s** (`yolov8s-balanced-kaggle-dataset`) | `exp.pt` | 50 | **62.4%** | **36.6%** | **63.9%** | **66.0%** | [Ultralytics Hub Link](https://platform.ultralytics.com/paranietharan-palasuntharam/pothole-detection/exp) |

---

## Documenting Rules

To ensure consistency and ease of tracking for research, any new model training runs or model updates **MUST** follow these documentation rules:

1. **Update Root `README.md`**:
   - Any new models, modified epochs, or updated metrics must be added/updated in the **Performance Metrics Comparison** table above.
   - Include the exact model weights file name (e.g., `*.pt`).

2. **Update Subfolder `Readme.md`**:
   - The directory-specific `Readme.md` file (e.g., `yolov8n-balanced-kaggle-dataset/Readme.md`) must be kept synchronized with the root file.
   - Detail the specific model weights file, the dataset details, and the local performance metrics table inside that folder's `Readme.md`.

3. **Validate Metric Accuracies**:
   - Ensure the metrics (mAP50, mAP50-95, Precision, Recall) match the final validation epochs on the Ultralytics Hub platform.
   - Verify that the Hub download links are correct and accessible.