# Time Series Anomaly Detection for Synthetically Generated Computer Sensor Data

This report investigates the generation and evaluation of synthetic sensor data for key system metrics. Synthetic data was generated using a time series forecasting model called VAR(Vector Autoregressive Model) and
compared against real sensor data collected over a defined period. The study aims to assess the accuracy
of the synthetic data by identifying discrepancies and anomalies between the two datasets. The analysis
provides insights into the model’s effectiveness in replicating real system behavior, highlighting areas
for improvement and the potential of synthetic data in system performance forecasting.

# Requirements

1) matplotlib
2) pandas
3) seaborn
4) statsmodels
5) wmi
6) psutil
7) datetime
8) Open Hardware Monitor App

# Note

To collect the sensor data, we need to execute the Python code while running the Open Hardware Monitor app in the background such that it extracts the sensor information. You can download the app from clicking the mentioned link, \href{https://openhardwaremonitor.org/}

