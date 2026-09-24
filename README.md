# Cryptocurrency Market Analytics & BTC Price Prediction

A group project about analyzing cryptocurrency market data and USD/IDR exchange rates.

The project collects cryptocurrency data, converts the values from USD to IDR, visualizes the crypto market, and uses Linear Regression as a baseline model for Bitcoin price prediction.

## Project Overview

The main parts of this project are:

- Collecting cryptocurrency data from the Coinranking API
- Collecting USD/IDR exchange rate data from ExchangeRate-API
- Processing the data using PySpark Structured Streaming
- Converting cryptocurrency prices and market capitalization from USD to IDR
- Visualizing the top cryptocurrencies by market capitalization
- Analyzing cryptocurrency market dominance
- Preparing Bitcoin data for machine learning
- Building a Linear Regression model for Bitcoin price prediction

## Dashboard

The dashboard focuses on the cryptocurrency market in IDR.

The visualizations include:

- Top 10 cryptocurrencies by market capitalization
- Cryptocurrency market dominance
- Comparison between actual and predicted Bitcoin prices

The market capitalization data is converted from USD to IDR using the collected USD/IDR exchange rate.

## Machine Learning

Linear Regression was used as a baseline model to predict Bitcoin price in IDR.

The dataset contains:

- `timestamp`
- `price_idr`
- `marketcap_idr`
- `change`
- `usd_idr`

### Model Results

| Metric | Result |
|---|---:|
| RMSE | 499,800.94 IDR |
| R² | 0.2170 |

The model is still a baseline and the prediction performance is limited. The R² score of 0.217 means that the current features explain around 21.7% of the variation in Bitcoin price.

## Limitations & Future Improvements

The current model can still be improved. Some possible improvements are:

- Collect more historical Bitcoin data.
- Add features such as trading volume and previous price changes.
- Add lagged prices, moving averages, and volatility.
- Compare Linear Regression with models such as Random Forest and XGBoost.
- Explore time-series models such as ARIMA or LSTM.
- Add other evaluation metrics such as MAE and MAPE.

## Tools

- Python
- PySpark
- PySpark MLlib
- Pandas
- Matplotlib
- REST API
- Linear Regression

##  My main contribution focused on the dashboard and data visualization
Worked on the cryptocurrency market dashboard.
Worked on converting cryptocurrency market data into IDR for visualization.
Created the market capitalization and market dominance visualizations.


## Project Structure

```text
crypto-market-analytics-btc-prediction/
│
├── README.md
├── TUGAS DMO.pdf
└── Copy_of_Salinan_dari_realdo_ipnyb-2.ipynb
