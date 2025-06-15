# E-Commerce Customer Spending Prediction

This project uses linear regression to predict how much a customer will spend yearly on an e-commerce platform, based on their app usage, website interaction, and membership history.

## Dataset
- CSV file: `Ecommerce Customers.csv`  
  (Contains customer behavior metrics and yearly spending)

## Tools Used
- Python (Pandas, Matplotlib, Seaborn, scikit-learn)
- Jupyter Notebook

## Objectives
- Identify which customer behavior factors influence spending the most
- Build a regression model to predict yearly customer spending
- Evaluate model performance and interpret coefficients

## Key Insights
- **Length of Membership** is the strongest predictor of yearly spending — loyal customers tend to spend more.
- Time spent on the **Mobile App** has a higher impact on spending than time on the website, suggesting the app is more effective for driving sales.
- The model achieved a strong **R² score**, indicating a good fit for the data.
- Residuals are normally distributed, confirming the linear regression model is appropriate.

## How to Run
1. Place `Ecommerce Customers.csv` in your working directory
2. Open and run `Customer_Spending_Prediction.ipynb`

## Status
Finished
