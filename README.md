# Stock Price Prediction with Machine Learning

This Python algorithm utilizes machine learning, specifically the Random Forest Classifier, to predict the price movement of the user input stock ticker. It involves data preprocessing, model training, and backtesting.

## Overview

The provided code is a Python algorithm that predicts the price movement of the stock using machine learning techniques. It fetches historical data, preprocesses it, trains a Random Forest Classifier model, and performs backtesting to evaluate the model's performance.

## Getting Started

To use the code, follow these steps:

1. Clone the repository or download the source code.

2. Install the required libraries:
   - yfinance: `pip install yfinance`
   - pandas: `pip install pandas`
   - scikit-learn: `pip install scikit-learn`

3. Import the necessary libraries:
   ```python
   import yfinance as yf
   import pandas as pd
   from sklearn.ensemble import RandomForestClassifier
   from sklearn.metrics import precision_score
4. Run the provided Python code in your preferred Python environment.

## Usage

The code performs the following steps:

1. Fetches historical data for the input stock ticker using the `yfinance` library.

2. Preprocesses the data by removing unnecessary columns, creating target variables, and selecting predictors.

3. Trains a Random Forest Classifier model using the selected predictors.

4. Evaluates the model's performance by making predictions on the test data and calculating the precision score.

5. Performs backtesting to simulate trading on historical data and evaluates the predictions using various metrics.


## Info

This is an individual project based on Dataquestio SP500 ML algorithm 
