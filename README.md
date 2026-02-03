# 🍕 Pizza House Sales Analysis

### Data Science Case Study • POS Analytics • Behavioral Segmentation

---

## 👋 Project Summary

This project analyzes point-of-sale (POS) data from a pizza restaurant to
understand **what drives revenue**, **when demand occurs**, and **how ordering
behavior changes across time and channels**.

The analysis emphasizes **interpretable insights** and **real-world decision
making**, using exploratory analysis and order-level segmentation rather than
predictive modeling.

---

## ❓ This Project Answers

- What is driving revenue growth: order volume or order value?
- When does demand peak by hour and day of week?
- How do weekday and weekend ordering patterns differ?
- Which order types dominate peak demand periods?
- How can order behavior be grouped into actionable personas?

---

## 🧰 Tools & Skills Demonstrated

- Python (pandas, matplotlib)
- Exploratory Data Analysis (EDA)
- Time-based analysis
- Behavioral segmentation
- Analytical storytelling
- Handling real-world data limitations

---
## 🗂️ Project Structure

```text
pizza-house-sales-analysis/
├── notebooks/
│   ├── 02_order_items_exploratory_analysis.ipynb
│   └── 03_order_and_customer_segmentation.ipynb
├── data/
│   ├── raw/
│   └── cleaned/
├── README.md
└── .gitignore

```

---

## 🔍 Analysis Overview

### Phase 2 - Exploratory Analysis
- Revenue and order volume trends
- Average order value (AOV) stability
- Order type distribution
- Peak hours and day-of-week patterns

**Key takeaway:**  
Revenue growth is driven primarily by **order volume**, not higher spend per order.

---

### Phase 4 - Order-Level Segmentation
- Order value tiers (low, mid, high)
- Time-of-day and day-of-week demand
- Weekday vs weekend behavior
- Order type interaction (pickup vs other)

**Key findings:**
- Demand is concentrated in late afternoon and evening hours.
- Weekends amplify weekday behavior rather than changing it.
- Pickup orders dominate across all time windows.
- Order value is continuous rather than forming distinct customer groups.

---

## 🧍 Order-Level Behavioral Personas

Due to the absence of a reliable order-to-customer identifier, the project
concludes with **order-level behavioral personas**:

- **Weekend Dinner Pickup Orders**
- **Weekday Core Orders**
- **High-Value Evening Orders**
- **Off-Peak Low-Value Orders**

These personas support staffing, promotions, and timing-based strategy decisions.

---

## ⚠️ Data Limitations

Customer-level segmentation (e.g., RFM analysis) was not possible due to missing
order-to-customer linkage in the POS data. This limitation is common in real-world
POS systems and is documented transparently.

---

## 🚀 Next Steps
- Demand forecasting by hour and day
- Experiment design for off-peak promotions
- Customer segmentation using linked POS or loyalty data

