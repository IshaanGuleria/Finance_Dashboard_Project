# 💼 Finance Dashboard | Power BI

A professional-grade interactive dashboard built using **Power BI** to track and analyze monthly income, expenses, and savings across multiple years. This dashboard helps users gain insights into their spending habits and financial growth with intuitive KPIs, time-based analysis, and category-level breakdowns.

---

## 📊 Project Overview

This Power BI dashboard provides a comprehensive view of financial performance across years (2021–2024). It features visual analytics on:

- Monthly income and expense patterns
- Savings vs. expenditure insights
- Category-level breakdown of spendings and savings
- Yearly and monthly growth tracking
- Drill-down into components like EMIs, groceries, rent, liquid cash, mutual funds, etc.

---

## 🛠️ Tech Stack

| Tool        | Purpose                          |
|-------------|----------------------------------|
| Power BI    | Data modeling, DAX, visualization|
| DAX         | Measures, KPIs, and dynamic filters |
| MS Excel    | Raw data storage and transformation |

---

📈 Key Features
1. 📅 Date-Slicer Navigation
Dynamic filters for year and month selection.

Enables focused financial analysis across timeframes.

2. 🔑 KPI Cards with Growth Tracking
Interactive cards for Income, Expense %, Savings, Savings %

Each card shows monthly growth via DAX and icons

Conditional formatting for alerts and highlights

3. 📉 Trend Analysis
Area chart for Expenses over Time

Visualizes monthly fluctuations in spending behavior

Provides insights into seasonal peaks and dips

4. 🧁 Donut Charts
Spending and Savings breakdown by components (e.g., House Rent, EMIs, Mutual Funds)

Quickly identifies top contributing categories to expense or savings

5. 💬 Custom Tooltips for Deep-Dive Analysis
Added dynamic tooltips to show additional context when hovering over visuals:

🧮 Net Worth Trend over time

💸 EMI and Groceries Contribution

📊 Total Income vs. Total Expense

💼 Category-wise drill-down of Savings

Tooltips enhance interactivity and reduce dashboard clutter

6. 🧾 Tabular View with Year-Wise Summary
Detailed matrix showing yearly breakdown:

Income sources (Freelance, Salary)

Expense categories

Savings types (Liquid Cash, FD, Mutual Funds, Emergency Fund)

Total and sub-totals for financial planning

---

## 🧠 DAX Measures Used

- `Total Income`
- `Total Expenses`
- `Total Savings`
- `Savings % = DIVIDE([Savings], [Income])`
- `Monthly Growth % = (Current Month - Previous Month) / Previous Month`
- Conditional formatting logic using `IF`, `SWITCH` for KPI indicators etc..

---

## 🧩 Challenges Faced

### 🧱 1. Dynamic Date Context
**Issue:** Syncing slicers across visuals to reflect the correct time period.  
**Solution:** Used `CALCULATE` and `DATESINPERIOD` to bind visuals dynamically with year/month slicers.

### 🎯 2. Performance Optimization
**Issue:** Dashboard lag with complex measures and multiple visuals.  
**Solution:** Removed redundant visuals, optimized DAX measures using `VAR`, and disabled unnecessary interactions.

### 📦 3. UX Consistency
**Issue:** Aligning color scheme and icon usage across cards and charts.  
**Solution:** Applied a consistent color theme and iconography to maintain a clean UI.

---

## 📎 Usage Instructions

1. Download the `.pbix` file or clone this repository.
2. Replace the data source path (Excel/CSV) if needed.
3. Open in **Power BI Desktop**.
4. Explore, filter, and interact with the dashboard.
5. Optionally publish to Power BI Service for sharing.

---



## 🌟 About Me
Hi there! I'm **Ishaan Guleria** — An IT professional passionate about learning, building, and delivering impactful solutions that drive real-world results.


Let's stay in touch! Feel free to connect with me on the following platforms:
[Connect with me on LinkedIn](https://www.linkedin.com/in/ishaan-guleria-865858200/)
