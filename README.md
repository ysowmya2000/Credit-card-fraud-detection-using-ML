# Credit-card-fraud-detection-using-ML
This is aimed at detecting fraudulent credit card transactions using machine learning techniques. The dataset used for this project contains transactions made by European cardholders in September 2013, presenting a significant class imbalance where fraudulent transactions represent only 0.172% of all transactions. This project leverages various machine learning algorithms to build a robust fraud detection model, optimized for highly imbalanced data.

## Project Overview
Credit card fraud detection is a critical task in financial systems to protect customers from unauthorized charges. This project aims to:

- Accurately classify transactions as fraudulent or legitimate.
- Handle the highly imbalanced nature of the dataset.
- Optimize the model performance using appropriate evaluation metrics such as the Area Under the Precision-Recall Curve (AUPRC).

## Dataset Description
The dataset used in this project is sourced from Kaggle. Below are the key characteristics of the dataset:
- Number of transactions: 284,807
- Number of frauds: 492 (0.172% of all transactions)
- Features:
  - V1, V2, ..., V28: Principal components obtained via PCA transformation (numerical features).
  - Time: Seconds elapsed between the first transaction and subsequent transactions.
  - Amount: Transaction amount (useful for cost-sensitive learning).
  - Class: Target variable, where 1 indicates fraud and 0 indicates a legitimate transaction.

## To Do
- Identify fraudulent transactions with high accuracy.
- Overcome the challenges posed by a highly imbalanced dataset.
- Use effective evaluation metrics to ensure reliability in real-world scenarios.

## Methodology
The project involves the following steps:
### 1. Data Preprocessing:
- Handling the imbalanced dataset using resampling techniques (e.g., oversampling, undersampling).
- Scaling the Amount and Time features for model compatibility.
### 2. Exploratory Data Analysis (EDA):
- Visualizing the distribution of features.
- Analyzing correlations and patterns in the data.
### 3. Model Selection:
- Implementing and tuning the following algorithms:
  - Logistic Regression
  - Random Forest
### 4. Evaluation:
- Using AUPRC as the primary metric.
- Comparing model performance using metrics like F1-Score, Precision, and Recall.

## Libraries
- pandas for data manipulation
- matplotlib and seaborn for visualization
- scikit-learn for machine learning models and evaluation

## Evaluation Metric
Given the class imbalance, traditional accuracy metrics are misleading. This project focuses on:
- Area Under the Precision-Recall Curve (AUPRC): A reliable metric for imbalanced classification.
- F1-Score: The harmonic mean of precision and recall.

## Results
The following algorithms were implemented and evaluated:
Logistic Regression
Random Forest
Best Model: Random forest
F1-Score: 82.00%


























### Dataset
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
