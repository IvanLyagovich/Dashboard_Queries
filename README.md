## README for the SQL File

This SQL file contains a series of queries performed on the "orders" table and various joins with other tables. These queries aim to retrieve and calculate different statistics and insights from the data. Here is a brief overview of each section:

1. **Count the total number of orders in the table:**
   - Retrieves the count of order_id column from the "orders" table.

2. **Calculate the total sum of prices for all orders:**
   - Calculates the sum of the price column from the "orders" table.

3. **Calculate the average price across all orders:**
   - Calculates the average price from the price column in the "orders" table.

4. **Calculate the total quantity of items across all orders:**
   - Calculates the sum of the quantity column in the "orders" table.

5. **Calculate the percentage of orders that have more than one item:**
   - Calculates the percentage of orders where the quantity is greater than 1.

6. **Calculate the sum of orders per year:**
   - Retrieves the year from the sale_date column and calculates the sum of prices for each year.

7. **Calculate the number of orders per month:**
   - Retrieves the year and month from the sale_date column and counts the number of orders for each month.

8. **Find the most popular items based on order count:**
   - Retrieves the item_name column and counts the number of orders for each item, ordering them by the order count in descending order.

9. **Join the orders and customers tables on order_id and transaction_id:**
   - Performs an inner join between the "orders" and "customers" tables based on the order_id and transaction_id columns.

10. **Calculate the total purchases for each listing:**
    - Calculates the total purchase amount by multiplying the price and quantity columns for each listing.

11. **Get the top 10 listings by total purchase and calculate the average total purchase:**
    - Retrieves the top 10 listings with the highest total purchase amount and calculates the average total purchase.

12. **Investigate the relationship between listing start date and total sales per listing:**
    - Joins the "orders" and "listings" tables based on the listing_id column and calculates the total purchase amount for each listing, including the listing start date.

13. **Investigate the total sales per box_id:**
    - Joins the "orders" and "listings" tables based on the listing_id column and calculates the total purchase amount for each box_id.

14. **Compute the overall average sales across all box_ids:**
    - Calculates the average total purchase amount across all box_ids.

15. **Finding average review score:**
    - Calculates the average star_rating from the "reviews" table.

16. **Calculate the average star rating by year:**
    - Retrieves the year from the date_reviewed column and calculates the average star rating for each year.

17. **Compare average total purchase for orders with and without coupon codes:**
    - Calculates the average order total for orders with and without coupon codes.

18. **Identify repeat customers:**
    - Retrieves the reviewer column and counts the number of orders for each reviewer, identifying repeat customers.

19. **Calculate average delivery time:**
    - Calculates the average delivery time by subtracting the date_paid from the date_shipped.

20. **Calculate revenue by city:**
    - Retrieves the addresses_city column from the "customers" table and calculates the total revenue by multiplying the price and quantity columns from the "orders" table.

21. **Calculate revenue by city and year:**
    - Retrieves the addresses_city and sale_date columns from the "customers" and "orders" tables,

 respectively. Calculates the total revenue by multiplying the price and quantity columns and groups the results by city and year.

22. **Calculate total quantity sold by city:**
    - Retrieves the addresses_city column from the "customers" table and calculates the total quantity sold from the "orders" table.

23. **Calculate monthly revenue:**
    - Retrieves the year and month from the sale_date column and calculates the monthly revenue by multiplying the price and quantity columns.

24. **Calculate average monthly order value:**
    - Retrieves the year and month from the sale_date column and calculates the average order value by dividing the total revenue by the number of orders.

Please note that these queries assume the existence of the relevant tables in the database. Before executing these queries, ensure that you have the necessary permissions and have imported the required data into the tables.
