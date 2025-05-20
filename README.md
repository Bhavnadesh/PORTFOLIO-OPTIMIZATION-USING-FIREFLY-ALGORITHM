Implemented Improved Firefly Algorithm for Optimal Portfolio Selection

- Fetched historical stock data using yfinance for 30 assets (2017–2022)
- Handled fallback to 'Close' prices if 'Adj Close' is unavailable
- Computed daily returns, expected annual returns, and covariance matrix
- Developed Improved Firefly Algorithm with cardinality constraints (K=20)
- Optimized portfolio weights balancing return and risk (lambda=0.5)
- Added checks for empty data and improved code robustness
