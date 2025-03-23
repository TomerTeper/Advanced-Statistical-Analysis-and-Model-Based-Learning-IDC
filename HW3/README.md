# Advanced Statistical Analysis and Model-Based Learning - Home Assignment 3

## **Course:** Advanced Statistical Analysis and Model-Based Learning (Fall 2024-2025)

---

## **Topics Covered**

- Statistical Estimation
- Hypothesis Testing (one and two samples)
- Confidence Intervals
- Analysis of Variance (ANOVA)
- Regression and Hypothesis Testing

---

## **Problems Overview**

### **Problem 1: Correlated Data**

- Examines the variance and expected value of the standard variance estimate in correlated data.
- Demonstrates the impact of correlation on variance estimation using the MA(1) model.
- Uses variance-covariance properties and Slutsky's theorem to derive asymptotic normality.

### **Problem 2: Variance Estimation**

- Derives a \((1 - \alpha)\) confidence interval for variance \(\sigma^2\).
- Computes confidence interval bounds for small sample sizes (\(n = 2, \dots, 10\)) and \(\alpha = 0.05\).
- Determines the minimum sample size needed to achieve a \(95\%\) confidence interval with a width of \(0.1s^2\).

### **Problem 3: Two-Sample Testing**

- Considers hypothesis testing for two independent samples.
- Derives the two-sample \(t\)-test statistic.
- Investigates Type I and Type II errors in two-sample comparisons.

### **Problem 4: ANOVA Decomposition**

- Proves the fundamental ANOVA decomposition:
  $$
  \mathrm{SS}_{\text{tot}} = \mathrm{SS}_{\text{within}} + \mathrm{SS}_{\text{between}}
  $$
- Expands and derives the sum of squares decomposition.
- Establishes connections between within-group and between-group variations.

### **Problem 5: Regression and Hypothesis Testing**

- Analyzes rainfall data from Tel Aviv beach (dataset: `rainfall_TLV_beach.csv`).
- Implements a linear regression model with seasonal components:
  $$
  y_t = \beta_0 + \beta_1 \cos( 2\pi(t/365)) + \beta_2 \sin( 2\pi(t/365)) + \epsilon_t
  $$
- Derives and computes the two-sample \(t\)-test statistic.
- Constructs an ANOVA table for \(k=2\) and computes the \(F\)-statistic.
- Proves the relationship \(t^2 = F\) in hypothesis testing.
- Compares the power of the \(t\)-test and the \(F\)-test.

---

## **Key Implementations**

- Statistical estimation using Python.
- Confidence interval computation and chi-square distributions.
- Hypothesis testing frameworks for one-sample and two-sample problems.
- ANOVA decomposition and variance partitioning.
- Linear regression modeling with seasonal effects.
- Comparison of \(t\)-test and \(F\)-test power.
