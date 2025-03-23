
# Advanced Statistical Analysis and Model-Based Learning - Home Assignment 5

## Key Topics Covered
- Multiple regression and competing predictors
- Variable selection (Backward selection, AIC, BIC, Cp, LOO-CV)
- Fourier series in regression
- Model validation and assumption checking
- A/B testing and hypothesis testing
- Statistical inference and central limit theorem

## Problem 1: Multiple Regression
- Load the car dataset and identify competing predictors.
- Analyze the relationship between engine cylinders, engine horsepower, and MSRP.
- Propose a method to evaluate the effect of engine horsepower on MSRP.

## Problem 2: Variable Selection
- Implement backward selection and track R-squared and F-test p-values.
- Compute leave-one-out cross-validation (LOO-CV) error for the final model.
- Evaluate all models using MSE, AIC, BIC, Cp, and LOO-CV.
- Build a model using the top 4 predictors from Lasso regression and compute its LOO-CV error.

## Problem 3: Selecting Order of Regression using Cross-Validation
- Process the AnneFrank.csv dataset and sort by hour.
- Use cross-validation to determine the optimal regression order.

## Problem 4: Violation of Assumptions
- Check if residuals follow a normal distribution.
- Analyze time-dependence in residuals using plots and correlation analysis.
- Use Fourier regression to capture periodic trends in residuals.
- Assess improvements in residual correlation after adding Fourier components.

## Problem 5: A/B Testing and Statistical Inference
- Prove that the Z-statistic converges to a standard normal distribution under the null hypothesis.
- Perform an A/B test on ab_test_data.csv to compare conversion rates and revenue.
- Provide a recommendation to the CEO based on statistical evidence while addressing multiple testing concerns.
