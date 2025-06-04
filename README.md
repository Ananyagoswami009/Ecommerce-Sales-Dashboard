#  Ecommerce Sales Dashboard Analysis

## Overview

The **Ecommerce Sales Dashboard** provides a powerful visualization of e-commerce sales data, aimed at analyzing key metrics such as total sales, quantity sold, profit margins, payment methods, and more. This dashboard enables users to gain valuable insights into the performance of products across different regions, categories, and timespans. By utilizing Power BI, this dashboard makes it easier for decision-makers to optimize business strategies and improve operational efficiency.

## Features

- **Sales Overview**: Displays the total sum of the sales amount, quantity sold, and profit along with Average Order Value (AOV).
- **State-wise Sales Distribution**: Analyzes sales amounts by state, helping businesses understand regional demand.
- **Category Breakdown**: Shows the quantity sold across product categories (e.g., clothing, electronics, furniture).
- **Payment Mode Analysis**: Breaks down sales by payment modes such as EMI, Credit Card, Debit Card, UPI, and COD.
- **Profit Over Time**: Displays monthly profit trends for the entire year.
- **Sub-Category Profit Distribution**: Analyzes profit across sub-categories (e.g., Saree, Bookcases, Printers).

## Dataset

### Dataset Overview

The dataset used for this dashboard contains detailed transaction data from an e-commerce platform. It includes the following variables:

- **Transaction Date**: The date the transaction was made.
- **State**: The state from which the order was placed.
- **Customer Name**: The name of the customer who made the purchase.
- **Product Category**: The category of the product purchased (e.g., Clothing, Electronics, Furniture).
- **Payment Mode**: The mode of payment used for the transaction (e.g., COD, UPI, Credit Card).
- **Transaction Amount**: The total amount spent on the transaction.
- **Quantity Sold**: The number of items purchased in the transaction.
- **Profit**: The profit generated from the transaction.

### Files in the Repository

1. **`Dataset/Order.csv`**: This file contains the raw transaction data that powers the analysis. The data is structured with columns for transaction date, customer name, state, category, payment method, amount, quantity sold, and profit.

2. **`EcommerceSalesDashboard.pbix`**: The Power BI file that contains the dashboard. This file is used to visualize the data, apply filters, and interact with the underlying sales data.

## Key Insights from the Dashboard

1. **Sales by State**:
   - **Kerala** leads in sales, followed by **Goa** and **Tamil Nadu**. This insight helps understand regional demand for products.
   
2. **Product Category Distribution**:
   - **Clothing** is the top-selling category, accounting for 63% of the sales volume, followed by **Electronics** (21%) and **Furniture** (16%).

3. **Payment Mode Distribution**:
   - **COD** (Cash on Delivery) remains the most popular payment method, followed by **UPI**, **Credit Card**, and **Debit Card**.
   
4. **Profit by Month**:
   - The dashboard highlights significant profit fluctuations across months, with **February** showing a dip while **March**, **June**, and **December** stand out as the top-performing months.

5. **Sub-Category Performance**:
   - **Sarees** is the leading sub-category in terms of profit, outperforming other product types such as **Bookcases**, **Printers**, and **Accessories**.

## Technologies Used

- **Power BI**: Used to create the interactive dashboard.
- **DAX (Data Analysis Expressions)**: Utilized for creating calculated columns and measures.
- **Power Query**: Used for data preprocessing, transforming, and cleaning.
  
## How to Use the Dashboard

1. **Prerequisites**:
   - Install [Power BI Desktop](https://powerbi.microsoft.com/en-us/downloads/) to open the `.pbix` file.
   
2. **Getting Started**:
   - Open the `EcommerceSalesDashboard.pbix` file in Power BI Desktop.
   - Explore the dashboard by using the **filters** at the top to segment data by **quarter** or **state**.
   
3. **Interactive Features**:
   - The dashboard provides several interactive features such as:
     - **Data Filters**: Filter by specific states or quarters.
     - **Bar Charts/Graphs**: Click on the segments of charts to filter the entire dashboard based on specific categories, payment methods, or time periods.

4. **Navigating the Dashboard**:
   - You can click on **months**, **categories**, or **payment modes** in the visuals to dynamically update the data presented in the dashboard. This allows for more granular insights.

## File Details

### **Files in the Repository**

1. **`Dataset/Order.csv`**: 
   - This CSV file contains transactional data used for analysis. It includes the following columns:
     - **TransactionID**
     - **TransactionDate**
     - **State**
     - **CustomerName**
     - **ProductCategory**
     - **PaymentMode**
     - **TransactionAmount**
     - **QuantitySold**
     - **Profit**
   
2. **`EcommerceSalesDashboard.pbix`**: 
   - This Power BI file contains the entire dashboard, built with the provided dataset. It incorporates various visual elements and DAX measures for insights into sales performance.

## Instructions for Using the Dataset and Dashboard

1. **Loading the Dataset**:
   - Open **Power BI Desktop**.
   - Navigate to **Get Data** → **CSV** → **Load** the `Order.csv` file.
   - Ensure the data is correctly parsed with appropriate columns.

2. **Exploring the Dashboard**:
   - Open the `EcommerceSalesDashboard.pbix` file and explore all the tabs and visuals.
   - Use the provided filters to explore different timeframes (quarters) and states.
   
## License

This project is licensed under the MIT License.

## Conclusion

This project provides a comprehensive Power BI dashboard for analyzing e-commerce sales data. The insights derived from the dashboard can help in making informed decisions for improving sales strategies, targeting specific regions, and understanding consumer behavior. The interactive elements of the dashboard make it an excellent tool for both business analysis and strategic decision-making.

---
