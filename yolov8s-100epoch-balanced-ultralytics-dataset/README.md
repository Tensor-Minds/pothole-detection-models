# YOLOv8s 100-Epoch Balanced Ultralytics Model

Performance details and links for the YOLOv8s model trained for 100 epochs on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolov8s.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset-2`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :--- |
| 100 | 66.4% | 39.4% | 68.0% | 68.1% | Platform Run |

### Training Configuration

*   **Base Model**: `ul://ultralytics/yolov8/yolov8s`
*   **Dataset Configuration**: `ul://paranietharan-palasuntharam-2/datasets/pothole-detection-merged-balanced-dataset`
*   **Task**: `detect`
*   **Epochs**: `100`
*   **Batch Size**: `16`
*   **Image Size (imgsz)**: `1280`
*   **Project**: `paranietharan-palasuntharam-2/pothole-detection`
*   **Run Name**: `yolov8s`
*   **Device**: `0`

