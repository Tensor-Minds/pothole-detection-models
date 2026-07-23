# YOLOv8m Balanced Ultralytics Model

Performance details and links for the YOLOv8m (YOLOv8 Medium) model trained for 75 epochs on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolov8m.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | Image Size | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 75 | 640 | 66.9% | 43.5% | 70.7% | 69.2% | Platform Run |

### Training Configuration

*   **Device**: `1`
*   **Base Model**: `ul://ultralytics/yolov8/yolov8m`
*   **Dataset Configuration**: `ul://paranietharan-palasuntharam-4/datasets/pothole-detection-merged-balanced-dataset`
*   **Project**: `paranietharan-palasuntharam-4/example-project`
*   **Run Name**: `yolov8m`
*   **Task**: `detect`
*   **Epochs**: `75`
*   **Batch Size**: `-1`
*   **Image Size (imgsz)**: `640`

