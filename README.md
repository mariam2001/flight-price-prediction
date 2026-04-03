# ✈️ Flight Price Prediction

## 📌 Overview

This project focuses on predicting flight ticket prices using machine learning.
The goal is to understand how different factors like airline, journey date, duration, and number of stops affect pricing, and build a model that can estimate ticket prices accurately.

---

## 🧠 Problem Statement

Flight prices can vary significantly depending on multiple factors.
In this project, we aim to:

* Analyze the dataset to understand pricing patterns
* Build a machine learning model to predict flight prices
* Improve model performance through feature engineering and data preprocessing

---

## 📊 Exploratory Data Analysis (EDA)

Some key observations from the data:

* Flight prices are **right-skewed**, meaning most prices are low with a few very high values
* Airlines and number of stops have a strong impact on ticket prices
* Duration and journey date also influence pricing trends

To handle skewness, a **log transformation** was applied to the target variable.

---

## 🧹 Data Preprocessing

Steps performed:

* Removed missing values
* Converted date columns into day and month
* Extracted useful features from time and duration
* Encoded categorical variables
* Converted total stops into numerical values

---

## ⚙️ Feature Engineering

Some engineered features include:

* Journey day and month
* Duration in minutes
* Number of stops (converted to numeric)

These features helped improve model performance by making patterns easier to learn.

---

## 🤖 Models Used

* Linear Regression (baseline)
* Random Forest Regressor

---

## 📈 Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

Random Forest performed better due to its ability to capture non-linear relationships in the data.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib & Seaborn

---

## 🚀 Future Improvements

* Hyperparameter tuning for better performance
* Try more advanced models like XGBoost
* Deploy the model using a simple web app (e.g., Streamlit)
* Improve feature engineering

---

## 🙌 Final Thoughts

This project helped me understand the full machine learning workflow, from data cleaning and exploration to model building and evaluation.
It also highlighted the importance of feature engineering and understanding the data before modeling.
