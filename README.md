# Deep-Learning

Project: 

https://colab.research.google.com/drive/1EUZsQU_amKTA9pRWw8dv9f5Ir0AeaPy8?usp=sharing

dataset link: https://www.kaggle.com/datasets/hojjatk/mnist-dataset

Handwritten Digit Classification using CNN Project Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify handwritten digits from the MNIST 
dataset. The model was trained and evaluated using deep learning techniques to achieve high accuracy while reducing 
overfitting.

The project includes:

Data preprocessing

Data augmentation

Batch normalization

Dropout layers

Model evaluation

Comparison between Adam and SGD optimizers

Dataset: The project uses the MNIST Handwritten Digits Dataset.

60,000 training images 10,000 testing images Image size:

28×28 pixels 

10 classes (digits 0–9)

Technologies Used:

Python

PyTorch

Torchvision

Matplotlib 

Data Preprocessing

The following preprocessing techniques were applied:

Resizing images

Normalization Converting images to tensors Data Augmentation

To reduce overfitting and improve generalization, the following augmentation techniques were used:

Random Rotation Random Affine Transformation CNN Architecture

The model consists of:

Convolution Layers 

ReLU Activation Function 

Max Pooling Layers

Batch Normalization

Dropout Layer Fully Connected Layers Optimizers Used

Two optimizers were used to compare performance:

Adam Optimizer SGD Optimizer Overfitting Reduction Techniques

The following methods were used to reduce overfitting:

Dropout

Batch Normalization 

Data Augmentation 

How to Run the Project:

Install the required libraries:

pip install torch torchvision matplotli

The final results in 2 models:

Model Accuracy Loss

CNN + Adam 98.20% 0.0527 

CNN + SGD 97.70% 0.0729

Then run all notebook cells sequentially.
