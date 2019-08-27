# Time-series-data-prediction
 <br>
Compare several methods including LSTM, GRU, TCN <br>
What I find through this experiment:  <br>
1. MinMaxScaler has better result than Standardscaler(z score standardization).<br>
2. When setting the hyperparameter in time series problem, batch size = 1 would get least loss and best accuracy, while it would take much longer time.<br>
3. For the single variable time series forecasting, TCN does not work as well as the RNN family does.
