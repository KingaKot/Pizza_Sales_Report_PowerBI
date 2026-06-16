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
#### **Revenue by Pizza Category**
This bar chart compares total revenue across pizza categories such as Classic, Supreme, Chicken, and Veggie. It helps identify which category contributes the most to overall revenue.

#### **Monthly Revenue Trend**
This table shows monthly revenue together with month-over-month change and percentage change. It helps track revenue movement over time and identify stronger or weaker months.

#### **Monthly Order Trend**
This line chart shows how order volume changes across months. It helps identify seasonal patterns and periods of higher or lower customer activity.

### Filters
The Overview page includes slicers for:
- Category
- Day of week
These filters allow users to explore sales performance for specific pizza categories or weekdays.

## 🍕 Product Performance Page

The Product Performance page focuses on product-level analysis. This page helps understand which pizzas perform best, which products generate the most revenue, and how price relates to demand.

<img width="1327" height="742" alt="pizza_product_performance" src="https://github.com/user-attachments/assets/556c9989-5b42-4f25-8938-83239471ffa2" />

### Key KPIs
- Unique Pizza Recipes - Number of unique pizza recipes available
- Available Pizza Sizes - Number and list of available pizza sizes
- Best Selling Product - Product with the highest quantity sold
- Least Selling Product - Product with the lowest quantity sold

### Visuals Included
#### **5 Highest Revenue Products**
This horizontal bar chart shows the five products that generated the highest revenue. It helps identify the strongest revenue contributors.

#### **5 Lowest Revenue Products**
This chart shows the five products with the lowest revenue contribution. It helps identify products that may need further business review, promotion, or menu optimization.

#### **Price vs Product Demand**
This scatter chart compares product price with the number of pizzas sold. It helps analyze whether higher-priced products have lower demand and whether some products perform well despite a higher price. The chart uses category colors to distinguish pizza groups.

## ⏰ Time Analysis Page
The Time Analysis page focuses on customer ordering patterns over time. It helps identify peak demand periods, busiest weekdays, and monthly order trends.

<img width="1327" height="743" alt="pizza_time_analysis" src="https://github.com/user-attachments/assets/872d7126-4f21-4df9-b5bc-69aabf4a01cf" />

### Key KPIs
- Peak Order Hour - Hour with the highest number of orders
- Highest Revenue Month - Month with the highest revenue
- Lowest Revenue Month - Month with the lowest revenue
- Busiest Day of Week - Weekday with the highest order volume
- Slowest Day of Week - Weekday with the lowest order volume

### Visuals Included
#### Peak Hours
This bar chart groups orders into time slots and shows when customers are most likely to order. It helps identify peak ordering periods during the day.

#### Demand Heatmap by Day and Hour
This heatmap shows demand intensity by weekday and hour. It provides a detailed view of customer behavior and helps identify the strongest combinations of day and time.

#### Orders by Day of Week
This chart compares order volume across weekdays. It helps identify the busiest and slowest days of the week.

#### Monthly Order Trend
This line chart shows how order volume changes month by month. It helps detect seasonality and changes in customer demand across the year.

## 🔎 Key Insights
Based on the analysis, the following insights were identified:
- The business generated approximately 818K € in revenue.
- A total of around 21K orders were placed.
- Around 50K pizzas were sold.
- Customers ordered an average of 2 pizzas per order.
- The highest revenue month was July.
- The lowest revenue month was October.
- The busiest day of the week was Friday.
- The slowest day of the week was Sunday.
- The peak order hour was 12:00.
- The best-selling product was The Classic Deluxe Pizza.
- The least-selling product was The Brie Carre Pizza.
- Classic and Supreme pizzas were among the strongest revenue-generating categories.
- Demand is strongest around lunch and evening time periods.





