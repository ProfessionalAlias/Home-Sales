
# Home Sales Analysis README
Instructions
File Renaming:

Rename the Home_Sales_starter_code.ipynb file to Home_Sales.ipynb.
Importing Necessary PySpark SQL Functions:

Import the required PySpark SQL functions for this assignment.
Reading Data into Spark DataFrame:

Read the home_sales_revised.csv data provided in the starter code into a Spark DataFrame.
Creating Temporary Table:

Create a temporary table named home_sales.
SparkSQL Queries:
Answer the following questions using SparkSQL:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
What is the "view" rating for homes costing more than or equal to $350,000? Determine the runtime for this query, and round off your answer to two decimal places.
Caching:

Cache the temporary table home_sales.
Check if the temporary table is cached.
Filtered Query on Cached Data:

Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
Partitioning and Parquet Data:

Partition the formatted parquet home sales data by the "date_built" field.
Create a temporary table for the parquet data.
Filtered Query on Parquet Data:

Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
Uncaching Temporary Table:

Uncache the home_sales temporary table.
Verify that the temporary table is uncached using PySpark.
GitHub Repository Upload:
Download your Home_Sales.ipynb file and upload it to your "Home_Sales" GitHub repository.
