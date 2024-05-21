# MNIST Image Classification

This repository contains practice code for building an image classification model using the MNIST dataset with TensorFlow and Keras.

## Overview

This project is a basic implementation of an image classification model that classifies handwritten digits from the MNIST dataset. The MNIST dataset is a well-known dataset in the field of machine learning and consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9).

## Model Architecture

The model is a simple neural network with the following architecture:
- Input layer: Flattening the 28x28 input images into a 784-element vector
- Hidden layer: Dense layer with 128 neurons and ReLU activation function
- Output layer: Dense layer with 10 neurons (one for each digit) and softmax activation function

## Installation

To run this project, you need to have Python and the following libraries installed:

- TensorFlow
- Keras (Keras is included in TensorFlow 2.x)
- NumPy
