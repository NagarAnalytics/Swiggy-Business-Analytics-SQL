# Swiggy-Business-Analytics-SQL
Analyzing consumer behavior, restaurant performance, and revenue growth for Swiggy using Advanced SQL

# Swiggy Business Intelligence Analysis (SQL)

## 📌 Project Overview
This project focuses on extracting actionable insights from Swiggy's transactional data. The analysis covers restaurant performance, customer ordering frequency, and revenue trends to help understand business growth and user retention.

## 🛠 Tools & Technologies
- **Language:** SQL (MySQL / PostgreSQL)
- **Key Concepts:** Window Functions (`LAG`, `RANK`, `DENSE_RANK`), Joins, CTEs, Aggregations, Date Manipulations.

## 📊 Key Business Questions Answered
1. **Revenue Growth:** Calculated **Month-over-Month (MoM) revenue** trends to identify peak growth periods.
2. **Customer Retention:** Identified "Loyal Customers" based on order frequency and average order value (AOV).
3. **Restaurant Performance:** Ranked restaurants by city based on total revenue and customer ratings.
4. **User Behavior:** Found the most popular food categories and the time of day with the highest order volume.
5. **Cuisine Analysis:** Analyzed which cuisines drive the highest profit margins across different regions.

## 💡 Technical Highlights (SQL Snippets)
- **MoM Revenue:** Used the `LAG()` function to compare the current month's sales against the previous month.
- **Top Customers:** Used `DENSE_RANK()` to categorize users into tiers (Gold, Silver, Bronze) based on their total spend.
- **Complex Joins:** Connected Users, Orders, Restaurants, and Menu items to create a master view of the delivery ecosystem.

## 📂 File Structure
- `Swiggy_Analysis_Queries.sql`: The complete set of SQL queries used for the analysis.
- `Swiggy_Dataset.csv`: (Optional) The raw or sample data used for the project.

## 🚀 How to Use
1. Clone this repository.
2. Run the `Swiggy_Analysis_Queries.sql` file in your preferred SQL editor (MySQL Workbench, pgAdmin, etc.).
