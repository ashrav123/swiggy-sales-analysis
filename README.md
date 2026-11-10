# swiggy-sales-analysis
SQL-based sales analysis of Swiggy orders using MySQL

1. **Project Overview**:
   
This project focuses on analyzing Swiggy restaurant sales data using MySQL to uncover business insights related to revenue performance, restaurant performance, geographical trends, and customer ordering patterns.

The project involves data cleaning, database structuring, and SQL-based business analysis to demonstrate how relational databases and SQL can be used to solve real-world business problems.

2. **Business Objectives**

The primary objectives of this analysis are to:

a) Evaluate overall sales and revenue performance.

b) Identify top-performing cities and restaurants.

c) Analyze revenue contribution across different states.

d) Understand monthly, yearly, and weekly ordering trends.

e) Examine dish pricing and customer ratings.

f) Identify ordering patterns across different price ranges.

g) Generate insights that can support business decision-making.


3. **Tools & Technologies**

Database: MySQL

Querying Language: SQL

IDE: MySQL Workbench

4. **Database Design**

The database follows a Star Schema design, consisting of one fact table and five dimension tables.

Fact table- fact_swiggy_orders

Contains transactional information, including order details, pricing, ratings, and foreign keys connecting the dimension tables.

Dimension table:

dim_date: Date-related information

dim_location: City, state, and location details

dim_restaurant: Restaurant information

dim_category: Food category details

dim_dish: Dish information




