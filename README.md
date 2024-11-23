# Academic rojects in AI and ML

# 🤖 Emotion Detection Using FER-2013 Dataset

Welcome to the **Emotion Detection** project! This repository contains a comprehensive implementation of an emotion detection model using the **FER-2013 dataset**. The project is built with a focus on **PyTorch-Lightning** and follows Object-Oriented Programming (OOP) principles.

---

## 📚 Project Overview

The **FER-2013 dataset** is a gray-scale image dataset of faces categorized into seven emotion classes:
1. Happiness
2. Neutral
3. Sadness
4. Anger
5. Surprise
6. Disgust
7. Fear

The dataset consists of **35,685 examples**, each 48x48 pixels in size, split into training and testing sets. The aim is to train a deep learning model to classify these emotions accurately.

---

## 🛠️ Tools & Technologies Used

- **Framework**: PyTorch-Lightning
- **Programming Paradigm**: Object-Oriented Programming (OOP)
- **Visualization**: TensorBoard and Matplotlib
- **Key Libraries**:
  - NumPy, Pandas
  - Torch, Torchvision
  - Pytorch-Lightning
  - Torchmetrics
  - OpenCV
  - PIL

---

## 🎯 Project Protocol

This project follows a structured protocol:
1. **Dataset Preprocessing**:
   - Load and preprocess the dataset.
   - Identify features and targets.
   - Split data into training, validation, and testing sets.
2. **Model Development**:
   - Build the architecture using PyTorch classes.
     - **DataLoader Class**: Handles loading and preprocessing.
     - **Dataset Class**: Manages data splitting.
     - **Model Class**: Implements the neural network architecture.
   - Define loss function and performance metrics.
3. **Training & Validation**:
   - Train and validate the model using TensorBoard and Matplotlib for visualization.
   - Evaluate the model on the test dataset.

---

## 📊 Dataset Summary

- **Dataset**: FER-2013
- **Image Size**: 48x48 pixels (gray-scale)
- **Emotion Categories**: 7
- **Total Examples**: 35,685

---

## 📑 References

- FER-2013 Dataset: [Kaggle Link](https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer)
- PyTorch Documentation: [PyTorch.org](https://pytorch.org/)

---
