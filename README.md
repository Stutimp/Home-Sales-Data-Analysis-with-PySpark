# Home_Sales
## Assignment on Big Data

In this assignment I have used the SparkSQL to determine key metrics about home sales data.Here I have used Spark to create temporary views, partition the data, cache my temporary table in order to expedite the queries time, and finally uncached and varified if the cached temporary table is already removed or not, in order to ensure the removal of any occupied spaces by cached data in the system.

Here I have answered the following questions using SparkSQl:

- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

(avg_price_bed4.png)


- What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

(price_bed3_bath3_datebuilt.png)


- What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

(avg_price_datebuilt_bed3_bath3_sqgte2000.png)


- What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.


(avg_price_viewRating_price_gte350000.png)





Thank you.


Regards,

Stuti Poudel
