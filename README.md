# CNN for CIFAR-10

A Convolutional Neural Network (CNN) implemented in PyTorch for image classification on the CIFAR-10 dataset.

## Project Overview

This project trains a CNN from scratch using PyTorch to classify images from the CIFAR-10 dataset.

The model uses multiple convolutional layers, ReLU activation functions, max pooling layers, and fully connected layers for classification.

## Dataset

CIFAR-10 consists of:

* 50,000 training images
* 10,000 test images
* 10 image classes

Classes:

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

## Model Architecture

* Conv2D (3 → 32)

* ReLU

* MaxPool2D

* Conv2D (32 → 64)

* ReLU

* MaxPool2D

* Conv2D (64 → 128)

* ReLU

* MaxPool2D

* Fully Connected Layer (2048 → 256)

* ReLU

* Output Layer (256 → 10)

## Training

* Optimizer: Adam
* Loss Function: CrossEntropyLoss
* Epochs: 20
* Batch Size: 64

## Results

* Test Accuracy: 74.83%

## Libraries Used

* PyTorch
* Torchvision
* NumPy
* Jupyter Notebook

## Run the Project

```bash
pip install torch torchvision
jupyter lab
```

Open:

```text
CNN_for_CIFAR10.ipynb
```

and run all cells.
