# 💼 Portfolio Curation Using Stock Market Analysis

A Python-based project for evaluating and comparing Indian IT and Pharma sector stocks to assist in portfolio construction. This project aims to simplify complex financial graphs and automate stock analysis for better investment decision-making.

---

## 🚩 Problem Statement

Building a stock portfolio is often a daunting task for individuals unfamiliar with the intricacies of financial markets. Complex charts, volatility, and technical jargon can be overwhelming — especially without a background in finance.

Traditional tools like Excel are widely used, but as data complexity grows, they fall short in handling large datasets or creating dynamic visualizations. Investors need simpler, more intuitive solutions that can help them:

- Understand **market dynamics** through clear visuals  
- Analyze **returns, volatility, and correlations**  
- Make **data-driven decisions** without deep financial expertise  

> 📉 **Only ~3% of Indian families participate in the stock market** despite over 11 crore demat accounts as of January 2023. This project is a step toward **financial inclusion and empowerment**.

---

## 🧠 Introduction

Manual data analysis in tools like Excel is time-consuming and error-prone. This project leverages Python to:

- 📊 Automate stock data retrieval from **Yahoo Finance**
- 🧮 Analyze price trends, returns, and volatility
- 🌐 Provide **interactive visualizations** using Python libraries
- 📈 Empower users with clear graphs and portfolio insights

> The goal is to **democratize access** to stock market insights and **reduce dependency** on complex financial knowledge.

---

## 🎯 Project Objective

The objective of this project is to make portfolio curation:

- ✅ **Simpler** through automated tools  
- 📚 **More educational** via easy-to-understand visualizations  
- 🔍 **More insightful** using real market data  
- 🤝 **Inclusive** for people with no prior finance background  

This approach fosters a deeper understanding of the stock market and enables users to:

- Choose stocks by **sector (IT, Pharma)**
- Filter based on **price brackets**
- Build portfolios aligned with **risk appetite and goals**

---

## 🧪 Proposed Solution

Our solution offers:

- 🧾 **Pre-defined stock code lists** categorized by price
- ⚙️ A ready-to-use **Python script** that fetches and analyzes stock data
- 📉 Graphical representations (e.g., price trends, returns, heatmaps)
- 💡 Insights into volatility, correlation, and return potential

> Just input the stock code and let Python handle the rest. No prior coding or finance expertise required.

---

## ⚙️ Technologies Used

| Tool/Library     | Purpose                                 |
|------------------|------------------------------------------|
| `yfinance`       | Pull historical stock data               |
| `pandas`         | Data wrangling and manipulation          |
| `numpy`          | Mathematical computations                |
| `matplotlib`     | Visualizations of time-series data       |
| `seaborn`        | Correlation heatmaps                     |
| `Jupyter`        | Interactive notebook development         |

---

## 🗂 Project Workflow

### 🏁 1. Commencement
- Curated company lists from IT and Pharma sectors
- Segregated stocks based on price ranges:
  - `< ₹500`
  - `₹500 – ₹1000`
  - `₹1000 – ₹2500`
  - `> ₹2500`

### 📥 2. Data Ingestion
- Stock tickers used in Python to pull real-time historical data via `yfinance`

### 📊 3. Analysis
- Cumulative returns
- Daily returns
- Rolling volatility
- Correlation matrices between stocks

### 📈 4. Visualization
- Line plots for trends
- Bar charts for comparative returns
- Heatmaps for correlation

---

## 🧾 Notebook Breakdown

- **🖥 IT Sector - Large Cap:** `comparison.ipynb`  
- **💊 Pharma Sector:** `Pharma1T2500Comprison.ipynb`  
- **🧪 IT - Mid/Small Cap:** `IT5H1TComparison.ipynb`  

---

## 🔧 Customize Your Portfolio

Want to analyze your own stocks?

```python
tickers = ['RELIANCE.NS', 'INFY.NS', 'HDFCBANK.NS']
