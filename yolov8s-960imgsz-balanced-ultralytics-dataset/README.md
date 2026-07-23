# YOLOv8s 960px Image Size Balanced Ultralytics Model

Performance details and links for the YOLOv8s model trained with an increased image size of 960px on the balanced Ultralytics dataset.

### Model Weights File
*   **File Name**: `exp.pt`

### Dataset
*   **Name**: `pothole-detection-merged-balanced-dataset-2`
*   **Link**: [Ultralytics Hub Dataset](https://platform.ultralytics.com/paranietharan-palasuntharam/datasets/pothole-detection-merged-balanced-dataset)

### Performance Metrics

| Epochs | Image Size | mAP50 | mAP50-95 | Precision | Recall | Hub Link |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 100 | 960 | 51.5% | 27.6% | 56.9% | 53.2% | Platform Run |

### Training Configuration

*   **Base Model**: `ul://ultralytics/yolov8/yolov8s`
*   **Dataset Configuration**: `ul://paranietharan-palasuntharam-2/datasets/pothole-detection-merged-balanced-dataset`
*   **Task**: `detect`
*   **Weight Decay**: `0.0007`
*   **Box Loss Weight**: `8.5`
*   **Label Smoothing**: `0.05`
*   **HSV-V Augmentation**: `0.5`
*   **Scale Augmentation**: `0.6`
*   **Mixup Augmentation**: `0.15`
*   **Copy Paste Augmentation**: `0.15`
*   **Epochs**: `100`
*   **Batch Size**: `-1`
*   **Image Size (imgsz)**: `960`
*   **Early Stopping Patience**: `30`
*   **Cosine LR**: `true`
*   **Multi-Scale training**: `0.9`
*   **Project**: `paranietharan-palasuntharam-2/pothole-detection`
*   **Run Name**: `exp`
*   **Device**: `0`

