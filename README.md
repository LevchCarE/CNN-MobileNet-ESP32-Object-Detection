

## ESP32 Object Detection with MobileNet and OpenCV

This project implements real-time object detection using a MobileNet model on video streams from an ESP32-CAM. The solution leverages OpenCV for video processing and object classification, allowing you to detect objects from an IP camera feed in your local network.

### Features

- Captures video frames from an ESP32-CAM over WiFi using its IP address.
- Utilizes a pre-trained MobileNet model for fast and efficient object detection.
- Supports object classification using COCO dataset labels.
- Visualizes detected objects with bounding boxes and class names in real time.
- Simple interface with OpenCV for display and interaction.

### How it Works

1. The script connects to the ESP32-CAM video feed via HTTP.
2. Each frame is captured and processed using OpenCV.
3. The MobileNet model detects objects and classifies them based on COCO classes.
4. Results are displayed with bounding boxes and labels in a resizable OpenCV window.

