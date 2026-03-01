# Auto-Price_Pred
Auto Price Prediction using Machine Learning with EDA and Regression models. An end-to-end ML project to predict automobile prices based on vehicle features.



🚗 Auto Price Prediction

End-to-End Machine Learning Project | Regression | Predictive Analytics

📌 Project Overview

This project focuses on predicting automobile prices using various vehicle attributes such as engine size, horsepower, fuel type, body style, and more.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, regression modeling, and performance evaluation.

The goal is to build an accurate regression model that estimates car prices based on given features.

🎯 Objectives

Perform detailed Exploratory Data Analysis (EDA)

Clean and preprocess the dataset

Handle missing values

Encode categorical variables

Train multiple regression models

Compare models and select the best-performing one

📂 Dataset Information

Dataset File: auto_imports.xls

Notebook: Auto Price_Pred.ipynb

Features include:

Symboling

Fuel Type

Aspiration

Body Style

Drive Wheels

Engine Location

Wheel Base

Length, Width, Height

Curb Weight

Engine Type

Horsepower

City MPG / Highway MPG

Price (Target Variable)

🔎 Exploratory Data Analysis (EDA)

Analysis performed:

Price distribution

Correlation heatmap

Horsepower vs Price relationship

Engine size vs Price

Fuel type comparison

Outlier detection using IQR method

📊 Key Insights:

Engine size and horsepower strongly influence price.

Larger vehicles tend to have higher prices.

Some features show multicollinearity.

Outlier handling improved model accuracy.

⚙️ Data Preprocessing

Missing value treatment

Label Encoding / One-Hot Encoding

Feature Scaling (StandardScaler / MinMaxScaler)

Train-Test Split

🤖 Machine Learning Models Implemented

Linear Regression

Ridge Regression

Lasso Regression

Decision Tree Regressor

Random Forest Regressor

XGBoost Regressor

📈 Model Evaluation Metrics

R² Score

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

Cross Validation

Hyperparameter Tuning (GridSearchCV)

🏆 Best Model

After comparing regression models:

Random Forest / XGBoost achieved the highest R² score.

Tree-based models performed better due to:

Capturing non-linear relationships

Handling feature interactions

Robustness to outliers

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

Jupyter Notebook
