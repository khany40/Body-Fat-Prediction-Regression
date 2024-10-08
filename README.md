# Body Fat Prediction using Linear Regression

## Introduction
The goal of this project is to predict a person's weight based on several measurable physical attributes such as age, height, and various body measurements (e.g., neck, chest, abdomen). This regression problem is solved using a Linear Regression model, which can be highly useful in healthcare contexts for understanding body composition.

## Dataset
The dataset is sourced from Kaggle and contains 252 rows and 15 columns, with attributes like Age, Height, and various circumferences. The target variable is Weight.

## Objective
- Load and preprocess the dataset.
- Train a Linear Regression model.
- Evaluate the model's performance using Mean Squared Error (MSE).
- Reflect on the results and model performance.

## Results
The model's performance is measured using the Mean Squared Error (MSE). The lower the MSE, the better the prediction accuracy. The exact MSE value depends on the training and testing data split and how well the model generalizes to unseen data.

## Reflection
- **Why this dataset?** The dataset contains physical measurements commonly used in healthcare, making it relevant for predicting body composition.
- **What problem are you solving?** We aim to accurately predict a person’s weight based on physical measurements.
- **What are the results?** MSE is used to evaluate how closely predicted weights align with actual weights. Lower MSE indicates better performance.
