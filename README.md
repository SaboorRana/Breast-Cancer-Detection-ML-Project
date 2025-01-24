# Breast-Cancer-Detection-ML-Project
# Breast Cancer Detection

This project implements a machine learning model to detect breast cancer based on diagnostic data. Using logistic regression, the model predicts whether the breast cancer is **malignant** or **benign**. The dataset used is the **Breast Cancer Wisconsin (Diagnostic) Dataset**, which is part of the `sklearn.datasets` module.

---

## Project Description

Breast cancer is one of the most common cancers among women worldwide. Early detection can significantly improve treatment outcomes and survival rates. This project leverages machine learning techniques to classify breast cancer cases as malignant or benign based on various diagnostic features such as mean radius, texture, and area.

The pipeline includes:
1. **Data Collection and Preprocessing**: Loading the dataset and preparing it for training.
2. **Model Training**: Training a logistic regression model on the dataset.
3. **Model Evaluation**: Assessing the model's accuracy on training and test data.
4. **Prediction System**: A simple system to predict the nature of breast cancer based on input data.

---

## Features

- **Input Features**: 30 diagnostic measurements, including:
  - Mean radius
  - Mean texture
  - Mean area
  - ...and more.
- **Target Variable**: 
  - `0`: Malignant
  - `1`: Benign
- **Model Used**: Logistic Regression
- **Performance**: 
  - Accuracy on training data: ~98%
  - Accuracy on test data: ~96%

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/breast-cancer-detection.git
