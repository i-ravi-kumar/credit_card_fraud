# Credit card Fraud Detection
## Project Overview 
This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.
The goal is to identify fraud transactions accurately while minimizing false positives.

## Problem Statement
Financial institutions face significant losses due to credit card fraud.
The challenge is to build a robust classification model that can:

- Handle imbalanced data

- Improve Recall for fraud class

- Maintain good Precision

- Achieve strong F1-score

## Dataset Information
This Dataset is downloaded from kaggle.This dataset contains credit card transaction records used to identify fraudulent transactions. The primary goal is to build and evaluate machine learning models capable of accurately distinguishing between legitimate and fraudulent activities.

The dataset includes transactions made by credit card users, where each transaction is labeled as fraud (1) or non-fraud (0)
[https://www.kaggle.com/datasets/chetanmittal033/credit-card-fraud-data]
## Tech Stack
* python
* pandas
* numpy
* seaborn
* matplotlib
* scikit-learn
* xGboost
* MLFlow

## Exploratory Data Aanalysis(EDA)
* checking class imbalance using counterplot
* outlier detection using boxplot
* heatmap

## Machine Learning Models Used
* Simple Logistic Regression
* Dndersampling
* Oversampling
* Undersampling - Smote,smote-tomek
* Decision Tree
* Random Forest
* XGBoost
* Random Search cv
* 
## Model Metrics
* Precision
* Recall
* f1_score
* confusion_matrix
## Best Model
After All model training, XGBoost is best model with metrics:
* Precision - 0.51
* Recall - 0.86
* F1_score - 0.64
## MLflow Experiment Tracking
## Future Improvements
