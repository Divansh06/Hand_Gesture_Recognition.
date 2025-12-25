✋ Hand Sign Recognition – 1
📌 Project Overview

Hand Sign Recognition – 1 is the first version of a real-time hand gesture recognition project.
This version focuses on hand detection, landmark extraction, and basic finger-counting logic, serving as a strong foundation for more advanced sign recognition systems in the future.

This project uses computer vision techniques to detect hands from a live camera feed and analyze finger positions in real time.

🎯 Objectives

Detect human hands in real time using a webcam

Extract 21 hand landmarks per hand

Implement basic finger counting logic

Display hand landmarks and connections on the video feed

Build a scalable base for future gesture recognition models

🛠️ Tech Stack

Programming Language: Python

Libraries Used:

MediaPipe

OpenCV

IDE / Environment: VS Code

Python Version: 3.10

⚙️ Features (Version 1)

Real-time webcam-based hand detection

Landmark tracking for fingers and wrist

Visual representation of hand skeleton

Finger open/close detection logic

Keyboard-controlled exit (press 'q' to close window)

🧠 How It Works

Webcam captures live video frames

Frames are converted from BGR to RGB

MediaPipe processes the frame to detect hands

21 landmarks per hand are extracted

Finger positions are analyzed using landmark coordinates

Results are visualized using OpenCV

🚀 Getting Started
✅ Prerequisites

Python 3.10

Webcam (for live detection)

🔮 Future Scope

This is Version 1 of the project. Planned improvements include:

Sign-to-text recognition

Gesture classification using ML/DL models

Support for custom hand gestures

Dataset creation and training pipeline
