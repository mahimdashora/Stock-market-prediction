# Stock-market-prediction
More than 90% of traders lose money on stock market because they fail to sync emotions with strategy to trade .Our approach of Stock Price prediction  is one the way to solve the problem
DJIA index prediction with LSTM-ARIMA hybrid model and News Sentiment Analysis .
Achieved accuracy rate of 98.5 % on 75-25 Train Test Split.


Combined News + Stock price data  is large file size of around 227 MB. If can't download here's link to kaggle :https://www.kaggle.com/aaron7sun/stocknews



 Access the weights of LSTM ,ARIMA models individually .\
 To use ARIMA model - Use command ''' loaded = ARIMAResults.load('arima_model.pkl') '''\
 
 To use LSTM model  - Use command ''' model = tf.keras.models.load_model('lstm_model.h5')'''
