An implementation of a feed-forward NeuralNet architecture using Keras for predicting the stock price movement.
Also to download historic prices, apply a strategy, and see the strategy performance vis-a-vis the actual stock prices.

This uses Pandas, NumPy, NSEPy, SciKit, MatPlotLib, and a host of other python libraries.


## Forecasting our datapoints
We prepare various input features which will be used by the artificial neural network to train itself for making the predictions. We define the following features:
- High minus Low price
- Close minus Open price
- 3 day moving average
- 10 day moving average
- 30 day moving average
- Standard deviation for a period of 5 days
- Relative Strength Index
- Williams %R
