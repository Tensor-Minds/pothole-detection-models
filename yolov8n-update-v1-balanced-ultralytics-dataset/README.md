# YOLOv8n Update v1 Balanced Ultralytics Model

Performance details and links for the YOLOv8n-update-v1 model trained on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolov8n-update-v1.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset-2`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :--- |
| 100 | 60.5% | 34.6% | 63.4% | 62.2% | Platform Run |

### Training Configuration

*   **Device**: `3`
*   **Base Model**: `ul://ultralytics/yolov8/yolov8n`
*   **Dataset Configuration**: `ul://paranietharan-palasuntharam-2/datasets/pothole-detection-merged-balanced-dataset`
*   **Project**: `paranietharan-palasuntharam-2/pothole-detection`
*   **Run Name**: `yolov8n-update-v1`
*   **Task**: `detect`
*   **Box Loss Weight**: `8`
*   **HSV-V Augmentation**: `0.5`
*   **Mixup Augmentation**: `0.05`
*   **Epochs**: `100`
*   **Batch Size**: `-1`
*   **Image Size (imgsz)**: `800`
*   **Early Stopping Patience**: `30`
*   **Cosine LR**: `True`

