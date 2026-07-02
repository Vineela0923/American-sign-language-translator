# American-sign-language-translator
# Overview

Communication barriers between hearing-impaired individuals and others can limit effective interaction.
This project presents a real-time American Sign Language (ASL) recognition system using deep learning techniques to bridge this gap.
The system detects hand gestures from a webcam and translates them into corresponding ASL alphabets in real time.

# Features
Real-time ASL alphabet recognition
Webcam-based gesture detection
Deep learning model using CNN
Image preprocessing & augmentation
Fast and accurate predictions
User-friendly output display

# Tech Stack
Programming Language: Python
#Libraries & Frameworks:
TensorFlow / Keras
OpenCV
NumPy
Pandas
Scikit-learn

# Project Structure
American-sign-language-translator/
│── README.md
│── asl_landmarks.csv
│── class_indices.pkl.html
│── h5.html
│── preprocess_landmarks.py
│── real_time_interface.py
│── train_model.py

# How It Works
# 1.Data Collection
Dataset contains labeled images of ASL hand gestures.
# 2.Preprocessing
Resizing images
Normalization
Data augmentation (rotation, flipping, zooming)
# 3.Model Training
A Convolutional Neural Network (CNN) learns:
Hand shape
Orientation
Finger positioning
# 4.Real-Time Prediction
Webcam captures live video
Each frame is processed
Model predicts ASL alphabet
Output displayed as text
