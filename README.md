# ALGO_TRADE_SYS

# Momentum + Value Algorithmic Trading Strategy

## Overview
This project demonstrates an **algorithmic trading strategy** that combines **Momentum** and **Value Investing** principles applied to S&P 500 stocks. The strategy ranks stocks using **6-month price momentum** and **valuation metrics (P/E ratio)** to create a composite score for stock selection.

The project includes:
- Monthly portfolio rebalancing
- Transaction cost adjustments
- Performance metrics including Sharpe ratio and maximum drawdown
- Visualization comparing portfolio performance vs S&P 500 benchmark

---

## Features

1. **Momentum Calculation**
   - Computes 6-month price returns to identify trending stocks.

2. **Value Metrics**
   - Pulls key valuation metrics (P/E, P/B, Dividend Yield, Market Cap) using `yfinance`.
   - Stocks with lower P/E are ranked higher for value investing.

3. **Composite Scoring**
   - Combines momentum and value ranks to select top stocks for investment.

4. **Monthly Rebalancing**
   - Portfolio is rebalanced at the start of each month to hold the top N ranked stocks.

5. **Transaction Costs**
   - Includes a small per-trade cost to simulate realistic trading.

6. **Performance Evaluation**
   - Calculates cumulative portfolio returns, Sharpe ratio, and maximum drawdown.
   - Compares strategy performance to the S&P 500 benchmark.

7. **Visualization**
   - Plots portfolio growth vs benchmark index.
   - Shows top momentum and value stocks.

---

## Getting Started

### Prerequisites
- Python 3.x  
- Google Colab or local Python environment  
- Required Python packages: Bash, pandas, numpy, yfinance, matplotlib
