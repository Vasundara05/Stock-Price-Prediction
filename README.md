# Stock Price Prediction

## Overview
This repository contains Jupyter notebooks demonstrating various machine learning models for stock price prediction. 
Currently, the models are demonstrated using Google stock data, but they can be easily adapted to predict the stock prices of any company by changing the ticker name.

## Models Implemented
- Linear Regression: A basic model to predict stock prices based on historical data.
- Other Models: Additional models and techniques will be added.

## Flexibility
The models provided in this repository are designed to be easily adaptable. You can replace the ticker symbol used in the code to predict the stock prices of any other company. 

# Linear Regression for Stock Price Prediction
Linear Regression:-Linear Regression is a simple yet powerful algorithm used for predicting continuous values based on the relationship between input features and the target variable.

## Libraries Used
The following libraries are used in this notebook:
- NumPy: For numerical operations and array handling.
- Pandas: For data manipulation and analysis.
- yFinance: For downloading stock price data.
- Matplotlib: For creating visualizations.
- Scikit-Learn: For implementing the Linear Regression model and evaluation metrics.

## Usage
1. Clone the Repository
   ```bash
   git clone https://github.com/Vasundara05/Stock-Price-Prediction.git
   
2. Navigate to the Notebooks Directory
   ```bash
   cd stock-price-prediction/notebooks
   
3. Install Required Packages
   - Make sure to install the required libraries by running:
   ```bash
   pip install numpy pandas yfinance matplotlib scikit-learn

4. Open the Notebook
   - Launch Jupyter Notebook and open the SPLinearRegression.ipynb file:
   ```bash
   jupyter notebook SPLinearRegression.ipynb

5. Update Ticker Symbol if required
   - In the notebook, find the cell where the ticker symbol is specified (e.g., ticker = 'GOOGL').
   - Replace 'GOOGL' with the ticker symbol of the company you want to analyze (e.g., 'MSFT' for Microsoft)

6.Run the Notebook
   - Execute all cells in the notebook to fetch data for the new ticker, preprocess the data, train the Linear Regression model, and evaluate its performance.
