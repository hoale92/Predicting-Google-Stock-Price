# Predicting-Google-Stock-Price
# Dataset
This dataset is of Google Stock Prices, downloaded from Yahoo Finance. It contains 3805 data points, from August 2004 to September 2019. Based on data of previous months, we try to predict the stock prices of the latest months.
# Parameter
The recurrent neural network (RNN) model is composed of a sequential input layer followed by three hidden layers with 50 neurons for each layer. A dropout rate of 0.2% is added after each layer to prevent overfitting. The output layer is a dense layer with linear activation function. The error of this model was 0.67.
# Result
Due to the complexity of the dataset and under the condition of hardware limitation, the Neural Network perform much less effective than the Random Forest and the Support Vector Machine.
