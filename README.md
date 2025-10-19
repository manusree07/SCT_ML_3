# SCT_ML_3
# Cats vs Dogs Image Classification using SVM

## Overview
This project implements a **Support Vector Machine (SVM)** classifier to distinguish between **cats and dogs** in images. It is part of **Task 3** of the **SkillCraft Technology Internship**.

The workflow covers a complete **machine learning pipeline for image classification**, including data preprocessing, dimensionality reduction, model training, evaluation, and visualization.

## Features
- **Image loading and preprocessing**:
  - Grayscale conversion
  - Resizing to uniform dimensions
  - Flattening images for SVM input
- **Dataset splitting** into training and test sets (80/20)
- **Dimensionality reduction** using PCA (from 10,000 to 200 features)
- **SVM classification** using LinearSVC
- **Model evaluation**:
  - Accuracy score
  - Confusion matrix
  - Classification report
- **Visualization**:
  - Confusion matrix heatmap
  - Sample predictions from test set

## Technologies Used
- Python  
- OpenCV, NumPy, Pandas  
- scikit-learn (SVM, PCA, metrics)  
- Matplotlib, Seaborn  
- TensorFlow (for dataset download)

## Usage
1. Clone the repository:
   ```bash
   git clone <repository_url>
