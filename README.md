1. Project Title

E-Commerce Data Analytics Capstone Project

2. Project Overview

This project focuses on analyzing e-commerce sales data from an Indian e-commerce website. The project uses Python, Pandas, Matplotlib, and Power BI to clean, analyze, visualize, and interpret sales data.

The analysis focuses on sales performance, profit, quantity, product categories, geographical performance, and sales trends over time. The final Power BI dashboard provides an interactive view of the analyzed data and supports data-driven business decision-making.

3. Problem Statement

The objective of this project is to analyze e-commerce sales data and identify important trends, patterns, high-performing and low-performing areas, and profitability patterns.

The analysis aims to answer questions such as:

- Which product categories generate higher sales?
- Which states contribute more to sales?
- How do sales change over time?
- Which product categories generate higher profit?
- Which areas require improvement?
- What business actions can be recommended based on the analysis?

4. Dataset Description

The dataset used for this project is the E-Commerce Data dataset containing sales information from an Indian e-commerce website.

The project uses three related datasets:

- List of Orders.csv – contains order information such as Order ID, Order Date, Customer Name, City, and State.
- Order Details.csv – contains sales transaction information such as Order ID, Amount, Profit, Quantity, Category, and Subcategory.
- Sales target.csv – contains sales target information by category and month.

The datasets were used for data preparation, exploratory analysis, visualization, and Power BI dashboard development.

5. Tools Used

The following tools and technologies were used:

- Python – data analysis and data preparation
- Pandas – data manipulation and analysis
- Matplotlib – data visualization
- Jupyter Notebook – Python analysis environment
- Power BI – interactive dashboard development
- Git – version control
- GitHub – project repository and documentation

6. Data Cleaning Process

The datasets were inspected for their columns, data types, missing values, and duplicate records.

During the cleaning process, duplicate records were checked in all three datasets. The List of Orders.csv file contained duplicate records, while the Order Details and Sales Target datasets did not contain duplicate records.

A total of 59 duplicate records were removed from the List of Orders dataset.

The cleaned dataset was then validated by checking its dimensions, missing values, and duplicate records. The cleaned List of Orders dataset was also saved separately for further analysis.

The final datasets were prepared for exploratory data analysis and visualization.

7. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the structure, distribution, relationships, and important characteristics of the data.

The analysis included:

- Descriptive statistics
- Correlation analysis
- Average sales, profit, and quantity
- Highest sales, profit, and quantity values
- Outlier detection using the IQR method
- Identification of important sales and profitability patterns
- Examination of trends and variations in the data

EDA helped identify important characteristics of the e-commerce business data and prepared the data for visualization and dashboard development.

8. Data Visualizations

Several visualizations were created to understand sales and profitability patterns.

The main visualizations included:

1. Monthly Sales Trend – shows changes in sales over time.
2. Sales by Product Category – compares sales performance across product categories.
3. Sales by State – compares sales performance across different states.
4. Top 10 Customers by Sales – identifies customers contributing higher sales.
5. Profit by Product Category – compares profitability across product categories.

These visualizations helped identify differences in sales, customer contribution, geographical performance, and profitability.

9. Power BI Dashboard

An interactive Power BI dashboard was created using the prepared e-commerce datasets.

The dashboard contains:

KPI Cards

- Sum of Amount – represents total sales.
- Sum of Profit – represents total profit.
- Sum of Quantity – represents total quantity sold.

Visualizations

- Sum of Amount by Category – Clustered Column Chart
- Sum of Amount by State – Clustered Bar Chart
- Sum of Amount by Year – Line Chart
- Sum of Profit by Category – Clustered Column Chart

Slicers

- Category Slicer – allows filtering by Clothing, Electronics, and Furniture.
- State Slicer – allows filtering by individual states.

The dashboard provides an interactive view of sales and profitability performance.

10. Key Business Insights

The analysis produced the following key business insights:

1. Sales performance differs across product categories, indicating differences in customer demand and contribution to overall sales.

2. Sales performance varies across states, showing that some geographical markets perform better than others.

3. Sales change over time, indicating periods of stronger and weaker business performance.

4. Sales and profit should be evaluated together because a category with high sales does not necessarily generate the highest profit.

5. High-performing categories and geographical markets represent potential opportunities for further business growth.

6. Low-performing categories and states may require further investigation and targeted improvement strategies.

11. Business Recommendations

Based on the analysis, the following recommendations are proposed:

1. Strengthen high-performing categories and markets: Maintain adequate inventory and continue targeted marketing activities in areas showing strong sales performance.

2. Improve low-performing areas: Investigate low-performing categories and states and consider promotional offers, better product visibility, competitive pricing, and regional marketing strategies.

3. Focus on profitability: Monitor profit along with sales and review categories with lower profitability to improve pricing, cost control, and profit margins.

4. Monitor performance regularly: Continue using Power BI dashboards and periodic data analysis to identify changes in sales and profitability and support timely decision-making.

12. Conclusion

This project demonstrates the complete data analytics workflow, from dataset selection and data cleaning to exploratory data analysis, visualization, Power BI dashboard development, and business interpretation.

The analysis provided useful information about sales trends, product categories, geographical performance, customer contribution, and profitability.

The final dashboard makes the results easier to understand and supports data-driven business decisions. The identified insights and recommendations can help the business strengthen high-performing areas, improve weaker areas, and work toward better sales and profitability.
