# Breast Cancer Detection

## Overview

This project is designed to develop and evaluate various machine learning models for detecting breast cancer. The primary objective is to build a reliable model that can assist healthcare professionals in diagnosing breast cancer early, thereby improving patient outcomes.

## Dataset

The dataset used for this project is provided as a CSV file. Make sure the dataset is placed in the root directory of the project before running the models.

- **File**: [`breast_cancer_data.csv`](breast_cancer_data.csv)

This file contains features derived from images of breast cancer tumors, with the target variable indicating whether the tumor is benign or malignant.

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

- **Principal Component Analysis (PCA)**: Applied to reduce the feature size from 31 to 8, while maintaining similar model performance. This helps in reducing computational complexity and improving model interpretability.
  
- **Standard Scaling**: All features were scaled using StandardScaler to ensure that each feature contributes equally to the model.

- **Handling Data Imbalance**: The dataset has an imbalance between benign and malignant cases. To address this, the focus was placed on models with better precision and recall rather than just accuracy.
  
  ![imbalance](https://github.com/user-attachments/assets/ea6756e6-8bd1-444c-b631-acb5bdd950fa)


## Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**

Given the data imbalance, precision and recall were particularly emphasized to select the best model.

## Usage

The project is primarily aimed at data scientists and researchers interested in applying machine learning to healthcare. It can be used as a foundation for further research or as a diagnostic tool for medical professionals.

## Results

The models were evaluated based on precision, recall, and accuracy. Due to the imbalanced nature of the data, the models that offered better precision and recall were preferred. PCA allowed us to reduce the number of features to 10 without significant loss of performance, making the models more efficient.

![performance](https://github.com/user-attachments/assets/c6440fa9-d373-4c45-8f86-ceac234784a5)


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

For any questions or comments, please contact:

**Navya Sai** - [navyasai1401@gmail.com](mailto:navyasai1401@gmail.com)
