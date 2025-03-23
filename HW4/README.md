# Advanced Statistical Analysis and Model-Based Learning - Home Assignment 4

## Overview

This assignment covers ANOVA, Bonferroni's correction, and confidence intervals in regression.

## Key Topics Covered

- ANOVA and Multiple Comparisons
- Hypothesis Testing with Bonferroni's Correction
- Confidence Intervals in Linear Regression

---

## Problem 1: ANOVA and Multiple Comparisons

**Overview:** Use ANOVA to analyze how winery and price affect wine quality in the Kaggle wine dataset.

### Steps:

1. **Data Cleaning:**

   - Rename "Gamla" to "Golan Heights Winery".
   - Keep relevant records and remove duplicates.
   - Include only wineries with at least 3 samples.

2. **Analysis:**

   - Perform ANOVA to evaluate the impact of winery and price on quality.
   - Interpret statistical significance.

---

## Problem 2: Exact Size of Bonferroni's Test

**Overview:** Analyze Bonferroni’s correction for multiple hypothesis testing and determine its exact size under independence.

### Tasks:

1. Show that Bonferroni’s procedure rejects H0 if min(pi) ≤ α/n.
2. Derive the exact size of the test under independence.
3. Compare Bonferroni’s bound (α) to the exact test size for n = 2, ..., 50.
4. Discuss the results.

---

## Problem 3: Prediction in Simple Regression

**Overview:** Explore confidence intervals in simple regression and derive predictive intervals for new observations.

### Tasks:

1. **Variance:** Find the variance of y(n+1) - (β0 + β1 x(n+1)) and explain why it's larger than that of β0 + β1 x(n+1).
2. **Confidence Interval:** Derive a (1-α) confidence interval for y(n+1).
   - Compare its width to that of β0 + β1 x(n+1).
   - Identify when the interval is narrowest.
3. **Averaging Two Responses:** Find a confidence interval for the mean of two responses at the same x(n+1) and compare it to (2).
