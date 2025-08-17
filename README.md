# Google Stock Price Prediction Using Recurrent Neural Network (RNN)

## Overview

This project aims to predict Google's stock prices using a Recurrent Neural Network (RNN) built with LSTM (Long Short-Term Memory) layers. The model is trained on historical stock price data and attempts to forecast future prices, providing a visualization of both the real and predicted stock prices.

## Project Structure

- **Part 1 - Data Preprocessing:**
  - Import libraries and dataset.
  - Perform feature scaling using `MinMaxScaler`.
  - Create a data structure with 60 timesteps and 1 output for training.
  - Reshape the input data to be compatible with the LSTM model.

- **Part 2 - Building the RNN:**
  - Initialize the Sequential model.
  - Add LSTM layers with Dropout regularization to prevent overfitting.
  - Compile the model with the Adam optimizer and Mean Squared Error loss function.
  - Fit the model to the training data.

- **Part 3 - Making Predictions and Visualizing Results:**
  - Use the trained model to predict stock prices on test data.
  - Visualize the results by comparing the real and predicted stock prices using Matplotlib.
## Visualising the test data results
<img width="571" height="455" alt="Stock_pred" src="https://github.com/user-attachments/assets/44e60ae0-d88a-4c04-9bc9-1a4e946c2ab2" />
