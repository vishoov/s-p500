Unsupervised Learning Trading Strategy Using Logistic Regression on SP500 Stocks

Project Overview: Developed a comprehensive trading strategy for SP500 stocks by employing Logistic Regression to predict market direction. Integrated key technical indicators including Garman-Klass Volatility, RSI, Bollinger Bands, ATR, MACD, and Dollar Volume to enhance predictive accuracy and strategy performance.

Key Metrics Implemented:


Relative Strength Index (RSI): Computed to identify overbought or oversold conditions in the stock, helping to determine potential buy or sell signals.
Bollinger Bands: Implemented to assess market volatility and identify potential price reversal points by comparing the price movements with the upper and lower bands.
Average True Range (ATR): Measured to evaluate market volatility and determine potential stop-loss levels.
Moving Average Convergence Divergence (MACD): Used to identify changes in the strength, direction, momentum, and duration of a trend.
Dollar Volume: Calculated to gauge trading activity and liquidity.
Implementation Details:

Data Source: Historical stock data obtained from Yahoo Finance.
Preprocessing: Handled missing values and ensured data integrity before applying technical indicators.
Feature Engineering: Created lagged features to capture temporal dependencies in stock prices.
Model Training: Applied Logistic Regression with balanced class weights to predict market direction based on the engineered features and technical indicators.
Performance Evaluation: Utilized performance metrics such as Sharpe Ratio to optimize the strategy and improve returns. Implemented Efficient Frontier methodology to maximize Sharpe Ratio and capture momentum patterns.
Achievements:

Successfully integrated multiple technical indicators to build a robust trading strategy.
Demonstrated enhanced strategy performance through optimized stock clusters and calculated monthly returns for different time horizons.
Visualized strategy performance and compared it against the market benchmark to assess effectiveness.
