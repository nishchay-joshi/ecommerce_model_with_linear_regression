# Ecommerce Customer Analysis and Prediction

This project explores an e-commerce customer dataset to understand customer behavior and predict yearly spending using multiple linear regression. The analysis focuses on features such as:

- Average Session Length
- Time on App
- Time on Website
- Length of Membership

## Dataset
The dataset `Ecommerce_Customers.csv` contains customer information including demographic data, app and website usage, and yearly spending.

## Key Features
- Exploratory Data Analysis (EDA) with visualizations:
  - Scatter plots and jointplots
  - Pairplots to examine correlations
  - Regression plots
- Multiple Linear Regression Model
- Model evaluation using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
- Coefficient interpretation to guide business strategy

## Findings
- **Length of Membership** is the strongest predictor of yearly spending.
- **Time on App** has a greater effect on spending than **Time on Website**.
- Increasing app engagement and fostering long-term membership can boost revenue.


## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
