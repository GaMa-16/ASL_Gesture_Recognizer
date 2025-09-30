# 🚀 Basic ASL Alphabet Recognition (High-Accuracy)

## Project Overview
This is a real-time American Sign Language (ASL) finger spelling recognition system capable of recognizing the 26 letters (A-Z) and a 'None' class. The core model uses a Deep Learning LSTM Network trained on custom, position-invariant landmark data.

- **Final Accuracy:** [Insert your final accuracy here, e.g., **93.83%**]
- **Classes:** 27 (A-Z + None)
- **Technology:** Python, OpenCV, MediaPipe, TensorFlow/Keras.

## 🛠️ Key Technical Achievement
The model uses **wrist-relative coordinate normalization** to ensure **position and scale invariance**. This means the gesture is recognized correctly regardless of where the hand is on the screen or how close it is to the camera.

## 🏃 Quick Start Guide

### Prerequisites
1. Install Python 3.10.
2. Ensure a fast, stable internet connection.
3. A functioning webcam.

### Installation & Execution
1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/GaMa-16/ASL_Gesture_Recognizer.git](https://github.com/GaMa-16/ASL_Gesture_Recognizer.git)
   cd ASL_Gesture_Recognizer
