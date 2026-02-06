
<p align="center">
  <a href="https://www.kaggle.com/code/hassanjameelahmed/microsoft-stock-forecast-2021-2026" target="_blank">
    <img src="GoldPulse.png" alt="Hassan Jameel" width="500">
  </a>
</p>

# 📈 Microsoft (MSFT) Stock Price Analysis & Forecasting 2021-2026

> **A Comprehensive Exploratory Data Analysis of Microsoft Corporation Stock Performance**

[![Dataset](https://img.shields.io/badge/Dataset-MSFT%20Stock-blue)](.)
[![Python](https://img.shields.io/badge/Python-3.8+-green)](.)
[![License](https://img.shields.io/badge/License-MIT-yellow)](.)

---

## 🎯 Project Overview

This project provides a comprehensive **Exploratory Data Analysis (EDA)** of Microsoft Corporation (NASDAQ: MSFT) stock price data spanning **5 years** from February 2021 to February 2026. The analysis covers daily trading patterns, price trends, volatility analysis, and actionable insights for investors and data enthusiasts.

### 🔑 Keywords

`Microsoft Stock`, `MSFT Analysis`, `Stock Market EDA`, `Financial Data Analysis`, `Time Series Analysis`, `Stock Price Prediction`, `Trading Volume Analysis`, `Investment Analytics`, `Tech Stock Performance`, `S&P 500`

---

## 📊 Dataset Information

### Coverage & Scope

| Attribute        | Details                             |
| ---------------- | ----------------------------------- |
| **Company**      | Microsoft Corporation (MSFT)        |
| **Exchange**     | NASDAQ                              |
| **Time Period**  | February 4, 2021 - February 2, 2026 |
| **Trading Days** | 1,255 records                       |
| **Features**     | 12 columns                          |
| **File Format**  | CSV                                 |
| **File Size**    | ~179 KB                             |

### Data Provenance

- **Source**: Historical stock market data (cleaned and preprocessed)
- **Collection Method**: Daily OHLCV (Open, High, Low, Close, Volume) data
- **Quality**: Cleaned dataset with adjusted prices and calculated features

---

## 📋 Column Details

| #   | Column Name        | Data Type | Description                                 | Example Value |
| --- | ------------------ | --------- | ------------------------------------------- | ------------- |
| 1   | `date`             | datetime  | Trading date in YYYY-MM-DD format           | 2021-02-04    |
| 2   | `open`             | float64   | Opening price at market open                | 232.84        |
| 3   | `high`             | float64   | Highest price during trading day            | 233.40        |
| 4   | `low`              | float64   | Lowest price during trading day             | 230.64        |
| 5   | `close`            | float64   | Adjusted closing price                      | 232.22        |
| 6   | `volume`           | int64     | Number of shares traded                     | 25,296,100    |
| 7   | `price_change`     | float64   | Daily price change (Close - Previous Close) | 0.18          |
| 8   | `price_change_pct` | float64   | Percentage change from previous day         | 0.078%        |
| 9   | `day_of_week`      | int64     | Day of week (0=Monday, 4=Friday)            | 3 (Thursday)  |
| 10  | `month`            | int64     | Month number (1-12)                         | 2 (February)  |
| 11  | `year`             | int64     | Trading year                                | 2021          |
| 12  | `quarter`          | int64     | Fiscal quarter (1-4)                        | 1             |

---

## 📈 Key Statistics Summary

### Price Range (2021-2026)

| Metric             | Value            |
| ------------------ | ---------------- |
| **Starting Price** | ~$232 (Feb 2021) |
| **Peak Price**     | ~$483 (Jan 2026) |
| **Ending Price**   | ~$425 (Feb 2026) |
| **5-Year Growth**  | ~83%             |

### Volume Statistics

- **Average Daily Volume**: ~25 million shares
- **Highest Volume Day**: 128+ million shares (Jan 29, 2026)

---

## 🏷️ Kaggle Tags

`finance`, `stock-market`, `exploratory-data-analysis`, `time-series`, `microsoft`, `nasdaq`, `investment`, `trading`, `visualization`, `python`, `pandas`, `seaborn`, `plotly`

---

## 🚀 Use Cases

1. **Investment Research**: Analyze historical performance for investment decisions
2. **Technical Analysis**: Study price patterns and trading signals
3. **Volatility Analysis**: Assess risk through price fluctuation analysis
4. **Machine Learning**: Training data for stock price prediction models
5. **Academic Research**: Financial market behavior studies

---

## 📁 Project Files

| File                      | Description                            |
| ------------------------- | -------------------------------------- |
| `MSFT_5years_cleaned.csv` | Main dataset file                      |
| `app.md`                  | Project documentation (this file)      |
| `New_App.ipynb`           | Jupyter notebook with EDA and analysis |

---

## 📄 License

This project is for educational and research purposes. Stock data is publicly available historical information.

---

_Created with ❤️ for Data Science & Financial Analysis_
