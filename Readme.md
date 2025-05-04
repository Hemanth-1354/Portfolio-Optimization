# Portfolio Optimization and Bollinger Band Strategy

This project focuses on building an optimized investment portfolio using historical stock data, advanced financial metrics, and strategic decision-making tools.

## 🧠 Key Concepts Covered

- **Portfolio Optimization**: We simulate thousands of portfolios using different stock weight combinations and select the ones with the highest Sharpe Ratio and lowest volatility.
- **Sharpe Ratio & Beta**: Used to evaluate risk-adjusted returns and market correlation.
- **Efficient Frontier**: Visualization of optimal portfolios given different levels of risk.
- **Bollinger Bands Strategy**: Suggests "Buy", "Sell", or "Hold" signals based on rolling mean and standard deviation bands.

## 💼 Stocks Analyzed

- Tesla (TSLA)
- Apple (AAPL)
- Nvidia (NVDA)
- AMD (AMD)
- Netflix (NFLX)
- S&P 500 ETF (SPY)

## 🛠 Tools & Libraries

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scipy.optimize` for optimization
- `Alpha Vantage` API for stock data
- `Backtrader` (for future backtesting)

## 🧪 Strategy Logic

1. **Correlation and Risk Analysis**: Visualize how stocks move together.
2. **Sharpe and Volatility Metrics**: Evaluate stocks over time.
3. **Portfolio Simulation**: Create 10,000+ random portfolios and pick the best ones.
4. **Bollinger Band Signals**: Depending on your holding period (short, medium, long), the system dynamically adjusts Bollinger Band width and gives investment suggestions.

## 📈 Output

- Correlation Heatmap
- Efficient Frontier with Max Sharpe and Min Volatility Points
- Top 5 Portfolio Configurations
- Dynamic Strategy Recommendation per Stock

## 🧩 Future Scope

- Incorporate sector-based diversification
- Real-time signal dashboard with alerts
- Integration with live brokerage APIs

---

