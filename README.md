# Multi-head Attention Based Gold Trend Line Prognostication

This project leverages a transformer-based deep learning model to predict gold price trends using historical data. By employing multi-head attention mechanisms, the model aims to capture complex temporal relationships within commodity price time series, delivering robust and accurate forecasts.

## Features

- **Data Preprocessing:** Cleans and prepares historical gold price data.
- **Transformer Model:** Utilizes multi-head attention layers for improved trend prediction.
- **Evaluation & Visualization:** Calculates evaluation metrics and visualizes actual vs. predicted prices.

## Evaluation Metrics

- **MAPE (Mean Absolute Percentage Error):** Measures the average magnitude of errors as a percentage, making it easy to understand how far predictions are from actual values.
- **Accuracy:** Computed as `1 - MAPE`, representing how close the model’s predictions are to the true values

## How It Works

1. **Data Loading:** Loads gold price data from CSV.
2. **Preprocessing:** Cleans and scales the data, creates training and test datasets.
3. **Model Training:** Trains a custom transformer model on the training set.
4. **Prediction & Evaluation:** Predicts on the test set and computes evaluation metrics.
5. **Visualization:** Plots and saves the comparison of actual and predicted prices.

## Usage

Run the provided Jupyter Notebook (`model.ipynb`) in Google Colab. Ensure your gold price CSV file is in your Google Drive.

---

Happy forecasting! 📈✨
