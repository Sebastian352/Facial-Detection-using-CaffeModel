# Real-time Object Detection and Image Display

This repository contains Python scripts for real-time object detection using OpenCV's deep neural network module and displaying images using both OpenCV and Matplotlib.

## Object Detection
The `main.py` script performs real-time object detection using a pre-trained deep neural network. It captures video from a camera source or file path and overlays bounding boxes on detected objects. The script utilizes the SSD (Single Shot MultiBox Detector) model implemented in OpenCV's DNN module.

### Requirements
- OpenCV (cv2)
- Python 3.x

### Usage
Run the script `main.py` with an optional argument specifying the camera source index. If no argument is provided, the default camera will be used.

Example:
```bash
python main.py
