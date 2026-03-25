# IoT Intrusion Detection Using Machine Learning and Deep Learning

This project explores intrusion detection in IoT network traffic using both classical machine learning and deep learning models.

developed as an undergraduate coursework project.

## Overview

The goal of this project is to classify IoT network traffic into benign or multiple attack categories using supervised learning techniques.

We compare the performance of multiple models, including:

- Logistic Regression
- Decision Tree
- Random Forest
- KNN
- Naive Bayes
- Gradient Boosting
- LightGBM
- XGBoost
- Deep Neural Network (DNN)
- 1D Convolutional Neural Network (1D-CNN)



## Dataset

- Based on a subset of the **CIC IoT-DIAD 2024 dataset**
- Includes:
  - 1 benign class
  - 10 attack classes
- Preprocessing steps:
  - Data cleaning
  - Feature selection (correlation-based reduction)
  - Standardization
  - SMOTE for handling class imbalance

---

## Methods

- Feature engineering and preprocessing
- Multi-class classification
- Comparison of traditional ML vs boosting vs deep learning models

---

## Results

- Best performance achieved by **LightGBM (~93% accuracy)**
- Followed by XGBoost and Random Forest
- Deep learning models showed competitive but slightly lower performance
