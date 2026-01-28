# 🍪 Power BI Cookie Sales Performance Dashboard

## 📌 Project Overview

This project presents an interactive **Power BI dashboard** built to analyze **cookie sales performance** across different product types and days of the week. The goal is to transform raw transactional data into **clear, business-relevant insights** that support decision-making around product performance, profitability, and sales timing.

This dashboard was developed as part of my **data analytics and business intelligence portfolio** to demonstrate skills in data modeling, DAX, and analytical storytelling.

---

## 🎯 Business Questions Addressed

The dashboard answers key questions such as:

* Which cookie types sell the most units?
* Which cookie types generate the highest profit and profit margin?
* How do sales, revenue, and profit vary by day of the week?
* Are high-selling products also the most profitable?

---

## 📂 Dataset Description

The dataset represents cookie sales transactions with the following key fields:

* **Cookie Type** – Category of cookie sold (e.g., Chocolate Chip, Sugar, Oatmeal Raisin)
* **Units Sold** – Quantity of cookies sold per transaction
* **Revenue** – Total sales value generated
* **Profit** – Net profit after costs
* **Date** – Transaction date
* **Customer Name** – Used for customer-level filtering

> Note: The dataset is used for analytical and portfolio demonstration purposes.

---

## 🧱 Data Modeling & Preparation

Several modeling and preparation steps were applied to ensure accurate and meaningful analysis:

1. Verified data types for numeric and date fields
2. Created calculated measures for:

   * Total Units Sold
   * Total Revenue
   * Total Profit
   * Profit Margin (%)
3. Built a weekday model using calculated columns:

   * **Day of Week Number** (for correct chronological sorting)
   * **Day of Week Name** (for readability in visuals)
4. Sorted day names by weekday number to ensure correct ordering (Monday → Sunday)

This approach follows standard BI best practices, where **categorical dimensions are modeled as columns rather than measures**.

---

## 📊 Dashboard Walkthrough

### 1️⃣ Summary Metrics

The dashboard begins with high-level **summary cards** presenting:

* Total Units Sold
* Total Revenue
* Total Profit

Cards were used instead of KPI gauges because the dataset does not include predefined business targets. This avoids misleading comparisons and ensures transparency.

---

### 2️⃣ Total Units Sold by Cookie Type

**Visual:** Clustered Bar Chart
**Purpose:** Compares sales volume across cookie categories.

**Insight:**

* Chocolate Chip cookies lead significantly in units sold.
* Other cookie types show relatively similar but lower sales volumes.

---

### 3️⃣ Profit by Cookie Type

**Visual:** Clustered Bar Chart
**Purpose:** Evaluates profitability by product category.

**Insight:**

* Chocolate Chip cookies generate the highest total profit.
* Some cookie types sell fewer units but still contribute meaningfully to profit.

---

### 4️⃣ Profit Margin by Cookie Type

**Visual:** Table
**Purpose:** Highlights efficiency and pricing effectiveness across cookie types.

**Insight:**

* Snickerdoodle shows the highest profit margin.
* High sales volume does not always imply the highest margin, emphasizing the importance of profitability analysis.

---

### 5️⃣ Units Sold by Day of the Week and Cookie Type

**Visual:** Stacked Column Chart
**Purpose:** Analyzes daily sales patterns and product contribution.

**Insight:**

* Mid-week days show higher overall sales volumes.
* Chocolate Chip cookies consistently dominate daily sales.

---

### 6️⃣ Revenue by Day of the Week and Cookie Type

**Visual:** Stacked Column Chart
**Purpose:** Examines revenue distribution across weekdays and products.

**Insight:**

* Revenue trends closely follow unit sales patterns.
* Certain days generate higher revenue despite similar unit volumes, suggesting pricing or product mix effects.

---

## 🔎 Interactivity & Filters

The dashboard includes interactive slicers that allow users to explore the data dynamically:

* **Cookie Type** – Filter analysis by specific products
* **Day of the Week** – Focus on individual weekdays or patterns

All visuals are cross-filtered to support deeper exploratory analysis.

---

## 🧠 Key Insights Summary

* Chocolate Chip cookies are the top-performing product in terms of units sold, revenue, and profit.
* Profitability varies across cookie types, highlighting opportunities for pricing or cost optimization.
* Sales and revenue tend to peak during mid-week periods.
* Profit margin analysis provides additional insight beyond volume-based metrics.

---

## 🛠 Tools & Technologies

* **Power BI Desktop** – Data modeling and visualization
* **DAX** – Measure creation and calculations
* **Data Visualization Best Practices** – Clear layouts, consistent color usage, and focused storytelling

---

## 🚀 Conclusion

This project demonstrates the ability to design a **business-focused Power BI dashboard** that balances clarity, analytical depth, and usability. It showcases practical skills in data modeling, metric design, and insight communication, making it suitable for data analyst and business intelligence roles.

---

**Author:** Rebecca Efua Guisgo
**Project Type:** Personal Portfolio Project
