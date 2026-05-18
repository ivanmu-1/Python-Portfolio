# LAX SARMIA Time-Series Analysis

This project is a basic SARIMAX time-series model designed to provide theoretical forecasting recommendations for LAX by analyzing official passenger terminal traffic data from the City of Los Angeles. The model uses aggregated terminal passenger figures and Pandas visualizations to identify traffic trends and forecast future passenger volumes. The overall goal is to predict overall traffic levels, leverage individual terminal data to identify bottlenecks, and support operational and planning decisions.

The overall goal is to practice and understand fundamental machine learning and time-series forecasting concepts while demonstrating how data analysis and predictive modeling can be applied to real-world data.

### Overview: 

[Time_Series_Notebook](https://github.com/ivanmu-1/Python-Portfolio/blob/main/LAX%20Time-series%20Analysis/notebook/Final_Time_Series.ipynb)

This project analyzes airport traffic data using Python, Pandas, Matplotlib, and statistical time-series modeling techniques. We begin with an exploratory overview of the dataset, examining traffic trends and terminal usage before moving into visualization and forecasting. Using Pandas and Matplotlib, we generate visualizations to identify underlying trends, seasonal behavior, and potential overreliance on specific terminals such as TBIT. Monthly traffic totals are aggregated to create a unified time-series dataset for analysis.

Before forecasting, we evaluate stationarity using:

Autocorrelation Function (ACF) analysis
Augmented Dickey-Fuller (ADF) statistical testing
Seasonal decomposition plots
Simple moving average visualizations

After confirming stationarity and seasonality characteristics, we implement time-series forecasting models using the statsmodels framework, including SARIMAX, along with auto_arima for parameter optimization. Because SARIMAX effectively handles seasonal and stationary time-series data, it was selected to model and forecast airport traffic trends while accounting for both long-term patterns and seasonal variation within the dataset. The final model produces forecasts that closely follow historical traffic behavior and observed seasonal trends, demonstrating strong predictive performance on the dataset.

### Tech Stack:
- Python
- Pandas
- Matplotlib
- Statsmodels
- pmdarima
- NumPy

#### Results:

