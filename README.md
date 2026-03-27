# 🍕 Pizza House Sales Analysis — Revenue Optimization & Operational Strategy System

## 📊 Overview

This project analyzes point-of-sale (POS) data from a pizza restaurant to uncover **revenue drivers, operational constraints, and high-impact growth opportunities**.

Built as a **multi-workbook analytics system**, the project progresses from raw data ingestion → revenue modeling → executive-level strategy.

---

## 🎯 What This Project Solves

- Where is revenue actually coming from?
- What limits revenue growth (demand vs operations)?
- How can the business increase revenue without increasing costs?
- What pricing, promotion, and operational strategies drive the highest ROI?

---

## 🔧 Data Pipeline (Workbooks 1–7)

A structured pipeline transforms raw Clover POS exports into a clean, analysis-ready dataset.

Key steps:

- Parsing irregular POS exports and identifying true headers  
- Standardizing schema and data types  
- Resolving SKU inconsistencies (size-based naming)  
- Mapping categories and product hierarchy  
- Engineering revenue fields (net of discounts)  
- Creating reproducible transformations  

👉 Result: Reliable, production-grade dataset for analysis

---

# 🔍 Revenue Optimization (Workbook 8)

## 🥇 SKU Revenue Concentration

- Revenue follows a Pareto distribution  
- A small subset of SKUs drives the majority of sales  

![SKU Revenue Concentration](visuals/sku_revenue_concentration.png)

---

## 💸 Discount Behavior

- Minimal discount usage across most SKUs  
- Strong pricing power across core menu  

![Discount Distribution](visuals/discount_distribution.png)

---

## 🚀 Opportunity Identification

- Largest opportunity concentrated in higher-size pizzas  
- Indicates pricing inefficiencies and upsell potential  

![Opportunity Chart](visuals/opportunity.png)

---

# 👥 Order Behavior & Segmentation (Workbook 9)

## 📊 Order Value Distribution

- Right-skewed distribution with concentration in lower-value orders  
- High-value orders drive disproportionate revenue  

![Order Distribution](visuals/order_distribution_95pct.png)

---

## 🧠 Revenue Concentration

- ~20% of orders generate ~40% of revenue  
- Moderate concentration → opportunity to increase AOV  

![Order Pareto](visuals/pareto_revenue_concentration.png)

---

## ⏰ Demand Patterns

- Peak demand: **4pm–7pm (dinner window)**  
- Strong weekend uplift (Fri–Sun)  
- Mid/high-value orders dominate peak  

![Revenue by Hour](visuals/revenue_by_hour_segment.png)

---

# ⚙️ Demand Forecasting & Operations (Workbook 11)

## 📈 Key Findings

- Revenue is **volume-driven**, not price-driven  
- Peak hours are **capacity-constrained**  
- Kitchen throughput limits revenue during dinner hours  
- Off-peak hours show **significant idle capacity**

---

## 👷 Operational Insight

- Kitchen = primary bottleneck  
- Cashier capacity limits order intake during rush  
- Demand is predictable and time-dependent  

👉 Revenue is constrained by execution, not demand

---

# 💰 Revenue Impact Modeling (Workbook 12)

## 📊 Baseline Metrics

- Average Order Value (AOV): ~30.70  
- Annual Orders: ~50,000+

---

## 🚀 Modeled Revenue Levers

### 1. AOV Expansion
- +5% → meaningful annual lift  
- +10% → high-margin revenue growth  
- No additional labor required  

---

### 2. Peak Throughput Optimization
- Increasing orders fulfilled during 4pm–7pm  
- Highest revenue-per-hour impact  
- Directly tied to staffing and kitchen efficiency  

---

### 3. Off-Peak Demand Generation
- Monetizes idle capacity before 4pm  
- Driven by promotions and lunch combos  
- Low operational risk, scalable upside  

---

# 🧠 Business Strategy Layer

## 🎯 AOV Optimization

- Spend thresholds:
  - Spend 30 → free garlic bread  
  - Spend 40 → free soda  

- Bundles:
  - Large pizza + sides + drink  
  - Multi-pizza deals  

- Upsells:
  - Size upgrades  
  - High-margin add-ons (bread, wings, drinks)  

---

## ⏰ Time-Based Strategy

- Off-Peak:
  - 5–10% targeted discounts  
  - Lunch combos  
  - Flyer campaigns  

- Peak:
  - No discounts  
  - Focus on AOV and speed  

- Post-Peak:
  - Light add-on incentives  

---

## 📉 Margin Discipline

- Safe discount range: **5–10%**  
- Avoid blanket discounts  
- Use:
  - Threshold-based incentives  
  - Bundled pricing  

---

# 📈 Key Business Impact

- Revenue Growth:
  - Driven by AOV + throughput + demand shaping  

- Cost Efficiency:
  - Better labor alignment reduces cost per order  

- Operational Improvement:
  - Faster peak execution  
  - More predictable staffing needs  

---

# 🔥 Final Takeaway

This project demonstrates that:

> Revenue growth is not a pricing problem — it is an **operations and strategy problem**

By aligning:
- Demand patterns  
- Menu structure  
- Operational capacity  

👉 The business can unlock **significant revenue growth without major cost increases**

---

## 🛠️ Tools & Technologies

- Python (pandas, matplotlib)  
- Jupyter Notebook  
- Data cleaning & feature engineering  
- Exploratory analysis  
- Business strategy modeling  

---

## 📁 Project Structure

- `notebooks/` → full analysis pipeline  
- `visuals/` → charts used in README  
- `data/` → raw + cleaned datasets (excluded)  

---

## ⚠️ Notes

Data is not included.  
This project focuses on **methodology, analysis, and business impact**.

---

## 👤 Author

Fernando Romero
