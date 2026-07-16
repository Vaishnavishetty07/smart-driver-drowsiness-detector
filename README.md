# Driver Drowsiness Detection System

An AI-based computer vision system that detects driver drowsiness in real-time and helps prevent accidents caused by fatigue. The system monitors the driver's eye movements and facial features using a camera and provides an alert when signs of drowsiness are detected.

## Project Objective

The main objective of this project is to develop a smart driver monitoring system that can identify drowsy behavior while driving. By using computer vision and deep learning techniques, the system continuously analyzes the driver's face and detects fatigue conditions to improve road safety.

## Features

- Real-time driver face detection
- Eye closure and blink monitoring
- Drowsiness detection using facial features
- Alert generation when the driver is sleepy
- Real-time video processing
- Computer vision-based monitoring system

## Working Principle

1. The system captures live video through a camera.
2. The driver's face is detected from the video frames.
3. Eye and facial landmarks are analyzed.
4. The system calculates signs of drowsiness based on eye closure duration.
5. If drowsiness is detected, an alert is generated to warn the driver.

## Technology Stack

### Programming Language
- Python

### Computer Vision
- OpenCV
- Dlib / Face Landmark Detection

### Machine Learning / Deep Learning
- Convolutional Neural Networks (CNN)
- Deep Learning techniques

### Libraries
- NumPy
- Pandas
- TensorFlow / Keras

### Tools
- VS Code
- Jupyter Notebook
- GitHub

## Project Structure

```

driver-drowsiness-detection/
│
├── dataset/
├── models/
├── main.py
├── requirements.txt
├── README.md
└── resources/

```

## How to Run the Project

### 1. Clone the Repository

```

git clone <repository-url>

```

### 2. Install Required Dependencies

```

pip install -r requirements.txt

```

### 3. Run the Application

```

python main.py

```

### 4. Allow Camera Access

The system will start capturing video through the camera and detect drowsiness in real time.

## Applications

- Driver safety monitoring systems
- Smart vehicles
- Transportation safety
- Fleet management systems
- Accident prevention systems

## Future Enhancements

- Integration with IoT-enabled vehicles
- Voice-based warning system
- Mobile application support
- Real-time cloud monitoring
- Improved accuracy using advanced deep learning models

## Author

Vaishnavi Shetty
