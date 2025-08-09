# Flat-and-house-price-predictor

🏠 Flat and House Price Prediction
This project aims to predict flat and house prices using a machine learning pipeline. It covers data collection, preprocessing, exploratory data analysis (EDA), feature engineering, model selection, and evaluation.

1.Data Gathering 📥
Collected housing datasets from online sources (e.g., Kaggle, real estate APIs).
Verified data consistency and correctness.

2.Data Cleaning 🧹
Removed duplicates and irrelevant columns.
Corrected inconsistent data formats.
Handled missing values.

3.Feature Engineering 🛠️
Created new meaningful features (e.g., price per square foot).
Encoded categorical variables with LabelEncoder and OneHotEncoder.
Applied scaling using MinMaxScaler / StandardScaler.

4.Exploratory Data Analysis (EDA) 📊
Visualized distributions, correlations, and price trends.
Used Matplotlib and Seaborn for clear insights.

5.Outlier & Missing Value Handling 🩹
Used IQR method and Z-score for outlier detection.
Imputed missing values with mean/median/mode as per feature type.

6.Feature Selection 🎯
Applied Correlation matrix, Chi-Square test, and Recursive Feature Elimination (RFE).

7.Model Selection & Evaluation 🤖
Models tried:
Linear Regression
Random Forest Regressor
XGBoost Regressor
Gradient Boosting Regressor
Evaluated using RMSE, MAE, and R² score.
