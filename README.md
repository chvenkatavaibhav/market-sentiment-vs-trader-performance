# Market Sentiment vs Trader Performance

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance by combining the Bitcoin Fear & Greed Index with Hyperliquid historical trading data.

The goal is to identify how different market sentiment conditions influence trader profitability, trading activity, win rates, and overall behavior.

---

## Datasets Used

### 1. Bitcoin Fear & Greed Index
Columns:
- timestamp
- value
- classification
- date

### 2. Hyperliquid Historical Trader Data
Columns:
- Account
- Coin
- Execution Price
- Size Tokens
- Size USD
- Side
- Timestamp IST
- Direction
- Closed PnL
- Fee
- Trade ID
- Transaction Hash

---

## Objectives

- Analyze trader performance under different market sentiment conditions.
- Compare profitability across Fear, Greed, Neutral, Extreme Fear, and Extreme Greed periods.
- Evaluate trader win rates.
- Study BUY vs SELL trade performance.
- Examine trading volume patterns.
- Identify top-performing traders.

---

## Methodology

1. Data Cleaning and Preprocessing
2. Date Standardization
3. Dataset Merging using Date
4. Exploratory Data Analysis (EDA)
5. Sentiment-Based Performance Analysis
6. Visualization and Insight Generation

---

## Key Findings

### Trading Volume by Sentiment

| Sentiment | Volume (USD) |
|------------|------------:|
| Fear | 331.0M |
| Greed | 226.5M |
| Neutral | 127.7M |
| Extreme Greed | 84.7M |
| Extreme Fear | 39.2M |

### Insights

- Fear periods generated the highest trading activity.
- Extreme Fear showed the lowest market participation.
- Trading behavior changes significantly across sentiment conditions.
- Profitability is concentrated among a small group of traders.
- Market sentiment provides valuable signals for risk management and strategy optimization.

---

## Top Performing Traders

| Rank | Total Closed PnL |
|--------|----------------:|
| 1 | 2.14M USD |
| 2 | 1.60M USD |
| 3 | 0.94M USD |
| 4 | 0.84M USD |

These traders captured a significant share of total profits, indicating strong differences in trading performance across accounts.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Conclusion

The analysis demonstrates a measurable relationship between Bitcoin market sentiment and trader behavior. Fear periods attracted the highest trading activity, while trader performance varied across sentiment conditions. Incorporating sentiment indicators into trading strategies may improve decision-making, risk management, and market timing.

---

## Author

Chede Venkata Vaibhav
