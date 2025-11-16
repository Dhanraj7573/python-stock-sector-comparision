# Sector Performance Analysis with Python & Yahoo Finance

This project compares how different stock market sectors perform over a chosen period (last 12 months by default).  
It pulls daily price data for 30 U.S. stocks from Yahoo Finance, calculates returns, and visualises performance across:

- **Technology**
- **Energy**
- **Industrials**

The result is a mini “league table” of sectors and stocks, plus several charts that show risk vs return.

---

## 🔍 Project Goals

- Turn raw stock prices into **clear, interpretable insights**.
- Compare **sector-level performance** over the same time window.
- Highlight:
  - Best & worst **stocks**
  - Best & worst **days** for each stock
  - Top performers and laggards within each **sector**

This is a good example of **data-driven equity analysis** using Python.

---

## What the Script Does

1. **Define sectors and tickers**

   ```python
   SECTORS = {
       "technology":  ['NVDA','MSFT','AAPL','AVGO','ORCL','PLTR','CSCO','IBM','AMD','CRM'],
       "energy":      ['XOM','CVX','COP','WMB','MPC','EOG','KMI','PSX','SLB','VLO'],
       "industrials": ['GE','CAT','RTX','BA','ETN','HON','DE','LMT','NOC','EMR']
   }

