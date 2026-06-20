# 🛍️ Customer Shopping Behavior Analytics

An end-to-end data analytics project analyzing **retail consumer shopping behavior** using **Python, SQL, and Power BI** to uncover trends, improve customer engagement, and optimize marketing & product strategies.

---

## 🚀 Business Problem

A leading retail company wants to understand its customers' shopping behavior to improve **sales**, **customer satisfaction**, and **long-term loyalty**.

> **"How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?"**

The analysis investigates how factors like **discounts, reviews, seasons, and payment preferences** drive consumer decisions and repeat purchases.

---

## 📈 Key Metrics at a Glance

| Metric | Value |
|---|---|
| 👥 Total Customers | **3.9K** |
| 💵 Avg. Purchase Amount | **$59.76** |
| ⭐ Avg. Rating | **3.75 / 5** |
| 🔄 Subscribed Customers | **27%** |
| ❌ Non-Subscribed Customers | **73%** |

---

## 📋 Dashboard Insights

### Revenue & Sales by Category
- **Clothing** leads in both revenue (**$0.10M**) and sales volume (**3.4M units**)
- **Accessories** follow with **$0.07M** revenue and **2.4M units**
- **Footwear**: **$0.04M** revenue, **1.2M units**
- **Outerwear** lowest at **$0.02M** revenue, **0.6M units**

### Revenue & Sales by Age Group
- **Young Adults** drive the highest revenue (**$62K**) and sales (**1,028 units**)
- **Middle-aged** customers close behind at **$59K** revenue, **986 units**
- **Adult** and **Senior** segments contribute **$56K** each, with **944** and **942 units** respectively

### Subscription & Engagement
- Only **27%** of customers are subscribed, indicating a strong opportunity for loyalty program growth

---

## 🛠️ Tools & Technologies

* **Python** — Data cleaning, preprocessing, and transformation (Pandas, NumPy)
* **MySQL** — Structured data storage, business query simulation
* **Power BI** — Interactive dashboard with slicers for Gender, Category, Subscription Status, and Shipping Type
* **Jupyter Notebook** — Exploratory data analysis & SQL integration via `mysql.connector`

---

## 🔄 Project Workflow

1. **Data Preparation & Modeling (Python)** — Cleaned and transformed the raw dataset; verified zero null values across all **15 fields**
2. **Data Analysis (SQL)** — Structured data into MySQL (`customer_behavior` database), ran queries on customer segments, loyalty, and purchase drivers
3. **Visualization & Insights (Power BI)** — Built an interactive dashboard highlighting key patterns across category, age group, and subscription status
4. **Report & Presentation** — Summarized findings and actionable business recommendations
5. **GitHub Repository** — Structured repo with scripts, queries, and dashboard files

---

## 📂 Dataset Fields

`customer_id`, `age`, `gender`, `item_purchased`, `category`, `purchase_amount`, `location`, `size`, `color`, `season`, `review_rating`, `subscription_status`, `shipping_type`, `discount_applied`, `previous_purchases`, `payment_method`, `frequency_of_purchases`, `age_group`, `purchase_frequency_days`

---

## 📂 Files Included

```
📁 Customer-Behavior-Analytics/
├── 📄 data_cleaning.ipynb          # Python data prep & transformation
├── 📄 sql_queries.sql              # Business queries on customer data
├── 📄 Customer_Behavior_Dashboard.pbix   # Power BI dashboard file
├── 📄 Project_Report.pdf           # Findings & recommendations
└── 📄 README.md
```

---

## 🔍 Key Insights

* **Clothing** is the top-performing category, generating **~50%** of total category revenue
* **Young Adults** are the highest-value segment, outperforming Seniors by **~10%** in revenue
* Subscription penetration is low (**27%**), highlighting a clear opportunity to boost retention via targeted offers
* Revenue and sales trends align closely across age groups, suggesting consistent purchase behavior with minor demographic variance

---

## ⚠️ Note

Database credentials have been removed.

## 📬 Contact
Anika Sahu | Data Analyst
Feel free to ⭐ this repo if you found it useful, or raise an issue for feedback!
