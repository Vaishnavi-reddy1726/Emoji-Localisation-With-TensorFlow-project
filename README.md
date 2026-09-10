## Emoji Localisation With TensorFlow

A deep learning project that uses **TensorFlow and Keras** to build a Convolutional Neural Network (CNN) for **emoji classification and localization**.

The model takes an image containing an emoji as input and produces two outputs:

* **Emoji Classification** – identifies the emoji class.
* **Bounding Box Regression** – predicts the position of the emoji within the image.

## Features

* CNN-based image classification
* Object localization using bounding box regression
* Multi-output neural network
* Custom Intersection over Union (IoU) metric
* Synthetic data generation
* Custom Keras callbacks
* Bounding box visualization

## Model Architecture

The network uses a **multi-output CNN** with:

**Input**

* Emoji image

**Output 1 – Classification**

* Predicts the emoji category

**Output 2 – Localization**

* Predicts the bounding box coordinates of the emoji

This allows the model to perform classification and localization simultaneously.

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Convolutional Neural Networks (CNN)
* Computer Vision

## Key Concepts

### Object Localization

Object localization identifies an object in an image and predicts its position using a bounding box.

### Multi-Output Neural Network

The CNN contains two output branches:

1. A classification branch for predicting the emoji class.
2. A regression branch for predicting the bounding box coordinates.

### Intersection over Union (IoU)

IoU is used to measure the overlap between the predicted bounding box and the ground-truth bounding box.

## Project Workflow

1. Create and visualize image data
2. Generate training examples
3. Plot ground-truth bounding boxes
4. Build a data generator
5. Design the CNN architecture
6. Implement the custom IoU metric
7. Compile the multi-output model
8. Implement a custom callback
9. Train the model
10. Evaluate classification and localization performance

## Results

The model is trained to simultaneously identify the emoji and predict its location within the image.



