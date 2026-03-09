Movie Rating Prediction using Machine Learning
# Project Overview

This project focuses on building a Machine Learning model that predicts the rating of a movie based on various attributes such as genre, director, actors, number of votes, and duration.

By analyzing historical movie data, the model learns patterns and relationships between movie features and their ratings. The trained model can then estimate the rating of new movies before release.

This project demonstrates the complete machine learning workflow including data preprocessing, feature engineering, model training, and evaluation.

# Objectives

Analyze movie dataset to understand factors influencing movie ratings

Perform data cleaning and preprocessing

Convert categorical variables into numerical format

Train a machine learning regression model

Evaluate model performance using appropriate metrics

Predict ratings for new movie samples

# Machine Learning Techniques Used

Regression Modeling

Feature Encoding

Data Cleaning

Model Evaluation

# Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Google Colab / Jupyter Notebook

# Dataset

The dataset contains information about movies including:

Feature	Description
Genre	Movie genre
Director	Director of the movie
Actor 1	Main actor
Actor 2	Supporting actor
Actor 3	Supporting actor
Votes	Number of user votes
Duration	Length of the movie
Rating	Target variable (IMDb rating)
# Project Workflow
1️⃣ Data Collection

Load the movie dataset using Pandas.

2️⃣ Data Preprocessing

Remove missing values

Clean numerical columns

Convert text features into numeric values using Label Encoding

3️⃣ Feature Selection

Selected important features influencing movie ratings.

4️⃣ Model Training

Trained a Random Forest Regressor to learn patterns in the data.

5️⃣ Model Evaluation

Evaluated model performance using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

6️⃣ Prediction

Used the trained model to predict ratings for new movie samples.

# Model Performance
Metric	Value
MAE	~0.45
RMSE	~0.70
R² Score	~0.85
Model Accuracy	~85%
# Feature Importance

The model identifies which features have the greatest impact on predicting movie ratings.

Key influencing factors include:

Number of Votes

Director

Actors

Movie Duration

Genre
