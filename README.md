🚀 SignifyX – Sign Language Detection System

AI-powered Flutter application that enables real-time sign language recognition using computer vision and deep learning.

📌 Overview

SignifyX is designed to break communication barriers between deaf/mute individuals and non-sign language users. The system uses MediaPipe for real-time hand landmark detection and a lightweight CNN-based TensorFlow Lite model for gesture classification.

The application works completely offline and supports multilingual output with voice feedback.

🎯 Key Features

Real-time Hand Gesture Recognition

Offline Functionality

Multilingual Output (Marathi, Hindi, English)

Two-Way Communication

Gesture Confidence Detection

Text-to-Speech Integration

🛠️ Tech Stack

Flutter

MediaPipe

TensorFlow Lite

Convolutional Neural Network (CNN)

Text-to-Speech (TTS)

🧠 System Architecture

Camera → MediaPipe → 21 Hand Landmarks → CNN (TFLite) → Softmax → Text Output → Voice Output
