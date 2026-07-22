# Driver Drowsiness Detection System

A real-time driver drowsiness detection system built using computer vision. It monitors facial landmarks through a webcam feed and alerts the driver when signs of fatigue are detected.

## How It Works

1. Captures live video from a camera.
2. Uses MediaPipe FaceMesh to detect facial landmarks (eyes, mouth, iris) in real time.
3. Calculates the following:
   - Eye Aspect Ratio (EAR) to detect prolonged eye closure
   - Mouth Aspect Ratio (MAR) to detect yawning
   - Head Pose (roll, pitch, yaw) to detect head nodding, using OpenCV's solvePnP
   - Gaze direction using iris landmarks
4. Combines these signals over a rolling time window to classify the driver's state as Normal or Drowsy.
5. Triggers an alert if drowsiness persists beyond a set threshold.

## Tech Stack

Language: Python

Computer Vision: OpenCV, MediaPipe FaceMesh

Core Techniques: Facial landmark detection, Eye Aspect Ratio and Mouth Aspect Ratio calculation, head pose estimation

## How to Run

Step 1: pip install opencv-python mediapipe numpy

Step 2: python main.py

## Author

Vaishnavi Shetty
