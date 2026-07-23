# YOLOv26s 100-Epoch Balanced Ultralytics Model

Performance details and links for the YOLOv26s (YOLOv26 Small) model trained for 100 epochs on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolov26s-100epoch.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | Image Size | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 100 | 640 | 64.9% | 40.7% | 69.2% | 67.7% | Platform Run |

### Training Configuration

*   **Base Model**: `ul://ultralytics/yolo26/yolo26s`
*   **Dataset Configuration**: `ul://paranietharan-palasuntharam-4/datasets/pothole-detection-merged-balanced-dataset`
*   **Task**: `detect`
*   **Epochs**: `100`
*   **Batch Size**: `-1`
*   **Image Size (imgsz)**: `640`
*   **Project**: `paranietharan-palasuntharam-4/example-project`
*   **Run Name**: `yolo26s-100-epoch`
*   **Device**: `0`

