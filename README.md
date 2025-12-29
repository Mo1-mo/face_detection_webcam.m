# Face Detection Using Webcam (MATLAB)

This project demonstrates real-time face detection using a webcam in MATLAB.
It utilizes the built-in `vision.CascadeObjectDetector` to detect faces and
draw bounding boxes around them.

## Features
- Real-time face detection
- Uses webcam input
- Automatically releases the webcam when the window is closed
- Clean and simple MATLAB implementation

## Requirements
- MATLAB
- Computer Vision Toolbox
- Webcam (built-in or external)

## How It Works
1. The webcam captures live video frames.
2. A Haar Cascade face detector processes each frame.
3. Detected faces are highlighted with red bounding
