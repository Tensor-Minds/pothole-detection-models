# YOLO11n 50-Epoch Balanced Ultralytics Model

Performance details and links for the YOLO11n (YOLO11 Nano) model trained for 50 epochs on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolo11n-50epoch.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | Image Size | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 50 | 640 | 57.3% | 32.2% | 60.6% | 59.8% | Platform Run |

### Training Configuration

*   **Device**: `0`
*   **Base Model**: `ul://ultralytics/yolo11/yolo11n`
*   **Dataset Configuration**: `ul://paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset`
*   **Project**: `paranietharan-palasuntharam/pothole-detection`
*   **Run Name**: `volov11n-50epoch`
*   **Task**: `detect`
*   **Epochs**: `50`
*   **Batch Size**: `-1`
*   **Image Size (imgsz)**: `640`

