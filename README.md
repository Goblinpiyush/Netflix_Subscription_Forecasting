# Netflix Subscribers Forecasting

This project aims to forecast the number of Netflix subscribers for the next five quarters using the ARIMA model. The project includes steps for data preprocessing, model fitting, and generating future predictions. 
The forecast results are visualized using matplotlib.

## Dataset

The dataset (`netflix_subscriptions_csv`) contains historical subscriber data with the following columns:
- `Time Period`: The time period of the data point (e.g., '2020-01-01' for quarterly data).
- `Subscribers`: The number of subscribers at that time period.

##  Summary
Data Preprocessing: Loading and preprocessing the dataset, converting 'Time Period' to datetime format and setting it as the index.
Model Fitting: Fitting an ARIMA model to the quarterly data with parameters (p=1, d=1, q=1).
Forecasting: Using the fitted ARIMA model to predict the number of subscribers for the next five quarters and visualize the results.
