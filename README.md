# SPY 15-Year Investment Horizon Analysis

This project analyzes the impact of market timing on long-term investment returns. Using historical data for the **SPY ETF (S&P 500)**, we simulate a **$1,000,000** initial investment across four distinct 15-year holding periods to observe how "Start Date" affects final wealth accumulation.

## 📊 Project Overview

The script pulls adjusted close prices (accounting for dividends) via the `yfinance` API and calculates:
* Total Return Multiplier
* Compound Annual Growth Rate (CAGR)
* Final Investment Value
* Comparison between different market cycle entry points (e.g., Dot-com peak vs. Financial Crisis).

## 📈 Key Findings

The analysis reveals a massive disparity in returns based solely on the year investment began, despite the identical 15-year holding duration.

| Start Date | End Date | Final Value | Total Return | CAGR |
| :--- | :--- | :--- | :--- | :--- |
| **Jan 1, 1995** | Dec 31, 2009 | $3,057,429 | 3.06x | 7.74% |
| **Jan 1, 2000** | Dec 31, 2014 | $1,941,406 | 1.94x | 4.52% |
| **Jan 1, 2005** | Dec 31, 2019 | $3,679,661 | 3.68x | 9.07% |
| **Jan 1, 2008** | Dec 30, 2022 | **$3,737,275** | **3.74x** | **9.19%** |

### Performance Comparison
* **🏆 Best Performer:** Jan 1, 2008 (The "Crisis" Cohort)
* **📉 Worst Performer:** Jan 1, 2000 (The "Dot-Com Peak" Cohort)
* **The Gap:** There is a **$1,795,868 difference** between the best and worst start dates. The 2008 investor ended up with **92.5% more money** than the 2000 investor.

## 🧠 Insights & Conclusions

### 1. High Valuations are the Biggest Risk
The 2000 cohort performed the worst not because of the crashes they endured, but because they paid a premium price to enter the market. Buying at historic P/E highs limited their long-term upside.

### 2. Crisis Can Be Opportunity
The investor who started in **2008**—right before the Great Financial Crisis—ended up winning.
* **Why?** Although they faced an immediate -37% crash, they stayed invested. Dividends were reinvested at market lows, and they captured the entirety of the 2009–2021 bull run.
* **Lesson:** *When* you are in the market matters less than *staying* in the market during recoveries.

### 3. 15 Years Reduces, But Doesn't Eliminate, Risk
Even the worst performer (2000) nearly doubled their money (1.94x) and beat inflation. However, the sequence of returns created a massive wealth gap compared to other periods.

---
