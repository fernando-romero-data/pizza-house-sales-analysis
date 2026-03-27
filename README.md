# 🍕 Pizza House Sales Analysis — Revenue Optimization & Operational Strategy System

## 🚀 Start Here

If you're reviewing this project:

- 👉 Start with **Workbook 12** → Strategic Recommendations & Business Impact  
- 👉 Then review **Workbook 11** → Demand Forecasting & Operations  
- 👉 Then **Workbook 8–9** → Revenue Drivers & Order Behavior  

This project is designed as a **progressive analytics system**, not a single notebook.

---

## 📊 Overview

This project analyzes point-of-sale (POS) data from a pizza restaurant to uncover:

- Revenue drivers  
- Operational bottlenecks  
- Customer order behavior  
- High-impact growth opportunities  

The goal is to answer:

> How can this business increase revenue **without increasing costs?**

---

## 🎯 What This Project Demonstrates

- End-to-end data pipeline development  
- Revenue decomposition and Pareto analysis  
- Behavioral segmentation without customer linkage  
- Demand forecasting (pandas-based)  
- Operational modeling (staffing + throughput)  
- Business strategy and decision-making  

---

## 🔧 Data Pipeline (Workbooks 1–7)

Built a structured pipeline to transform raw Clover POS exports into analysis-ready data:

- Parsing irregular POS reports  
- Identifying true headers in noisy files  
- Standardizing schema and data types  
- Resolving SKU naming inconsistencies  
- Engineering revenue metrics  
- Creating reproducible transformations  

👉 Output: Clean, reliable dataset for all downstream analysis  

---

# 🔍 Revenue Optimization (Workbook 8)

- Revenue follows a Pareto distribution  
- Small subset of SKUs drives majority of sales  
- Minimal discount pressure → strong pricing power  
- Largest opportunity in higher-size pizzas  

---

# 👥 Order Behavior & Segmentation (Workbook 9)

- Order values are right-skewed  
- ~20% of orders generate ~40% of revenue  
- Peak demand: **4pm–7pm**  
- Strong weekend uplift  

👉 Revenue is driven by **when and how customers order**

---

# ⚙️ Demand Forecasting & Operations (Workbook 11)

- Revenue is **volume-driven**, not price-driven  
- Peak hours are **capacity-constrained**  
- Kitchen = primary bottleneck  
- Cashier throughput limits intake during rush  
- Off-peak = underutilized capacity  

👉 Revenue is constrained by execution, not demand  

---

# 💰 Revenue Impact Modeling (Workbook 12)

## Baseline

- AOV: ~30.70  
- Annual Orders: ~50,000+  

---

## Key Growth Levers

### 1. AOV Expansion
- Increase revenue per order via:
  - Bundles
  - Upsells
  - Spend thresholds  

---

### 2. Peak Throughput Optimization
- Increase orders fulfilled during 4pm–7pm  
- Highest revenue-per-hour impact  

---

### 3. Off-Peak Demand Generation
- Monetize idle capacity before 4pm  
- Driven by promotions and combos  

---

# 🧠 Business Strategy Layer

## AOV Strategy

- Spend 30 → free garlic bread  
- Spend 40 → free soda  
- Bundle optimization (family + multi-pizza deals)  
- Upsells (size upgrades, add-ons)

---

## Time-Based Strategy

- Off-Peak:
  - 5–10% targeted discounts  
  - Lunch combos  

- Peak:
  - No discounts  
  - Focus on AOV + speed  

- Post-Peak:
  - Light add-on incentives  

---

## Margin Discipline

- Safe discount range: **5–10%**  
- Avoid blanket discounting  
- Use threshold-based incentives  

---

# 📈 Business Impact

- Increased revenue per order (AOV)  
- Higher revenue during peak hours  
- Improved labor efficiency  
- Better utilization of existing capacity  

---

# 🔥 Final Takeaway

> Revenue growth is not a pricing problem — it is an **operations and strategy problem**

By aligning:
- Demand patterns  
- Menu structure  
- Operational capacity  

👉 The business can unlock significant growth **without major cost increases**

---

## 📁 Repository Structure
