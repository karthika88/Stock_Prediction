# Stock_Prediction
Stock Price Prediction with Sentiment Analysis and Time Series Models

## Project Overview
This project aims to predict and forecast stock prices by combining sentiment analysis of business news and time series forecasting models. The sentiment analysis is performed using **VADER**, a tool specifically designed for text analysis, and the stock data is enriched with sentiment scores to improve forecasting accuracy.

We explore the following forecasting models:
- **ARIMA (AutoRegressive Integrated Moving Average)**
- **Prophet** (Time Series Forecasting by Facebook)
- **LSTM (Long Short-Term Memory)** for sequence prediction.

The models are enhanced with **feature engineering**, **feature scaling**, and **cross-validation** to improve performance and prevent overfitting.

## Steps Involved:
1. **Data Collection**: Collecting stock data and business news.
2. **Sentiment Analysis**: Using VADER to analyze business news and extract sentiment scores.
3. **Data Preprocessing**: Merging stock data and sentiment scores, handling missing data, and scaling features.
4. **Modeling**: Implementing ARIMA, Prophet, and LSTM models.
5. **Evaluation**: Using **Mean Squared Error (MSE)** and **Mean Absolute Error (MAE)** to evaluate the models.
6. **Visualization**: Plotting actual vs. predicted stock prices.

## Requirements:
- Python 3.x
- Libraries:
    - pandas
    - numpy
    - matplotlib
    - sklearn
    - statsmodels
    - fbprophet
    - tensorflow
    - vaderSentiment

## Installation:
1. Install Python dependencies:
   ```bash
   pip install pandas numpy matplotlib scikit-learn statsmodels fbprophet tensorflow vaderSentiment
