# Gold-Price-Forecasting-Short-Term-vs.-Long-Term-LSTM-Models


Overview
Gold price prediction is crucial for financial markets, and this project explores the effectiveness of LSTM networks for forecasting gold prices. It compares models trained to predict short-term and long-term trends, helping to identify the most reliable model for different forecasting windows.

Key Features
Short-Term vs. Long-Term Forecasting: The project contrasts models trained for short-term and long-term predictions.
LSTM Model Architecture: Utilizes LSTM networks for time series forecasting, known for their ability to capture sequential dependencies.
Data Processing: Preprocessing of time series data for feature extraction, normalization, and splitting into training/testing datasets.
Evaluation: Performance of the models is evaluated using common metrics like Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).

Results:

Short-Term Model:
Forecast Horizon: Predicting gold prices for the next 7 days.

Performance Metrics:
Root Mean Squared Error (RMSE): 19.46
Mean Absolute Percentage Error (MAPE): 0.37%
Visualization: Predicted gold prices closely followed the trend of actual prices, demonstrating that the LSTM model effectively captured short-term fluctuations in gold prices.
![image](https://github.com/user-attachments/assets/45af85de-e925-422c-8bc3-6be60601ab93)

<img width="1387" alt="Real_price_gold_dec_16_19" src="https://github.com/user-attachments/assets/e0058a27-366b-4cd6-8021-d89c9badf6f2" />
picture credit: TradingView. (n.d.). TradingView — Track all markets. https://www.tradingview.com/



Long-Term Model:
Forecast Horizon: Predicting gold prices for a longer period (30-60 days).
Performance Metrics:
RMSE: Higher compared to the short-term model, indicating increased prediction error over the longer horizon.
MAPE: Slightly higher than the short-term model, reflecting the challenge of forecasting over extended periods.
