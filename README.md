# Nifty Event Calendar Backtest — RBI Policy Dates 2024-2025

## Research Question
Can a short ATM straddle strategy around RBI policy dates 
generate consistent profits by capturing IV crush?

## Strategy
Sell ATM straddle 2 days before RBI announcement.
Buy back 2 days after. Repeat for all 8 RBI events.

## Results
- Win Rate: 6/8 trades (75%)
- Total P&L: -86 Nifty points (net loss)
- Best trade: Dec 2024 (+236 points)
- Worst trade: Apr 2025 (-529 points)

## Key Finding — Taleb's Warning
High win rate does not equal profitable strategy.
Two tail events (Feb 2025 and Apr 2025 rate cuts) wiped out 
6 consecutive winning trades.
Short volatility strategies are fragile to tail risk.

## Trading Conclusion
Blind short volatility before every RBI = negative expectancy.
Selective trading only when outcome is highly expected = better edge.
Position sizing and stop losses are essential.

## Charts
- event_backtest.png — HV before vs after + IV crush rate
- pnl_simulation.png — P&L per trade + equity curve

## Tech Stack
Python, yfinance, Pandas, NumPy, Matplotlib, Google Colab

## Author
Aayush Naithanii | NISM Series VIII Certified
