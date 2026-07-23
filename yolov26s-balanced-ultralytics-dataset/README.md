# YOLOv26s Balanced Ultralytics Model

Performance details and links for the YOLOv26s model trained on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolov26s.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | Image Size | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 100 | 640 | 65.1% | 41.1% | 70.0% | 67.3% | Platform Run |

### Training Configuration

*   **Base Model**: `ul://ultralytics/yolo26/yolo26s`
*   **Dataset Configuration**: `ul://ankayatchchelvi-palasuntharam/datasets/pothole-detection-merged-balanced-dataset`
*   **Task**: `detect`
*   **Epochs**: `100`
*   **Batch Size**: `-1`
*   **Image Size (imgsz)**: `640`
*   **Project**: `ankayatchchelvi-palasuntharam/test-yolo-training`
*   **Run Name**: `yolov26s`
*   **Device**: `0`

