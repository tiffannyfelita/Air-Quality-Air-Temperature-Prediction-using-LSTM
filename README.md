# Air-Quality-Air-Temperature-Prediction-using-LSTM
Analyzing time series air quality data and predicting pollution levels (PM2.5) using an LSTM neural network. The model results are correlated with respiratory disease trends to understand the environmental impact on public health.

This project serves as the final project for the course and successfully achieved a perfect score. It focuses on predicting air temperature (AT) one hour ahead based on historical air quality data (PM10, CO, NO₂, etc.) using a multivariable time series approach.

A baseline LSTM model with a hidden size of 10 and a single-layer regressor with linear activation was developed, followed by a modified model with optimized hyperparameters.The performance improvement clearly demonstrates the model’s effectiveness:

Metric	Baseline Model	Modified Model
MAE	0.4769	0.4410
MSE	0.4385	0.3540
R² Score	0.9378	0.9498
MAPE	1.54%	1.42%

The modified model outperforms the baseline across all evaluation metrics, showing a lower prediction error (MAE, MSE, MAPE) and higher accuracy (R² Score). This confirms that the model effectively captures temporal dependencies and relationships between air quality parameters, making it highly reliable for short-term air temperature forecasting.
