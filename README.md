# 💳 Credit Card Analysis Power BI Dashboard Project

An end-to-end data analytics project leveraging **MySQL** for data extraction and querying, and **Power BI** for creating an interactive, 3-page reporting solution. This project provides real-time financial metrics, customer behavior insights, transaction trends, and Week-Over-Week (WoW) performance analysis to drive business growth and risk management.

---

<p align="center">
  <img src="https://github.com/sabbirakash/Credit-Card-Analysis-Power_BI-Dashboard-Project/blob/main/Images/Customer%20Rerport%20Dashboard.png" alt="Credit Card Customer Repport Analysis" width="100%">
</p>

<p align="center">
  <img src="https://github.com/sabbirakash/Credit-Card-Analysis-Power_BI-Dashboard-Project/blob/main/Images/Transaction%20Report%20Dashbaord.png" alt="Credit Card Transaction Analysis" width="100%">
</p>

<p align="center">
  <img src="https://github.com/sabbirakash/Credit-Card-Analysis-Power_BI-Dashboard-Project/blob/main/Images/Others%20Report.png" alt="Credit Card Analysis Report" width="100%">
</p>

---

## 📌 Table of Contents
* [Project Objectives](#-project-objectives)
* [Tech Stack & Methods](#-tech-stack--methods)
* [Dashboard Architecture & Structure](#-dashboard-architecture--structure)
* [Key Business Insights (YTD & WoW)](#-key-business-insights-ytd--wow)
* [Data Flow & Workflow](#-data-flow--workflow)
* [How to Run the Project](#-how-to-run-the-project)

---

## 🎯 Project Objectives

* **Drive Revenue Growth:** Identify trends and optimize high-performing business sectors.
* **Expand Market Reach:** Increase total transaction volume and active customer base using data-driven strategies.
* **Customer Segmentation:** Target gender-specific financial behaviors and customer profiles to maximize contributions.
* **Card Performance:** Focus on promoting high-volume card categories (Blue & Silver) to optimize market share.
* **Geographical Expansion:** Strengthen performance in top revenue-contributing states (TX, NY, CA)[cite: 2].
* **Risk Management:** Monitor and improve customer activation rates while minimizing account delinquency rates.

---

## 🛠️ Tech Stack & Methods

* **Database & Data Processing:** MySQL (data querying, aggregation, and business logic execution)
* **Visualization & Analytics:** Power BI Desktop
* **Calculations & Logic:** Advanced DAX measures (WoW calculations, custom aggregations, dynamic targets)
* **UI/UX Design:** Interactive Slicers, Custom Layouts, and Cross-Filtering Visuals

---

## 📐 Dashboard Architecture & Structure

The Power BI report consists of **3 interconnected pages**:

1. **Customer Report:**
   * Focuses on demographics including Gender, Age Group, Marital Status, Education Level, and Job Type[cite: 2].
   * Evaluates revenue, interest earned, customer income, and state-wise distribution (TX, NY, CA, FL, NJ)[cite: 2].
2. **Transaction Report:**
   * Tracks total transaction amounts, interest earned, quarterly revenue trends, and total transaction counts[cite: 1].
   * Analyzes spend patterns by expenditure type (Bills, Entertainment, Fuel, Grocery, Food, Travel) and transaction method (Swipe, Chip, Online)[cite: 1].
3. **Others / Calculation Matrix Report:**
   * Serves as the underlying analytical engine connecting the main dashboards[cite: 3].
   * Computes Week-Over-Week (WoW) metrics, activation rates (30 days), delinquency rates by job category, and state-wise revenue shares[cite: 3].

---

## 💡 Key Business Insights

### 📊 Year-To-Date (YTD) Summary
* **Overall Revenue:** $57M[cite: 1, 2]
* **Total Interest Earned:** $8M[cite: 1, 2]
* **Total Transaction Volume:** $46M across 667K transactions[cite: 1]
* **Gender Contribution:** Male customers contributed **$31M**; Female customers contributed **$26M**[cite: 2].
* **Card Category Share:** **Blue** and **Silver** cards drive **93%** of overall transaction share[cite: 1, 3] (Blue alone accounts for 83.11% of sales)[cite: 3].
* **Geographical Leaders:** **TX, NY, and CA** contribute **68%** of total overall revenue[cite: 2, 3].
* **Operational Metrics:** 
  * Overall Activation Rate: **57.46%**[cite: 3]
  * Overall Delinquency Rate: **6.06%**[cite: 3]

### 📈 Week-Over-Week (WoW) Performance (Week 53)
* **Revenue Increase:** Up by **28.8%**[cite: 3]
* **Transaction Amount & Count:** Increased by **35.0%** and **3.4%** respectively[cite: 3]
* **Active Customer Count:** Grew by **16.3%**[cite: 3]

---

## 🔄 Data Flow & Workflow

```txt
[Raw Data] ➔ [MySQL Database Queries] ➔ [Power BI Data Modeling] ➔ [DAX & KPI Engine] ➔ [Interactive Dashboards]
```
* Database Stage: Wrote SQL queries to extract, join, and structure raw transactional and customer tables according to key objectives.

* Data Modeling Stage: Integrated data into Power BI, handled missing values, created table relationships, and defined data types[cite: 3].

* DAX Engine: Implemented DAX formulas for Week-Over-Week (WoW) dynamic performance comparisons and ratio calculations[cite: 3].

* Visual Dashboard Design: Built dynamic charts, dynamic cards, slicers, and structured grid navigation for intuitive reporting[cite: 1, 2, 3].

## 📂 How to Run the Project
**Database Setup:**

Import the SQL schema and transactional datasets into your local MySQL Server.

Run the provided .sql query files to prepare aggregated views.

**Power BI Report:**

Open the .pbix file using Power BI Desktop.

Update the data source credentials to connect to your MySQL database instance if required.

**Interact:**

Navigate across the 3 pages (Customer Report, Transaction Report, and Others) using the interactive tabs and apply slicers for custom timeframes or customer demographics[cite: 1, 2, 3].

---

# 👨‍💻 Author

**Sabbir Uddin Akash**

🌐 Portfolio: [Sabbir Uddin Akash](https://sabbirakash.github.io)

💻 GitHub: [sabbirakash](https://github.com/sabbirakash)

💼 LinkedIn: [Sabbir Uddin Akash](https://www.linkedin.com/in/sabbirakash)

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

Your support motivates me to build more Data Analytics, Python, SQL, Excel, and Power BI projects.

