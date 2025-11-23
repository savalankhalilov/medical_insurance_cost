# Model benchmarking for choosing the best model to predict medical insurance cost.

## 1. Project Overview
This project predicts medical insurance costs using machine learning and deep learning techniques.
By analyzing customer health and demographic data the model estimates the expected insurance charges.
This can help insurance companies and healthcare organizations evaluate risk-based pricing.

The workflow includes:
- Exploratory data analysis and visualization
- Data cleaning and categorical encoding
- Model training and evaluation using regression techniques
- Hyperparameter optimization using Optuna

## 2. Dataset
The dataset contains individual medical insurance records with the following features:
- Age  
- Gender  
- BMI  
- Number of children  
- Smoking status  
- Residential region  
- Charges (target variable)

(Source: https://www.kaggle.com/datasets/mirichoi0218/insurance)

## 3. Models used
- K-Nearest Neighbors 
- Random Forest
- XGBoost
- CatBoost
- LightGBM
- Artificial Neural Network


## 4. Result
The best performing model is optimizied CatBoost.
- Test R2: 88.36%
- Train R2: 87.10%
