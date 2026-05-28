# 🤟 Sign Language Alphabet Recognition

## 📋 Summary
In this project, I built a real-time ASL alphabet recognition system that detects hand signs for letters A–I from a live webcam feed. It includes both a recognition module and a custom dataset collection pipeline — making it possible to train the model on your own data directly from your camera.

## Features

- Real-time ASL alphabet detection (A–Z)
- Custom dataset collector with countdown timer and auto-capture
- Trained classifier on hand landmarks extracted by MediaPipe
- Live predicted letter displayed on screen

## Tech Stack

| Tool | Role |
|------|------|
| Python | Core language |
| MediaPipe | Hand landmark detection |
| OpenCV | Webcam feed and rendering |
| scikit-learn | Classifier training and inference |
| NumPy | Feature processing |

