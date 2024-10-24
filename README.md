# MNIST_digit_Classification
MNIST Handwritten Digit Classification Using ANN
This project implements an Artificial Neural Network (ANN) to classify handwritten digits (0-9) from the MNIST dataset. The ANN model is trained on 60,000 images and tested on 10,000 images, achieving an accuracy of around 98%.

Key Features:
Dataset: The MNIST dataset contains 28x28 grayscale images of handwritten digits.
Model: A simple ANN architecture with two hidden layers using ReLU activation functions and a softmax output layer.
Optimization: The model is trained using the Adam optimizer and categorical cross-entropy loss function.
Results: The model successfully classifies digits with high accuracy, making it suitable for basic image recognition tasks.
Dependencies:
Python 3.x
TensorFlow/Keras
NumPy
Matplotlib
Dataset:
The MNIST dataset can be downloaded from Kaggle.

Results:
The project includes visualizations like accuracy and loss curves, as well as a confusion matrix to highlight the model's performance on test data.
