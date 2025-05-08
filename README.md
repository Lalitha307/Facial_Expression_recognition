# Face Detection and Emotion Recognition

This project is a real-time facial emotion recognition system that uses deep learning to detect faces and classify emotions from live webcam feed. It identifies five emotions: **Angry**, **Happy**, **Neutral**, **Sad**, and **Surprise**.

## Features

- Real-time face detection using Haar Cascade.
- Emotion classification using a custom-trained Convolutional Neural Network (CNN).
- Trained on grayscale images resized to 48x48.
- Model serialization and reuse with JSON and HDF5.

## Demo

Run the `FD.py` script to start real-time emotion recognition via webcam.

## Technologies Used

- Python
- OpenCV
- TensorFlow & Keras
- NumPy
- CNN (Convolutional Neural Network)
