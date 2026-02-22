# MNIST CNN Classifier (PyTorch)

## Overview
This project implements a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset using PyTorch.

## Architecture
- Conv2d(1, 16, 3)
- MaxPool2d(2)
- Conv2d(16, 32, 3)
- MaxPool2d(2)
- Linear(32*5*5, 128)
- Linear(128, 10)

## Results
- Training Accuracy: XX%
- Validation Accuracy: XX%
- Test Accuracy: XX%

## Features
- Confusion Matrix
- Misclassified Image Visualization
- Loss Curve
- Model Saving & Loading

## How to Run
python pytorch_cnn.py