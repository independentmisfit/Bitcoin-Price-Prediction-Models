# Bitcoin-Price-Prediction-Models
"Predict Bitcoin prices using ARIMA, XGBoost, and LSTM models. This project demonstrates how different models handle highly volatile time series data and compares their performance using key evaluation metrics."

## Overview
This repository contains the code and resources for predicting Bitcoin prices using three distinct modeling approaches: ARIMA (statistical), XGBoost (machine learning), and LSTM (deep learning). The project demonstrates how different models perform on highly volatile time series data, such as Bitcoin prices, and compares their effectiveness using RMSE, MAE, and MAPE metrics. The data used spans from June 2010 to August 2024, and the models are evaluated based on their ability to predict Bitcoin prices for September 2024.

## ^^Models Used**
- ARIMA: A statistical model that captures linear dependencies in time series data.
- XGBoost: A machine learning algorithm known for its accuracy and speed in handling structured data.
- LSTM: A deep learning model designed for sequential data and long-term dependencies, making it suitable for volatile time series like Bitcoin.
## Data
The dataset includes daily closing prices of Bitcoin from June 2010 to August 2024, sourced from reliable financial data providers. This historical data is used for training and evaluating the models.

Installation
To run the code, you'll need the following Python packages:

'''bash
pip install numpy pandas scikit-learn tensorflow statsmodels matplotlib xgboost
Clone the repository:

''' bash
git clone https://github.com/yourusername/Bitcoin-Price-Prediction-Models.git
cd Bitcoin-Price-Prediction-Models

## **Usage**
Prepare the Data:
Load the dataset and perform basic data preprocessing (i.e., handling missing values, normalization, etc.).

## **Train Models:**
Run the scripts for training the models individually:

- ARIMA_model.py: Code for fitting and evaluating the ARIMA model.
- XGBoost_model.py: Code for XGBoost model training and evaluation.
- LSTM_model.py: Code for LSTM model training and evaluation.
## **Evaluate Results:**
Compare the performance using the metrics RMSE, MAE, and MAPE to determine the best model for predicting Bitcoin prices.

## **Key Results**
- The LSTM model outperforms ARIMA and XGBoost with the lowest RMSE (2436.37), indicating that it is better suited for forecasting volatile time series like Bitcoin.
- The ARIMA model provides good baseline performance, while XGBoost struggles with the non-linear, volatile nature of Bitcoin data.
Visualization
- Time series plot of Bitcoin prices over the years.
- Visual comparison of actual vs. predicted prices for each model.
- Error metrics comparison across the models.
## **Future Work**
- Explore hybrid models that combine statistical and machine learning approaches.
- Experiment with other deep learning architectures like GRU or CNNs for further improvement.
