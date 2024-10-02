# Vietnam_Stock_Prediction

## Overview
This project focuses on predicting the stock prices of four major Vietnamese companies: PNJ, FPT, MSN, and VIC, using Long Short-Term Memory (LSTM) neural networks. The dataset used for this project was provided by Finpros, where I completed my test_internship. The goal is to accurately forecast future stock prices using historical stock data, and during the analysis, I evaluated the correlation of the data to simplify the model by removing the volume column.

## Dataset
The dataset consists of historical stock price data for PNJ, FPT, MSN, and VIC, covering the following features:
- `Date`
- `Open`
- `High`
- `Low`
- `Close`
- `Volume`

### Data Source
The data was collected during my internship at Finpros, which provided detailed historical stock prices for the four companies mentioned above.


### Model Architecture
The model architecture consists of:
- LSTM layers to capture temporal dependencies
- Dense layers to predict the future stock price

