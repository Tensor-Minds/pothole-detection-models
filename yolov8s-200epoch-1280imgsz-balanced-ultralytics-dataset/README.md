# YOLOv8s 200-Epoch 1280px Image Size Balanced Ultralytics Model

Performance details and links for the YOLOv8s model trained for 200 epochs with an increased image size of 1280px on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolov8s-200-epoch.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | Image Size | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 200 | 1280 | 68.2% | 43.0% | 71.1% | 69.0% | Platform Run |

### Training Configuration

*   **Device**: `3`
*   **Base Model**: `ul://ultralytics/yolov8/yolov8s`
*   **Dataset Configuration**: `ul://paranitharan002/datasets/pothole-detection-merged-balanced-dataset`
*   **Project**: `paranitharan002/pothole-detection`
*   **Run Name**: `yolov8s-200`
*   **Task**: `detect`
*   **Epochs**: `200`
*   **Batch Size**: `8`
*   **Image Size (imgsz)**: `1280`

