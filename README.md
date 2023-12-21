# Stock Market Prediction Repository

This repository contains Python code for predicting stock market trends using machine learning techniques. There are two main scripts in this repository, each focusing on predicting stock prices for different companies.

## File Descriptions

1. **Hyperparameters_Stock_Value_Based_on_Past_Closing_Volume_Extra_features.ipynb:**
   - This Jupyter Notebook file focuses on predicting stock market trends for the company 'NIO' (NIO Inc.). It utilizes historical stock market data downloaded using the 'yfinance' library.
   - The code calculates technical indicators such as Simple Moving Averages (SMA) and Relative Strength Index (RSI) to capture patterns and trends in the data.
   - It creates a Bi-LSTM model and conducts hyperparameter optimization

2. **Stock_Prediction_Based_on_Past_Closing_and_Volume.ipynb:**
   - This Jupyter Notebook file serves as a template for predicting stock market trends for other companies. Users can modify the `stock_list` variable to select different companies for analysis.
   - It downloads historical stock market data for the specified company and calculates SMA and RSI, providing a framework for extending the analysis to other stocks.

## Usage

1. Open and run the Jupyter Notebooks using a Python environment with the required libraries installed.
2. Explore the code, modify parameters, and adapt the scripts for predicting stock prices for additional companies.
3. Analyze the results, visualizations, and technical indicators to gain insights into the predicted stock market trends.

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, torch, sklearn, plotly, yfinance

## Instructions

1. Clone the repository to your local machine.
   ```bash
   git clone git@github.com:shamsbasir/Stock_Prediction.git
