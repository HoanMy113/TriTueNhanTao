
# Drowsiness Detection System

## Introduction
This project is an AI-based system that detects driver drowsiness using computer vision.  
The system analyzes facial images from a webcam and determines whether the user is **awake or drowsy**.  
If the system detects signs of drowsiness, it will trigger an **alert sound** to warn the user.

## Objective
The goal of this project is to build a system that can:
- Detect signs of drowsiness in real time
- Help prevent accidents caused by fatigue
- Improve safety in situations such as driving, working, or monitoring tasks

## Technologies Used
- Python  
- Deep Learning  
- Convolutional Neural Network (CNN)  
- OpenCV  
- Webcam for real-time detection  

## Model Architecture
The model uses a **CNN (Convolutional Neural Network)** to analyze facial images.

Main layers in the model:
- Input Layer
- Convolutional Layer
- Pooling Layer
- Flatten Layer
- Fully Connected Layer
- Output Layer (Softmax)

The output predicts two states:
- **Awake**
- **Drowsy**

## System Workflow
1. Capture image from webcam  
2. Detect face in the frame  
3. Predict eye state using the CNN model  
4. If drowsiness is detected for a period of time  
5. The system plays an alert sound

## Model Performance
- Training Accuracy: ~96%  
- Test Accuracy: ~93%  
- Loss: ~0.19  

The model performs well and shows no overfitting.

## Advantages
- Real-time detection
- Lightweight model
- Can run on a normal computer
- Easy to integrate into driver safety systems

## Limitations
- Lower accuracy in low-light conditions
- Performance decreases if the user wears sunglasses or a mask
- Cannot detect other behaviors like yawning or frequent blinking

## Authors
Group 13  
AI in Business Project
