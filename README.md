# Time-series-forecasting-lstm
This project predicts stock prices using Long Short-Term Memory (LSTM) networks. It trains the model on historical stock data, optimizing hyperparameters such as layers, neurons, batch size, and epochs. The model is evaluated with RMSE, MAE, and R² to ensure accurate forecasts.

## Project Overview

The project involves:
- Using **LSTM** and **multilayer LSTM** models to forecast future stock prices.
- Evaluating the impact of changing model hyperparameters like:
  - Number of layers
  - Number of neurons
  - Batch size
  - Number of epochs
  - Dropout regularization
- Performance is measured using:
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R² score (Coefficient of Determination)

## Technologies Used

- **Python**
- **Keras**: For building and training the LSTM models.
- **Pandas**: For data manipulation.
- **Numpy**: For numerical computations.
- **Matplotlib**: For visualizations.

## Dataset

The project uses **NSE stock price historical data** for Tata Motors stock prices, spanning from 2014 to 2024.

- **Download Link:** [NSE Stock Historical Price Data on Kaggle](https://www.kaggle.com/datasets/stacknishant/nse-stock-historical-price-data)
