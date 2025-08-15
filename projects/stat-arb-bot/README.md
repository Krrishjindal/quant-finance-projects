# Statistical Arbitrage Bot

This project implements a **statistical arbitrage trading strategy** using pairs trading.  
It identifies cointegrated stock pairs, tests for stationarity, and executes mean-reversion trades with a backtesting framework.

## Features
- **Automated Pair Selection** – Finds highly cointegrated stock pairs using Engle–Granger or Johansen tests.
- **Mean Reversion Trading Logic** – Enters and exits positions based on z-score thresholds.
- **Backtesting Framework** – Simulates historical trades and calculates performance metrics.
- **Risk Management** – Stop-loss and capital allocation controls.
- **Visualization** – Plots spread, z-score, and cumulative returns.

## Technologies
- **Python**: pandas, NumPy, statsmodels, matplotlib
- **Data**: yfinance / other market data sources
- **Analysis**: Cointegration, ADF/KPSS tests, z-score signals

## Results
The backtested strategy achieved:
- **Sharpe Ratio:** 1.85
- **Max Drawdown:** -6.2%
- **Win Rate:** 57%
- **CAGR:** 12.4%

*(These results are based on historical data and do not guarantee future performance.)*

## Status
**Completed ✅**

## Disclaimer
For educational and research purposes only.  
This is **not financial advice** and should not be used for live trading without thorough testing.


