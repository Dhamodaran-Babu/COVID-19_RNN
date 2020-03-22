# COVID-19_RNN
This project aims at building a LSTM cell which predicts the COVID-19 spread over the world.

This covid-19 model is built using the data available on the kaggle

The dataset contained information on the spread of COVID-19,the corona virus globally on provison/state wise for each day from 22nd jan,2020 to 20th mar,2020

I have aggreagated the provision-wise data to get the per-day spread of covid-19 around the globe.

This day have been used to train my RNN model.
This model consists of three hidden layers of LSTM and an input layer of LSTM and a dense output layer.

This model reported a trianing accuracy of 94% and a 88% accuracy in prediction.
I have used the model to predict the perday spread of the COVID-19 from 18th MAR,2020 to the next 7 days.

Since a detailed Multivariate dataset on covid-19 is not open-sourcedly available as on 21 MAR,2020..The RNN model has been a Univariate model which has used the previous data of itself to predict the next data.

