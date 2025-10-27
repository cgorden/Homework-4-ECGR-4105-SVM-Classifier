# Machine Learning: SVM Classification and Regression

This repository contains two machine learning problems using Support Vector Machines.

## Setup

Install required packages:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Problem 1: Breast Cancer Classification

Classifies breast cancer tumors as benign or malignant using SVM with different kernels compared against Logistic Regression.

Run the script. It will load the built-in breast cancer dataset and train 5 models.

### Expected Output

Console will show dataset info, model performance metrics (Accuracy, Precision, Recall), and identify the best model.

Three plots will be generated:
- Individual metric comparisons
- Combined performance bar chart
- Confusion matrices

## Problem 2: Housing Price Prediction

Predicts house prices using Support Vector Regression with different kernels compared against Ridge and Lasso regression.

Requires Housing.csv file in the same directory with columns: area, bedrooms, bathrooms, stories, mainroad, guestroom, basement, hotwaterheating, airconditioning, parking, prefarea, price.

Run the script to train 6 regression models.

### Expected Output

Console will show model performance metrics (RMSE, MAE, R2) sorted by best R2 score.

Three plots will be generated:
- Performance comparison bar chart
- Actual vs Predicted scatter plot for best model
- Residuals distribution histogram

- 
