# YOLOv8s 350-Epoch 1280px Image Size Balanced Ultralytics Model

Performance details and links for the YOLOv8s model trained for 350 epochs with an increased image size of 1280px on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolov8s-350-epoch.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | Image Size | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 350 | 1280 | 68.8% | 45.9% | 75.1% | 68.3% | Platform Run |

### Training Configuration

*   **Device**: `1`
*   **Base Model**: `ul://ultralytics/yolov8/yolov8s`
*   **Dataset Configuration**: `ul://paranitharan002/datasets/pothole-detection-merged-balanced-dataset`
*   **Project**: `paranitharan002/pothole-detection`
*   **Run Name**: `350-epoch`
*   **Task**: `detect`
*   **Epochs**: `350`
*   **Batch Size**: `16`
*   **Image Size (imgsz)**: `1280`

