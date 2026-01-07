# Coca-Cola Stock Analysis

This project performs an analysis of the historical stock data for The Coca-Cola Company (KO). The analysis is contained within a Jupyter Notebook and utilizes various data files to explore trends and other insights related to Coca-Cola's stock performance.

## Project Notebook

This project consists of a single Jupyter Notebook, `Project1.ipynb`, which contains all the code and analysis.

### Notebook Details

The `Project1.ipynb` notebook covers the following steps:
*   **Data Loading and Cleaning:** Imports historical stock data and handles missing values.
*   **Feature Engineering:** Calculates technical indicators like Moving Averages (20-day and 50-day), Daily Returns, and Volatility.
*   **Exploratory Data Analysis (EDA):** Visualizes the stock's closing price, trading volume, and feature correlations.
*   **Machine Learning:** Trains a RandomForestRegressor model to predict the closing price based on the engineered features.
*   **Model Evaluation:** Assesses the model's performance using metrics like Mean Squared Error (MSE) and Mean Absolute Error (MAE).
*   **Live Prediction:** Fetches recent stock data using `yfinance` and uses the trained model to make a prediction on the latest data.

