# tip-prediction-linear-regression

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

    - Overfitting vs. generalization

    - Model evaluation using MSE

    - Visualization with Plotly (2D, 3D, polynomial curves)
