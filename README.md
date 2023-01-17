# Daily-Weather-Forecasting

![Weather Forecast](image_forecast.jpg)

The Dataset was designed for the developers who want to train the model on Weather Forecasting for Indian climate. 

The dataset provides data from 1st January 2013 to 24th April 2017 in the city of Delhi, India. The 4 parameters here are
meantemp, humidity, wind_speed, meanpressure. We are more concerned about the meantemp in this model. Although the prediction of every other variable which includes humidity, wind speed and mean pressure, can be done too. I suggest you take one first

I have created models with xgboost, lstm and prophet. 

For regular time series forecasting, it is usually better to use lstm. Lstm is a recurrent neural network which is useful in retaining information for a longer time frame. Facebook prophet is also another option. It was designed by facebook ai team. It is very simple to use, it only needs data that is well processed then it makes good predictions. We could also use regular machine learning algorithms such as xgboost, lgbm, catboost, linear regression for the purpose too but they usually would give a less accurate predition compared to the lstm models.

Other deep learning models that can be used are cnn, mlp, gru.
