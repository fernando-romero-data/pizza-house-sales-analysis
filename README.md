# 🍕 Pizza House Sales Analysis

## Overview
Analysis of point-of-sale (POS) data for a pizza restaurant to understand
revenue drivers, timing patterns, and ordering behavior. The project emphasizes
interpretable insights and real-world decision-making over predictive modeling.

## Key Insights
- Revenue growth is driven primarily by **order volume**, not higher spend per order.
- Demand is concentrated in **late afternoon/evening hours** and **weekends**.
- **Pickup orders dominate** across all time windows and drive peak demand.
- Order behavior is consistent enough to define **actionable order-level personas**.

## Analysis Scope
- Exploratory analysis of revenue and order trends
- Timing-based segmentation (hour, day, weekend)
- Order type interaction (pickup vs other)
- Order-level behavioral personas

## Tools
Python · pandas · matplotlib · Jupyter Notebook

> Note: Customer-level segmentation was not possible due to missing
order-to-customer linkage in the POS data.

---

## Detailed Analysis Summary

## Project Overview
This project analyzes point-of-sale (POS) data from a pizza restaurant to
understand revenue trends, ordering behavior, and demand patterns over time.
The analysis is structured as a multi-phase data science case study, with an
emphasis on interpretable insights and real-world decision-making rather than
predictive modeling.

The project covers exploratory analysis, timing-based behavior, order-type
interactions, and order-level segmentation to inform operational and marketing
strategy.

---

## Project Structure

pizza-house-sales-analysis/
├── notebooks/
│   ├── 02_order_items_exploratory_analysis.ipynb
│   └── 03_order_and_customer_segmentation.ipynb
├── data/
│   ├── raw/
│   └── cleaned/
├── README.md
└── .gitignore

Note: Raw and cleaned datasets are intentionally excluded from this repository.

---

## Analysis Phases

### Phase 2 — Exploratory Analysis
- Revenue and order volume trends
- Average order value (AOV) stability
- Order type distribution
- Peak hours and day-of-week patterns

Key takeaway:  
Revenue growth is driven primarily by order volume rather than increases in
average order value.

---

### Phase 4 — Order-Level Segmentation
The segmentation phase focuses on observable order behavior rather than
assumed customer intent.

Segments explored:
- Order value tiers (low, mid, high)
- Time-of-day and day-of-week demand
- Weekday vs weekend behavior
- Order type interaction (pickup vs other)

Key findings:
- Demand is highly concentrated during late afternoon and evening hours.
- Weekends represent a significant amplification of weekday behavior.
- Pickup orders dominate across all time windows and drive peak demand.
- Order value is continuous rather than forming distinct customer groups.

---

## Order-Level Behavioral Personas
Because the order-level dataset does not contain a reliable customer identifier,
true customer-level segmentation (e.g., RFM analysis) was not possible.

Instead, the project concludes with order-level behavioral personas that
approximate customer behavior without assuming individual tracking:

- Weekend Dinner Pickup Orders
- Weekday Core Orders
- High-Value Evening Orders
- Off-Peak Low-Value Orders

These personas provide actionable insights for staffing, promotions, and
timing-based strategies.

---

## Tools Used
- Python
- pandas
- matplotlib
- Jupyter Notebook

---

## Data Limitations
While a separate customer table exists, the orders dataset does not contain a
shared customer identifier that allows reliable linkage between orders and
customers. As a result, customer lifecycle modeling and retention analysis
were outside the scope of this project.

Future analyses would benefit from enhanced POS or loyalty system exports
that include order-level customer identifiers.

---

## Key Skills Demonstrated
- Data cleaning and validation
- Exploratory data analysis (EDA)
- Behavioral segmentation
- Time-based analysis
- Analytical storytelling
- Handling real-world data limitations

---

## Next Steps (Optional)
- Demand forecasting by hour and day
- Experiment design for off-peak promotions
- Customer segmentation using linked POS or loyalty data
