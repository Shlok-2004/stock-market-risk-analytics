# 📊 Stock Market Risk & Behavior Analytics System

An end-to-end financial analytics project designed to analyze stock market risk and behavior using historical price data.  
Instead of predicting prices, this system focuses on understanding volatility, drawdowns, and correlation structures to support data-driven investment insights.

---

## 🎯 Project Objective

To build a decision-support analytics system that:

- Measures stock return behavior over time  
- Quantifies short-term risk using rolling volatility  
- Evaluates downside risk through drawdown analysis  
- Analyzes diversification potential using correlation matrices  
- Visualizes insights in an interactive Power BI dashboard  

---

## 📌 Key Features

✔ Daily Return Calculation  
✔ 30-Day Rolling Volatility  
✔ Maximum Drawdown Analysis  
✔ Cumulative Return Comparison  
✔ Correlation Matrix Heatmap  
✔ Interactive Power BI Dashboard  

---

## 🛠 Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- yfinance API  
- Power BI  
- DAX (Data Analysis Expressions)  

---

## 📂 Project Structure

```
stock-market-risk-analytics/
│
├── data/
│   ├── clean_stock_data.csv
│   ├── stock_analytics_data.csv
│   ├── stock_correlation_matrix.csv
│   ├── max_drawdown.csv 
│
├── stock_market_risk_&_behaviour_analysis.ipynb
│
├── dashboard/
│   ├── Stock Market Risk & Behavior Analytics Dashboard.pbix
│   └── dashboard_screenshot.png
│
└── README.md

```

---

## 📊 Risk Metrics Implemented

### 1️⃣ Daily Return

Measures percentage change in stock price between consecutive trading days.

\[
Daily\ Return = \frac{P_t - P_{t-1}}{P_{t-1}}
\]

---

### 2️⃣ Rolling Volatility (30-Day)

Standard deviation of daily returns over a rolling 30-day window.  
This metric captures short-term fluctuations in stock risk.

---

### 3️⃣ Drawdown

Measures the percentage decline from a stock’s historical peak price.

\[
Drawdown = \frac{Current\ Price - Peak\ Price}{Peak\ Price}
\]

---

### 4️⃣ Maximum Drawdown

Represents the worst historical loss from peak to trough, indicating the maximum downside risk experienced by a stock.

---

### 5️⃣ Correlation Matrix

Measures how stocks move relative to each other.  
Used to evaluate diversification opportunities and portfolio risk structure.

---

## 📈 Dashboard Overview

The Power BI dashboard includes:

- KPI Summary (Latest Price, Average Daily Return, Average Volatility, Maximum Drawdown)
- Rolling Volatility Trend Analysis
- Drawdown Behavior Visualization
- Cumulative Return Comparison
- Risk Comparison Across Stocks
- Correlation Heatmap

---

## 🔍 Key Insights

- NVIDIA demonstrates strong cumulative growth but exhibits higher volatility and deeper drawdowns.
- HDFCBANK maintains relatively stable volatility and lower downside risk.
- Tesla shows significant drawdown phases during market corrections.
- Correlation analysis highlights diversification potential between selected equities.

---

## 🚀 How to Run

1. Install required Python libraries:

```bash
pip install pandas numpy yfinance
```

2. Run the data collection and cleaning notebook.
3. Generate the analytics dataset.
4. Open the `.pbix` file in Power BI Desktop.
5. Use slicers to interactively explore stock behavior.

---

## 🧠 Learning Outcomes

This project demonstrates:

- Time-series data analysis  
- Financial risk metric engineering  
- Data cleaning and transformation  
- Analytical storytelling through dashboards  
- DAX-based measure creation  
- Comparative equity risk evaluation  

---

## 📌 Future Improvements

- Add Sharpe Ratio  
- Add Beta (market sensitivity)  
- Expand to additional stocks and indices  
- Deploy dashboard via Power BI Service  

---

## 👤 Author

Shlok Dendage  
  

---

⭐ If you found this project useful, feel free to star the repository.
