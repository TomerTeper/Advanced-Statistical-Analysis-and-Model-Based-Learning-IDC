# Advanced Statistical Analysis and Model-Based Learning - Home Assignment 2

## Overview

This assignment focuses on probability distributions, properties of the linear model, and numerical methods such as Singular Value Decomposition (SVD). The tasks involve theoretical analysis and computational exercises in Python.

## Key Topics Covered

- Probability review
- Normal, Chi-Squared, t, and F distributions
- Distributional properties of the linear model
- Solving least squares (LS) using Singular Value Decomposition (SVD)

## Instructions

- Include your student IDs and the submission date in the top cell.
- Submit a copy of the notebook with code implemented in the designated sections.
- Theoretical exercises can be written directly in the notebook or submitted as additional notes.

## Problem Breakdown

### Problem 1: Conditional Expectation

- Definition and properties of conditional expectation.
- Proof of the orthogonality principle.
- Application in statistical modeling.

### Problem 2: Sampling from Distributions

- Sampling from uniform, normal, Chi-Squared, t, and F distributions.
- Using the Central Limit Theorem (CLT) for normal approximation.
- Implementing inverse cumulative distribution functions.

### Problem 3: Statistical Modeling

- Applying Singular Value Decomposition (SVD) to solve least squares problems.
- Analyzing the distributional properties of regression models.

### Problem 4: Conditional Distribution

- Given a multivariate normal distribution, find:
  1. The distribution of X given Y = 1.
  2. The joint distribution of X and Y given Z = 1.
  3. The distribution of Y given Z = 2 and X = 3.
  4. Compute the probability that Y is in the interval [-1,1] given Z = 4 and X = 3.

### Problem 5: Distributional Properties of the Least Squares Estimate

- Deriving the least squares estimator for beta.
- Proving key residual properties:
  - The sum of predicted values times residuals is zero.
  - The squared norm of residuals equals the squared norm of y minus the squared norm of predicted values.
- Finding distributions of:
  - The vector of residuals and predicted values.
  - The vector of predicted values and the least squares estimate.
- Bonus: Comparing probabilities of extreme residuals in the predicted vs. true residuals.

### Problem 6: Model Fitting, t- and F-Tests

- Using the house prices dataset from the EDA notebook.
- Implementing t-tests and F-tests for model evaluation.
- Interpreting the statistical significance of model coefficients.

## Code Implementation Highlights

- Custom functions for sampling from different probability distributions.
- Use of NumPy, SciPy, and Matplotlib for numerical computations and visualizations.
- Random seed initialization based on a student ID for reproducibility.
