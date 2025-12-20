Gemstone Price Prediction using Linear Regression
Project Overview

This project performs exploratory data analysis and gemstone price prediction using a linear regression model. The objective is to analyze the relationship between gemstone features and price and build a regression model using manual preprocessing techniques without pipelines.

Dataset

File: gemstone.csv

Target Variable: price

Features include numerical attributes such as carat, depth, table, and dimensions, and categorical attributes such as cut, color, and clarity.

Tools and Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Exploratory Data Analysis

Examined dataset structure using head, info, and describe

Checked for missing values

Plotted correlation heatmap for numerical features

Visualized price distribution using a histogram

Data Preprocessing

Separated target variable from features

Identified categorical and numerical columns

Applied one-hot encoding to categorical features

Combined numerical and encoded categorical features manually

Split data into training and testing sets with an 80:20 ratio

Model Development

A linear regression model was trained using the processed training dataset and used to generate predictions on the test dataset.

Model Evaluation

The model performance was evaluated using:

Root Mean Squared Error (RMSE)

R-squared (R²) score

How to Run

Clone the repository

Ensure gemstone.csv is present in the project directory

Run the notebook or Python script using Python or Google Colab

Learning Outcomes

Practical experience with exploratory data analysis

Manual preprocessing of numerical and categorical data

Implementation of linear regression for price prediction

Evaluation of regression models using standard metrics

Future Improvements

Feature scaling and normalization

Experiment with advanced regression models

Cross-validation and hyperparameter tuning

Model deployment as a web application

Author

Aarthy Swetha M
