# Internship-Projects
First Internship Project-CNN-based handwritten digit classification using TensorFlow
MNIST Handwritten Digit Recognition using CNN

Project Overview

This project uses a Convolutional Neural Network (CNN) to recognise handwritten digits from the MNIST dataset.

The model classifies grayscale images into 10 categories (digits 0–9) using TensorFlow and Keras.

Dataset

Dataset: MNIST

Training images: 60,000

Testing images: 10,000

Image dimensions: 28 × 28 pixels

Image type: Grayscale

Number of classes: 10 (0–9)

CNN Architecture

The model consists of the following layers:

Input Layer – accepts 28 × 28 grayscale images.

Convolutional Layer – 32 filters of size 3 × 3 with ReLU activation.

Max Pooling Layer – 2 × 2 pooling.

Flatten Layer – converts feature maps into a one-dimensional vector.

Dense Layer – 64 neurons with ReLU activation.

Output Layer – 10 neurons with Softmax activation.

Model Configuration

Optimizer: Adam

Loss Function: Sparse Categorical Crossentropy

Batch Size: 100

Epochs: 5

Validation Split: 10%

Model Performance

Metric

Result

Training Accuracy

99.02%

Validation Accuracy

98.80%

Test Accuracy

98.44%

Test Loss

0.0460

Technologies Used

Python

NumPy

Matplotlib

TensorFlow

Keras

Scikit-learn

Google Colab

Jupyter Notebook

Project Files

mnist_cnn.ipynb – Jupyter Notebook containing the implementation, training and evaluation.

mnist_cnn.keras – Saved trained CNN model.

Future Improvements

Test the model with custom handwritten digit images.

Build an interactive application.

Deploy the trained model as a web application.

Author

AI/ML Learning Project – Handwritten Digit Recognition using CNN.
