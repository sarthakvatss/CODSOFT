Credit Card Fraud Detection
# Project Overview

This project focuses on building a Machine Learning model to detect fraudulent credit card transactions. Fraud detection is a critical real-world application of data science, where financial institutions analyze transaction patterns to identify suspicious activity.

The model analyzes transaction data and classifies each transaction as fraudulent or genuine using machine learning techniques.

# Objective

The main objective of this project is to develop a classification model that can accurately identify fraudulent credit card transactions while minimizing false positives.

# Dataset Description

The dataset contains anonymized credit card transactions made by European cardholders.

Features include:

V1 – V28: Principal components obtained through PCA transformation

Amount: Transaction amount

Time: Seconds elapsed between transactions

Class: Target variable

0 → Genuine Transaction

1 → Fraudulent Transaction

One of the main challenges in this dataset is class imbalance, where fraudulent transactions represent a very small percentage of total transactions.

# Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Imbalanced-learn (SMOTE)

# Project Workflow
1️⃣ Data Exploration

Loaded and inspected the dataset

Analyzed class distribution to understand imbalance

2️⃣ Data Preprocessing

Normalized the transaction Amount feature

Removed unnecessary columns

Prepared features and target variables

3️⃣ Handling Class Imbalance

Since fraud cases are extremely rare, SMOTE (Synthetic Minority Oversampling Technique) was used to balance the dataset by generating synthetic examples of the minority class.

4️⃣ Model Training

A Random Forest Classifier was trained to classify transactions as fraudulent or legitimate.

5️⃣ Model Evaluation

The model was evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

# Model Performance

The trained model achieved strong performance in detecting fraudulent transactions.

Key evaluation metrics included:

Accuracy: ~97–99%

High Recall for Fraud Detection

Improved F1-score after applying SMOTE

These metrics indicate that the model effectively detects fraudulent transactions while maintaining reliable overall performance.
