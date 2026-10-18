🛒 E-Commerce Customer Churn Analysis Using MySQL

📌 Project Overview

This project focuses on cleaning, transforming, and analyzing e-commerce customer churn data using MySQL. The goal is to explore customer behavior, identify churn patterns, understand customer complaints, and generate meaningful insights from customer data using SQL queries.

The project demonstrates practical SQL skills through data preprocessing, aggregation, filtering, subqueries, and table joins.

🎯 Project Objectives

- Clean and prepare customer churn data for analysis.
- Handle missing values and identify outliers.
- Standardize inconsistent categorical values.
- Create new columns to improve data analysis.
- Analyze customer churn, complaints, payment preferences, and shopping behavior.
- Examine warehouse-to-home distance and customer activity.
- Combine customer and return data to analyze returns from churned customers who complained.

🛠️ Tools & Technologies

- Database: MySQL
- Language: SQL
- Platform: MySQL Workbench

🧹 Data Cleaning

The following data-cleaning operations were performed:

- Imputed missing numerical values using mean imputation, rounded to the nearest integer where required.
- Imputed missing values in selected columns using mode imputation.
- Identified and removed records with excessive warehouse-to-home distances according to the assignment criteria.
- Standardized preferred login device, preferred order category, and payment mode values.

🔄 Data Transformation

- Renamed columns for consistent naming.
- Created "ComplaintReceived" to classify customers as Yes or No based on complaint information.
- Created "ChurnStatus" to classify customers as Churned or Active.
- Removed the original "Churn" and "Complain" columns after creating the new categorical columns.

📊 SQL Analysis Performed

The project covers the following analytical tasks:

1. Counted active and churned customers.
2. Calculated average tenure and total cashback for churned customers.
3. Calculated the percentage of churned customers who complained.
4. Identified the city tier with the highest number of churned customers preferring Laptop & Accessory.
5. Identified the most preferred payment mode among active customers.
6. Calculated order amount hike for single customers preferring mobile phones for ordering.
7. Calculated the average number of registered devices among UPI users.
8. Identified the city tier with the highest customer count.
9. Analyzed coupon usage by gender.
10. Calculated customer counts and maximum app usage hours by preferred order category.
11. Calculated total order count for credit-card customers with the maximum satisfaction score.
12. Calculated the average satisfaction score of customers who complained.
13. Identified the most common order category among customers who used more than five coupons.
14. Ranked the top three order categories by average cashback amount.
15. Analyzed preferred payment modes using tenure and order-count conditions.
16. Categorized customers by warehouse-to-home distance and compared churn status.
17. Retrieved details of married, City Tier 1 customers whose order count exceeded the overall average.
18. Created a customer returns table, inserted eight records, and joined return records with customer data to identify churned customers who complained.

🧠 SQL Concepts Practiced

- "SELECT", "WHERE", and "ORDER BY"
- Aggregate functions: "COUNT()", "SUM()", "AVG()", and "MAX()"
- "GROUP BY" and "HAVING"
- "CASE" statements
- Subqueries
- "UPDATE", "ALTER TABLE", and "DROP"
- Missing-value handling and data standardization
- "INNER JOIN"
- Table creation and data insertion

💡 Key Learning Outcomes

- Developed practical experience in SQL-based data cleaning and transformation.
- Practiced aggregating and filtering customer data to answer business questions.
- Learned to analyze customer churn and complaint patterns.
- Applied subqueries and joins to combine customer and return information.
- Improved problem-solving skills through real-world-style analytical tasks.

👩‍💻 Author

Anju Das M

Aspiring Data Analyst

🔗 Connect With Me

- LinkedIn: "Anju Das M" (http://www.linkedin.com/in/anjudasm12)
- GitHub: "anju-das-m" (http://github.com/anju-das-m)

---

This project was completed as part of MySQL learning and practical SQL assignment work.
