# Hand-Sign-Recognition-System
This project implements a hand sign recognition model that detects specific gestures and maps them to functions like rotate, zoom, and place to manipulate a 3D object in real time within a Unity environment.

The model uses MediaPipe Holistic (including FaceMesh and hand landmarks) to extract keypoints and a trained TensorFlow model to classify actions. The recognized gesture triggers changes in the 3D object's orientation, position, or zoom level.

🚀 Features

Real-time Hand Sign Detection — Uses MediaPipe Holistic for pose, hand, and face landmark extraction
Action Classification — Trained TensorFlow model predicts gestures
3D Object Control — Integrates with Unity to perform operations like:
🔄 Rotate the object
🔍 Zoom in / Zoom out
📍 Place the object
Live Camera Feed — Displays real-time video with detected gestures using OpenCV

🛠️ Tech Stack

Programming Language: Python
Libraries:
MediaPipe
 — Landmark detection
OpenCV
 — Real-time video processing
TensorFlow / Keras
 — Gesture classification
NumPy — Feature extraction and manipulation
Platform Integration: Unity (3D object control)
