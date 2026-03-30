# Stock Market Analysis - Tech Giants Comparison

A comprehensive Jupyter notebook analyzing 5 years of stock price data (2013-2018) for major tech companies: Apple, Amazon, Google, and Microsoft. This project includes time series analysis, return calculations, risk assessment, market crash analysis, and investment simulations.

## 📊 Overview

This project performs in-depth analysis of historical stock data to identify:
- **Safest stock** - based on volatility (daily return standard deviation)
- **Best performer** - based on total return percentage over 5 years
- **Investment potential** - using $1 million investment simulation
- **Market risks** - identifying worst trading days for each stock
- **Comparative analysis** - normalized price trends across all 4 stocks

## 📈 Data

The analysis covers 4 major tech stocks:
- **AAPL** - Apple Inc.
- **AMZN** - Amazon Inc. 
- **GOOG** - Alphabet Inc. (Google)
- **MSFT** - Microsoft Corporation

**Time Period:** January 2013 - December 2018 (5 years, ~1,258 trading days)

## 🏆 Key Findings

| Metric | Stock | Value |
|--------|-------|-------|
| **Highest Total Return** | AMZN | 440.86% |
| **2nd Best Return** | MSFT | 225.26% |
| **3rd Best Return** | AAPL | 135.12% |
| **Lowest Return** | GOOG | 87.76% |
| **Safest (Lowest Volatility)** | GOOG | 1.41% |
| **Highest Volatility** | AMZN | 1.82% |

### Investment Simulation Results
If you had invested **$1 Million in Amazon** on January 2, 2013:
- **Final Value (Dec 31, 2018):** $5,408,589
- **Total Gain:** $4,408,589
- **Return:** +440.86%

## 📚 Notebook Sections

1. **Data Collection** - Loading CSV files for 4 tech stocks
2. **Data Cleaning & Preparation** - Type conversions, null checks, duplicate detection, data validation
3. **EDA & Time Series Analysis** - Daily returns calculation, volatility analysis
4. **Risk Assessment** - Standard deviation of daily returns for each stock
5. **Total Return Analysis** - Comparing final returns using cumulative returns
6. **Investment Simulations** - $1M investment value projections for Amazon
7. **Market Crash Analysis** - Top 5 worst trading days for each stock with visualizations
8. **Comprehensive Comparison** - 4-panel visualization showing:
   - Cumulative returns comparison (2013-2018)
   - Normalized price comparison (base = 100)
   - Risk vs Return scatter plot
   - Total return bar chart

## 📉 Worst Market Crashes (Top 5 Losses by Stock)

### Amazon (AMZN)
- Worst loss: -10.41% (January 29, 2016)
- Most volatile stock but highest rewards

### Microsoft (MSFT)
- Worst loss: -10.64% (July 1, 2013)
- Recovered well with strong long-term performance

### Apple (AAPL)
- Worst loss: -7.87% (February 28, 2014)
- Moderate volatility with steady growth

### Google (GOOG)
- Worst loss: -5.10% (February 2, 2018)
- Most stable with smallest daily crashes

## 🛠️ Technologies Used

- **Python 3.7+** - Programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Static visualizations
- **Seaborn** - Statistical data visualization
- **Plotly Express** - Interactive charts (optional)
- **Jupyter Notebook** - Interactive analysis environment

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sameer2403/StockMarketAnalysis.git
   cd StockMarketAnalysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook StockPrice.ipynb
   ```

4. Run cells sequentially to reproduce the analysis

## 📁 Project Structure

```
StockMarketAnalysis/
├── StockPrice.ipynb           # Main analysis notebook
├── README.md                  # Project documentation
├── .gitignore                 # Git ignore rules
└── individual_stocks_5yr/     # Historical CSV data
    ├── AAPL_data.csv
    ├── AMZN_data.csv
    ├── GOOG_data.csv
    └── MSFT_data.csv
```

## 💡 Key Insights

1. **Amazon's Dominance**: AMZN delivered 440.86% return, 5x higher than Google
2. **Risk-Return Tradeoff**: Amazon has highest volatility but highest rewards
3. **Google's Safety**: GOOG has lowest volatility (1.41%) making it safest choice
4. **Microsoft's Balance**: MSFT offers good balance of 225% return with moderate risk
5. **Market Crashes**: All stocks experienced significant single-day drops, with MSFT and AMZN showing -10%+ drops

## 🎯 Use Cases

- Investment research and decision making
- Risk assessment for portfolio construction
- Understanding historical stock performance
- Learning data analysis with real-world data
- Time series analysis techniques

## 📖 How to Use This Notebook

1. **Learning**: Study the data cleaning and analysis techniques
2. **Research**: Use findings to inform investment decisions
3. **Modification**: Adapt code to analyze other stocks or time periods
4. **Reference**: Use as template for similar financial analyses

## ⚠️ Disclaimer

This analysis is for educational and research purposes only. Past performance does not guarantee future results. Always consult with a financial advisor before making investment decisions.

## 👨‍💼 Author

Created for stock market analysis and investment research.

**Repository**: https://github.com/sameer2403/StockMarketAnalysis
