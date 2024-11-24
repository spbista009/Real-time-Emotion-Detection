# Real-time Emotion Detection with DeepFace and OpenCV

This project performs real-time emotion detection using the DeepFace library and OpenCV. It detects faces in video frames and predicts the dominant emotion for each detected face.

## Features

- Detects faces using OpenCV's Haar Cascade classifier.
- Analyzes emotions using DeepFace's pre-trained models.
- Supports real-time detection through webcam or video file input.

## Requirements

- Python 3.6+
- OpenCV
- DeepFace
- NumPy (installed automatically with OpenCV and DeepFace)

## Installation

1. Clone the repository or download the project files.
2. Install the required Python libraries:
   ```bash
   pip install opencv-python deepface

# File Structure

emotion_detection_webcam.py: Script for real-time emotion detection via webcam.
README.md: Documentation for the project.

# How It Works

Face Detection: Uses Haar Cascade to detect faces in the video frame.
Emotion Analysis: Passes the detected face to DeepFace to predict the dominant emotion.
Result Display: Draws a bounding box around the face and labels it with the detected emotion.

# Supported Emotions

The system can detect the following emotions:

- Happy
- Sad
- Angry
- Neutral
- Fear
- Surprise
- Disgust

# Notes

The DeepFace.analyze() method has enforce_detection=False to prevent the script from crashing if no face is detected in a frame.
For optimal results, ensure good lighting and a clear view of the face.



Happy coding! 😊