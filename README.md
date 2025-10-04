# 🎚️ Gesture Volume Control

This project uses **hand tracking** with **Mediapipe** and **OpenCV** to control the computer's system volume using hand gestures.

## 📹 Working Principle
- Detects hand landmarks using Mediapipe.
- Measures the distance between thumb and index finger.
- Maps that distance to the system's master volume (via PyCaw).

## 🧠 Tech Stack
- Python
- OpenCV
- Mediapipe
- PyCaw

## ▶️ Run the Project
1. Install dependencies:
   ```bash
   pip install -r requirements.txt

2.Run the code:

   python VolumeControl.py


3.Move your thumb and index finger closer/farther to decrease/increase volume.
