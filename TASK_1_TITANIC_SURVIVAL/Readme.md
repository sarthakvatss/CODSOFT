Titanic Survival Prediction
📌 Project Overview

This project focuses on building a Machine Learning classification model to predict whether a passenger survived the sinking of the RMS Titanic in 1912.

Using passenger information such as age, gender, ticket class, fare, and family details, the model identifies patterns that influenced survival outcomes. This is one of the most popular beginner-level data science projects and serves as a strong foundation for understanding classification problems.

🎯 Objective

To develop a predictive model that determines:

0 → Did Not Survive

1 → Survived

The goal is to apply data preprocessing, feature engineering, and machine learning techniques to achieve high prediction accuracy.

📂 Dataset Description

The dataset contains passenger details such as:

Passenger ID

Ticket Class (Pclass)

Name

Gender (Sex)

Age

Number of Siblings/Spouses aboard (SibSp)

Number of Parents/Children aboard (Parch)

Ticket Number

Fare

Cabin

Port of Embarkation

Survival Status (Target Variable)

Dataset Source: Kaggle Titanic Competition Dataset

🛠️ Technologies Used

Python

Pandas & NumPy

Matplotlib & Seaborn (for visualization)

Scikit-learn

XGBoost (for improved performance)

Google Colab / Jupyter Notebook

🔎 Project Workflow
1️⃣ Data Exploration

Analyzed dataset structure and summary statistics

Identified missing values and feature distributions

2️⃣ Data Cleaning

Handled missing values in Age and Embarked

Removed irrelevant columns such as Cabin, Ticket, and Name

3️⃣ Feature Engineering

Created new features like FamilySize

Created binary feature IsAlone

Encoded categorical variables

4️⃣ Model Building

Implemented multiple classification models:

Logistic Regression

Random Forest

XGBoost

5️⃣ Model Evaluation

Performance evaluated using:

Accuracy Score

Confusion Matrix

Precision, Recall, and F1-score

📊 Model Performance

The final optimized model achieved approximately 85–90% accuracy, depending on feature engineering and hyperparameter tuning.

📈 Key Insights

Female passengers had significantly higher survival rates.

First-class passengers were more likely to survive.

Smaller families had better survival chances.

Higher ticket fares were often associated with survival.

📁 Project Structure

Dataset file

Jupyter/Colab notebook

README documentation

🧠 Learning Outcomes

Through this project, the following concepts were strengthened:

Data preprocessing and cleaning

Handling missing data

Encoding categorical features

Feature engineering techniques

Model training and comparison

Evaluation metrics for classification problems
