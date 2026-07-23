# YOLO26n Balanced Ultralytics Model

Performance details and links for the YOLO26n model trained on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolo26n-training.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset-2`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :--- |
| 100 | 58.9% | 34.3% | 64.1% | 59.8% | Platform Run |

### Training Configuration

*   **Device**: `5`
*   **Base Model**: `ul://ultralytics/yolo26/yolo26n`
*   **Dataset Configuration**: `ul://paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset-2`
*   **Project**: `paranietharan-palasuntharam/pothole-detection`
*   **Run Name**: `yolo26n-training`
*   **Task**: `detect`
*   **Epochs**: `100`
*   **Batch Size**: `16`
*   **Image Size (imgsz)**: `640`

