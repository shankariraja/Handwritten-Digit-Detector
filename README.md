# Handwritten Digit Detector

## Overview
This project detects handwritten digits (0-9) using deep learning. It trains a model on a dataset of grayscale digit images and their corresponding labels.

## Preprocessing
- Images are resized to 28x28 pixels and converted to grayscale.
- Pixel values are normalized.
- The dataset is split into training and testing sets.

## Model
The model is a CNN built with Keras:
- Convolutional layers with ReLU activation.
- Max pooling layers for downsampling.
- Dropout layers to prevent overfitting.
- Dense layers with ReLU activation.
- Output layer with softmax activation.

## Training
The model is trained for 30 epochs using Adam optimizer and sparse categorical crossentropy loss.

## Inference
The model predicts digits from test images and compares with actual labels.

## Dependencies
- Pandas
- NumPy
- tqdm
- TensorFlow/Keras
- Matplotlib

