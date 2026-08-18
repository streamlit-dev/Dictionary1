# TASK 6: Sales Trend Analysis Using SQL Aggregations

## 🎯 Objective
Analyze monthly revenue trends and identify top performing months from ONLINE_SALES dataset using SQL aggregation functions.

## 🛠️ Tools & Technologies
- **Database**: MySQL 8.0
- **Skills**: SQL, GROUP BY, SUM, ORDER BY, LIMIT, Date Functions

## 📊 Dataset
`ONLINE_SALES` table with fields: order_id, order_date, revenue, product_category

## 📈 Key Findings
- **Data Period**: January 2025 to May 2025
- **Highest Revenue Month**: May 2025 - ₹7,500.00
- **Top 3 Revenue Months**: May, March, April 2025
- **Insight**: Revenue shows upward trend with peak in May 2025

## 📸 Results
### Monthly Revenue Report
![Monthly Report](MONTHLY_RESULT.png)

### Top 3 Performing Months
![Top 3](TOP3_RESULT.png)

## 💡 SQL Queries Used
Used `GROUP BY MONTH(order_date)`, `SUM(revenue)`, and `ORDER BY DESC LIMIT 3` for analysis.

## 👩‍💻 Author
**Suman** | Python | Streamlit Developer | Data Analyst
