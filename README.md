Q1. What is a Time Series?
Definition: A time series is a sequence of data points indexed in time order. It represents the evolution of a particular phenomenon over time, where each data point is associated with a specific timestamp or time period.

Applications:

Economics and Finance: Stock market analysis, economic forecasting.
Business: Sales forecasting, demand planning, inventory management.
Engineering: Signal processing, anomaly detection.
Healthcare: Patient monitoring, disease outbreak prediction.
Climate Science: Weather forecasting, climate change analysis.
Q2. Common Time Series Patterns
Patterns:

Trend: Long-term increase or decrease in data over time.
Seasonality: Periodic fluctuations or patterns that occur at fixed intervals.
Cyclicality: Similar to seasonality but with irregular and non-fixed intervals.
Irregularity (or Residuals): Random variations or noise that cannot be attributed to trend, seasonality, or cyclicality.
Identification and Interpretation:

Visual Inspection: Plotting the data and observing patterns.
Decomposition: Separating the time series into its components (trend, seasonality, and residuals).
Statistical Tests: Using statistical techniques to quantify and analyze patterns.
Q3. Time Series Data Preprocessing
Steps:

Handling Missing Values: Imputation using mean, median, forward or backward filling.
Dealing with Outliers: Smoothing techniques or outlier detection methods.
Normalization and Scaling: Standardization to ensure consistent scales.
Stationarity Transformation: Differencing to stabilize mean and variance.
Resampling: Adjusting frequency (e.g., from hourly to daily data).
Q4. Time Series Forecasting in Business Decision-Making
Usage: Helps businesses predict future trends, plan resources, optimize inventory, and make informed decisions based on expected outcomes.

Challenges: Seasonal variations, unexpected events (e.g., COVID-19), data quality issues, and model accuracy over long-term forecasts.
Q5. ARIMA Modelling for Time Series Forecasting
ARIMA: Autoregressive Integrated Moving Average.

Usage: Suitable for data exhibiting non-stationarity.
Components:
AR (Autoregressive): Dependent on its own past values.
I (Integrated): Differencing to achieve stationarity.
MA (Moving Average): Dependent on past forecast errors.
Forecasting: Uses historical data to predict future values based on these components.
Q6. ACF and PACF in ARIMA Model Identification
ACF (Autocorrelation Function): Measures correlation between a time series and its lagged values.
PACF (Partial Autocorrelation Function): Measures direct correlation between a time series and its lagged values after removing the effects of intervening observations.
Interpretation: Helps identify the order (p, d, q) of the ARIMA model by identifying significant lags where correlations are strong.
Q7. Assumptions of ARIMA Models
Stationarity: Data should have constant mean, variance, and autocovariance over time.
No Multicollinearity: Predictors (lags) should not be highly correlated.
Normality: Residuals should follow a normal distribution.
Q8. Choosing a Time Series Model for Sales Forecasting
Recommendation: Seasonal ARIMA (SARIMA) model due to the presence of seasonality in monthly sales data.
Why: SARIMA can capture both the seasonal and non-seasonal components effectively, providing accurate forecasts.
Q9. Limitations of Time Series Analysis
Short Historical Data: Insufficient data for reliable predictions.
Complexity: Difficulty in modeling non-linear relationships or sudden changes.
Assumptions: Models may fail if underlying assumptions (like stationarity) are violated.
External Factors: External events (e.g., pandemics, policy changes) can disrupt historical patterns.
Q10. Stationary vs Non-Stationary Time Series
Stationary: Mean, variance, and autocovariance are constant over time.
Non-Stationary: Mean, variance, or autocovariance vary over time.
Impact on Forecasting: Stationarity is crucial for ARIMA models; non-stationary series require differencing or transformation to stabilize statistical properties.
