# cnn-image-classifier-cifar10

## Project Overview

This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras for image classification on the CIFAR-10 dataset.

The model learns to classify images into one of ten categories:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

## Dataset

CIFAR-10 is a benchmark computer vision dataset containing:

* 60,000 RGB images
* 10 image classes
* Image size: 32 × 32 pixels
* 50,000 training samples
* 10,000 testing samples

## Data Preprocessing

* Pixel values normalized from [0, 255] to [0, 1]
* Labels encoded using sparse categorical format
* Dataset split into training and testing sets

## CNN Architecture

The model consists of:

1. Convolution Layer (32 filters, 3×3, ReLU)
2. Max Pooling Layer (2×2)
3. Convolution Layer (32 filters, 3×3, ReLU)
4. Max Pooling Layer (2×2)
5. Flatten Layer
6. Dense Layer (64 neurons, ReLU)
7. Output Layer (10 neurons, Softmax)

## Training Configuration

* Framework: TensorFlow / Keras
* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Metric: Accuracy

## Model Accuracy

Test Accuracy: **72.43%**

The model successfully learns meaningful visual features from CIFAR-10 images and achieves competitive performance for a simple CNN architecture.

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib

## Future Improvements

* Data Augmentation
* Batch Normalization
* Dropout Regularization
* Transfer Learning
* Deeper CNN Architectures (ResNet, VGG)

## Author

Sarthak

