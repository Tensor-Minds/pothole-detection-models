# YOLOv8n Train with 200 Epoch Model

Performance details and links for the YOLOv8n model trained for 200 epochs with an increased image size of 1280px on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolov8n-train-with-200-epoch.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | Image Size | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 200 | 1280 | 63.0% | 35.5% | 64.7% | 65.1% | Platform Run |

### Training Configuration

*   **Device**: `0`
*   **Base Model**: `ul://ultralytics/yolov8/yolov8n`
*   **Dataset Configuration**: `ul://paranietharan-palasuntharam-2/datasets/pothole-detection-merged-balanced-dataset`
*   **Project**: `paranietharan-palasuntharam-2/pothole-detection`
*   **Run Name**: `train-with-200-epoch`
*   **Task**: `detect`
*   **Epochs**: `200`
*   **Batch Size**: `16`
*   **Image Size (imgsz)**: `1280`

