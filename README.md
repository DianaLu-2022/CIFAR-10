# CIFAR-10 Image Classification using Machine Learning and Deep Learning Techniques

## Overview

This project explores the application of traditional computer vision techniques and deep learning models to classify images from the CIFAR-10 dataset. The dataset consists of 60,000 32x32 color images in 10 classes, with 50,000 training images and 10,000 test images.

## Methods

### Traditional Computer Vision Techniques

1. **Feature Extraction Methods:**
   - **Histogram of Oriented Gradients (HOG):** Captures edge and gradient structures crucial for object recognition.
   - **Local Binary Patterns (LBP):** Effective for capturing textures and patterns within images.

2. **Color Space Analysis:**
   - Utilized RGB and HSV color spaces to extract distinct color information.
   - Converted images to grayscale for optimized feature extraction using traditional algorithms.

3. **Model Selection:**
   - **Support Vector Machine (SVM):** Utilized with RBF kernel for its efficiency in high-dimensional spaces.
   - **Decision Tree Classifier:** Selected for its simplicity and interpretability.

### Deep Learning Models

1. **Convolutional Neural Networks (CNNs):**
   - Implemented several CNN architectures ranging from 3-layer to 6-layer networks using ReLU and ELU activation functions.
   - Hyperparameters such as learning rate, batch size, and weight decay were optimized to improve model performance.

2. **Model Evaluation:**
   - Models were trained and validated on the CIFAR-10 dataset.
   - Achieved high accuracy with deeper CNN models, demonstrating the effectiveness of deep learning in image classification tasks.

## Results

- **SVM with HOG features** achieved an accuracy of 0.56, demonstrating its potential in handling detailed image features.
- **Six-layer CNN models** achieved up to 0.84 accuracy, significantly outperforming traditional methods and highlighting the advantages of deep learning in complex visual data interpretation.

