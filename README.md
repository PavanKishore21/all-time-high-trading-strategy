# **All-Time High Stock Trading Strategy**

An algorithmic trading strategy designed to identify stocks at all-time highs, leveraging historical price data and advanced financial metrics for optimal portfolio performance. This project implements a systematic approach to backtesting and risk management, providing insights into stock performance and portfolio growth.

---

## **Features**
- **Stock Selection**: Filters stocks based on trading volume and total traded value from the National Stock Exchange (NSE).
- **All-Time High Detection**: Identifies stocks surpassing historical price peaks using rolling window analysis.
- **Sharpe Ratio Calculation**: Evaluates risk-adjusted returns for optimal stock selection.
- **Entry/Exit Signals**: Automates entry and exit price calculations, supporting monthly trading decisions.
- **Backtesting**: Measures strategy performance with metrics like CAGR, maximum drawdown, and win-loss ratios.
- **Portfolio Analysis**: Tracks cumulative returns, equity curves, and drawdowns for performance optimization.

---

## **Key Results**
- **CAGR**: 19.99% over 248 months.
- **Max Drawdown**: -15.03%.
- **Return Range**: -9.01% to 21.67% per month.
- **Positive Months**: 137; **Negative Months**: 111.

---

## **Technologies Used**
- **Programming**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, NSEpy, Yahoo Finance API
- **Tools**: Data analysis, portfolio optimization, financial backtesting

---

## **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/PavanKishore21/all-time-high-trading-strategy.git
   cd all-time-high-trading-strategy
2. Install required Python libraries:
   ```bash
   pip install pandas numpy matplotlib yfinance nsepy
3. Run the script:
   ```bash
   python all_time_high.py

