# WeatherPredict

Multiple ANNs weather prediction with multiple cities weather data sets created in Google Colab, using Pyhton and Tensorflow. DelhiWeather contains all the models within the same notebook file, while the models for other cities are split into different notebooks. CSV dataset files are contained within appropriate directories. 

## Model 1. LSTM
First model utilizes Long Short-Term Memory network to exploit temporal dependencies across sequences of wather data

## Model 2. CNN
Second model uses Convolutional Neural Network to classify weather data. CNNs ability to process multiple sequences simultaneously makes them efficient for handling large datasets, including time series

## Model 3. GRU
Gated Recurrent Unit network is able to capture temporal factors of weather data. It also has a attention mechanism allowing it to find patterns hidden in the dataset

## Model 4. DAY AND YEAR TIME
For the final model (which uses LSTM network), data is preprocessed so that the temporal information is added - this approach leverages repeating weather conditions, which occur periodically during the day or the year.