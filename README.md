# Predicting-stock-price-LSTM-RNN-2

# Analysing AAPL Stock

## Insight:
high correlation with the 'low' price suggests that the closing price often occurs closer to the lowest price observed during a trading session. When the 'low' price is higher, the closing price tends to be higher, and when the 'low' price is lower, the closing price tends to be lower.

## Parameters taken 

 We are selecting specific columns from the 'data' DataFrame to create our feature matrix 'x' and target vector 'y.' 'x' will contain the features (predictors), which are "Open," "High," "Low," and "Volume." 'y' will contain the target variable, which is "Close."
