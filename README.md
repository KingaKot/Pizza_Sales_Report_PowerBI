# 🍕 Pizza Sales Report
This project presents an interactive Pizza Sales Report built in Power BI. The report analyzes pizza sales performance from multiple business perspectives, including overall revenue, product performance and time-based demand patterns.

The goal of this report is to help a pizza business understand:
- how overall sales are performing,
- which products generate the most revenue,
- which products have the highest and lowest demand,
- when customers are most likely to place orders,
- how revenue and order volume change over time.

## 🛠️ Tools
- **Power BI** - data visualization
- **Power Query** - data loading and transformation
- **DAX** - calculated measures and business metrics

## 📂 Dataset Description
The dataset contains pizza sales transactional data, including order dates, order times, pizza names, categories, sizes, prices, and quantities sold. The analysis is based on four tables:
- 'orders' - contains order-level information such as order ID, order date, and order time
- 'orders_details' - contains transaction-level details, including pizza IDs and quantities
- 'pizzas' - contains pizza variant information such as pizza ID, size, and price
- 'pizza_types' - contains pizza names, categories, and ingredients

## 📊 Report Structure
The Power BI report consists of four main pages:
1. Welcome Page
2. Overview
3. Product Performance
4. Time Analysis

## 🏠 Welcome Page
The report starts with a landing page that introduces the dashboard and provides navigation buttons to the analytical pages.
<img width="1323" height="741" alt="Pizza_landing_page" src="https://github.com/user-attachments/assets/ec632ba3-c4ed-4854-9e57-97d68d558e2c" />

## 📈 Overview Page
The Overview page provides a high-level summary of the pizza business performance. It is designed to give users a quick understanding of the most important business metrics before moving into more detailed analysis.
<img width="1327" height="745" alt="Pizza_overview" src="https://github.com/user-attachments/assets/3acfd5ec-c003-4c4f-9609-1f48381bbefd" />

### Key KPIs
- Avg Pizzas per Order - Average number of pizzas included in one order
- Avg Orders per Day - Average number of orders placed per day
- Total Orders - Total number of customer orders
- Total Pizzas Sold - Total number of pizzas sold
- Revenue - Total sales revenue

### Visuals Included
#### Revenue by Pizza Category
This bar chart compares total revenue across pizza categories such as Classic, Supreme, Chicken, and Veggie. It helps identify which category contributes the most to overall revenue.

#### Monthly Revenue Trend
This table shows monthly revenue together with month-over-month change and percentage change. It helps track revenue movement over time and identify stronger or weaker months.

#### Monthly Order Trend
This line chart shows how order volume changes across months. It helps identify seasonal patterns and periods of higher or lower customer activity.

### Filters
The Overview page includes slicers for:
- Category
- Day of week
These filters allow users to explore sales performance for specific pizza categories or weekdays.



