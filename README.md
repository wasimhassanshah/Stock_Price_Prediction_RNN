# Stock_Price_Prediction_RNN
Stock Price Prediction of Apple Inc. Using LSTM Recurrent Neural Network

# Purpose
Purpose of this project is to build stock price predictor model to help the quantitative traders to take calculated decisions.

# Price Indicator
Stock traders mainly use three indicators for prediction: Price of Open, High, Low and Closing Prices, In this project,Closing price is used for prediction.

# Model
Three sequential LSTM layers have been stacked together and one dense layer is used to build the RNN model using Keras deep learning library. 

# Test:
Test accuracy metric is root mean square error (RMSE).

# Results
- Original data close price plot
![](https://github.com/wasimhassanshah/Wasim_Shah_Portfolio/blob/main/images/OriginalColsepricevalue.png)
- After the training the fitted curve with original stock price:
![](https://github.com/wasimhassanshah/Wasim_Shah_Portfolio/blob/main/images/Orgnaltrainpredct%20LSTM%20Stock%20a.png)
- Future 30 days Prediction of Close price:
![](https://github.com/wasimhassanshah/Wasim_Shah_Portfolio/blob/main/images/30days%20pedct%20LSTM%20Stock.png)
- Final plot Original + Predicted for 30 days Close price value of stocks
![](https://github.com/wasimhassanshah/Wasim_Shah_Portfolio/blob/main/images/Final%20LSTM%20Predct%20Stock.png)


# Dependencies
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Sklearn
- tensorflow
- keras
