# Analyzing the Effect of Sentiment Analysis on Stock Price Prediction

Welcome to the "Analyzing the Effect of Sentiment Analysis on Stock Price Prediction" project repository! This project investigates the impact of sentiment analysis, specifically using VADER sentiment intensity analyzer, on predicting stock prices. We explore whether sentiment from Twitter data can improve the accuracy of stock price predictions using Long Short-Term Memory (LSTM) models.

## Introduction

Sentiment analysis is a valuable tool for understanding public sentiment about a company or product. This project aims to explore whether incorporating sentiment analysis, specifically using the VADER sentiment intensity analyzer, improves the accuracy of stock price predictions. We compare two LSTM models, one with sentiment as an additional independent variable and one without sentiment, to evaluate their predictive performance.

## Data Collection

### Yahoo Finance Stock Data

We collected historical stock price data for the selected company from Yahoo Finance. This dataset serves as the basis for our stock price prediction models.

### Twitter Data using Snscrape

We gathered tweets related to the selected company from Twitter using the Snscrape library. These tweets provide the sentiment data for our analysis.

## Sentiment Analysis

### VADER Sentiment Intensity Analyzer

We employed the VADER sentiment intensity analyzer to perform sentiment analysis on the collected tweets. VADER provides sentiment scores (positive, negative, neutral, and compound) for each tweet.

## Stock Price Prediction Models

### LSTM Models

We implemented two LSTM models for stock price prediction. One model includes sentiment scores as an additional independent variable, while the other does not. LSTM models are known for their ability to capture temporal dependencies in time series data.

## Results

### Comparing Models

We compare the performance of the two LSTM models to assess the impact of sentiment analysis on stock price prediction accuracy.

### Graphs and R2 Values

We visualize the predicted stock prices from both models and calculate the R2 values to measure the goodness of fit. The results are presented in graphical form for easy interpretation.
