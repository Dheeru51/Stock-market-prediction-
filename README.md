# Project Overview 
In this project, we leverage historical stock market data to train an LSTM model. The model learns from past price patterns and trends, enabling it to predict future stock prices. The LSTM network is specifically designed to capture long-term dependencies and has proven to be effective in time series forecasting tasks.

# Dataset
We use a publicly available dataset from yfinance containing historical stock prices of various companies. The dataset includes features like opening price, closing price, volume, etc. We preprocess the data, splitting it into training and testing sets, and perform any necessary data transformations.

# Model Training
The LSTM model is built using deep learning frameworks like TensorFlow. We train the model on the training dataset, adjusting hyperparameters such as the number of hidden layers, the number of neurons per layer, and the learning rate. We employ techniques like regularization and dropout to prevent overfitting.

# Evaluation and Result
Once the model is trained, we evaluate its performance on the testing dataset. We compute various metrics such as mean squared error (MSE), root mean squared error (RMSE), and mean absolute error (MAE) to assess the model's accuracy. We visualize the predicted stock prices alongside the actual prices to gain insights into the model's performance.

