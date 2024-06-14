I used the information I learned in class from Module 22 and practice with the class example exercises to complete this assignment.

## Home Sales
### Module 22 Challenge

### Instructions

1. Rename the <code>Home_Sales_starter_code.ipynb</code> file as <code>Home_Sales.ipynb</code>.
2. Import the necessary PySpark SQL functions for this assignment.
3. Read the <code>home_sales_revised.csv</code> data in the starter code into a Spark DataFrame.
4. Create a temporary table called <code>home_sales</code>.
5. Answer the following questions using SparkSQL:
    - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    - What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    - What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to            2,000 square feet? Round off your answer to two decimal places.
    - What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

6. Cache your table <code>home_sales</code>.
7. Check if your temporary table is cached.
8. Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
9. Partition by the "date_built" field on the formatted parquet home sales data.
10. Create a temporary table for the parquet data.
11. Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
12. Uncache the <code>home_sales</code> temporary table.
13. Verify that the <code>home_sales</code> temporary table is uncached using PySpark.
14. Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.
