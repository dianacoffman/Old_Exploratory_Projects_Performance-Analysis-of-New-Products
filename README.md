# New product customer acceptance detection with SQL

# Overview 📖

Conducted exploratory analysis and data cleansing to understand menu items are doing well/not well and what the top customers seem to like the best, which is very important to understand before starting marketing campaigns to increase sales. Used SQL to summarize trends; discovered that the dishes with the highest purchase potential are dishes from the Italian category. Created a report with an insights and recommendations section so that the restaurant can make better use of marketing and sales campaigns, and also boost sales in other categories.

# Table of Contents 📚

- Introduction
- Situation
- Strategy
- Business Questions
- Data collected from SQL data mining
- Insights
- Suggestion for improvements

# Introduction 📝

World Cafe is a restaurant that has diverse menu offerings and serves generous portions. The Taste of the World Cafe debuted a new menu at the start of the year.

# Situation 🔎

After switching the menu, they don’t know which menu items are doing well or not well and what the top customers seem to like the best, which is very important to understand before starting marketing campaigns to increase sales.

# Strategy 🎯

- Exploratory Data Analysis in SQL to understand:
What is on the new menu; Get an idea of the data that’s been collected this year; Understand how customers are reacting to the new menu
- Transcribe the data so that the World Cafe owner, sales manager and marketing team understand what the data is telling them about the new menu
- Generate insights from the data
- Suggest improvements

# Business Questions ⚖️

- What categories do we have?
- What is the number of items on the menu?
- What are the least and most expensive?
- How many Italian dishes are on the menu? 
- What are the least and most expensive?
- How many dishes are in each category? 
- What is the average dish price within each category?
- What is the date range of the table?
- How many orders were made within this date range?
- How many items were ordered within this date range?
- Which orders had the most number of items?
- How many orders had more than 12 items?
- What were the least and most ordered items?
- What categories are the least and most ordered items?
- What were the top 5 orders that spent the most money?
- What are the insights of the highest spend order?
- What are the top 5 highest spend orders? - What are the insights of those?

# Data collected from SQL data mining 📑

1) Menu:

- Categories: Mexican, Italian, American and Asian
- Number of items on the menu = 32
- What is the least expensive? Edamame (least expensive) = $5.00
- What are the most expensive? Shrimp (most expensive) = $19.95
- How many Italian dishes are on the menu? Which Italian dishes are on the menu? 9 items = Spaghetti, Spaghetti & Meatballs, Fettuccine Alfredo, Meat Lasagna, Cheese Lasagna, Mushroom Ravioli, Shrimp Scampi, Chicken Parmesan, Eggplant Parmesan
- What are the least expensive Italian dishes? Least expensive Spaghetti = $14.50
- What are the most expensive Italian dishes? Most expensive Shrimp Scampi = $19.95
- How many dishes are in each category? Mexican (9), Italian (9), American (9) and Asian (8)
- What is the average dish price within each category? American (10.06), Mexican (11.8), Asian (13.475) and Italian (16.5)

2) Orders:

- What is the date range of the table? 2023-01-01 to 2023-03-31
- How many orders were made within this date range? 5370
- How many items were ordered within this date range? 12234 
- Which orders had the most number of items? Max/Most number of items per order is 14
- How many orders had more than 12 items? 20 orders had more than 12 items

3) Customer Behavior:

- What were the most ordered items? Most Hamburguer (622). Also, American and Asian are the most ordered
- What were the least ordered items? Least Chicken Tacos (123). Also, Mexican food looks the least ordered
- What were the top 5 orders that spent the most money?  Top 5 highest spend order ~ 192, 191, 190, 189 and 185. Also, the highest top 1 is order_id 440
- What are the insights of the highest spend order? So I can see all details of the highest top 1 order (order_id 440). Also, they ordered more Italian food (8 items)

# Insights💡

- The new menu is doing well, with the category that is generating the most sales being the Italian food category
- Mexican dishes are being ordered less by customers
- The average number of orders is around 60 sales per day over the 3-month period (2023-01-01 to 2023-03-31)
- The most ordered item is Hamburger (622) - American category
- The least ordered item is Chicken Tacos (123) - Mexican category

# Suggestion for improvements 🛠️

- Since the maximum and minimum prices for Italian food are ~$14 and ~$19, and these are the most requested by customers, it is recommended to align the prices of the other categories to this value, since foods such as Edamame (least expensive) = $5.00 could have a higher profit margin
- Since the greatest potential for purchase is in Italian dishes, it is recommended to focus investment in marketing campaigns with the Italian category highlighted
- To highlight sales in other categories, it is recommended to run promotions such as special days for each category, thus boosting sales in other categories as well. Thus, after 6 months, if sales in other categories, especially Mexican food, continue to be low, it is recommended to remove it from the menu
