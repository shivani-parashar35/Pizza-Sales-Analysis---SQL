🍕 Pizza Sales Analysis — SQL Project

A data analytics project focused on extracting actionable business insights from a pizza restaurant's sales data using SQL. The analysis covers customer orders, revenue trends, product performance, and peak demand periods.

🎯 Objective

The objective of this project is to analyze pizza sales data using SQL to extract meaningful business insights from customer orders, sales, and revenue data. Through targeted SQL queries, the project identifies best-selling pizzas, evaluates sales performance, analyzes order trends, determines peak business hours, and uncovers revenue-driving factors.

🛠️ Tools Used

MySQL — Data querying and analysis
Microsoft Excel — Supporting data checks
Canva — Presentation design

🗄️ Database Schema

The dataset consists of four related tables:

• `orders` - `order_id` (INT), `order_date` (DATE), `order_time` (TIME) |
• `order_details` - `order_details_id` (INT), `order_id` (INT), `pizza_id` (TEXT), `quantity` (INT) |
• `pizzas` - `pizza_id` (TEXT), `pizza_type_id` (TEXT), `size` (TEXT), `price` (DOUBLE) |
• `pizza_types` - `pizza_type_id` (TEXT), `name` (TEXT), `category` (TEXT), `ingredients` (TEXT) |

🔍 Key Business Questions Answered

1. 📦 What is the total number of orders placed?
2. 💰 What is the total revenue generated from pizza sales?
3. 🏆 Which pizza is the highest priced?
4. 📏 What is the most common pizza size ordered?
5. 🍽️ What are the top 5 most ordered pizza types by quantity?
6. 🥗 What is the total quantity ordered per pizza category?
7. ⏰ How are orders distributed across hours of the day?
8. 📊 What is the category-wise distribution of pizza varieties?
9. 📅 What is the average number of pizzas ordered per day?
10. 💵 What are the top 3 pizza types by revenue (overall and per category)?
11. 📈 What percentage does each pizza category contribute to total revenue?
12. 📉 How has cumulative revenue trended over time?

💡 Key Insights

- ✅ 21,350 total orders were placed, reflecting strong customer demand.
- ✅ Total revenue generated: $817,860.05.
- ✅ The Greek Pizza ($35.95) is the highest-priced item on the menu.
- ✅ Large-sized pizzas are the clear customer favorite (18,526 orders).
- ✅ The Classic Deluxe Pizza is the best-selling type by quantity (2,453 orders).
- ✅ Classic** pizzas lead category demand (14,888 units), while Chicken pizzas — despite having the fewest varieties — drive the highest revenue.
- ✅ Order volume peaks at 12 PM (2,520 orders), confirming lunch as the busiest period.
- ✅ Average daily order volume: 138 pizzas/day, indicating stable demand.
- ✅ Cumulative revenue shows a consistent upward trend, reflecting sustained business growth.

🧠 SQL Concepts Applied

- Joins (`INNER JOIN` across multiple tables)
- Aggregate functions (`SUM`, `COUNT`, `AVG`, `ROUND`)
- Subqueries
- Common Table Expressions (CTEs)
- Window functions (`RANK()`, `SUM() OVER()`)
- Grouping and sorting for business KPIs

📌 Business Recommendations

- 📦 Prioritize inventory and staffing around Large-size and Classic/Chicken category pizzas.
- ⏱️ Optimize staffing schedules to cover the 11 AM–8 PM peak window.
- 💲 Leverage high-margin, high-revenue items (e.g., Chicken-based pizzas) in targeted promotions.
- 📊 Use daily/cumulative revenue trends for forecasting and inventory planning.

📁 Project Deliverables

- SQL query scripts with corresponding result sets
- Summary presentation (PDF) with insights and visuals
