# Customer Spending Prediction Using Decision Tree Regressor

This project focuses on analyzing customer purchasing behavior from an online retail dataset and building a machine learning model using Decision Tree Regressor to predict total customer spending.

## Objective

To predict the total amount spent by each customer based on their purchase behavior using a decision tree regression model.

## Dataset

The dataset contains historical transaction records of a retail store. Each row represents a product purchase.

## Preprocessing Steps

- Removed rows with missing `CustomerID` or `Description`
- Removed rows with negative or zero values in `Quantity` or `UnitPrice`
- Calculated `TotalPrice` by multiplying `Quantity` and `UnitPrice`
- Grouped data by `CustomerID` to aggregate total purchases, quantity, and spending

## Features Used

- Number of unique invoices per customer
- Total quantity of items purchased
- Total amount spent (target variable)

## Model

A Decision Tree Regressor was trained on the processed data to predict total spending per customer.

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
