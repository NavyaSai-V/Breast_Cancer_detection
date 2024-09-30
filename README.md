Copy code
# Breast Cancer Detection

## Overview

This project focuses on building machine learning models to detect breast cancer based on diagnostic features from tumor images. The main objective is to develop a reliable and efficient model to help healthcare professionals in early detection of breast cancer.

## Dataset

The dataset used for this project contains features computed from digitized images of breast cancer tumors. The target variable indicates whether the tumor is benign or malignant.

- **File**: `breast_cancer_data.csv`
- **Dimensions**: 569 samples, 31 features
- **Target**: Binary variable (`0`: Benign, `1`: Malignant)

### Key Features

The dataset consists of several features derived from tumor images, including:

- Mean radius
- Mean texture
- Perimeter
- Area
- Smoothness

## Machine Learning Models

Five machine learning algorithms are implemented to predict the nature of the tumor:

1. **Logistic Regression**
2. **Support Vector Machine (SVM)**
3. **K-Nearest Neighbors (KNN)**
4. **Decision Tree**
5. **Random Forest**

## Core Techniques

- **Principal Component Analysis (PCA)**: Dimensionality reduction from 31 to 10 features to enhance computational efficiency without significant performance loss.
  
- **Standard Scaling**: Feature standardization is done using `StandardScaler` to ensure all features contribute equally to the model.

- **Handling Class Imbalance**: Since the dataset has an imbalance between benign and malignant cases, precision and recall were emphasized over accuracy to prevent misclassifications.

## Evaluation Metrics

Given the imbalanced dataset, the following metrics are used to evaluate the models:

- **Accuracy**: Overall model correctness.
- **Precision**: How often the model avoids false positives.
- **Recall**: How well the model identifies true positives.

## Results

The models were evaluated and compared using precision, recall, and accuracy. Due to the imbalanced nature of the data, models with better precision and recall were preferred. PCA helped reduce the feature set while maintaining similar model performance.


![performance](https://github.com/user-attachments/assets/c6440fa9-d373-4c45-8f86-ceac234784a5)

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-repo/breast-cancer-detection.git
cd breast-cancer-detection
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

For any questions or comments, please contact:

**Navya Sai** - [navyasai1401@gmail.com](mailto:navyasai1401@gmail.com)
