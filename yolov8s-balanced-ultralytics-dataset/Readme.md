# YOLOv8s Balanced Ultralytics Model

Performance details and links for the YOLOv8s model trained on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `exp.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset-2`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :--- |
| 50 | 62.4% | 36.6% | 63.9% | 66.0% | Platform Run |

### Training Configuration

*   **Device**: `5`
*   **Base Model**: `ul://ultralytics/yolov8/yolov8s`
*   **Dataset Configuration**: `ul://paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset-2`
*   **Project**: `paranietharan-palasuntharam/pothole-detection`
*   **Run Name**: `exp`
*   **Task**: `detect`
*   **Epochs**: `50`
*   **Batch Size**: `32`
*   **Image Size (imgsz)**: `640`

