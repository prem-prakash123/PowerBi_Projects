Ecommerce Dashboard
![images](https://github.com/prem-prakash123/PowerBi_Projects/blob/main/2.Ecommerce-Analysis/Images/Ecommerce_Sales_dashboard.png)


📌 Overview

This project features an interactive E-commerce Sales Dashboard that provides a comprehensive view of customer demographics, regional performance, and sales channel efficiency. The dashboard is designed to transform raw transactional data into actionable business intelligence using several core data analysis techniques.

🛠️ Tools & Technologies

* Power BI: Used for data ingestion, data modeling, building interactive visualizations, and exploratory data analysis.

📊 Dashboard Visual

This dashboard applies several fundamental data analysis methodologies to extract meaningful insights from the dataset:

* Demographic Segmentation: The data is partitioned by customer attributes (Age Group and Gender) to identify target audiences. The *Sales by Age Group and Gender* and *Gender wise sales* charts demonstrate how to analyze consumer behavior across different cohorts (e.g., Adults vs. Seniors, Men vs. Women).
* Time Series Analysis: The *Monthly orders vs Sales* combo chart evaluates trends over time. Plotting both the sales amount and order count chronologically helps identify seasonality, peak sales months, and the correlation between order volume and total revenue.
* Geospatial / Regional Analysis: The *Top 5 State saleswise* and *Top 5 Cities* visuals represent geographic data modeling. This technique is used to identify high-performing regional markets (like Maharashtra and Bengaluru) to optimize localized marketing and supply chain logistics.
* Multivariate Analysis: The *Top 5 Cities* chart is a dual-axis (combo) chart that plots two different variables—`Sum of Amount` (Revenue) and `Count of Order ID` (Volume)—against a single dimension (City). This allows analysts to see if higher order volumes actually translate to higher revenue.
* Categorical & Channel Analysis: The *Total Order Channel Wise* and *B2B vs B2C* charts evaluate performance across discrete categories. This helps the business determine which platforms (Amazon, Myntra, Flipkart) and business models yield the highest return.
* Interactive Slicing & Dicing: The inclusion of slicers (`Channel`, `Month`, `Category`) represents dynamic data filtering. This allows users to drill down into specific subsets of data without needing to write new queries, facilitating exploratory data analysis (EDA).

📈 Key Insights Derived

* Target Demographic: Adult women represent the largest revenue-generating segment.
* Top Channels: Amazon and Myntra are the dominant platforms for order volume.
* Regional Leaders: Maharashtra and its capital, Mumbai, alongside Bengaluru (Karnataka), drive the highest regional sales.

🚀 How to Use This Dashboard

To interact with the dashboard and explore the data locally:

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
2. Clone or download this repository to your local machine.
3. Open the `.pbix` file using Power BI Desktop.
4. Use the slicers at the bottom of the dashboard (Channel, Month, Category) to filter the data dynamically and explore specific business scenarios.
