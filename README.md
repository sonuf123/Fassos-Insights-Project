### Fassos Case Study Project README

 Overview
This project focuses on analyzing data related to Fassos, a food delivery service, from the perspective of a Data Analyst. The analysis aims to provide insights into various aspects of the business, including roll metrics, driver and customer experience, ingredient optimization, pricing, and ratings.

 ## Data Sources
- Customer Orders: Contains information about customer orders, including order ID, customer ID, roll ID, order date, and additional details.
- Driver: Stores data related to drivers, including driver ID, name, and other relevant information.
- Driver Order: Includes details about orders delivered by drivers, such as order ID, driver ID, pickup time, distance, duration, and cancellation status.
- Ingredients: Contains data about ingredients used in rolls.
- Rolls: Stores information about rolls, including roll ID, name, and other attributes.
- Rolls Recipes: Provides details about the recipes of rolls, including ingredients used in each roll.

## Analysis Tasks

 A. Roll Metrics
1. How many rolls were ordered?
2. How many unique customer orders were made?
6. What was the maximum number of rolls delivered in a single order?

B. Driver and Customer Experience
3. How many successful orders were delivered by each driver?

C. Ingredient Optimization
8. How many rolls were delivered that had both exclusions and extras?

D. Pricing and Ratings
4. How many of each type of roll was delivered?
10. What was the number of orders for each day of the week?

## Data Cleaning
7. For each customer, how many delivered rolls had at least 1 change and how many had no change?

## SQL Queries
For executing the analysis tasks, the following SQL queries can be used:

Certainly! Here's how you can represent the SQL queries in a tabular format using Markdown:

| SQL Query                   |
|-----------------------------|
| `select * from CUSTOMER_ORDERS;` |
| `select * from DRIVER;`          |
| `select * from driver_order;`    |
| `select * from ingredients;`     |
| `select * from rolls;`           |
| `select * from rolls_recipes;`   |

This Markdown table will display the SQL queries in a neat and organized format.







Conclusion
By analyzing the provided datasets, insights can be gained into various aspects of Fassos' operations, which can help in making informed decisions to optimize performance and enhance customer satisfaction.


