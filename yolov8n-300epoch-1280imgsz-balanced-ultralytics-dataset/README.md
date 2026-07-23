# YOLOv8n 300-Epoch 1280px Image Size Balanced Ultralytics Model

Performance details and links for the YOLOv8n (YOLOv8 Nano) model trained for 300 epochs with an increased image size of 1280px on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolov8n-300epoch.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | Image Size | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 300 | 1280 | 64.0% | 37.4% | 66.4% | 65.5% | Platform Run |

### Training Configuration

*   **Device**: `6`
*   **Base Model**: `ul://ultralytics/yolov8/yolov8n`
*   **Dataset Configuration**: `ul://palasuntharam-ponnampalam/datasets/pothole-detection-merged-balanced-dataset`
*   **Project**: `palasuntharam-ponnampalam/example-project`
*   **Run Name**: `yolov8n-300epoch`
*   **Task**: `detect`
*   **Epochs**: `300`
*   **Batch Size**: `-1`
*   **Image Size (imgsz)**: `1280`

