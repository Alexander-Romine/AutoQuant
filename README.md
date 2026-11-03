# AutoQuant

Automated portfolio simulation and analysis for building and testing investment strategies.

**Live site:** https://auto-quant-portfolio.vercel.app

![AutoQuant screenshot](screenshot.png)

## Features

- Search and add tickers to build a portfolio, with weight allocation and saved portfolios
- DRIP (dividend reinvestment) and optional margin leverage with a custom borrow rate
- Portfolio optimizer: Max Sharpe, Min Volatility, Value (P/E), GARP (PEG) and Size (EV/EBITDA)
- Monte Carlo simulation — 10K to 50K runs over 5, 10 or 20 years
- Managed strategy with monthly, quarterly or annual rebalancing
- Historical backtest chart with drawdown summary
- Allocation pie with expected return, average drawdown and volatility
- Diversification heatmap of ticker correlations
- Light and dark themes, portfolios and settings kept in the browser

## Tech Stack

- [Vite](https://vite.dev/)
- JavaScript
- [Chart.js](https://www.chartjs.org/)
- Market data from [Twelve Data](https://twelvedata.com)
- Hosted on [Vercel](https://vercel.com)
