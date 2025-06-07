# Real-Time Driver Drowsiness Detection System

## 🚗 Overview
The Real-Time Driver Drowsiness Detection System is a Python-based application designed to enhance road safety by monitoring the driver’s facial features in real time and detecting signs of fatigue or drowsiness. When drowsiness is detected, an alert sound is triggered to wake the driver, helping to prevent road accidents.

## 🛠️ Technologies Used
- **Python**
- **OpenCV** – for image processing and real-time video capture
- **Dlib** – for facial landmark detection
- **Pygame** – for playing alert sounds
- **imutils** – for convenience functions in computer vision tasks

## 📦 Requirements
Before running the project, ensure you have the following installed:
```bash
pip install opencv-python
pip install dlib
pip install pygame
pip install imutils

driver-drowsiness-detection/
├── main.py                  # Main script to run the application
├── shape_predictor_68_face_landmarks.dat  # Dlib pre-trained model
├── alarm.wav               # Audio file to alert the driver
├── README.md               
