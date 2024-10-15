# Sign Language Detection Using YOLO

This project implements a client-server system for real-time sign language detection using a custom YOLO model. The client captures video frames and sends them to the server, which processes each frame using the YOLO model to predict sign language gestures.This project uses YOLOv8 from Ultralytics for real-time object detection and sign language gesture recognition.

## Features
- **Client-Server Communication**: The client streams video to the server via UDP.
- **YOLO Model Inference**: The server uses a custom-trained YOLO model to predict sign language gestures.
- **Real-Time Display**: Predictions are displayed on the server-side.

## Requirements

### Server-Side:
- Python 3.x
- OpenCV (`opencv-python`)
- NumPy (`numpy`)
- Ultralytics YOLOv8 (`ultralytics`)
- PyTorch (`torch`)

### Client-Side:
- Python 3.x
- OpenCV (`opencv-python`)

### Install Dependencies:

```bash
pip install opencv-python numpy ultralytics torch



