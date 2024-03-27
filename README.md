# Bicycle_Sales_Analysis
This project analyze data from the Bicycle Sales db provided by the datacamp team.
Objective:
The main objective of this project is to analyze bicycle sales and answer the following questions:
1. ¿What are the top 3 most sold products, categories and brands?
2. ¿Does the sales of a certain product change from store to store?
3. ¿Who are the most loyal clients?
4. ¿Which staff member made the most sales?

Tools:
The key tool used for this project is SQL. I combined subqueries, window functions and simple joins. 

Insights:
To present this information I used Power BI. The principal reason for doing this is that being able to handle data modeling of 9 tables is more efficient with Power BI. Besides, I think it can agreggate extra value to the project due to the versatility to make connections to different data sources, not to mention the cleaning data process.

About the data:
Tables used in this project have been provided by the DataCamp team Bicycle Sales database. This means all the rights of use correspond to them.
Specific tables and columns are:
- order_items: It is a table that capture orders from stores, asigning an order_id. It includes the following columns: discount,item_id,list_price,order_id, product_id and quantity.
- orders: This table capture the orders from the stores then add an order status and an order date. It includes the following columns: customer_id,order_date,order_id,order_status,required_date,shipped_date,staff_id and store_id.
- stores: This table contains general information about stores, and include: store_id, store_name, phone	email, street, city, state and zip_code.
- products: This table contains general information about products, and include:product_id, product_name	brand_id, category_id, model_year, list_price.
- stocks: This table contains data of the stores stock, and include:product_id, quantity, store_id.
- brands: This table contains general information about brands, and include: brand_id and brand_name.
- categories: This table contains general information about categories, and include: category_id and category_name.
- staffs: This table contains general information about staff members, and include: staff_id, first_name	last_name, email ,phone, active ,store_id and manager_id.
- customers: This table contains general information about customers, and include: customer_id, first_name	last_name, phone, email, street, city, state and zip_code.
