# monday_coffee_project
![Company Logo](https://github.com/najirh/Monday-Coffee-Expansion-Project-P8/blob/main/1.png)
# Introduction
This SQL project analyzes a coffee sales dataset for a company named ”Monday
Coffee” to derive insights about customer behavior, product performance, and
market potential across various cities. The dataset includes information about
cities, products, customers, and sales transactions. The project encompasses
exploratory data analysis (EDA) and ten analytical queries to address specific
business requirements, ranging from estimating coffee consumer populations
to identifying high-potential markets. The goal is to provide actionable insights
for business expansion and optimization strategies.
The objectives are to:
• Understand the dataset structure and relationships between tables.
• Perform EDA to inspect the data and ensure its integrity.
• Answer business questions through SQL queries, covering sales performance,
customer segmentation, and market analysis.
• Provide recommendations based on the analysis for targeting high-potential
cities.
# Table Description
The dataset consists of four tables: city, products, customers, and sales.
These tables capture information about city demographics, coffee products, customer details, and sales transactions, respectively. Below is a detailed description of each table and its columns.
# Exploratory Data Analysis (EDA)
EDA was performed to inspect the contents of each table and ensure data integrity. The following SQL queries were executed:
1. SELECT * FROM city
Purpose: View all city data, including population and estimated rent.
2. SELECT * FROM products
Purpose: Inspect the list of coffee products available.
3. SELECT * FROM customers
Purpose: Review customer data and their associated cities.
4. SELECT * FROM sales
Purpose: Examine sales transactions, including dates, products, and totals.
These queries helped confirm the relationships between tables (e.g., foreign keys)
and identify any potential data quality issues, such as missing values or inconsistent formats.
# Business Requirements
The business requirements were addressed through ten SQL queries, each designed to provide specific insights into sales performance, customer behavior,
and market potential. Below are the queries, their purposes, and the SQL code,
with corrections or notes where applicable.


## Key Questions
1. **Coffee Consumers Count**  
   How many people in each city are estimated to consume coffee, given that 25% of the population does?

2. **Total Revenue from Coffee Sales**  
   What is the total revenue generated from coffee sales across all cities in the last quarter of 2023?

3. **Sales Count for Each Product**  
   How many units of each coffee product have been sold?

4. **Average Sales Amount per City**  
   What is the average sales amount per customer in each city?

5. **City Population and Coffee Consumers**  
   Provide a list of cities along with their populations and estimated coffee consumers.

6. **Top Selling Products by City**  
   What are the top 3 selling products in each city based on sales volume?

7. **Customer Segmentation by City**  
   How many unique customers are there in each city who have purchased coffee products?

8. **Average Sale vs Rent**  
   Find each city and their average sale per customer and avg rent per customer

9. **Monthly Sales Growth**  
   Sales growth rate: Calculate the percentage growth (or decline) in sales over different time periods (monthly).

10. **Market Potential Analysis**  
    Identify top 3 city based on highest sales, return city name, total sale, total rent, total customers, estimated  coffee consumer
    

## Recommendations
After analyzing the data, the recommended top three cities for new store openings are:

**City 1: Pune**  
1. Average rent per customer is very low.  
2. Highest total revenue.  
3. Average sales per customer is also high.

**City 2: Delhi**  
1. Highest estimated coffee consumers at 7.7 million.  
2. Highest total number of customers, which is 68.  
3. Average rent per customer is 330 (still under 500).

**City 3: Jaipur**  
1. Highest number of customers, which is 69.  
2. Average rent per customer is very low at 156.  
3. Average sales per customer is better at 11.6k.
