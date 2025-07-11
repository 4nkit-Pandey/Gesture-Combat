# Gesture-Combat
This code enables to play any game (specifically codded for Tekken 6) through hand and body gestures.
🎮 Gesture-Controlled Tekken 6 with Python + AI
This project lets you play Tekken 6 using your real-life body movements — no keyboard or controller required.
Using just a webcam and Python, I built a system that detects gestures like punches, kicks, crouches, and jumps and converts them into actual in-game actions.

⚙️ How It Works
🧠 Computer Vision (OpenCV) captures live video from your webcam
💪 MediaPipe (by Google) detects 33 body keypoints in real-time
🧠 Custom Gesture Logic analyzes body positions to recognize specific actions (like a punch if your wrist is above your shoulder)
⌨️ pynput simulates keyboard inputs mapped to the Tekken 6 emulator controls
🎮 PPSSPP emulator is used to run Tekken 6

🧠 Key Features
Detects real-time body movement

Maps gestures to game keys like A, S, Z, X, arrow keys

Works with Tekken 6, can be extended to other games

Helps understand AI-based input control from scratch

📚 What I Learned
How to use OpenCV for camera input

How MediaPipe tracks human pose landmarks

How to write custom gesture logic using Python

How to simulate keypresses for controlling external apps

✅ Requirements
Python 3.10

OpenCV

MediaPipe

pynput

PPSSPP Emulator

A webcam


