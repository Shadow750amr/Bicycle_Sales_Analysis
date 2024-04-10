# Bicycle_Sales_Analysis

Description: This project analyze data from the Bicycle Sales db provided by the datacamp team.
This data simulates a 3 year sales transactions from 3 stores: Baldwin Bikes, Rowlett Bikes and Santa Cruz Bikes.
The main objective of this project is to analyze bicycle sales and answer the following questions:
1. ¿What are the top 3 most sold products, categories and brands?
2. ¿Does the top sales of a certain product change from store to store?
3. ¿Who are the most loyal clients?
4. ¿Which staff member made the most sales?

Tools and enviroment:
The key tool used for this project is SQL. I combined subqueries, window functions and simple joins. 
I used the datacamp enviroment to run the queries, so it may not work if you try to run it in a jupyter notebook or a DBMS.

Insights:
To present this information I used Power BI. The principal reason of doing this is that being able to handle data modeling of 9 tables is more efficient with Power BI. Besides, I think it can agreggate extra value to the project due to the versatility to make connections to different data sources, not to mention the cleaning data process.

Focusing froup:
This analyze is oriented to provide KPI´s to the sales force team and stakeholders.

About the data:
Tables used for this project have been provided by the DataCamp team. This means that I don´t own the rights.
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



Repo documents: 
This repository includes the following documents:
- Bicycle_Sales_Data (Folder): Contains the csv files used for the project.
- The ipynb file used to share the SQL queries.
- The pbix file where dashboard is accesible.
- A pdf with dasboard images and aditional information about M code, DAX expressions and data modeling.



Further analysis:
- This project does not include any profit analysis due to the lack of information (in this case, standard cost per product or other cost variable).
- A deeper analyze in the sales of 2018 is needed due to the overall lower of sales and orders.

