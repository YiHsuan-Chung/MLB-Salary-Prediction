# MLB Player Salary Prediction Using XGBoost (2015–2024)

## Project Overview
This project uses XGBoost to predict MLB player salaries based on player statistics from 2015 to 2024. It also compares models using all features and selected features to examine how feature selection affects prediction accuracy.

## Methods
- Data preprocessing and one-hot encoding
- XGBoost regression
- GridSearchCV with 5-fold cross-validation
- Feature importance and feature selection
- Model evaluation using R² and MSE

## Results
The models showed different prediction results across the ten years. The highest test R² was 0.8311 in 2017, while 2020 had the lowest R² of 0.4477.

Feature selection reduced the number of features, but it did not always improve prediction accuracy.

## My Contribution
This project was part of a university research project. My main responsibility was developing and evaluating the XGBoost models.

## Tools
Python, pandas, scikit-learn, XGBoost, Matplotlib
