# -Retail-Sales-Dashboard-using-Power-BI
An interactive business intelligence dashboard built in Power BI to analyze customer purchases, product performance, and revenue trends using a simulated retail sales dataset.

## Overview / Description:
This project showcases a dynamic Retail Sales Dashboard developed in Power BI, aimed at providing actionable insights into customer behavior, sales trends, and product performance. The dataset includes transactional data such as purchase date, customer demographics, product category, and total sales value.

The dashboard enables users—like business analysts, marketing teams, or retail managers—to:

- Monitor sales performance across different age groups, genders, and product categories.
- Compare revenue and quantity sold by product lines.
- Identify top-selling categories and peak sales months.

This project demonstrates the power of data storytelling and visualization using Power BI to support data-driven decision-making in a retail context.

## Dataset Information
The dataset used in this project simulates retail transactions and includes customer, product, and sales details. It is structured to support various types of analysis, such as customer segmentation and product performance tracking.

### Main Columns
- Transaction ID – Unique ID for each transaction.
- Date – Date of purchase.
- Customer ID – Unique identifier for each customer.
- Gender – Male or Female.
- Age – Age of the customer.

### Product Details
- Product Category – Type/category of the product sold.
- Quantity – Number of units sold in the transaction.
- Price per Unit – Selling price of a single unit.
- Total Amount – Derived column (Quantity × Price per Unit).

## Dashboard Features / Key Insights
The Power BI dashboard provides a visually compelling and interactive summary of sales performance and customer behavior. Below are the main features and insights captured:

### KPI Cards
- Total Customers – Displays the number of unique customers.
- Total Product Sales – Total quantity of products sold.
- Total Revenue – Overall revenue generated from all transactions.

### Key Visualizations
- Top Selling Product Categories – Horizontal bar chart showing products with the highest sales volume.
- Revenue by Product Category – Vertical bar chart comparing total revenue across different product types.
- Sales by Age Group – Highlights purchase behavior across customer age segments.
- Monthly Quantity Trend – Line chart showing how product demand changes month by month.
- Sales Distribution by Gender – Pie chart representing the gender-based share of sales.
- Quantity Sold (%) by Product Category – Donut chart showing contribution of each category in total quantity sold.

### Customer Insights
- Distinction between New and Repeated customers based on purchase history.
- Age group analysis to understand target demographics.

The dashboard is designed to help stakeholders quickly identify growth opportunities, customer trends, and high-performing product lines.

### Customer Segmentation Columns (Added via Power BI)
- Age Group – Binned age ranges for demographic analysis.
- First Purchase Date – The earliest purchase date for each customer.
- Customer Type – Classified as New or Repeated, based on whether the transaction date is the customer’s first purchase.
These columns were used to create DAX measures and visuals in Power BI for deeper insight and trend tracking.

## Tools & Technologies Used
This project leverages the following tools and technologies:
- Power BI Desktop – Used for building interactive visualizations and the dashboard interface.
- Power Query Editor (Transform Data) – Performed all data cleaning and transformation steps, such as:
  - Removing nulls or errors
  - Creating calculated columns (e.g., Customer Type, Age Group)
  - Formatting and standardizing data types
- DAX (Data Analysis Expressions) – Used to build calculated measures (e.g., Total Revenue, Total Quantity Sold).
- Kaggle – Source of the raw dataset, simulating real-world retail transactions.

All preprocessing, transformation, and modeling steps were completed entirely within Power BI—no external tools were used for data wrangling.

## Visualizations Included
The dashboard includes a variety of visual elements designed to present key business metrics and trends in a clear and engaging format:

### KPI Cards
- Total Customers
- Total Product Sales
- Total Revenue

### Charts and Graphs
- Bar Chart – Top Selling Product Categories by quantity.
- Column Chart – Revenue by Product Category.
- Line Chart – Monthly Quantity Trend to show seasonal patterns or growth.
- Stacked Column Chart – Sales by Age Group and Gender.
- Pie Chart – Sales Distribution by Gender.
- Donut Chart – Quantity Sold (%) by Product Category.
These visuals provide a well-rounded view of:
- Sales performance across products and time
- Customer demographics and behaviors
- Contribution of different segments to revenue and volume

# Screenshot
![Dashboard Screenshot](https://github.com/Akanksha5102/-Retail-Sales-Dashboard-using-Power-BI/blob/main/Snapshot%20of%20the%20Dashboard.png)




