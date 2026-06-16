# Quantitative Trend Backtester & Risk Analytics Engine

## Project Overview
This project leverages an engineering systems approach to analyze historical market data and backtest a systematic trading thesis. Built entirely in Python using Google Colab, the engine streams asset data via the `yfinance` API, models rolling trend lines, and maps historical volatility alongside capital drawdown boundaries to evaluate downside risk profiles.

## Core Features & Methodology
* **Automated Data Ingestion:** Streams daily historical price architectures for any equity or benchmark index ($TSLA$, $SPY$).
* **Trend Optimization:** Employs 20-day and 50-day Simple Moving Average (SMA) crossover arrays to generate objective logic boundaries.
* **Risk Mapping:** Calculates 30-day rolling annualized volatility arrays via `NumPy` and `Pandas`.
* **Downside Analysis:** Models worst-case historical Peak-to-Trough Capital Drawdowns to isolate structural portfolio risks.

## Technologies Used
* **Language:** Python 3 (Google Colab Environment)
* **Data Processing:** Pandas, NumPy
* **Data Visualizations:** Matplotlib

## Key Analytical Insights
*(Note: Paste your printed output metrics here!)*
* **Tesla ($TSLA$) Max Drawdown:** XX.XX% 
* **S&P 500 ($SPY$) Max Drawdown:** XX.XX%

## Next Milestones on the Roadmap
- [ ] Implement Daily Vectorized P&L Calculation Architecture (Block 2)
- [ ] Build Out Transaction Cost and Execution Slippage Constraints
- [ ] Expand Strategy Analytics to include Sharpe Ratio and Win/Loss Ratios
