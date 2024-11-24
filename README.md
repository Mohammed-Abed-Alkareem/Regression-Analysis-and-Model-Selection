

# Regression Analysis and Model Selection

## Overview

This project involves building and evaluating regression models to predict car prices using the **YallaMotors Cars Dataset**. The aim is to explore linear and nonlinear regression techniques, apply feature selection and regularization, and perform hyperparameter tuning to optimize model performance.

---

## Project Objectives

1. Perform **data preprocessing** to clean, normalize, and prepare the dataset for modeling.
2. Build **linear and nonlinear regression models**, including:
   - **Linear Regression**
   - **LASSO Regression**
   - **Ridge Regression**
   - **Polynomial Regression**
   - **Radial Basis Function (RBF) Regression**
3. Compare models using performance metrics:
   - R-squared
4. Implement **forward feature selection** to optimize input features.
5. Apply **regularization techniques** to minimize overfitting.
6. Use **grid search** for hyperparameter tuning.
7. Evaluate the final model on a test dataset and report performance.

---

## Dataset

- **Source**: [Kaggle Cars Dataset](https://www.kaggle.com/datasets/ahmedwaelnasef/cars-dataset/data)
- **Description**: Includes ~6,750 rows and 9 columns, scraped from the YallaMotors website. Features include car make, model, year, mileage, engine size, and price.
- **Objective**: Predict car prices as the target variable.

**Data Preprocessing Steps**:
- Handle missing values
- Encode categorical variables
- Normalize numerical features
- Convert car prices to a consistent currency (e.g., USD)

---

## Steps Implemented

### 1. Data Preparation
- Data cleaning, feature encoding, and standardization
- Splitting into training (60%), validation (20%), and testing (20%) sets

### 2. Model Development
- Implemented regression models:
  - Linear Regression (closed-form solution and gradient descent)
  - Polynomial Regression (degrees 2–10)
  - LASSO and Ridge Regression
  - RBF Regression

### 3. Model Selection
- Evaluated using the validation set
- Selected best model based on MSE and R-squared metrics

### 4. Feature Selection
- Forward selection to iteratively add features that minimize validation error

### 5. Regularization
- Explored LASSO and Ridge with varying regularization parameters (λ)
- Used grid search to determine optimal λ

### 6. Hyperparameter Tuning
- Tuned hyperparameters for all models using grid search

### 7. Final Model Evaluation
- Assessed the best-performing model on the test set
- Compared predicted vs actual car prices

---

## Results

- Detailed results, metrics, and visualizations are included in the report.
- Insights on model performance and limitations.

---
