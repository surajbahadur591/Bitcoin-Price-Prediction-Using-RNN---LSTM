# Bitcoin-Price-Prediction-Using-RNN-LSTM
This notebook demonstrates the prediction of the bitcoin price by the neural network model. We are using long short term memory (LSTM)

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes

### Prerequisites
you need to install all the necessary libraries n order to run the project
`sklearn`
`tensorflow`
`pandas`
`matplotlib`

### Installing
```
pip install sklearn
pip install tensorflow
pip install pandas
pip install matplotlib
```
## --------------------------------------------------------------------------
### we will be going through a four step process to predict cryptocurrency prices:
1. Getting real-time crptocurrency data(bitcoin).
2. Prepare data for training and testing.
3. Predict the price of crptocurrency using LSTM neural network (deep learning).
4. Visualize the prediction results.

### 1. Getting real-time crptocurrency data(bitcoin)
You can collect the current data for Bitcoin from [Yahoo Finance](https://in.finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD)

### 2. Prepare data for training and testing.
You can preprocess the data before dividing it into traning and testing
```
data_training = data[data['Date']< '2020-01-01'].copy()
data_training
```

```
data_test = data[data['Date']> '2020-01-01'].copy()
data_test
```
###
