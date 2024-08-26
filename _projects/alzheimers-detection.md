---
title: "Exploring Optimization Techniques for Alzheimer's Detection using MRI Scans"
date: 2023-02-29
tags: [deep learning, CNN, medical imaging, Alzheimer's, MRI, optimization techniques]
header:
  image: "images/projects/alzheimers-detection/image.png"
  teaser: "/images/teasers/ad.jpeg"
excerpt: "Developing and optimizing CNN models for classifying Alzheimer's disease severity from MRI scans"
mathjax: "true"
---


This project aims to develop and compare machine learning models for classifying Alzheimer's disease severity based on MRI images. The main focus is on implementing and evaluating an optimized Convolutional Neural Network (CNN) model to achieve superior performance compared to a baseline model.

## Dataset

- Source: Kaggle
- Images: Preprocessed MRI scans (128x128 pixels)
- Classes:
  1. Mild Demented (896 images)
  2. Moderate Demented (64 images)
  3. Non Demented (3200 images)
  4. Very Mild Demented (2240 images)

## Methodology

1. Data Preprocessing:
   - Resize images to 128x128 pixels
   - Normalize pixel values to range [0, 1]

2. Model Architectures:
   - Simple Model (Baseline)
   - Optimized Model

3. Optimization Techniques:
   - L2 Regularization
   - Dropout Regularization
   - Batch Normalization
   - Early Stopping
   - Adam Optimizer with Learning Rate Decay

4. Training and Evaluation:
   - Fixed number of epochs (10) and batch size (32)
   - Early stopping with patience of 5 epochs
   - Comprehensive metrics: accuracy, precision, recall, F1-score, specificity, and sensitivity
   - Confusion matrices for detailed performance analysis

## Results

The optimized model demonstrated significant improvements over the baseline model:

- Simple Model:
  - Accuracy: 54.30%
  - Precision: 61.32%
  - Recall: 54.30%
  - F1 Score: 52.97%

- Optimized Model:
  - Accuracy: 94.30%
  - Precision: 94.48%
  - Recall: 94.30%
  - F1 Score: 94.33%

## Key Findings

1. The optimized model showed a substantial increase in all performance metrics compared to the simple model.
2. Optimization techniques effectively addressed overfitting and improved generalization.
3. The project demonstrates the potential of deep learning in medical image analysis for Alzheimer's detection.

## Future Work

- Hyperparameter tuning for further performance improvements
- Experimenting with different CNN architectures (e.g., ResNet)
- Exploring transfer learning with pre-trained models on larger medical image datasets

## Tools and Technologies

- Python
- TensorFlow / Keras
- NumPy
- scikit-learn
- OpenCV
- Matplotlib
- Seaborn

[View Project on GitHub](https://github.com/CtripleU/Exploring-Optimization-Techniques-for-Alzheimer-s-Detection-using-MRI-Scans.git)