# Breast Cancer Detection

## Overview

This project is designed to develop and evaluate various machine learning models for detecting breast cancer. The primary objective is to build a reliable model that can assist healthcare professionals in diagnosing breast cancer early, thereby improving patient outcomes.

## Dataset

- 
- **Dimensions**: 569 samples and 31 features.
- The dataset contains various features derived from images of breast cancer tumors, such as mean radius, texture, perimeter, area, smoothness, etc.
- The target variable indicates whether the tumor is benign or malignant.

## Models Used

1. **Logistic Regression**
2. **Support Vector Machine (SVM)**
3. **K-Nearest Neighbors (KNN)**
4. **Decision Tree**
5. **Random Forest**

## Key Techniques

- **Principal Component Analysis (PCA)**: Applied to reduce the feature size from 31 to 10, while maintaining similar model performance. This helps in reducing computational complexity and improving model interpretability.
  
- **Standard Scaling**: All features were scaled using StandardScaler to ensure that each feature contributes equally to the model.

- **Handling Data Imbalance**: The dataset has an imbalance between benign and malignant cases. To address this, the focus was placed on models with better precision and recall rather than just accuracy.

## Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**

Given the data imbalance, precision and recall were particularly emphasized to select the best model.
