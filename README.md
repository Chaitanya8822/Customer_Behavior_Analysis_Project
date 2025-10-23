# 🛍️ Customer Shopping Behavior Analysis

## 📖 Overview

This project analyzes customer shopping behavior using data from **3,900 transactions** across multiple product categories. The objective is to uncover key insights into **spending patterns, product preferences, customer segments**, and **subscription behaviors** to support data-driven business strategies.

The analysis combines **Python** for data preprocessing and EDA, **PostgreSQL** for business insights through SQL, and **Power BI** for interactive visualization.

---

## 📊 Dataset Summary

* **Rows:** 3,900
* **Columns:** 18
* **Key Features:**

  * Demographics: Age, Gender, Location, Subscription Status
  * Purchase Details: Item, Category, Purchase Amount, Season, Size, Color
  * Behavior: Discount Applied, Review Rating, Frequency, Shipping Type
* **Missing Data:** 37 values in Review Rating (imputed by median per category)

---

## 🧠 Methodology

### 🔹 Data Preparation & EDA (Python)

* Imported dataset using `pandas` and explored with `.info()` and `.describe()`
* Cleaned missing data and standardized column names
* Engineered features: `age_group`, `purchase_frequency_days`
* Ensured consistency and removed redundant columns

### 🔹 SQL Analysis (PostgreSQL)

* Connected cleaned data to PostgreSQL
* Conducted business analysis:

  * Revenue by gender and age group
  * Top-rated products
  * Discount and shipping impact
  * Customer segmentation (New, Returning, Loyal)
  * Subscription vs. non-subscription spending

### 🔹 Visualization (Power BI)

* Built an interactive dashboard displaying key KPIs
* Highlighted revenue trends, top products, and customer insights

---

## 💡 Business Insights

* Promote exclusive **subscriber benefits** to increase retention
* Implement **loyalty programs** for repeat buyers
* Optimize **discount strategies** to balance profit and engagement
* Focus **marketing campaigns** on high-revenue customer segments

---

## 🧰 Tools & Technologies

* **Programming:** Python
* **Database:** PostgreSQL
* **Visualization:** Power BI
* **Libraries:** pandas, numpy, matplotlib

---

## 📈 Results

The integrated analysis delivers actionable insights for improving business performance by identifying key revenue drivers, customer trends, and strategic opportunities.


## 🧩 Author

**Kotari Chaitanya Krishna**
📧 [chaitanyakotari8822@gmail.com]
💼 Data Science | SQL | Power BI | Python
