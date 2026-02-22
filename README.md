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
- Final Training loss: 0.0226
- Validation Accuracy: 99.49%
- Test Accuracy: 99.01%

## Features
- Confusion Matrix
- Misclassified Image Visualization
- Loss Curve
- Model Saving & Loading

## How to Run
1. Install dependencies:
pip install -r requirements.txt

2. Launch Jupyter Notebook:
jupyter notebook

3. Open `pytorch_cnn.ipynb` and run all cells.