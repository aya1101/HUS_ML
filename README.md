# HUS Machine Learning Final Project: Heart Disease Prediction

This project focuses on predicting the presence of heart disease by analyzing patient data using various machine learning techniques. The goal is to identify key risk factors and build accurate predictive models to assist in early diagnosis.

## Overview

Heart disease is one of the leading causes of death worldwide. Early prediction through data-driven models can support timely intervention and improve patient outcomes. This project implements a complete pipeline from data preprocessing, feature engineering, model training, hyperparameter tuning, to performance evaluation.

## Models Implemented

- K-Nearest Neighbors (KNN)  
- Logistic Regression  
- Decision Tree  
- Support Vector Machine (SVM)  
- AdaBoost  

Each model was optimized using GridSearch to tune hyperparameters and maximize prediction accuracy.

## Methodology

- Data preprocessing: handling missing values, normalization, and feature selection.  
- Model training and validation using stratified cross-validation.  
- Hyperparameter tuning via GridSearchCV.  
- Performance evaluation using metrics such as accuracy, precision, recall, and F1-score.

## Dataset

The dataset contains clinical and demographic data of patients, including risk factors relevant to heart disease. Data was sourced from publicly available medical records and preprocessed for model consumption.

---

Repository link: [github.com/aya1101/HUS_ML](https://github.com/aya1101/HUS_ML)

## Results

The models were evaluated based on their accuracy on the validation dataset. The results are summarized below:

| Model                 | Accuracy |
|-----------------------|----------|
| K-Nearest Neighbors    | 87.5%    |
| Decision Tree         | 83.9%    |
| Logistic Regression   | 88.7%    |
| Support Vector Machine | 89.9%    |
| AdaBoost              | 89.9%    |

The Support Vector Machine (SVM) and AdaBoost models achieved the highest accuracy of **89.9%**, demonstrating strong predictive performance for heart disease classification.
