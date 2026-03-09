# Movie Rating Prediction using Machine Learning

# Overview
This project builds a **Machine Learning model to predict movie ratings** based on features such as **genre, director, actors, number of votes, and duration**.

The goal is to analyze historical movie data and develop a regression model capable of estimating movie ratings given by users or critics.

This project demonstrates a complete **Machine Learning workflow**, including data preprocessing, feature engineering, model training, and evaluation.

---

# Objectives
- Analyze movie dataset and identify factors influencing movie ratings
- Perform **data cleaning and preprocessing**
- Convert categorical features into numerical values
- Train a **machine learning regression model**
- Evaluate model performance
- Predict ratings for new movie samples

---

# Machine Learning Approach
This project uses a **Random Forest Regressor**, which is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

# Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

# Dataset Features

| Feature | Description |
|------|------|
| Genre | Type of movie |
| Director | Director of the movie |
| Actor 1 | Lead actor |
| Actor 2 | Supporting actor |
| Actor 3 | Supporting actor |
| Votes | Number of user votes |
| Duration | Length of the movie |
| Rating | Target variable |

---

# Project Workflow

 1️⃣ Data Collection
Load and inspect the movie dataset using **Pandas**.

 2️⃣ Data Preprocessing
- Removed missing values
- Cleaned numerical columns
- Encoded categorical features using **Label Encoding**

 3️⃣ Feature Engineering
Selected relevant features influencing movie ratings.

 4️⃣ Model Training
Used **RandomForestRegressor** to train the model.
 5️⃣ Model Evaluation
Performance evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
