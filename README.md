# Bitcoin Price Prediction using LSTM and Multi-Feature Analysis

![GitHub](https://img.shields.io/github/license/KaHimFu/BTC-prediction)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)

Predicting Bitcoin prices using a hybrid LSTM model incorporating sentiment analysis, technical indicators, and macroeconomic data.

## Overview
This project leverages a **Long Short-Term Memory (LSTM)** neural network to forecast Bitcoin (BTC) prices. It integrates:
- **Sentiment Analysis**: CryptoBERT-derived sentiment scores from news/social media.
- **Technical Indicators**: RSI, MACD, Bollinger Bands, and moving averages.
- **Macroeconomic Context**: NASDAQ Composite Index correlations.
- **Historical BTC Prices**: OHLC (Open, High, Low, Close) data.

## Features
- **Hybrid Model Architecture**: Combines quantitative and qualitative data sources.
- **CryptoBERT Integration**: Domain-specific sentiment analysis for cryptocurrency markets.
- **Dynamic Feature Engineering**: Automated calculation of technical indicators.
- **Time-Series Forecasting**: LSTM-based sequence modeling for volatility capture.

## Requirements:
- numpy>=1.21.0
- pandas>=1.3.0
- tensorflow>=2.8.0
- transformers>=4.18.0  # For CryptoBERT
- ta>=0.10.0            # Technical indicators
- matplotlib>=3.5.0
