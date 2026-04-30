# MS22-Theory-Assingment-1--Multi-Output Time-series Forecasting
**Department of Computer Science, Faculty of Sciences, Jamia Millia Islamia**
**M.Sc. Artificial Intelligence and Machine Learning**
**Project Overview**
This repository contains the implementation of a Multi-Output Time-series Forecasting model using LSTM (Long Short-Term Memory) neural networks. The objective is to predict future stock prices based on historical data as part of the MS-22 coursework.
## Dataset **Source:** NIFTY-50 Stock Market Data (2000 - 2021) from NSE (National Stock Exchange) India.  **Link:** [Kaggle NIFTY-50 Dataset](https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data/data)    **Assigned File:** `[ASIANPAINT.csv]`
## Model Details
This implementation follows the multi-input/multi-output sliding window approach: **Input:** Last 10 days of data across 11 features. **Output:** Predicted values for the next 5 days across 11 features. **Evaluation Metrics Used:** Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).
## Files in this Repository  `MS22 Lstm assignment.ipynb`: The Jupyter Notebook containing data preprocessing, model training, evaluation metrics, and the date-wise prediction plots. ASIANPAINT.csv`: The specific dataset assigned for this implementation.
## Uploaded By
* **Name:** Adnan Sheikh
