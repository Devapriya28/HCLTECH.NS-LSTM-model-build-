# HCLTECH.NS-LSTM-model-build

## 📝 Overview

This project predicts HCLTECH (NSE) stock closing prices using a Long Short-Term Memory (LSTM) deep learning model.

Historical stock data is fetched using yfinance.

Data is preprocessed and scaled.

Model is trained with 60 days of past data to predict the next day price.

Finally, the model can forecast tomorrow’s closing price.

## 📂 Workflow

Data Collection → Yahoo Finance API (yfinance)

Preprocessing → Scaling with MinMaxScaler

Sequence Creation → 60 days → 1 prediction

Model Building → LSTM layers + Dense layers

Training → Historical data (2005 onwards)

Testing → Model evaluated on unseen data

Prediction →

Past data vs Predicted (graph)

Tomorrow’s predicted price

## 🙌 Acknowledgements

Yahoo Finance
 for stock data

TensorFlow/Keras
 for deep learning framework

## 📊 Example Output

Graph:

Blue line → Actual Close Price

Orange line → Predicted Close Price

Tomorrow Prediction:
Predicted Closing Price for Tomorrow
