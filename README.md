# Hype vs Price: Ozempic Search Interest vs NVO Stock

This project analyzes how public interest in Ozempic (via Google Trends)
relates to Novo Nordisk's stock price (NVO), using weekly time series data.

It:
- pulls Google Trends data for "Ozempic"
- pulls NVO stock prices from Yahoo Finance
- aligns and merges the time series
- normalizes both series using z-scores
- runs a lagged correlation analysis
- visualizes how hype leads or lags price

Run the notebook in `notebooks/01_ozempic.ipynb` to reproduce the analysis.