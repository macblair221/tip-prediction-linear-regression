# tip-prediction-linear-regression

Predicting Restaurant Tips Using Linear Regression and Feature Engineering

This project explores how different features influence the accuracy of tip prediction models using the Tips dataset.
The goal is to build, visualize, and compare several linear regression models while demonstrating core machine learning concepts such as feature engineering, multicollinearity, standardization, and overfitting.

The project was developed entirely in Python using NumPy, Pandas, and Plotly, inside a Jupyter Notebook.

Overview

I built and evaluated multiple regression models to understand which factors best predict the tip customers leave at a restaurant.
The models tested include:

Simple Linear Regression using total bill

Multivariate Linear Regression using total bill + table size

Standardized Two-Feature Model

Fourth-Degree Polynomial Regression to study overfitting

Model with One-Hot Encoded Categorical Features (day of the week)

Each model was trained using the normal equation, and evaluated using mean squared error (MSE).

Key Concepts Demonstrated
• Linear Regression from First Principles

Design matrices were created manually and parameters were solved using

𝑤
∗
=
(
𝑋
𝑇
𝑋
)
−
1
𝑋
𝑇
𝑦
.
w
∗
=(X
T
X)
−1
X
T
y.
• Feature Engineering

The project includes:

Polynomial features up to degree 4

Standardization

One-hot encoding of categorical variables

Comparison of feature importance

• Model Evaluation

Each model’s performance was assessed with:

Mean Squared Error (MSE)

Visual inspection through plots (2D, 3D, polynomial curves)

Extrapolation behavior (to show overfitting)

• Visualization

Interactive Plotly charts were generated, including:

Scatter plots

Regression lines

3D regression surfaces

Polynomial hypothesis functions

Results Summary
Model	MSE
Total Bill Only	~1.0360
Total Bill + Table Size	~1.0146
Standardized Two-Feature	~1.0146
Fourth-Degree Polynomial	~0.9454
Total Bill + OHE Day	~1.0317
