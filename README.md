# Gold Scheme Deposit Day Analysis (Excel Project)

## 📌 Problem Statement
I invest monthly in a gold savings scheme where deposits can be made on any day between the 1st and 26th of the month.
Since gold prices fluctuate daily, this project explores whether certain days of the month tend to have lower prices,
so deposits can be timed more intelligently.

---

## 📊 Objective
To analyze historical gold price data and determine whether:
- Any specific day (1–26) consistently offers lower prices, or
- A safer deposit *window* can be identified instead of chasing exact lows.

---

## 🛠 Tools Used
- Microsoft Excel
- Pivot Tables
- Basic date-based analysis

---

## 📁 Data Source
Daily gold price data (XAU/USD) sourced from public market data.
Retail gold prices vary by city, but daily price movements are driven by the same global market.
This project focuses on **pattern analysis**, not exact price prediction.

---

## 📈 Methodology
1. Imported daily gold price data
2. Extracted day-of-month and month information
3. Filtered data to deposit window (1–26)
4. Used Pivot Tables to calculate average price per day
5. Checked whether low-price days were clustered or scattered

---

## 🔍 Key Findings
- No single day between 1 and 26 consistently shows the lowest gold price
- Low-price days are scattered across the month
- This suggests that timing advantage is weak and unreliable

---

## ✅ Recommendation
Instead of trying to predict the lowest day:
- Use a **risk-minimization strategy**
- Deposit consistently in the **early or mid part of the month**
- Avoid overfitting decisions based on short-term price movements

---

## ⚠️ Limitations
- Analysis is based on a limited historical window
- Retail gold prices include local adjustments not modeled here
- This is a decision-support analysis, not a forecasting model

---

## 📎 Files
- `Gold_Deposit_Day_Analysis.xlsx` – Excel analysis file

---

## 🧠 Learning Outcome
This project demonstrates:
- Real-world data analysis thinking
- Honest interpretation of results
- Using Excel to support decisions under uncertainty
