# MNIST Digit Classification using Neural Networks

## Project Overview

This project focuses on building a Neural Network model to classify handwritten digits (0–9) from the MNIST dataset. The model learns patterns from grayscale images and predicts the correct digit using deep learning techniques.

Handwritten digit recognition is a fundamental problem in Computer Vision and is widely used in applications like postal code recognition, bank cheque processing, and document digitization.

## Dataset

The project uses the MNIST dataset, which contains:

70,000 grayscale images

28 × 28 pixel images

10 classes (digits 0–9)

## Dataset Split:

Training Data: 60,000 images

Testing Data: 10,000 images

## Technologies Used

Python

NumPy

TensorFlow / Keras

Matplotlib

Scikit-learn

Project Workflow

## Import Libraries: 
Load required Python libraries for deep learning and visualization.

## Load Dataset: 
Import the MNIST dataset using Keras datasets.

## Data Preprocessing

Normalize pixel values

Reshape data for neural network input

Build Neural Network Model

Input Layer

Hidden Layers

Output Layer with Softmax activation

## Model Training
Train the neural network on the training dataset.

## Model Evaluation
Evaluate accuracy on the test dataset.

## Prediction
Predict digits for unseen handwritten images.

## Model Architecture

Input Layer: 784 neurons (28×28 flattened image)

Hidden Layer: Dense layer with ReLU activation

Output Layer: 10 neurons with Softmax activation

## Results

Achieved high accuracy on the MNIST test dataset.

Successfully classifies handwritten digits with strong performance.

## Example prediction:

Input Image:
Predicted Digit: 3
