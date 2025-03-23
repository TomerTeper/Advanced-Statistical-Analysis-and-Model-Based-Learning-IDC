# Advanced Statistical Analysis and Model-Based Learning - Home Assignment 1

## Overview

This is the first homework assignment for the **Advanced Statistical Analysis and Model-Based Learning** course (Fall 2024-2025). The assignment covers fundamental statistical and machine learning concepts, including exploratory data analysis (EDA) and the linear model.

## Key Topics Covered

- The Linear Model
- Linear Least Squares
- Exploratory Data Analysis (EDA)
- Normal, Chi-Squared, t, and F distributions
- Sinusoidal Regression and Linearization Trick
- Least Squares and Weighted Least Squares
- Pearson Correlation and Coefficient of Determination ($R^2$)

## Problems

### Problem 1: Exploratory Data Analysis (EDA)

- **Topic:** Data exploration and visualization
- **Tasks:**
  1. Download the **Red Wine Quality Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality).
  2. Select the following five variables for analysis: `density`, `alcohol`, `volatile acidity`, `citric acid`, and `quality`.
  3. Perform an exploratory analysis including:
     - Summary statistics
     - Correlation matrix
     - Data visualization (histograms, scatter plots, etc.)

### Problem 2: The Linear Model

- **Topic:** Linear regression and model evaluation
- **Tasks:**
  1. Fit a linear regression model using `quality` as the response variable and the other four selected variables as predictors.
  2. Interpret the coefficients and assess model performance using:
     - R-squared
     - Mean Squared Error (MSE)
  3. Perform residual analysis to evaluate model assumptions.

### Problem 3: Linearization Trick in Sinusoidal Regression

- **Topic:** Transforming nonlinear models into linear models
- **Tasks:**
  1. Use a linearization trick to fit a sinusoidal regression model.
  2. Transform the nonlinear function into a linear one using logarithms or trigonometric identities.
  3. Fit a least squares model and compare results to the original function.

### Problem 4: Least Squares

- **Topic:** Optimization using least squares
- **Tasks:**
  1. Implement the least squares method for solving an overdetermined system.
  2. Compare analytical and numerical solutions.
  3. Evaluate the performance of the model using residual analysis.

### Problem 5: Weighted Least Squares

- **Topic:** Addressing heteroscedasticity using weighted least squares
- **Tasks:**
  1. Implement weighted least squares regression.
  2. Analyze how different weight choices affect model performance.
  3. Compare results with ordinary least squares (OLS).

### Problem 6: Pearson Correlation and $R^2$

- **Topic:** Understanding correlation and model fit
- **Tasks:**
  1. Compute the Pearson correlation coefficient between selected variables.
  2. Interpret correlation values and their significance.
  3. Compute and analyze the coefficient of determination ($R^2$) for different regression models.
