# YOLOv5 Custom Object Detection

This project demonstrates custom object detection using YOLOv5 with datasets from Roboflow.

---

## Features

- Train YOLOv5 on custom datasets.
- GPU acceleration for faster training.
- Perform inference on images and videos.

---

## Setup

1. Clone YOLOv5 repository and install dependencies:
   ```bash
   git clone https://github.com/ultralytics/yolov5.git
   cd yolov5
   pip install -r requirements.txt
   pip install roboflow
   
Download your dataset via Roboflow API.
Usage
Training: Train YOLOv5 using your custom dataset.
Inference: Run detection on images or videos.
Outputs
Training Results: Found in runs/train/.
Inference Results: Saved in runs/detect/.

Acknowledgments
YOLOv5 by Ultralytics
Roboflow
