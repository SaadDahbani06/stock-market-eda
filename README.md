## Stock Market EDA 

An exploratory data analysis (EDA) of selected US stocks using Yahoo Finance data via `yfinance`. The notebook walks through data collection, cleaning, feature engineering (returns, volatility, moving averages), and a variety of visual analyses, including correlations, risk/return, and a simple equal-weight portfolio vs. SPY.

### Features
- Clean, reproducible analysis with fixed date range and tickers
- Daily returns, annualized volatility, moving averages
- Correlation heatmap, cumulative returns, normalized price comparison
- Risk vs return scatter, COVID period impact analysis
- Simple equal-weight portfolio vs SPY benchmark

### Project Structure
- `Stock_Market_Analysis_Project.ipynb`: Main analysis notebook
- `requirements.txt`: Python dependencies
- `.gitignore`: Ignore cache and environment clutter
- `LICENSE`: MIT License

### Quickstart
1. Create and activate a virtual environment (recommended):
```bash
python3 -m venv .venv && source .venv/bin/activate
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Launch Jupyter and run the notebook:
```bash
jupyter lab
# or
jupyter notebook
```

### Configuration
You can change tickers and dates at the top of the notebook:
- `tickers = ['AAPL', 'MSFT', 'META', 'GOOGL', 'SPY']`
- `start_date = '2020-01-01'`
- `end_date = '2025-01-01'`

### Data Source
Prices are downloaded from Yahoo Finance via the `yfinance` Python package. Data may be subject to provider limitations and revision.

### Disclaimer
This project is for educational purposes only and does not constitute financial advice. Past performance does not guarantee future results.

### License
MIT © 2025 Saad Dahbani


