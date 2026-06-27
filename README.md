# 🛍️ Customer Behaviour Analysis

An end-to-end data analytics project that analyzes customer shopping patterns using **Python**, **SQL**, and **Power BI** — covering data cleaning, exploratory analysis, business intelligence queries, and an interactive dashboard.

---

## 📁 Project Structure

```
customer_behaviour_analysis/
│
├── customer_behaviour.ipynb         # Python: EDA & data preprocessing
├── customer_behaviour.sql           # SQL: Business intelligence queries
├── customer_behavior_dashboard.pbix # Power BI: Interactive dashboard
└── customer_shopping_behavior.csv   # Dataset
```

---

## 🎯 Objective

To understand customer purchasing patterns by analyzing demographics, spending habits, subscription behavior, discount usage, and product preferences — and visualize key insights through an interactive Power BI dashboard.

---

## 🔧 Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas | Data cleaning & EDA )
| SQL (MySQL) | Business queries & segmentation |
| Power BI | Interactive dashboard |

---

## 📊 Dataset

**File:** `customer_shopping_behavior.csv`

Contains transactional and demographic data for retail customers, including fields like:

- `customer_id`, `age`, `gender`
- `item_purchased`, `category`, `purchase_amount`
- `review_rating`, `subscription_status`
- `discount_applied`, `shipping_type`
- `previous_purchases`

---

## 🐍 Python Analysis (`customer_behaviour.ipynb`)

The Jupyter Notebook covers:

- Data loading and initial exploration
- Null value handling and data type corrections
- Age group binning and feature engineering
- Exploratory Data Analysis (EDA) :
  - Purchase distribution by gender and age group
  - Category-wise revenue trends
  - Correlation between subscription status and spending
  - Discount impact analysis

---

## 🗄️ SQL Analysis (`customer_behaviour.sql`)

10 business-focused queries answering key questions:

| # | Question |
|---|----------|
| Q1 | Total revenue by gender |
| Q2 | Discount users who still spent above average |
| Q3 | Top 5 products by average review rating |
| Q4 | Average purchase amount: Standard vs Express shipping |
| Q5 | Do subscribed customers spend more? (Avg spend + total revenue) |
| Q6 | Top 5 products with highest discount usage rate |
| Q7 | Customer segmentation: New / Returning / Loyal |
| Q8 | Top 3 most purchased products within each category |
| Q9 | Are repeat buyers more likely to subscribe? |
| Q10 | Revenue contribution by age group |

## 📈 Power BI Dashboard (`customer_behavior_dashboard.pbix`)

The dashboard provides interactive visual insights including:

- Revenue breakdown by gender and age group
- Category-wise and product-wise sales performance
- Subscription vs non-subscription spending comparison
- Discount impact on purchase behavior
- Shipping preference analysis
- Customer loyalty segmentation

---

## 📌 Key Insights

- Subscribed customers show higher average spend and total revenue compared to non-subscribers
- Certain product categories have significantly higher discount dependency
- Loyal customers (10+ previous purchases) form the largest revenue-generating segment
- Age group analysis reveals distinct purchasing patterns across demographics
