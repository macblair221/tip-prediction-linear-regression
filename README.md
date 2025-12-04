# Tip prediction linear regression analysis

This project analyzes how different features influence the accuracy of predicting restaurant tip amounts using linear regression. The goal is to compare multiple models, evaluate their performance, and explore how feature engineering affects predictions.

The project was completed in Python using Jupyter Notebook, NumPy, Pandas, and Plotly. 

# Overview

I built several regression models to determine which features best predict the tip a customer leaves. The models include:

  1. Simple linear regression using total bill

  2. Multivariate regression using total bill and table size

  3. Standardized two-feature model

  4. Fourth-degree polynomial regression

  5. Linear regression with one-hot encoded categorical features (day of week)

All models were trained using the closed-form normal equation and evaluated using mean squared error (MSE).

# Key Concepts Demonstrated

    - Linear regression from first principles

    - Manual design matrix creation

    - Feature engineering: polynomial features, standardization, and one-hot encoding
    
    - Multicollinearity awareness and avoiding rank-deficient matrices

# Results Summary

Model Performance (lower MSE is better):

  1. Total Bill Only: approx 1.0360

  2. Total Bill + Table Size: approx 1.0146

  3. Standardized Two-Feature: approx 1.0146

  4. Fourth-Degree Polynomial: approx 0.9454

  5. Total Bill + One-Hot Encoded Day: approx 1.0317

The polynomial model produced the lowest MSE but failed when extrapolating, demonstrating classic overfitting (example: a 350 dollar bill produced an unrealistic predicted tip above 100,000 dollars).

# Repository Contents

  - tip_prediction.ipynb (main notebook)

  - README.md

  - images folder (optional for storing exported charts)
