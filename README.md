# Home_Sales
## Assignment on Big Data

In this assignment I have used the SparkSQL to determine key metrics about home sales data.Here I have used Spark to create temporary views, partition the data, cache my temporary table in order to expedite the queries time, and finally uncached and varified if the cached temporary table is already removed or not, in order to ensure the removal of any occupied spaces by cached data in the system.

Below are the key metrics analyzed using SparkSQL:

1. **Average price for a four-bedroom house sold for each year**

   ![Average Price for Four-Bedroom Houses](Images/avg_price_bed4.png)

2. **Average price of a home for each year the home was built, with three bedrooms and three bathrooms**

   ![Average Price of Homes Built per Year with Three Bedrooms and Three Bathrooms](Images/price_bed3_bath3_datebuilt.png)

3. **Average price of a home for each year the home was built, with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet**

   ![Average Price of Homes Built per Year with Specific Criteria](Images/avg_price_datebuilt_bed3_bath3_sqgte2000.png)

4. **Average price of a home per "view" rating, with an average home price greater than or equal to $350,000**

   ![Average Price of Homes per View Rating](Images/avg_price_viewRating_price_gte350000.png)





Thank you.


Regards,

Stuti Poudel
