# NASDAQ Top 5 – Stock Return Analysis

A professional financial analysis of the five largest NASDAQ-listed companies by market capitalisation, covering the period **January 2025 – June 2026**.

| Ticker | Company |
|--------|---------|
| MSFT | Microsoft |
| AAPL | Apple |
| NVDA | NVIDIA |
| AMZN | Amazon |
| GOOGL | Alphabet |

---

## Scope of Analysis

This project delivers a structured, data-driven overview of recent stock performance across five major technology companies. It is designed as a foundation for client-facing financial reporting and can be extended with custom ticker symbols, date ranges, or additional metrics on request.

The analysis covers:

- **Closing prices over time** – price development visualised as a multi-line chart
- **Daily simple rate of return** – individual subplots per stock for granular comparison
- **Mean daily return** – bar chart ranking stocks by average performance
- **Variance** – quantified measure of return unpredictability per stock
- **Standard deviation** – risk assessment in the same unit as returns
- **Correlation matrix** – heatmap showing how closely stocks move together

---

## Tech Stack

- Python 3.11+
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [yfinance](https://github.com/ranaroussi/yfinance)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)

---

## Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/annearcana/nasdaq-top5-analysis.git
cd nasdaq-top5-analysis

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the notebook
jupyter notebook nasdaq_top5_analysis.ipynb
```

---

## Sample Insights

- The stock with the **highest mean daily return** delivered the strongest average performance over the period.
- The stock with the **highest standard deviation** carried the greatest day-to-day price risk.
- All five stocks exhibit **positive return correlations** — a characteristic pattern within the technology sector, driven by shared exposure to macroeconomic factors such as interest rates and AI market sentiment.
- A **Sharpe Ratio** analysis is available as an add-on to compare risk-adjusted performance across stocks.

---

## Services

Interested in a tailored analysis for your portfolio or a specific set of assets?  
**[Get in touch](mailto:annearcana@outlook.com)**

---

## Acknowledgements

This project was developed independently, inspired by a financial data analysis framework from [Codecademy](https://www.codecademy.com). All code, analysis, and written content are original work by Anne Arcana.

---

*© 2026 Anne Arcana · Data sourced via Yahoo Finance (yfinance) · Not financial advice.*
