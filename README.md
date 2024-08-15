# PRODIGY_ML_04
Hand Sign and Gesture Recognition
This project is a sample program that recognizes hand signs and finger gestures using a Multi-Layer Perceptron (MLP) model. The hand pose is estimated using MediaPipe, which provides key points for hand landmarks.

Overview
The system detects hand gestures by analyzing key points estimated from the hand's pose. These key points are then used as inputs to a simple MLP model for gesture classification.

Features
Hand Pose Estimation: Uses MediaPipe to detect hand landmarks and key points.
Gesture Recognition: Implements a Multi-Layer Perceptron (MLP) to classify different hand signs and gestures.
Real-Time Processing: Processes hand gestures in real-time for interactive applications.
Usage
Run the Program:
python main.py
Instructions:
The program will start capturing video from your webcam.
Perform hand gestures in front of the camera.
The system will recognize and display the corresponding gesture on the screen.
Requirements
Python 3.x
MediaPipe
TensorFlow (or other deep learning frameworks if used)
OpenCV (for video capture and processing)
Contributing
Acknowledgements
MediaPipe: For hand pose estimation.
TensorFlow: For implementing the MLP model.
