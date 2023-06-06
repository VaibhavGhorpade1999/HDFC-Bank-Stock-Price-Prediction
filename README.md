# HDFC Bank Stock Price Prediction using LSTM and Sentiment Analysis
- This project aims to predict the future stock prices of HDFC Bank using a Long Short-Term Memory (LSTM) neural network and sentiment analysis calculated from newspaper articles.
- The LSTM model leverages the historical stock price data to identify patterns and trends, enabling it to make accurate predictions.

## Table of Contents
- [Introduction](#introduction)
- [Data Collection](#data-collection)
- [Data Preprocessing](#data-preprocessing)
- [Sentiment Analysis](#sentiment-analysis)
- [LSTM Model](#lstm-model)
- [Results](#results)


## Introduction
- Predicting stock prices is a challenging task due to the complexity and volatility of financial markets. 
- This project combines the power of LSTM, a type of recurrent neural network (RNN), with sentiment analysis to forecast HDFC Bank's stock prices. 
- Sentiment analysis is performed using two popular libraries, Vader and TextBlob, to analyze the sentiment of news articles related to the bank.

## Data Collection
- The historical stock price data for HDFC Bank is collected from reliable financial sources or APIs. 
- Additionally, newspaper articles related to the bank are scraped or obtained using a web scraping tool. 
- The stock price data and textual data from the articles are used as the input for the LSTM model.

## Data Preprocessing
- Before feeding the data into the LSTM model, it undergoes preprocessing steps such as removing outliers, handling missing values, and normalizing the data. 
- The textual data is processed by removing stop words, performing tokenization, and converting the text into numerical representations.

## Sentiment Analysis
- Sentiment analysis is performed on the newspaper articles using two popular Python libraries: Vader and TextBlob. 
- Vader provides a rule-based sentiment analysis approach that estimates the sentiment of a piece of text. 
- TextBlob, on the other hand, offers a sentiment analysis model trained on a large dataset. 
- The sentiment scores obtained from these libraries are used as additional features for the LSTM model.

## LSTM Model
- The LSTM model is a type of RNN architecture that can process and learn from sequential data. 
- It is well-suited for time series prediction tasks. The LSTM model is trained on the preprocessed stock price data along with the sentiment scores. 
- The model learns to identify patterns and dependencies in the data, enabling it to make future predictions.

## Results
- The performance of the LSTM model is evaluated using appropriate evaluation metrics such as mean squared error (MSE) or root mean squared error (RMSE)= 0.80948037. The accuracy of the sentiment analysis using Vader and TextBlob is also assessed. 
- The results are presented in a clear and concise manner, providing insights into the effectiveness of the model and sentiment analysis approach.


