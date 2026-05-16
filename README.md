# MNIST-MLP-Neural
Handwritten Digit Recognition using MLP
Project Overview

This project implements a handwritten digit recognition system using a Multilayer Perceptron (MLP) neural network with the MNIST dataset.

The model is trained to classify handwritten digits from 0 to 9 with high accuracy using TensorFlow and Keras.

Features
MNIST dataset loading
Data preprocessing and normalization
One-hot encoding
MLP neural network architecture
Batch Normalization and Dropout
Two training experiments
Accuracy and loss visualization
Model comparison
Random digit prediction
Save best trained model
Technologies Used
Python
NumPy
Matplotlib
TensorFlow / Keras
Model Architecture
Input Layer (28x28)
↓
Flatten Layer
↓
Dense Layer + ReLU
↓
Batch Normalization
↓
Dropout
↓
Dense Layer + ReLU
↓
Output Layer (Softmax)
Dataset

The project uses the MNIST dataset:

60,000 training images
10,000 testing images
Image size: 28×28 pixels
How to Run

Install required libraries:

pip install tensorflow numpy matplotlib

Run the project:

python main.py
Results

The model achieves approximately:

Model 1 Accuracy: ~97%–98%
Model 2 Accuracy: ~98%–99%
Output Examples
Training accuracy graphs
Loss graphs
Random digit prediction
Saved trained model file
Author

Final Project — Handwritten Digit Recognition using MLP Neural Network.
