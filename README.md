# Multiple Linear Regression — Boston Housing

## Project Overview

This project builds and evaluates a Multiple Linear Regression model on the Boston Housing dataset to understand how features like crime rate, number of rooms, and property tax relate to median house value, and to predict prices from those features.

## Results

- R² = 0.707 (Adj. R² = 0.698) — the model explains about 70.7% of the variance in median house price (MEDV)
- F-statistic = 82.72 (p < 0.001) — the model as a whole is statistically significant
- Strongest predictors (by t-statistic magnitude):
      LSTAT (% lower-status population): strongest effect overall, negative — higher LSTAT → lower price
      DIS (distance to employment centers): negative — farther from job centers → lower price
      PTRATIO (pupil-teacher ratio): negative — worse school ratios → lower price
      RM (avg. rooms per dwelling): positive — more rooms → higher price
      NOX (nitric oxide concentration): negative — more pollution → lower price


## Tools and Technologies

- Python
- Jupyter Notebook
- pandas
- numPy
- scikit-learn
- statsmodels
- dmba
- matplotlib
- seaborn

## Project Workflow

1. Importing the required libraries
2. Loading the dataset
3. Exploring and understanding the data
4. Data preprocessing(Cleaning, Handling Missing Values and Visualization)
5. Splitting the data into training and testing sets
6. Building the Multiple Linear Regression model
7. Making predictions
8. Evaluating model performance

## Machine Learning Model

Multiple Linear Regression is used to understand the relationship between a dependent variable and multiple independent variables.

## Dataset

The project uses the Boston Housing dataset for analysis and model development.

## Project Files

- `ML_Project1(MLR).ipynb` – Jupyter Notebook containing the complete analysis and machine learning implementation.
- `BostonHousing.csv` – Dataset used for the project.
- `Screenshot 2026-07-28 233828.png` – Project screenshot.

## Conclusion

This project provided practical experience in data preprocessing, exploratory data analysis, model building, prediction, and evaluation using Python and Multiple Linear Regression.
