# 🧠 Classifying Brain Tumors from MRI Scans Using CNNs

This project implements a deep learning pipeline using Convolutional Neural Networks (CNNs) to classify brain MRI scans into four categories: Glioma, Meningioma, Pituitary, and Healthy. It aims to support early diagnosis and improve outcomes in brain tumor detection using non-invasive imaging.

![dist](https://github.com/user-attachments/assets/e3c002e2-3433-47a1-880c-aa92dbb3d80b)

## 📊 Dataset Overview

- **Total Images**: 7,023 RGB MRI scans  
- **Classes**:
  - Glioma (1,621 images)
  - Healthy (2,000 images)
  - Meningioma (1,645 images)
  - Pituitary (1,757 images)
- **Image Size**: 224x224  
- **Split**: 80% Train, 10% Validation, 10% Test

## 🎯 Objectives

- Develop a CNN model to classify MRI scans into tumor categories.
- Enable early diagnosis and treatment planning for brain tumors.
- Visualize CNN layers and performance metrics for better explainability.

## 🧠 Methodology

- **Preprocessing**: Image resizing, normalization, and augmentation  
- **Model Architecture**:  
  - Multiple Conv2D + MaxPooling layers  
  - Batch Normalization & Dropout for regularization  
  - Global Average Pooling + Dense output layer  
- **Optimization**:
  - Adam optimizer  
  - EarlyStopping & ReduceLROnPlateau for training control  
- **Evaluation**:
  - Confusion Matrix  
  - Classification Report  
  - ROC Curves

## 📈 Results

| Metric      | Value      |
|-------------|------------|
| Accuracy    | ~95%       |
| Precision   | High across all classes |
| ROC-AUC     | Excellent separation between classes |
