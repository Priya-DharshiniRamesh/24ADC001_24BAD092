# Business Intelligence Lab – Experiment 1
## FAANG Stock Price Analysis using Tableau & Power BI

This repository contains the implementation of **Business Intelligence Experiment 1**, where Tableau and Power BI were used to analyze a FAANG stock price dataset. The experiment focuses on understanding the interfaces of both BI tools, importing data, creating visualizations, building dashboards, and comparing predicted and actual stock prices.

---

## 🎯 Objective

To understand the basic interface, data import process, and visualization capabilities of **Tableau** and **Power BI** using a FAANG stock price dataset. The experiment also explores dashboard creation, filters, calculated fields, and KPI visualization for financial data analysis.

---

## 🛠️ Tools Used

- Tableau Desktop / Tableau Public
- Microsoft Power BI Desktop
- CSV Dataset (FAANG Stock Prices)

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `TABLEAU EXP-1.twb` | Tableau workbook containing worksheets, calculated fields, and dashboard |
| `Power BI EXP-1.pbix` | Power BI report containing charts, slicers, KPI card, and DAX measure |
| `EX 1 (24BAD092).docx` | Lab record including pre-lab, in-lab, and post-lab exercises |

---

## 📊 Dataset

The dataset contains historical stock market information for FAANG companies along with technical indicators.

### Dataset Columns

| Column | Description |
|---------|-------------|
| Date | Trading date |
| Ticker | Stock symbol |
| Open | Opening price |
| High | Highest price |
| Low | Lowest price |
| Close | Closing price |
| Volume | Number of shares traded |
| SMA_7 | 7-Day Simple Moving Average |
| SMA_21 | 21-Day Simple Moving Average |
| EMA_12 | 12-Day Exponential Moving Average |
| EMA_26 | 26-Day Exponential Moving Average |
| RSI_14 | Relative Strength Index |
| MACD | Moving Average Convergence Divergence |
| MACD_Signal | MACD Signal Line |
| Bollinger_Upper | Upper Bollinger Band |
| Bollinger_Lower | Lower Bollinger Band |
| Daily_Return | Daily Percentage Return |
| Volatility_7d | Seven-Day Rolling Volatility |
| Next_Day_Close | Next Day Closing Price |

> **Note:** The dataset is not included in this repository. Reconnect the workbook or report to your local copy of the dataset if required.

---

# 📈 Tableau Implementation

### Visualizations Created

- 📈 Close Price Trend (Line Chart)
- 📊 Volume vs Predicted Price (Scatter Plot)
- 📋 Predicted Price by Stock (Highlight Table)
- 📉 Prediction Error Analysis

### Calculated Field

```text
Prediction Error = ABS([Next_Day_Close] - [Close])
```

### Filters Used

- Ticker
- Date

### Dashboard Features

- Interactive filtering
- Stock-wise analysis
- Date-wise trend analysis
- Prediction error visualization

---

# 📊 Power BI Implementation

### Visualizations Created

- 📈 Line Chart – Close Price Trend
- 📊 Clustered Column Chart – Close Price vs Predicted Price
- 📌 KPI Card – Average Prediction Error
- 🎛️ Slicers – Stock Ticker and Date

### DAX Measure

```DAX
Prediction Error =
ABS(Predicted - Close)
```

### Dashboard Features

- Interactive slicers
- KPI card
- Comparison of actual and predicted prices
- Dynamic filtering
- User-friendly report layout

---

## 🚀 How to Open the Project

### Tableau

1. Open `TABLEAU EXP-1.twb`.
2. Reconnect the workbook to your local dataset if prompted.
3. Explore the worksheets and dashboard.

### Power BI

1. Open `Power BI EXP-1.pbix`.
2. Refresh or reconnect the dataset if necessary.
3. View the interactive report.

---

## 📚 Key Learning Outcomes

- Understood the interfaces of Tableau and Power BI.
- Imported datasets from CSV files.
- Created multiple business visualizations.
- Applied filters and slicers for interactive analysis.
- Built calculated fields and DAX measures.
- Designed dashboards for financial data visualization.
- Compared predicted stock prices with actual closing prices.
- Learned how BI tools support business decision-making.

---

## 📷 Dashboard Preview

### Tableau Dashboard
<img width="934" height="470" alt="image" src="https://github.com/user-attachments/assets/bb1bddcb-bb87-4c89-bd76-ad9338e6d0f3" />


### Power BI Dashboard

<img width="916" height="497" alt="image" src="https://github.com/user-attachments/assets/e12e6377-551f-4076-b110-55c441338ce2" />


---

## ✅ Result

Successfully explored the interfaces and fundamental features of Tableau and Power BI. Imported the FAANG stock dataset, created interactive visualizations, implemented calculated fields and DAX measures, and designed dashboards for stock price analysis and financial decision-making.

---

## 👨‍💻 Author

**Priya Dharshini R**

- Register Number: **24BAD092**
- Department of Artificial Intelligence and Data Science
- Kumaraguru College of Technology
