MPG Prediction Using Linear Regression
Overview
This repository contains Python code to predict vehicle MPG (Miles Per Gallon) using a linear regression model trained on a dataset with various car features.

Steps
Import Libraries: Pandas, NumPy, Matplotlib for data handling and visualization. Scikit-learn for model building and evaluation.

Read Data: Load Data.csv using Pandas.

Data Exploration: Check data structure and sample records using data.info() and data.head().

Data Preprocessing:

Drop unnecessary columns (displacement, cylinders, car name).
Handle missing values in horsepower by dropping rows with NaN and converting to integer type.
Data Visualization: Plot scatter plots (acceleration vs mpg, weight vs mpg) to visualize relationships.

Define Features and Label: Separate features (horsepower, weight, acceleration, model year, origin) and label (mpg).

Split Data: Use train_test_split() to create training and test sets.

Model Building: Initialize and train a Linear Regression model using LinearRegression() from scikit-learn.

Model Evaluation: Calculate R-squared score (r2_score) to assess model performance on the test set.
