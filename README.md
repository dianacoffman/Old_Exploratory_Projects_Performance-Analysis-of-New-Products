## Performance analysis of new products with SQL

## Overview 📖

Conducted exploratory analysis and data cleaning to understand menu items are doing well/not well and what the top customers seem to like the best, which is very important to understand before starting marketing campaigns to increase sales. Used SQL to summarize trends; discovered that the dishes with the highest purchase potential are dishes from the Italian category. Created a report with an insights and recommendations section so that the restaurant can make better use of marketing and sales campaigns, and also boost sales in other categories.

## Table of Contents 📚

- Introduction
- Situation
- Strategy
- Business Questions
- Data collected from SQL data mining
- Insights
- Recommendations

## Introduction and Situation 📝🔎

World Cafe is a restaurant that has diverse menu offerings and serves generous portions. The Taste of the World Cafe debuted a new menu at the start of the year. After switching the menu, they don’t know which menu items are doing well or not well and what the top customers seem to like the best, which is very important to understand before starting marketing campaigns to increase sales.

## Strategy 🎯

- Exploratory Data Analysis in SQL to understand:
What is on the new menu; Get an idea of the data that’s been collected this year; Understand how customers are reacting to the new menu
- Transcribe the data so that the World Cafe owner, sales manager and marketing team understand what the data is telling them about the new menu
- Generate insights from the data
- Suggest improvements

## Business Questions ⚖️

- Which categories are the most and least popular, and how does this impact our menu and pricing strategy?
- What are the top highest spend orders, and what insights can we gain from them to enhance our pricing and promotional strategies?
- What is the average price of dishes within each category, and how does this influence customer choices and profitability?
- How many orders were made within a specific date range, and what does this tell us about customer behavior and peak periods?

## Data collected from SQL data mining 📑

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

## Insights💡

- Italian Food Category Leads Sales: The Italian food category is currently our top performer, generating the highest sales among all menu categories. This suggests strong customer preference and demand.
- Decline in Mexican Dishes: Orders for Mexican dishes are noticeably lower compared to other categories, indicating a potential shift in customer preferences or dissatisfaction.
- Order Volume Overview: We observe an average of approximately 60 sales per day over the three-month period from January 1, 2023, to March 31, 2023. This provides a baseline for our daily sales performance.
- Top and Bottom Sellers: The Hamburger, from the American category, is the most frequently ordered item with 622 orders. In contrast, the Chicken Tacos from the Mexican category are the least ordered, with only 123 orders.

## Recommendations 🛠️

- Adjust Pricing Strategy: Given that Italian dishes, which are priced between $14 and $19, are the most popular, we recommend aligning the prices of other menu categories closer to this range. Items like Edamame, currently priced at $5.00, could be priced higher to improve profit margins without significantly affecting customer demand.
- Enhance Marketing Focus: To capitalize on the strong performance of Italian dishes, we should prioritize marketing campaigns that highlight this category. Targeted promotions can drive further engagement and sales within this segment.
- Boost Sales in Underperforming Categories: Implement promotional strategies, such as special discount days for each category, to increase visibility and sales across all menu offerings. If, after six months, categories like Mexican food continue to underperform, consider evaluating the option of removing them from the menu to optimize overall profitability.
