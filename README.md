# Apple-Stock-Price-Prediction
This project implements a time series forecasting model to predict Apple Inc.'s stock prices using historical stock data. The primary objective is to analyze trends and forecast future stock prices with the help of machine learning and deep learning techniques.

**Objective**
To build a predictive model that can forecast Apple stock closing prices based on historical data using time series analysis techniques such as LSTM (Long Short-Term Memory).

**Tools & Technologies**
Python
Pandas, NumPy
Matplotlib, Seaborn (for visualization)
Scikit-learn
Keras / TensorFlow (for RNN & LSTM modeling)
CSV data

**Workflow**
1) Data Collection
    - Historical Apple stock data fetched from Yahoo Finance or stored in CSV format

2) Exploratory Data Analysis (EDA)
    - Visualized trends in opening, closing, high, and low prices
    - Checked for stationarity and missing values

3) Feature Engineering
    - Selected 'AdjClose' price as the target
    - Scaled the data using MinMaxScaler

4) Modeling
    - Used RNN & LSTM neural network to capture time dependencies in stock prices
    - Split dataset into training and testing sets

5) Evaluation
    - Evaluated model performance using RMSE
    - Compared predicted vs actual prices visually

**Results**
The RNN model was able to learn the stock price trend patterns.
Predicted values followed the actual prices closely, indicating potential for further enhancement with more features.
