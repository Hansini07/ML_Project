# Crop Yield Prediction Using Ridge, Lasso, and Elastic Net

## About the Project

This project predicts **crop yield** using agricultural, soil, and weather-related factors. It applies and compares three regularized regression techniques:

- Ridge Regression
- Lasso Regression
- Elastic Net Regression

## Dataset

- **Rows:** 19,689
- **Columns:** 9
- **Target:** `yield`
- **Problem Type:** Regression
- **Learning Type:** Supervised Learning

The dataset contains information about crops, area, production, fertilizer, pesticides, season, state, and yield. Additional soil and weather data are also integrated.

## Methodology

1. Data preprocessing
2. Exploratory Data Analysis
3. Correlation analysis
4. Feature engineering
5. Data scaling and encoding
6. Train-test splitting
7. Ridge, Lasso, and Elastic Net modeling
8. Model evaluation and comparison

## Models

**Ridge Regression** – Uses L2 regularization to handle multicollinearity.

**Lasso Regression** – Uses L1 regularization and performs feature selection.

**Elastic Net** – Combines L1 and L2 regularization.

## 📈 Evaluation Metrics

- R² Score
- RMSE
- MAE
- MSE

## 🛠️ Technologies

Python, Pandas, NumPy, Matplotlib, Scikit-learn, Google Colab

## 👩‍💻 Project

An academic machine learning project focused on **crop yield prediction using regularized regression techniques**.
