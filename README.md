# Madhav-Ecommerce-Sales-Dashboard

📝 Overview
This project is an interactive Power BI dashboard that visualizes e-commerce sales performance across multiple dimensions such as customer demographics, product categories, and payment modes. It is built using two relational datasets joined via the Order ID column to generate comprehensive and actionable business insights.

Datasets Used
📌 Dataset 1: Customer & Order Info
Column Name	Description
Order ID	Unique ID for each transaction
Order Date	Date of order placement
CustomerName	Name of the customer
State	State of customer residence
City	City of customer residence

📌 Dataset 2: Order Details
Column Name	Description
Order ID	Matches Dataset 1 for join
Amount	Total bill amount of the order
Profit	Profit earned from the order
Quantity	Number of items in the order
Category	Product category (e.g., Clothing)
Sub-Category	More specific product classification
PaymentMode	Mode of transaction (e.g., COD, UPI)

🔍 Key Insights & Features
📌 KPI Cards:

144K: Total Amount

23K: Total Profit

1784: Total Quantity

39K: Average Order Value (AOV)

📍 Top States by Sales: Maharashtra, Madhya Pradesh, and Uttar Pradesh leading in total revenue.

👤 Customer-Wise Insights: Top buyers like Harivansh, Shiva, and Sarita contributed the most to revenue.

📦 Quantity Distribution by Category:

Clothing: 63%

Electronics: 20%

Furniture: 17%

💳 Preferred Payment Modes:

COD: 43%

Debit Card: 16%

UPI: 17%

Credit Card & EMI: 12% each

📈 Monthly Profit Loss: Breakdown of profit/loss trends across January, February, and March.

🛒 Sub-Category Profit Analysis: Highlights high-profit subcategories like Printers and Phones, and low-performing ones like Saree.

🎯 Dynamic Filters:

Quarter-wise segmentation using slicers (Qtr1, Qtr2, etc.)

State-wise filtering for regional performance insights

💡 Tools & Technologies
Power BI Desktop

Data Modeling with relationships using Order ID

DAX for calculated fields like AOV

Slicers & Filters for dynamic user interaction

Pie, Bar, and Line Charts for intuitive visual storytelling

🚀 Outcome
This dashboard enables business users to:

Monitor profit trends by time and product type

Understand customer buying patterns

Optimize sales strategy based on geography and product categories

Improve operational decisions like payment mode preference handling
