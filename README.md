# My-Custom-Linear-Regression


# Salary Prediction using Custom Linear Regression

## Overview

This project involves predicting salaries based on years of experience using a custom linear regression model. The dataset contains two columns: `Years of Experience` and `Salary`. The goal is to predict the salary for a given number of years of experience and visualize the best-fit line using our custom linear regression model.

## Dataset

The dataset consists of the following columns:
- `Years of Experience`: The number of years a person has been working.
- `Salary`: The corresponding salary for the given years of experience.

## Objectives

1. **Predict Salary**: Given a new value of years of experience, predict the corresponding salary.
2. **Visualize Best Fit Line**: Plot the data points and visualize the best fit line derived from our custom linear regression model.

## Key Features

- Implementation of a custom linear regression model from scratch.
- Visualization of data points and the best fit line using `matplotlib`.
- Easy-to-understand code and clear documentation for educational purposes.

## Installation

To run this project, you will need Python and the following libraries:
- `numpy`
- `matplotlib`
- `pandas` 


## Usage

1. **Load the Dataset**: Load the dataset containing years of experience and salary.
2. **Train the Model**: Use the custom linear regression model to train on the dataset.
3. **Predict Salary**: Predict the salary for a new value of years of experience.
4. **Visualize**: Plot the original data points and the best fit line.

Example usage:
# Load dataset
data = pd.read_csv('path/to/your/dataset.csv')

# Predict salary
years_of_experience = 5
predicted_salary = model.predict(years_of_experience)
print(f'Predicted Salary for {years_of_experience} years of experience: {predicted_salary}')

# Visualize best fit line
model.plot_best_fit_line(X, y)
```

## Custom Linear Regression Model

The custom linear regression model includes:
- **Fit Method**: Calculates the best-fit line using the least squares method.
- **Predict Method**: Predicts the salary for a given years of experience.
- **Plot Method**: Visualizes the data points and the best fit line.

## Visualization custom linear regression model

## Thank Yoy!
