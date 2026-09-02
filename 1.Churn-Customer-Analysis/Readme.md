Customer Churn Analysis Dashboard - https://github.com/prem-prakash123/PowerBi_Projects/blob/main/1.Churn-Customer-Analysis/Images/Churn%20customer%20analysis%20dashboard.png

📌 Project Overview

This project involves a comprehensive Power BI dashboard designed to analyze customer churn for a subscription-based service. By examining demographic data, account information, and subscribed services, this analysis identifies key drivers of customer attrition. The project leverages robust data modeling and DAX calculations to provide actionable insights for improving customer retention.

📊 Dashboards & Visualizations

The project features two primary dashboard views:

* Customer Analysis Dashboard:** A high-level overview of key business metrics. You can see this in the file `Customer Analysis Dashboard.png`.
* Churn Customer Analysis Dashboard:** A deep dive into the specific characteristics of churned customers, including gender breakdown, service usage, and ticket generation. See `Churn customer analysis dashboard.png` for details.

#Key Insights Highlighted:

* Overall KPIs:** The business has 7,043 total customers with an overall churn rate of 26.54% (1,869 churned customers) and total revenue of $16.06M.
* Payment Method Trends: Customers paying via electronic checks exhibit the highest churn rate at 45.29%. For a detailed visual, refer to `churn by payment method.png`.
* Contract Tenure: Churn is heavily concentrated in the first year of the contract, peaking at a 48.28% churn rate in Year 0. This trend is visualized in `Year of contract.png`.
* **Internet Service Usage: Fiber optic is the most widely used internet service (43.96% of the customer base), as shown in `internet services.png`. However, it also correlates with specific churn patterns when compared to DSL or no internet service.

🗄️ Data Modeling

The data is structured relationally using a central `Customer` table linked to several fact and dimension tables via a primary key (`customerID`). The complete schema can be viewed in `Data modeling.png` and includes the following tables:

* `Customer` (Demographics like Gender, Partner, SeniorCitizen, Dependents)
* `Churn_table` (Churn status)
* `Services` (Subscribed features like Device Protection, Internet Service)
* `Subscriptions` (Contract type, Monthly Charges)
* `Support` (Admin and Tech ticket counts)

🧮 DAX Measures

Custom DAX (Data Analysis Expressions) measures were created to calculate dynamic metrics and power the dashboard visuals. As seen in `Dax.png`, some of the key calculated measures include:

* `churn_rate%`
* `total customer`
* `total revenue`
* `total_churn_customer`
* Various percentage distributions for subscribed services (e.g., `% Device Protection`, `% Tech Support`).


