# anomaly-detection-predictive-maintainence
To develop a system capable of detecting anomalies in machine operations using sensor data in order to predict potential failures before they occur, enabling predictive maintenance and reducing unplanned downtime.


Machines are provided with several sensors in modern industrial setup to monitor parameters like vibration, temperature, pressure, and many more. Machines are always prone to wear and tear as they operate; therefore, some anomalies occur during their normal functioning and lead to the final failure. These failures generally precede anomalies in sensor data; thus, early detection would be crucial to minimize downtime and maintenance costs. These classic approaches of reactive maintenance fix problems or machines after they fail, at the cost of very expensive repairs and unplanned downtime. On the contrary, anomaly detection aims to detect anomaly behavior in the machines as soon as it happens so that an early warning system could indicate predictions and preventive measures can be taken before a failure actually happens. 

The ARIMA model, which stands for AutoRegressive Integrated Moving Average, is a popular statistical method used for time series forecasting.
ARIMA(p, d, q)
AR (AutoRegressive) — The model uses past values (lags) to predict future values.

p is the number of lag observations included.

I (Integrated) — This involves differencing the data to make it stationary (i.e., constant mean and variance over time).

d is the number of times the data is differenced.

MA (Moving Average) — The model uses past forecast errors in a regression-like model.

q is the number of lagged forecast errors.

When to Use ARIMA
Data shows a trend but no seasonality.

You need to forecast future points based on past values.


