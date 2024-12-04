# Simple Inception Model on MNIST Dataset

This repository demonstrates the implementation of a simple **Inception Model** architecture on the **MNIST dataset** for handwritten digit classification. The project is implemented in Python using a Jupyter Notebook.

---

## Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Model Architecture](#model-architecture)


---

## Overview

The MNIST dataset is a widely used benchmark for image classification tasks, consisting of grayscale images of digits (0-9). This project implements a scaled-down version of the **Inception architecture**, designed to handle the dataset's relatively simple structure while exploring the benefits of multi-scale convolutional features.

---

## Dataset

- **Source**: The MNIST dataset can be directly loaded from TensorFlow/Keras datasets.
- **Size**: 
  - Training set: 60,000 images.
  - Test set: 10,000 images.
- **Image Dimensions**: 28x28 pixels, grayscale.

---

## Model Architecture

The implemented model is inspired by Google's **Inception** architecture but simplified to suit the MNIST dataset. The key components include:
- **Multiple filter sizes**: Parallel convolutions with different kernel sizes (e.g., 1x1, 3x3, 5x5).
- **Dimensionality reduction**: 1x1 convolutions are used to reduce computational complexity.
- **Max-pooling**: Extracts dominant features in parallel with convolutions.

The architecture is depicted below:

![Inception Model Architecture](inception_model.png)

---
