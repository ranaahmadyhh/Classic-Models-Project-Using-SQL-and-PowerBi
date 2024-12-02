# Global Classic Collections - Sales Analysis and Prediction 📊💼

## Overview 🌍
Welcome to the **Global Classic Collections** project! This project aims to help **Global Classic Collections**, a company that offers high-end collectible products like model cars and airplanes, analyze their sales and performance data to gain valuable insights and drive business decisions. The analysis is based on data retrieved from the company's **MySQL database**.

## Business Scenario 🎯
Global Classic Collections has noticed variances in sales across different offices and product lines. The management team is particularly interested in understanding:
1. Which offices are performing the best and worst? 🏢
2. Which product lines are contributing the most to the business? 🚗✈️
3. How can they predict future sales trends based on historical data? 🔮

## Data Cleaning 🧹
To ensure the accuracy of the analysis, we performed some data cleaning steps:
- Removed duplicate entries to maintain clean and reliable data.
- Added a new column in the **orderdetails** table: `revenueEach`. This was calculated by multiplying the **quantityOrdered** and **priceEach** columns, providing a clear representation of revenue for each order line.

## Descriptive Analysis 📈
The descriptive analysis provides insights into the revenue generated across various offices:
- **Paris, France**: $648,572 (highest performing office)
- **Tokyo, Japan**: $38,099 (lowest performing office)

This discrepancy in revenue highlights the varying performance levels across regions, potentially due to factors like **market demand**, **operational efficiency**, and **local economic conditions**.
![image](https://github.com/user-attachments/assets/7137e248-ccf0-4073-9267-0590f470fc99)

## Diagnostic Analysis 🧐
We examined why certain offices underperformed compared to others:
- **Paris Office**: 5 employees, highest revenue of **$30,837.62** with the most orders and customer engagement.
- **Tokyo Office**: With only 1 office and fewer employees, performance in Tokyo was significantly lower.

It is evident that offices with more employees tend to perform better, suggesting a positive correlation between staff size and sales performance.
![image](https://github.com/user-attachments/assets/75cb9491-9357-4e3f-8608-7c0d618ae818)

## Predictive Analysis 🔮
Based on historical data, we forecasted future trends:
- **Top-performing Product Line**: **Classic Cars** 🚗
- **Revenue Prediction for Next Quarter**: $81,639

Using the average revenue growth rate from the past 4 quarters, we predicted that **Classic Cars** will continue to perform strongly, especially during peak months like **October and November**, when festive season demand drives sales.
![image](https://github.com/user-attachments/assets/5b04acd7-e67f-4e73-b3a2-9aaca3539cc0)

## Key Insights 🔑
- The **Paris office** outperforms all other locations in terms of revenue, largely due to higher employee numbers and better customer engagement.
- The **Classic Cars** product line is the top performer, with a forecasted revenue growth of $81,639 in the upcoming quarter.
- **Tokyo's performance** is much lower, which may be attributed to fewer employees and lower customer engagement.

## Technologies Used 💻
- **MySQL** for database management
- **PowerBi** for data analysis and predictions


## Conclusion 🎉
By analyzing past sales data, we have uncovered crucial insights into the performance of various offices and product lines within Global Classic Collections. Our predictive model provides valuable forecasts that can help management optimize their strategies for future success. 

---

