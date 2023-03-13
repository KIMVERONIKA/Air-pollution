
 ## 6th_project Air-pollution using Reccurent Neural Network
 
 ## Objective/Goal
 To Create a model that will predict air pollution by Recurrent Neural Network (RNN) 
 
 ## Role
 We worked independently for 1 month for our 6th team project to extract, clean, analyze, visualize, create model with RNN and fit the models.
 
 ## Data
 This hourly dataset contains the PM2.5 data of US Embassy in Beijing. Meanwhile, meteorologigal data from Beijing Capital International Airport are also included.
 Dataset has 43824 rows  and 13 columns.
 
 
 ## Tools Used
  SimpleImputer, Pipeline, LabelEncoder, MinMaxScaler, Sequential, LSTM, Bidirectional
 
 
 ## Models Used
 LSTM models for univariate time series forecasting.

 LSTM models for multivariate time series forecasting.
 Vanilla LSTM, Stacked LSTM, Bidirectional LSTM
 
 ## Code 
 Code for this project can be found here: https://github.com/KIMVERONIKA/Air-pollution/blob/main/2023_03_04_6th_Air_pollution_prediction.ipynb
 
 ## Results
 We used a Recurrent Neural Network of architectures for an LSTM, Vanilla , Bidirectional.

-Use the data as features to predict pollution dew point and atmospheric temperature are correlated to the atmospheric pressure.

-Based on the minimum validation losses the model RNN the metrics are close to each other.

Model of Vanilla LSTM the minimal amount of the error (RMSE: 61.982, Test MAE: 30.863), Model of Stacked LSTM the minimal amount of the error (RMSE: 58.034, Test MAE: 26.785), Model Bidirectional LSTM the minimal amount of the error (RMSE: 20.178, Test MAE: 38.438) Best model Bidirectional LSTM with low score of error.
