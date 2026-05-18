# LAX SARMIA Time-Series Analysis

This project is a basic SARIMAX time-series model designed to provide theoretical forecasting recommendations for LAX by analyzing official passenger terminal traffic data from the City of Los Angeles. The model uses aggregated terminal passenger figures and Pandas visualizations to identify traffic trends and forecast future passenger volumes. The overall goal is to predict overall traffic levels, leverage individual terminal data to identify bottlenecks, and support operational and planning decisions.

The overall goal is to practice and understand fundamental machine learning and time-series forecasting concepts while demonstrating how data analysis and predictive modeling can be applied to real-world data.

### Overview: 

The Script ()

We first begin with a basic overview of the data, examining its contents before diving into Pandas analysis and Matplotlib visualizations. Through these visualizations, we apply statistical modeling techniques to uncover underlying trends, including seasonal patterns and the overreliance on specific terminals such as the TBIT terminal. To achieve this, we aggregate the total traffic data into a unified monthly count.

Before moving on to modeling, we test the data for stationarity using both the Autocorrelation Function (ACF) and p-value–based statistical tests, such as the Augmented Dickey-Fuller (ADF) test. Additionally, we create further visualizations, including seasonal decomposition plots and simple moving average graphs, to confirm the presence of seasonality and evaluate stationarity.

After confirming stationarity, we import the necessary frameworks and libraries from statsmodels, including SARIMAX, as well as auto_arima for parameter optimization, and begin the forecasting process. Due to SARIMAX’s ability to effectively handle seasonal and stationary time-series data, we use it to model and forecast airport traffic trends while accounting for both seasonal variation and long-term patterns in the dataset.
