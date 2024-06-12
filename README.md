# Pizza Sales Analysis

This repository contains SQL queries for analyzing pizza sales data. The project answers various business questions using basic to advanced SQL queries.

## Overview
This project uses a sample dataset of pizza sales to perform comprehensive analysis and derive insights. The analysis ranges from basic queries, such as retrieving the total number of orders, to advanced queries, like calculating the percentage contribution of each pizza type to the total revenue.

## Files
- `pizzasales.sql`: Contains all the SQL queries used in the analysis.
- `pizza_sales.zip`: Sample data used for the analysis.

## Analysis Questions and SQL Queries

### Basic
1. **Retrieving Data**
   - Retrieve the total number of orders placed.
   - Identify the most common pizza size ordered.
2. **Calculations**
   - Calculate the total revenue generated from pizza sales.
   - Identify the highest-priced pizza.
3. **Aggregations**
   - List the top 5 most ordered pizza types along with their quantities.

### Intermediate
1. **Joins**
   - Join the necessary tables to find the total quantity of each pizza category ordered.
   - Join relevant tables to find the category-wise distribution of pizzas.
2. **Aggregations and Grouping**
   - Determine the distribution of orders by hour of the day.
   - Group the orders by date and calculate the average number of pizzas ordered per day.
   - Determine the top 3 most ordered pizza types based on revenue.

### Advanced
1. **Calculations and Analysis using subqueries**
   - Calculate the percentage contribution of each pizza type to total revenue.
   - Analyze the cumulative revenue generated over time.
2. **Advanced Aggregations using window function**
   - Determine the top 3 most ordered pizza types based on revenue for each pizza category.

## How to Use
1. Download the sample data from (https://github.com/Ayushi0214/pizza-sales---SQL/blob/main/pizza_sales.zip).
2. Run the queries in `pizzasales.sql` using your preferred SQL environment.

## Results and Insights
- The most popular pizza size is Large.
- The Greek Pizza is the highest-priced pizza.
- The top 5 most ordered pizza types are The Classic Deluxe Pizza, The Barbecue Chicken Pizza, The Hawaiian Pizza, The 
  Pepperoni Pizza, and The Thai Chicken Pizza.
- The highest revenue-generating pizza types are determined based on the analysis.
- Orders are most frequent during the Lunch time and evening hours.

## Acknowledgments
Credit to the original data source provided by Ayushi jain (https://github.com/Ayushi0214)

