# YOLO Object Detection System


This project demonstrates the implementation of an object detection system using the YOLO (You Only Look Once) algorithm. It enables detecting objects in images or videos efficiently and accurately.

## Features

- Real-time object detection using YOLO.
- Supports **YOLOv3** and **YOLOv3-Tiny** models.
- Handles image and video inputs.
- Adjustable confidence thresholds for filtering detections.
- Non-Maximum Suppression (NMS) for reducing overlapping bounding boxes.

---

## Prerequisites

Ensure the following tools and dependencies are installed:

1. **Python 3.x**  
2. Python Libraries:
   - `opencv-python`
   - `numpy`
   - `matplotlib`
3. **YOLO Files:**
   - `yolov3.cfg` or `yolov3-tiny.cfg` (configuration file)
   - `yolov3.weights` or `yolov3-tiny.weights` (pre-trained weights , availlable at yolo official website)
   - `coco.names` (class labels)

Install dependencies using `pip`:
```bash
pip install opencv-python numpy matplotlib
