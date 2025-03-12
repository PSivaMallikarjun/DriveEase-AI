# DriveEase-AI
Enhancing night driving safety with AI
VisionSafe AI – AI-Powered Adaptive Headlight & Battery Management System

# Project Overview
VisionSafe AI is an AI-powered system that dynamically adjusts vehicle headlight intensity based on human face detection, preventing glare and enhancing road safety. Additionally, it incorporates an AI-driven battery charge prediction model to monitor power inflow and outflow efficiently.

# Features
AI-Based Headlight Adjustment: Detects human faces and reduces headlight intensity dynamically to prevent glare for other drivers.
Deep Learning Battery Management: Uses a neural network model to predict battery charge percentage based on inflow and outflow.
Real-Time Processing: Utilizes OpenCV for face detection and PyTorch for deep learning predictions.
Interactive UI: Built with Gradio for easy user interaction.

# Tech Stack
Computer Vision: OpenCV (Haar Cascade for face detection)
Deep Learning: PyTorch (Neural Network for battery charge prediction)
Frontend UI: Gradio (User-friendly interactive interface)
Programming Language: Python

# Installation & Setup
Clone the repository:

git clone https://github.com/PSivaMallikarjun/VisionSafeAI.git  
cd VisionSafeAI  
Install dependencies:

!pip install gradio torch torchvision opencv-python numpy  
Run the application:


python app.py  
# How It Works
Headlight Adjustment

The system processes an uploaded image and detects human faces using OpenCV.
If faces are detected, the headlight intensity is reduced dynamically.
Battery Charge Prediction

The neural network predicts the battery charge percentage based on power inflow and outflow.
Outputs real-time charge percentage and headlight intensity.
# Demo
Upload a front-facing image in the UI to see real-time headlight adjustment. Adjust sliders to check battery charge predictions.

# Future Enhancements
Real-time video feed integration for continuous headlight adjustments.
Enhanced ML models for better accuracy.
IoT integration for direct vehicle implementation.
# Contributing
Feel free to submit issues, feature requests, or pull requests to improve the project!
![Screenshot 2025-03-12 222822](https://github.com/user-attachments/assets/89b33a1f-17c4-4cdd-b1bd-c5b2c3446668)
![Screenshot 2025-03-12 222831](https://github.com/user-attachments/assets/e0f6f4e0-09b9-409a-999a-9646292045f7)
![Screenshot 2025-03-12 222842](https://github.com/user-attachments/assets/b044648c-5fc4-449d-b9e9-c006e4753ca0)



