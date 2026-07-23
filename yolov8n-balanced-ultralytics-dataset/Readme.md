# YOLOv8n Balanced Ultralytics Model

Performance details and links for the YOLOv8n model trained on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `exp-2.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset-2`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :--- |
| 100 | 59.4% | 34.1% | 63.4% | 61.2% | Platform Run |

### Training Configuration

*   **Device**: `4`
*   **Base Model**: `ul://ultralytics/yolov8/yolov8n`
*   **Dataset Configuration**: `ul://paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset-2`
*   **Project**: `paranietharan-palasuntharam/pothole-detection`
*   **Run Name**: `exp-2`
*   **Task**: `detect`
*   **Epochs**: `100`
*   **Batch Size**: `64`
*   **Image Size (imgsz)**: `640`

