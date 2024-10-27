# Salary Prediction Model

## Overview
This project is focused on building a linear regression model to predict salaries based on years of experience. The dataset consists of salary data and corresponding years of experience.

## Files
- `linear_regression_model.ipynb`: Jupyter notebook containing the code and analysis.

## Data Description
- `years_of_experience`: An array representing the years of experience.
- `salary`: An array representing the salary corresponding to each year of experience.

## Methodology
1. **Data Preparation**: Arrays for years of experience and salaries are created using NumPy.
2. **Model Calculation**:
   - Calculate the mean of years of experience and salaries.
   - Compute the coefficients for the linear regression (slope and intercept) using the formula derived from the least squares method.
3. **Results**:
   - Display the calculated slope (`m`) and intercept (`b`) of the linear regression line.
   - `m` represents the increase in salary for each year of experience.
   - `b` is the starting salary when the experience is zero.

## Execution
Run all cells in the Jupyter notebook to see the process and the results of the linear regression analysis.
