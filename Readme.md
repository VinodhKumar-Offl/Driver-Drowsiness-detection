# Drowsiness and Yawn Detection System

## Overview

The Drowsiness and Yawn Detection System is a real-time computer vision application designed to enhance driver safety by detecting signs of drowsiness and yawning. The system uses facial landmarks and eye/lip measurements to monitor the driver's fatigue levels and triggers alerts when drowsiness or yawning is detected.

## Features

- Real-time video stream processing with configurable webcam index.
- Accurate detection of eye closure and yawning with visual feedback on the video frame.
- Integration of a voice alarm system that alerts the driver when drowsiness or yawning is detected.
- Configurable thresholds for eye aspect ratio (EAR) and lip distance to customize detection sensitivity.

## Technologies Used

- Python
- OpenCV
- dlib
- NumPy
- Machine Learning (scikit-learn)

## Project Structure

- `drowsiness_yawn.py`: Main Python script for the drowsiness and yawn detection system.
- `haarcascade_frontalface_default.xml`: Haar Cascade classifier for face detection.
- `shape_predictor_68_face_landmarks.dat`: Pre-trained model for facial landmark detection.
- `demo.gif`: Demo GIF showcasing the system in action.
- `requirements.txt`: List of Python dependencies required to run the project.
