# Predicting Dramatic Drawdowns in Bitcoin

## Project Proposal
We used quantitative analysis to predict significant BTC price drawdowns exceeding 20% in a 24 hour period. We trained a LSTM Neural Network with a  combination of historical price, volatility, volume and sentiment data to develop a predictive model.


## Data sources
To provide sufficient training data and capture previous boom and bust cycles our intent is to go back to at least mid-summer of 2017. As recently demonstrated, BTC price can significantly move within minutes/hours. Our intent is utilize hourly time series data for price, volatility, and volume datasets. Possible sources include:
* News API
* Twitter API
* Fear and greed indicator/indexes
* Gemini API
* Google Trends
* Kaggle


## Predictions and Conclusions
- Time series analysis BTC hourly price forecasting using Hodrick-Prescott Filter and ARMA, ARIMA, GARCH models. 

- 20% drawdown chosen to provide sufficient examples for deep learning neural net training.
BTC trades 24 / 7
hourly price and volume data utilized
59x 20% drawdowns since 10/2016
33x 20% drawdowns since 1/2017 (dataset used)

- Sentiment analysis 16million historical tweets about Bitcoin using NLP.


## Presentation

Below is the link to our presentation

[Project Presentation](https://github.com/amanafzali/Project_2/blob/main/Project%20Presentation.pdf/)
