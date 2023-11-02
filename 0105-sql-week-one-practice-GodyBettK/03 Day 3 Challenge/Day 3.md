This is a continuation of the ABC Database business problem. 
Here you will practice your querying skills. 
Your task is to answer the following two questions: 
1. Which product has the highest price? Only return a single row.
solution:
SELECT * FROM products ORDER BY price DESC LIMIT 1;
--The most expensive product is Product M with product_id 13
   
2. Which order_id had the highest number of items in terms of quantity
SELECT * FROM order_items ORDER BY quantity DESC;
   order_id 4 has the highest number of items (4) of product_id 2 (Product B)
