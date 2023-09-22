# About
Climate change is causing more intense heat waves and air pollution worldwide. Air Quality Index (AQI) prediction and heatwave prediction are two critical environmental forecasting tasks that have garnered significant attention in recent years due to their impacton public health and safety.The model will make use of advanced time series analysis techniques for predicting Air Quality Index (AQI) and HeatWave. Heatwave Prediction Using Hybrid Model of Autoencoder and BiLSTM-LSTM and AQI Forecasting Using Autoencoder and ARIMA.
***
# Project Overview
### Data Collection
The data was collected from the city Karimnagar in Telangana,
India, and provides a significant amount of information for the
models.
***
## Heatwave Prediction
A hybrid model that combines an autoencoder and
combined form of Bidirectional LSTM and LSTM for
forecasting individual features of heatwave and a DNN is
used for the prediction of heatwave.
#### 1. Data Preparation
The data preparation stage is where the input data is
preprocessed and cleaned for use in the hybrid model. This
stage involves data cleaning, including removing missing
values, data normalization.
#### 2. Denoising using Autoencoder
The autoencoder is trained on the preprocessed data to learn a
compressed representation of the data, which is used as input
for the combination of Bidirectional LSTM and LSTM models.
#### 3. Feature selection
In this study, employed the ExtraTreeClassifier
algorithm for feature selection to identify the most important features for predicting heatwaves.
#### 4. Forecasting individual features
Output from autoencoder is given to combinational model of BiLSTM-LSTM for forecasting individual features.
#### 5. Prediction
The prediction stage is where the output from the
combination of Bidirectional LSTM and LSTM is fed into
a DNN for final prediction. The DNN generates the final
prediction of whether a heatwave occurs or not.
***
## AQI Prediction
For the prediction of AQI (Air Quality Index), we are using
Autoencoder and ARIMA (Autoregressive Integrated Moving
Average) model. AQI is a measure of air quality that is
used to assess how polluted the air is in a specific location.
#### 1. Data Preparation
The first step in data preprocessing is
to identify and remove any missing values or outliers. This
is important to ensure that the data is consistent and reliable.
#### 2. Denoising using Autoencoder
The autoencoder receives the raw data as input and compresses it, enabling the
reduction of the number of parameters that need to be trained.
This reduction in parameters helps to minimize the risk of
overfitting, which is a common problem when models are too
complex for the given dataset.
#### 3. Forecasting
The output of the autoencoder is given to Autoregressive Integrated
Moving Average (ARIMA) model. ARIMA is used for forecasting AQI.
***
### Performance Analysis
RMSE, MAPE, R<sup>2</sup>, MAE is used for performance analysis.

