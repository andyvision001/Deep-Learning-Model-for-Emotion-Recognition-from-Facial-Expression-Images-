# Emotion Recognition with Deep Learning Models

This repository contains the implementation and evaluation of five deep learning models for emotion recognition using facial expression image datasets. The models include a proposed Convolutional Neural Network (CNN) implemented in TensorFlow and PyTorch, SANet, VGG-16, and ResNet50. These models were evaluated on four publicly available datasets: Extended Cohn-Kanade (CK+), Facial Expression Recognition (FER2013), Karolinska Directed Emotional Faces, and Natural Human Faces Images.

## Overview
The study focuses on:
- Data exploration and preprocessing of the datasets.
- Hyperparameter tuning using a defined parameter grid.
- Model evaluation based on accuracy, F1 score, AUC ROC, training/evaluation time, and memory usage.

## Key Results
- **CK+ Dataset Performance**:
  - **SANet**: Achieved the highest accuracy (±98%), F1 score (±97%), AUC ROC (±0.98), with the best training time (±1388.40s) and evaluation time (±277.14s).
  - **TensorFlow CNN**: Accuracy (±95%), F1 score (±95%), AUC ROC (±0.98).
  - **PyTorch CNN**: Accuracy (±95%), F1 score (±94%), AUC ROC (±0.98), with the best memory usage (±345.85 MB).
  - **VGG-16**: Accuracy (±90%), F1 score (±84%), AUC ROC (±0.98).
  - **ResNet50**: Lowest performance with accuracy (±42%), F1 score (±26%), AUC ROC (±0.79).
- **Cross-Dataset Performance**: ResNet50 performed poorly across all datasets, while the other models showed fair performance on FER2013, Karolinska, and Natural Human Faces datasets.

## Conclusions
The study highlights SANet's superior performance in accuracy, F1 score, and training/evaluation time, with PyTorch CNN excelling in memory efficiency. The results underscore the importance of enhanced computing resources and hyperparameter tuning for improving model performance in emotion recognition tasks.

## Purpose
This repository serves as a comprehensive resource for researchers and practitioners working on emotion recognition using deep learning. It provides a foundation for further advancements in model optimization and dataset exploration.

## Future Work
Future efforts will focus on optimizing computational resources, refining hyperparameter tuning, and exploring additional datasets and models to enhance accuracy, speed, and efficiency in emotion recognition systems.