# Time-Series-Analysis
following is the aim of each lab
Lab1 
(1) Detecting trends using Hodrick -Prescott Filter.
(2) Detrending a Time Series (Pandas, Signal, HP filter)
Dataset 1: India_Exchange_Rate_Dataset.xls
1. Implement detrending using differencing from scratch.
Dataset 2: shampoo.csv
1. Implement detrending using pandas differencing using diff() function.
2. Implement detrending using SciPy signal using signal.detrend submodule.
3. Implement detrending using HP filter using hp_filter submodule of statsmodels.

Lab2
Seasonality:
(1) Multiple Box Plots
(2) Autocorrelation Plot
(3) Deseasoning of Time-Series Data
(4) Seasonal Decomposition (Additive and Multiplicative)
i. Trend
ii. Seasonal Index
iii. Residual
(5) Detecting Cyclic Variation
Dataset 1: Facebook Stock Market Performance
1. Simulate the time series components from scratch.
2. Create the three decomposition models from scratch.
3. Implement seasonality decomposition using the seasonal_decompose() method.
Dataset 2: India Exchange Rate Dataset
1. Implement seasonality decomposition on the mentioned dataset (using additive and multiplicative decomposition).
Lab3
Dataset 1: Smart City Index Headers
1. Implement data wrangling with the help of various pre-processing strategies

Lab4
Dataset 1: Facebook Stock Market Performance
1. Implement Simple, Double and Triple Exponential Smoothing and analyse the best method to smoothen the dataset.

Lab5
Implement Augmented Dickey-Fuller test for unit roots on the dataset and find the following:
a. Calculate the following
i. Test Statistic
ii. P-value
iii. No Lags Used
iv. Number of Observations Used
v. Critical Value 1%, 5%, 10%
b. Conclude if the time series data contains unit roots or not.
c. Also, infer if the data is stationary or not.
d. Apply differencing if the data is not stationary.

Lab6
Dataset1: Facebook Stock Market Performance
1.Implement ARIMA(p,d, q)model on the given dataset.
a.Plot a histogram and compare the values with N(0,1).
b.Check for Stationarity.
c.State the coefficients which has to be used for theappropriatemodel selected.
d.Calculate the evaluation metrics (MSE, RMSE, MAPEand R2).
e.Forecast the future values and plot Confidence Interval Upper boundand Confidence Interval Lowerboundwith respect to train, testand predicted.
f.Analyse theactual data with predicted based on the plots:
i.Standardize Residual
ii. Histogram plus estimated density
iii.Normal Q-Q
iv. Correlogram
Lab7
Dataset1: ice_cream_vs_heater.csv
1.Implement thestochasticmodel on the given dataset.
a.Normalizethe dataset
b.Take First Difference to Remove Trend
c.Remove Increasing Volatility
d.Remove Seasonality
e.Plot the PACF forHeaterattribute
f.Select an appropriate modelbased on the correlationplot.
g.Calculate the Correlation between "heater" and lagged "ice cream".
h.Fit a VAR Model.
i.Analyze the Correlation matrix of residuals
j.State the final model used based on the coefficients and lag values.

Lab8
Dataset: Any sales/finance dataset.
1.Perform the following:
Step 1: Import all the libraries from Keras for neural network architectures.
Step 2: Define a function that extracts features (lagged values)
Step 3: Initializing Sequence, steps, and reshaping the output to input it to our CNN model.
Step 4: Reshaping the X matrices.
Step 5: Define the CNNmodel.
Step 6: Implement CNN Model Fitting.
Step 7: Predict the futurevalues.
Step 8:Plot the graph the predicted values

Lab9
Dataset1: Facebook Stock Market Performance
1.Iterate through combinations of models to best fit our time series.
2.Pick the GARCH model orders according to the PACF plot.
3.Fit the GARCH(p, q) model to our time seriesand predict the future volaitily.
4.Examine the model residuals and squared residuals for autocorrelation.
5.Implement theRolling Forecast Origin






