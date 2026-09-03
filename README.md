# 📊 Vrinda Store Data Analysis — Excel Dashboard

## 🛍️ Project Overview

This project analyzes **Vrinda Store's 2022 sales data** using Microsoft Excel to understand customer behavior, sales performance, order trends, and channel contribution.

The goal was to transform raw sales data into an **interactive dashboard** that can help the business understand its customers and identify opportunities to improve sales.

The project follows an end-to-end data analytics workflow:

**Data Cleaning → Data Processing → Data Analysis → Visualization → Insights → Business Recommendations**

---

## 🎯 Business Problem

Vrinda Store sells products online through multiple channels and wanted to analyze its 2022 sales data to better understand its existing customers and identify strategies for business growth.

The analysis focuses on questions such as:

* How do monthly sales and order volumes compare?
* Which month generated the highest sales and orders?
* Do men or women contribute more to sales?
* What is the distribution of order statuses?
* Which states generate the highest sales?
* Which customer age groups and genders contribute the most?
* Which sales channels contribute the most orders?
* What customer segment should be targeted for future growth?

---

## 🧹 Data Cleaning

Before performing the analysis, the dataset was reviewed and cleaned to improve consistency and usability.

### Key cleaning activities:

* Checked Order IDs for missing or duplicate values
* Checked Customer IDs
* Standardized gender values such as:

  * `M` → `Men`
  * `W` → `Women`
* Checked dates for consistency
* Verified order status values
* Checked product categories
* Standardized size values
* Verified numerical fields such as Quantity and Amount
* Checked city, state, and country fields for missing values

This ensured that the dataset was suitable for further analysis.

---

## ⚙️ Data Processing

Additional calculated columns were created to make the analysis more meaningful.

### Age Group

Customers were segmented into three groups:

* **Teenager**
* **Adult**
* **Senior**

An Excel `IF` formula was used to categorize customers based on age.

### Month

A separate month column was created from the order date using the `TEXT` function.

This made it easier to perform month-wise sales and order analysis.

---

## 📈 Analysis & Visualization

Pivot Tables and Pivot Charts were used to analyze the cleaned dataset.

### 1. Monthly Sales vs Orders

A combination chart was created to compare:

* Monthly sales amount
* Number of orders

A secondary axis was used so that sales and order counts could be visualized effectively despite their different scales.

### 2. Men vs Women Sales

A Pie Chart was created to compare sales contribution between men and women.

The analysis showed that **women contributed a larger share of sales**, approximately **65%**, compared with men at approximately **35%**.

### 3. Order Status Analysis

Order statuses were analyzed using a Pivot Table and Pie Chart.

The major statuses included:

* Delivered
* Cancelled
* Returned
* Refunded

The analysis showed that **Delivered** orders represented the largest portion of orders.

### 4. Top 5 States by Sales

A Top-N filter was applied to identify the states generating the highest sales.

The top five states identified were:

1. Maharashtra
2. Karnataka
3. Uttar Pradesh
4. Telangana
5. Tamil Nadu

### 5. Age Group vs Gender

Age groups were compared against gender using Pivot Tables and charts to understand which customer segments were contributing the most orders.

The analysis identified **Adult Women** as the strongest customer segment, contributing around **35% of orders**.

### 6. Sales Channel Analysis

Different sales channels were compared to understand their contribution to overall orders.

The analysis highlighted **Amazon, Flipkart and Myntra** as the major contributing channels, together accounting for approximately **80% of sales contribution**.

---

## 🎛️ Interactive Dashboard

The final dashboard uses **Pivot Charts and Slicers** to make the analysis interactive.

Available slicers include:

* 📅 Month
* 🛒 Channel
* 📦 Category

Selecting a slicer automatically updates the connected charts, allowing users to analyze specific months, channels, or categories without manually rebuilding the reports.

For example, selecting **Amazon** filters the dashboard to show Amazon-specific performance, while selecting a particular month updates the dashboard accordingly.

---

## 🔍 Key Insights

The analysis produced several actionable insights:

* 📅 **March** recorded the highest sales and order volume.
* 👩 **Women** contributed the majority of sales.
* 👩‍💼 **Adult Women** emerged as the strongest customer segment.
* 🚚 **Delivered** was the dominant order status.
* 📍 **Maharashtra, Karnataka, Uttar Pradesh, Telangana and Tamil Nadu** were the top five states by sales.
* 🛒 **Amazon** was the largest contributing sales channel, with approximately **35%** contribution.
* 🛍️ **Amazon, Flipkart and Myntra** together contributed approximately **80% of sales**.

---

## 💡 Business Recommendations

Based on the analysis, the recommended target segment is:

> **Women aged 30–49 living in Maharashtra, Karnataka and Uttar Pradesh.**

Potential strategies include:

* 🎟️ Targeted coupons and discounts
* 📢 Personalized promotional campaigns
* 🛒 Campaigns focused on Amazon and Flipkart
* 👩‍💼 Marketing campaigns specifically targeting adult women
* 📍 State-specific promotions in high-performing regions

These recommendations are intended to help Vrinda Store increase sales by focusing marketing efforts on its strongest customer segment and sales channels.

---

## 🛠️ Tools & Skills Used

**Tools:**

* Microsoft Excel

**Analytics Skills:**

* Data Cleaning
* Data Processing
* Exploratory Data Analysis
* Pivot Tables
* Pivot Charts
* Slicers
* Data Visualization
* Customer Segmentation
* Business Insights
* Data-driven Recommendations

---

## 📂 Project Files

* `Vrinda Dataset.xlsx` — Raw dataset
* `Vrinda Store Analysis.xlsx` — Cleaned data, analysis and dashboard

---

## 📌 Project Outcome

This project demonstrates how raw e-commerce sales data can be transformed into an **interactive business intelligence dashboard** using Excel.

Rather than only presenting numbers, the project focuses on converting data into **actionable business insights and recommendations**.

### End-to-end workflow:

```text
Raw Data
   ↓
Data Cleaning
   ↓
Data Processing
   ↓
Pivot Tables
   ↓
Pivot Charts
   ↓
Interactive Dashboard
   ↓
Business Insights
   ↓
Recommendations
```

---

## 👨‍💻 Skills Demonstrated

`Excel` `Data Analytics` `Data Cleaning` `Pivot Tables` `Pivot Charts` `Slicers` `Data Visualization` `Customer Segmentation` `Business Intelligence` `Business Analytics`

---

⭐ If you find this project useful, feel free to explore the files and use the approach for your own data analytics projects.
