# Product-Demand-Forecasting

## Product demand forecasting of Walmart Stores using time series forecasting methods 

The code is written in Python and can be executed in Kaggle or a local development environment having at least 20GB RAM. It is not possible to run the code in the free Google Colab version as the RAM limit is 12.7 GB only. However, there is a workaround for this. The memory intensive computations have been run and the resulting data has been saved to csv files. The pre-processing steps can thus be skipped, and the code can be run from the ‘Train test split’ section without worrying about memory constraints. 

The dataset consists of three files : calender.csv, sell_prices.csv and sales_train.csv. The sell_prices.csv and sales_train.csv can be downloaded from https://www.kaggle.com/competitions/m5-forecasting-accuracy/data 

The goal is to predict product demand through sales of the products at four different stores named CA1,CA2,CA3 and CA4. 

Seven different time-series models are created:Seasonal Naïve Forecast,Holt-Winters exponential smoothing method,ETS (ExponenTial Smoothing) model,ETS (ExponenTial Smoothing) log model,SARIMA (Seasonal Autoregressive Integrated Moving Average) model,SARIMA (Seasonal Autoregressive Integrated Moving Average) log model and the Prophet model.

For CA1 the best model is the Holt-Winters log model.For CA2, the best model is the ETS log model.For CA3 the ETS log model is the best model. For CA4, the ETS log model is the best model. 
