# **Prophet Optimization with Particle Swarm Optimization (PSO) for Adjusted Closing Price Forecasting in Xiaomi-Corporation**

## **Details :**
> Optimizing Prophet's hyperparameters, such as changepoint_prior_scale, seasonality_prior_scale, and holidays_prior_scale, with Particle Swarm Optimization (PSO)
> Optimizing Prophet's forecasting accuracy by incorporating the Prophet model with Additional Regressors, such as *Open*, *High*, *Low*, *Close*, and *Volume*
> This project uses Xiaomi Corporation Stock Prices data that was obtained from Yahoo Finance (https://finance.yahoo.com/quote/1810.HK/history)
> The Prophet model was not given with a custom list of holidays that gives effect to the value of the Adjusted Closing Price of Xiaomi Corporation
> The Prophet model uses the "Piecewise Linear" formula to calculate the Trend Component / g(t)
> There are 4 models designed in this project, which are "Standard Prophet" / "Prophet", "Standard Prophet with Additional Regressors" / "Prophet + Reg", "Standard Prophet Optimized with PSO" / "Prophet + PSO", and "Standard Prophet with Additional Regressors and Optimized with PSO" / "Prophet + Reg + PSO"

## **Result :**
The "Prophet + Reg + PSO" model achieved a high level of accuracy with MAPE and R2 values of 0.00000008522 and 0.999, respectively. This means the "Prophet + Reg + PSO" model is very accurate in forecasting the Adjusted Closing Prices of Xiaomi Corporation.
