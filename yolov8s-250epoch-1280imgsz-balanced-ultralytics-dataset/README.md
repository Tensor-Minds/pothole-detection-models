# YOLOv8s 250-Epoch 1280px Image Size Balanced Ultralytics Model

Performance details and links for the YOLOv8s model trained for 250 epochs with an increased image size of 1280px on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolov8s-250-epoch.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | Image Size | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 250 | 1280 | 68.9% | 45.0% | 73.9% | 68.8% | Platform Run |

### Training Configuration

*   **Device**: `5`
*   **Base Model**: `ul://ultralytics/yolov8/yolov8s`
*   **Dataset Configuration**: `ul://paranitharan002/datasets/pothole-detection-merged-balanced-dataset`
*   **Project**: `paranitharan002/pothole-detection`
*   **Run Name**: `yolov8s-250-epoch-3`
*   **Task**: `detect`
*   **Epochs**: `250`
*   **Batch Size**: `16`
*   **Image Size (imgsz)**: `1280`

