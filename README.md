# Champagne-Sales-Forecasting

**Problem Statement:**
Provided Perrin Freres Monthly Champagne Sales data. The data is univariate time series, using the same forecast the sales of Champagne.

**Solution Explaination:**
The data is **non-stationary** and **seasonal**. The stationarity of the data is checked using both the **rolling statistics test** and the **AD-Fuller test**. The data is made stationary by taking a **difference of 12 months**. Since, the data is seasonal hence **SARIMAX algorithm** is used for forecasting the sales of the champagne.

The Repository contains the following:
1) Jupyter Notebook, contains the solution of the problem statement.
2) Dataset
3) README.md file
