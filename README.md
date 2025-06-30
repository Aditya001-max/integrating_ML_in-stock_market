# Integrating_ML_in-Stock_Market


## Overview

This is a machine learning-based stock trading system that predicts future stock prices using historical data and neural networks. Built for flexibility and customization, it enables users to train, test, and simulate trading strategies with ease.

## Features
-   Predict stock prices with deep learning models (LSTM, indicators)
-   Fetch historical data via Alpha Vantage API
-   Modular, customizable codebase
-   Real-time trading simulation
-   Visual insights and performance charts

## Requirements

-   Python 3.5+
-   Libraries: alpha_vantage, pandas, numpy, sklearn, keras, tensorflow, matplotlib
  Install all dependencies: by `pip install -r requirements.txt`


## How to use this model

>> First Clone the repository

>> Install dependencies by using pip install `pip install -r requirements.txt`

>> Fetch and save stock data to CSV `python data_csv_saved_files.py --help`

>> Edit one of the model files to accept the symbol you want

>> Modify the model architecture as needed

>> Modify dataset preprocessing / history_points inside util.py

>> Train the model `python training_model_script.py` or `python initial_model.py`

>>  Run the trading algorithm on the newly saved model `python stock_trade_algorithm.py`


## Visual Output
>>  Predicted vs actual prices
>>  Model loss and accuracy
>>  Technical analysis overlays

## Learn more 

## License

This project is released under the GPL-3.0 License.(https://www.gnu.org/licenses/quick-guide-gplv3.html)
