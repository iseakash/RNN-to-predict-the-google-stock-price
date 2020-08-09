# RNN-to-predict-the-google-stock-price
Implementation of recurrent neural networks to predict the google stock price for next one month based on the datasets containing Google stock price from the beginning of 2012 to the end of 2016.

Data Description:- This dataset contains google stock price for four years from 2012 to 2016 at daily interval with 1258 rows and five columns namely - Date, Open, High, Low, Close, and Volume.

Steps:- 1. Importing the libraries 2. Importing the training dataset 3. Feature Scaling  4. Creating a data structure with 60 timesteps and 1 output  5. Reshaping                         6. Building and Training the RNN with four LSTM layer and some Dropout regularisation  7. Making the predictions and visualising the results.

Epochs: 100
Batch Size: 32
Timestamps: 60
