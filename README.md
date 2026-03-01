# Customer Purchase Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior for a retail business to uncover patterns that drive revenue, customer satisfaction, and loyalty. Using Python for data preprocessing, MySQL for querying, and Power BI for visualization, the analysis provides actionable insights to support data-driven business decisions.

The goal is to help the company understand **who buys, what they buy, and what influences repeat purchases**, enabling optimized marketing strategies and improved customer engagement.

---

## Business Problem

Retail management observed changes in purchasing behavior across demographics, product categories, and promotional usage.

**Key Question:**

> How can customer shopping data be leveraged to identify trends, improve engagement, and optimize marketing and product strategies?

---

## Dataset Summary

* **Records:** 3,900 customers
* **Features:** 18 columns
* **Key Areas:**

  * Customer demographics
  * Purchase details
  * Shopping behavior
* **Missing Data:** ~0.95% in Review Rating (handled via median imputation)

---

## Tech Stack

* **Python:** Pandas, NumPy
* **Database:** MySQL
* **ORM:** SQLAlchemy, PyMySQL
* **Visualization:** Power BI

---

## Data Preparation

Key preprocessing steps:

* ✅ Missing value treatment using **category-wise median**
* ✅ Column name standardization (SQL-friendly)
* ✅ Age group segmentation
* ✅ Purchase frequency converted to numeric days
* ✅ Removed redundant columns
* ✅ Loaded clean data into MySQL

These steps ensured high-quality, analysis-ready data.

---

## Analysis Performed

The project answers important business questions such as:

* Revenue contribution by gender
* Impact of discounts on high-value customers
* Top-rated and most-purchased products
* Spending behavior by shipping type
* Subscription program effectiveness
* Customer lifecycle segmentation
* Revenue distribution by age group

Advanced SQL techniques including **window functions and segmentation logic** were used.

---

## Power BI Dashboard

An interactive executive dashboard was built featuring:

* 🔹 KPI summary cards
* 🔹 Subscriber distribution
* 🔹 Revenue by category
* 🔹 Top 5 most purchased products
* 🔹 Revenue by subscription status
* 🔹 Revenue by age group
* 🔹 Average spend by shipping type
* 🔹 Interactive slicers for deep analysis

The dashboard enables stakeholders to perform **self-service analytics**.

---

## 📊 Key Insights

- Male customers generated the highest share of total revenue, indicating that this segment tends to spend more on average and represents a strong target for focused marketing efforts.

- Customers who subscribed to the membership program generated noticeably higher revenue than non-subscribers, showing the program is working well.

- Mid-age customers turned out to be the biggest revenue contributors, making them a priority demographic for targeted campaigns and personalized offers.

- Customers who selected Express or premium shipping showed higher average order values, suggesting an opportunity to position faster delivery options as a revenue-driving upsell.

- Several products relied heavily on discounts to generate sales, highlighting a potential risk to margins and the need for more strategic promotion planning.

- A distinct group of customers used discounts but still spent above the overall average, identifying valuable, relatively price-insensitive buyers worth nurturing.

- Repeat purchasers demonstrated a greater likelihood of subscribing, revealing a strong opportunity to convert loyal shoppers into long-term members.

- Purchase activity remained concentrated within a small number of top-performing products and categories, indicating where inventory focus and marketing investment should be prioritized.

- The overall average review rating remained healthy at approximately 3.75, reflecting generally positive customer satisfaction while still leaving room for improvement.

- Purchase patterns show many customers shop weekly or fortnightly, indicating strong potential for effective loyalty and retention programs.
  
---

## Business Recommendations

* Target high-value demographic segments
* Expand and promote subscription programs
* Optimize discount strategy to protect margins
* Prioritize inventory for top-demand products
* Use shipping behavior for upsell opportunities

---

