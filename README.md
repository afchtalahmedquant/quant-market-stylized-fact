# quant-market-stylized-fact

# Quantitative Analysis of Financial Market Stylized Facts

This project explores well-known **empirical properties ("stylized facts") of financial markets** using Python and 20 years of historical market data.

The goal is to investigate whether real market data follow the assumptions commonly used in classical financial models.

## Key Questions

Do financial returns actually follow a normal distribution?

Are correlations stable through time?

Is volatility constant?

This project investigates these questions using empirical data.

---

# Dataset

Historical daily price data downloaded using **Yahoo Finance**.

Assets analyzed:

- SPY — S&P 500 ETF
- AAPL — Apple Inc.
- TSLA — Tesla Inc.
- DAX — German Equity Index

Time period:

2005 – 2026

---

# Stylized Facts Investigated

### 1. Volatility Clustering

Financial markets exhibit **persistent periods of high and low volatility**.

Large price changes tend to be followed by large price changes.

This phenomenon motivates models such as:

- EWMA (RiskMetrics)
- GARCH

---

### 2. Fat Tails

Empirical return distributions show **higher kurtosis than the normal distribution**.

This means extreme events occur more frequently than predicted by Gaussian models such as Black-Scholes.

Tools used:

- Histogram
- QQ-plot
- Kurtosis & Skewness

---

### 3. Correlation Breakdown During Crises

Asset correlations tend to **increase significantly during market stress**.

This reduces the effectiveness of diversification exactly when investors need it most.

---

# Methods

The analysis includes:

- Log-returns computation
- Annualized statistics
- Rolling volatility
- EWMA volatility (RiskMetrics)
- Distribution analysis
- Autocorrelation of returns and volatility
- Correlation matrices across assets

---

# Technologies

Python ecosystem:

- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scipy
- yfinance

---

# Key Insights

The analysis confirms several well-known stylized facts:

• volatility clustering  
• fat-tailed return distributions  
• low autocorrelation in returns  
• persistent autocorrelation in volatility  
• correlations increase during crises

---

# Example Output

Rolling volatility during major crises:

- 2008 Global Financial Crisis
- COVID-19 Market Crash
- 2022 Bear Market

Volatility spikes above **80% annualized** during extreme periods.

---


# Author

Ahmed — Quantitative Finance Enthusiast

Interested in:

- Quantitative research
- Financial data science
- Volatility modeling
