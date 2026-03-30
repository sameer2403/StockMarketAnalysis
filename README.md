# Stock Market Analysis

A comprehensive Jupyter notebook analyzing 5 years of stock price data for major tech companies (Apple, Amazon, Google, Microsoft).

## Overview

This project performs time series analysis and return calculations on historical stock data to identify:
- **Safest stock** - based on volatility (daily return standard deviation)
- **Best stock** - based on total return percentage
- Trend analysis and price patterns

## Data

The analysis covers 4 major tech stocks:
- **AAPL** (Apple)
- **AMZN** (Amazon) 
- **GOOG** (Google)
- **MSFT** (Microsoft)

Time period: 5 years of daily pricing data

## Key Findings

| Stock | Total Return | Risk (Volatility) |
|-------|--------------|-------------------|
| AMZN  | 440.86%      | Highest gains     |
| MSFT  | 225.26%      | Strong performer  |
| AAPL  | 135.12%      | Steady growth     |
| GOOG  | 87.76%       | Most conservative |

## Notebook Content

1. **Data Collection** - Loading CSV files for 4 tech stocks
2. **Data Cleaning & Preparation** - Type conversions, null checks, duplicate detection
3. **EDA & Time Series Analysis** - Daily returns, volatility calculations
4. **Total Return Analysis** - Comparing final returns across stocks
5. **Visualizations** - Bar charts and trend analysis

## Usage

1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

2. Open the notebook:
   ```bash
   jupyter notebook StockPrice.ipynb
   ```

3. Run cells sequentially to reproduce the analysis

## Files

- `StockPrice.ipynb` - Main analysis notebook
- `individual_stocks_5yr/` - Historical CSV data for each stock

## Technologies

- Python 3
- Pandas - Data manipulation
- NumPy - Numerical computation
- Matplotlib & Seaborn - Visualization
- Jupyter - Interactive notebooks

## Author

Created for stock market analysis and investment research.
