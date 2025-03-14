---
title: "Exploring Unsupervised Learning for Stock Returns Forecasting"
excerpt: >
  This Project explores the hypothesis that clustering stocks by time series similarity enhances the accuracy of the forecasting models.  
  <br/><img src="/images/Edge.png" style="width:700px; height:350px;">
collection: portfolio
---

View this project on my Github: [Link Here](https://github.com/Ellie-Yang-Siying/Exploring-Unsupervised-Learning-for-Stock-Returns-Forecasting)

Financial markets are complex systems influenced by numerous interconnected factors and non-linear dynamics. Predicting stock prices requires methods that uncover patterns without overfitting to noise. Traditional models like ARIMA are limited by linear assumptions, while advanced techniques such as Long Short-Term Memory networks (LSTMs) can model non-linear dependencies. In this project, we explore the hypothesis that clustering stocks by time series similarity enhances the accuracy of the forecasting models. Using k-means clustering with Dynamic Time Warping (DTW) and Fourier Coefficients as distance metrics, we group FTSE 250 stocks to isolate meaningful patterns within clusters. These will serve as the foundation for both linear and non-linear predictive models. Specifically, we train ARIMA, LightGBM, and LSTM models on clustered data, comparing their performance against models trained on individual stock series or the entire dataset. We aim to determine whether clustering helps filter out irrelevant signals while incorporating valuable contextual data, addressing overfitting and noise.


