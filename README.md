#  Car Price Prediction Using Machine Learning

##  Project Overview

This project predicts car prices based on vehicle specifications such as brand, model, year, engine size, mileage, fuel type, and transmission.

The objective is to build a regression model that can estimate the price of a car using historical vehicle data.

---

##  Dataset

Source:
https://www.kaggle.com/datasets/amjadzhour/car-price-prediction

Dataset contains 1000 records with the following features:

- Make
- Model
- Year
- Engine Size
- Mileage
- Fuel Type
- Transmission
- Price (Target Variable)

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook / Kaggle Notebook

---

##  Project Workflow

### 1. Data Loading
Loaded dataset using Pandas.

### 2. Data Inspection
- Checked dataset shape
- Checked data types
- Verified missing values

### 3. Data Preprocessing

#### Categorical Features
Applied One-Hot Encoding on:

- Make
- Model
- Fuel Type
- Transmission

#### Numerical Features
Applied Standard Scaling on:

- Year
- Engine Size
- Mileage

### 4. Train-Test Split

- Training Data: 80%
- Testing Data: 20%

### 5. Model Building

Implemented and compared:

1. Linear Regression
2. Ridge Regression
3. Lasso Regression

### 6. Model Evaluation

Evaluation Metrics:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

##  Results

| Model | R² Score | MAE |
|---------|---------|---------|
| Ridge Regression | 0.8172 | 1810.19 |
| Lasso Regression | 0.8171 | 1810.54 |
| Linear Regression | 0.8171 | 1810.55 |

### Best Model

 Ridge Regression achieved the highest R² Score:

- R² Score = 0.8172
- MAE = 1810.19

---

##  Prediction System

The project also includes a user input prediction system where users can enter:

- Make
- Model
- Year
- Engine Size
- Mileage
- Fuel Type
- Transmission

and receive the predicted car price instantly.

Example:

Predicted Price: 30107.65

---

##  Future Improvements

- Hyperparameter tuning
- Random Forest Regression
- XGBoost Regressor
- Streamlit Web App Deployment
- Feature Importance Analysis

---

##  Author

**Priya Rathod**

Kaggle:
https://www.kaggle.com/priyarathod789512

GitHub:
https://github.com/your-github-username
