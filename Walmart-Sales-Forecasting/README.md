# Walmart Sales Forecasting
This repository contains a Python-based project to forecast weekly sales for Walmart stores using the Walmart Recruiting Store Sales Forecasting dataset. The solution employs time-series analysis and machine learning models like RandomForestRegressor and XGBoost to predict sales based on historical data.
## Overview
 **Dataset**: Walmart Recruiting Store Sales Forecasting (from Kaggle or UCI).
 
 **Goal**: Predict weekly sales using features like date, store, department, and holiday indicators.
 
 **Models**: Random Forest, XGBoost with time-based features and rolling averages.
 
 **Tools**: Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib.
## Features
- Loads and preprocesses ZIP-compressed CSV data in Google Colab.
- Creates time-based features (month, lag values, holidays).
- Splits data for training and testing with time-series validation.
- Visualizes actual vs. predicted sales and feature importance.
- Includes bonus steps for seasonal decomposition and model comparison.
## Setup
1.	Clone the repository:
      git clone https://github.com/your-username/walmart-sales-forecasting.git
1.	Install dependencies: 
      pip install pandas numpy scikit-learn xgboost matplotlib
2.	Upload the walmart-recruiting-store-sales-forecasting.zip dataset to Google Colab's session storage.
## Usage
1.	Open the notebook in Google Colab.
2.	Run all cells sequentially to extract data, preprocess, train models, and visualize results.
3.	Adjust file paths or parameters (e.g., zip_file) if needed.
