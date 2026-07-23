# YOLOv26n 150-Epoch 1280px Image Size Balanced Ultralytics Model

Performance details and links for the YOLOv26n (YOLOv26 Nano) model trained for 150 epochs with an increased image size of 1280px on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolov26n-150epoch.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | Image Size | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 150 | 1280 | 64.3% | 37.3% | 66.5% | 65.4% | Platform Run |

### Training Configuration

*   **Base Model**: `ul://ultralytics/yolo26/yolo26n`
*   **Dataset Configuration**: `ul://paranitharan002/datasets/pothole-detection-merged-balanced-dataset`
*   **Task**: `detect`
*   **Epochs**: `150`
*   **Batch Size**: `-1`
*   **Image Size (imgsz)**: `1280`
*   **Project**: `paranitharan002/pothole-detection`
*   **Run Name**: `yolov26n-150epoch`
*   **Device**: `0`

