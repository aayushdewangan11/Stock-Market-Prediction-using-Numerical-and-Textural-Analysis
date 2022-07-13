# Stock-Market-Prediction-using-Numerical-and-Textural-Analysis
Objective: 
To create a hybrid model for stock price/performance prediction using numerical analysis of historical stock prices, and
sentimental analysis of news headlines(of that particular day).

Extract Sentiment Scores from given newspaper headlines data, with the help of nltk's SentimentIntensityAnalyzer

I used LSTM (Long Short-Term Memory), to model the temporal effects of past events(both Textual, i.e the sentiment scores and Historical stock data) on opening prices

Achieved Training loss: 0.0479 and Validation loss: 0.0254

Achieved RMSE on the Test data : 475.102

Dataset:
* Historical stock prices(SENSEX (S&P BSE SENSEX)) from https://finance.yahoo.com/

* Textual (News) data from https://bit.ly/36fFPI6
