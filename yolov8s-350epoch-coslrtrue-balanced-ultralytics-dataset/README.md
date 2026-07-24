# YOLOv8s 350-Epoch Cosine LR Balanced Ultralytics Model

Performance details and configuration for the YOLOv8s model trained for 350 epochs with Cosine Learning Rate schedule (`cos_lr=True`) on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `yolov8s-350-epoch-coslrtrue.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | Image Size | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 350 | 640 | 68.8% | 45.7% | 74.3% | 69.2% | Platform Run |

### Training Configuration

*   **Device**: `0`
*   **Base Model**: `ul://ultralytics/yolov8/yolov8s`
*   **Task**: `detect`
*   **Epochs**: `350`
*   **Cosine LR (cos_lr)**: `True`
*   **Optimizer**: `auto`
