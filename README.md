📈 MACD Wavelet Trading Bot
This bot runs an enhanced MACD-based trading strategy using wavelet smoothing and executes real trades through the Alpaca API.

🚀 What It Does
Pulls recent price data (e.g. SPY) from Yahoo Finance

Calculates MACD (12 EMA − 26 EMA) and 9 EMA signal line

Applies wavelet transforms to smooth out noisy price signals

Trades when smoothed MACD crosses above/below the signal line

Uses Alpaca API to place real/paper trades every 4 hours

📚 Strategy Source
This bot is based on the January 2025 paper:
“Optimizing MACD Trading Strategies: A Dance of Finance, Wavelets, and Genetics” (arXiv)

The paper improves classic MACD trading by:

Applying wavelet transforms to denoise signals

Using MACD divergence analysis

Optimizing MACD parameters using a genetic algorithm

📊 Backtests in the paper showed a ~5% annual return boost and improved Sharpe ratio.
