# 📈 AAPL and NVDA Stocks Overview
## 📝 Project Description
This project applies financial econometrics to analyze two major tech stocks — Apple (AAPL) and NVIDIA (NVDA) — using advanced technical indicators and statistical models. We leverage Moving Average (MA), Relative Strength Index (RSI), Bollinger Bands, and Cointegration strategies to identify profitable trading opportunities, optimize entry/exit points, and evaluate mean-reversion patterns.
The study combines Python-based backtesting with quantitative finance techniques to compare the performance of multiple strategies over a two-year period, providing a clear, data-driven basis for investment decisions.

## 📊 Project Overview
The analysis explores:

a. Trend-following strategies (Moving Average crossovers)

b. Momentum-based indicators (RSI thresholds)

c. Volatility bands (Bollinger Bands)

d. Statistical arbitrage (Cointegration and Mean Reversion)

e. Backtesting was performed to assess the profitability of each method, with a focus on return optimization and risk management.

## 🗂 Dataset Structure & Source
Source: Yahoo Finance historical data for AAPL and NVDA (daily adjusted close prices).

## 📈 Insight Summary
These are the conclusion based on each technical analysis's results found:

#### 🔸 MA and RSI
![MA and RSI](https://github.com/trinitarn/Equity_Research_NVDA_AAPL/blob/main/First%20Photo.jpg)

### 1. Moving Average (MA) Strategy — MA(20,100)
NVDA: ~+195% return in backtesting — very strong uptrend signal.

AAPL: ~+40% — profitable but far less aggressive growth.

Verdict: Buy NVDA for trend-following gains.

### 2. Relative Strength Index (RSI 40,60)
NVDA: ~+34% return — momentum plays work well.

AAPL: ~+12.4% — still positive but weaker.

Verdict: Buy NVDA for momentum trades; AAPL less responsive.

#### 🔸 Bollinger Bands and Cointegration
![Bollinger Bands and Cointegration](https://github.com/trinitarn/Equity_Research_NVDA_AAPL/blob/main/Second%20Photo.jpg)

### 3. Bollinger Bands (20,2)
Combined test (both stocks): ~+10.59% return.

Signals are weaker here but still indicate NVDA has larger deviations from the mean, meaning more profitable breakouts/reversions.

Verdict: Favor NVDA when trading volatility bands.

### 4. Cointegration Strategy
Pairing AAPL & NVDA allows market-neutral trading:

Buy NVDA when spread is below threshold (undervalued relative to AAPL).

Sell NVDA when spread is above threshold.

This strategy profits from relative mispricing regardless of market direction.

Verdict: Use NVDA as the long leg in pairs trading, AAPL as the short leg when divergence occurs.

## 📌 Final Recommendation
Primary Buy: NVDA — outperforms in trend, momentum, and volatility strategies.

Secondary Role: AAPL — keep as a hedge in cointegration strategy to manage risk.

Best Combined Approach:

Aggressive Growth → NVDA standalone trades (MA + RSI).

Lower Risk → Cointegration pairs (Long NVDA, Short AAPL when spread is wide).

## Final Product

This was actually my class project with 2 of my friends and [here's](https://github.com/trinitarn/Equity_Research_NVDA_AAPL/blob/main/PPT%20Analyzing%20Stocks.pdf) the final presentation.
