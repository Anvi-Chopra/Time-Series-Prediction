# Time-Series-Prediction

There are a wide variety of methods available for time forecasting. The prediction model I built is using Autoregressive Integrated Moving Average (ARIMA), which is a statistical model that predicts future values using past values, is an extension of Autoregressive Moving Average (ARMA). 

ARIMA does not assume stationarity but it assumes that the data exhibits no seasonality.

##  Libraries used

1. Pandas
2. Numpy
3. Math
4. Matplotlib
5. ARIMA
6. SkLearn

## Dataset used

Road dataset where the length of road is divided into approx. 100 subsections. There are 13 parameters available and their value is given for 10 years for all the unique subsections. The dataset is provided in data file.

## Development

The project is built in Python using ARIMA. The task was to predict values of the 10th year for all subsections for parameters 9, 10, 11, 12 and 13. Finally, compare the predicted values with the actual given values and calculate the RMSE of the model. 

## Output

![image](https://user-images.githubusercontent.com/105603559/193466457-9650bfeb-6b8d-4b9e-be2e-89b3e75d28b3.png)
