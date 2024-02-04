# Predicting-stock-price-LSTM-RNN-2

# Analysing AAPL Stock

### LSTM 
LSTM is one of the best machine learning approaches for time series forecasting. LSTMs are recurrent neural networks designed to remember data for a longer period. 

### Process
1. We start by importing all the necessary Python libraries and collecting the latest stock price of Apple
2. To visualise, we make a candlestick chart of the data.
3. We try and find correlation between the Close Coloumn and the target coloumn.
### 4. Training LSTM for Stock Price Prediction
a) split the data into training and test sets.
b) We prepare a neural network architecture for LSTM
c) We proceed to train our neural network model for stock price prediction.
d) We give 2 input values according to features that we have used to predict the final result.

P.S: Uploading a newer file as well that tells you the error.

## Insight:
high correlation with the 'low' price suggests that the closing price often occurs closer to the lowest price observed during a trading session. When the 'low' price is higher, the closing price tends to be higher, and when the 'low' price is lower, the closing price tends to be lower.

## Parameters taken 

 We are selecting specific columns from the 'data' DataFrame to create our feature matrix 'x' and target vector 'y.' 'x' will contain the features (predictors), which are "Open," "High," "Low," and "Volume." 'y' will contain the target variable, which is "Close."
