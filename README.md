# BitcoinPricePrediction

### Aim of the project

The aim of the project is to develop a solution that predicts price of Bitcoin with the use of Jupyter, Python with some Data Science libraries. 

### Description of the project

The source of the data used to train ML model is https://www.investing.com/crypto/bitcoin/historical-data. After reading a data as DataFrame (a type of data used in Pandas library), some columns are dropped - only "Date" and "Price" are used to train a model. Before training, data are scaled with the use of `MinMaxScaler()` function. Keras is used to creating and training the ML model. In this model, there are 3 layers - 2 LSTM layers and a dense layer. After training, the model is saved and the comparison of real and predicted prices is shown. 
