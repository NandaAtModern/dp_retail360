# Readme #

### Overview ###
The User Purchase Behaviour Data Product aggregates sales data across various regions to provide insights into sales trends, performance metrics, and customer behaviors. It includes data on sales volumes, revenue, and product performance.

### What is this repository for? ###

* Comprehensive sales data aggregated by region and product.
* Real-time updates and historical data analysis.
* Customizable metrics

### Usage ###

* Pre-requisite: PostgreSQL version 12 or higher & a PostgreSQL client such as psql or DBeaver.
* Run queries to analyze sales performance
'''SELECT region, SUM(quantity_sold) AS total_sales
FROM Sales
GROUP BY region'''


### Who do I talk to? ###

* Repo owner or admin
