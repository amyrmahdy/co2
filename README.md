# **Time Series Forecasting of CO2 Levels using ARIMA**

This project aims to forecast future CO2 levels using ARIMA (Autoregressive Integrated Moving Average) model. The dataset used for this project contains monthly average CO2 levels from Mauna Loa Observatory in Hawaii, USA from 1958 to 2021.


## **Installation**

To run this project, you need to have the following packages installed:

- pandas

- numpy

- matplotlib

- statsmodels

- sklearn

You can install these packages using pip:

```
pip install pandas numpy matplotlib statsmodels scikit-learn
```

## **Usage**

To run the project, you can simply run the notebook `time_series_forecasting.ipynb` in Jupyter Notebook or JupyterLab.

The notebook contains the following sections:


1. Loading and visualizing the data

2. Checking for stationarity using Augmented Dickey-Fuller test and differencing if needed

3. Determining the parameters for ARIMA model using ACF and PACF plots

4. Decomposing the time series to observe the trend, seasonal, and residual components

5. Splitting the data into train and test sets

6. Training and evaluating the ARIMA model on the train set

7. Visualizing the actual vs predicted values for the test set

8. Calculating the R-squared score to evaluate the accuracy of the model

## **Contributing**

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## **License**

[MIT](https://choosealicense.com/licenses/mit/)

## **Additional Resources**

- Kaggle Notebook: [Forecasting CO2 Levels using ARIMA Model](https://www.kaggle.com/code/amyrmahdy/forecasting-co2-levels-using-arima-model)

- Medium Article: [Time Series Forecasting with ARIMA: Predicting Carbon Dioxide Levels](https://amyrmahdy.medium.com/time-series-forecasting-with-arima-predicting-carbon-dioxide-levels-91db8c323add)


<br >
<br >

Author: **amyrmahdy**

Date: **24 Jan 2023**
