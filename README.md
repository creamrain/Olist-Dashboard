### Olist E-Commerce Analysis

### Project Overview

This data analysis project aims to provide insights into the performance of Olist Store, a Brazilian Departmental Store, enabling Olist to make data-driven decisions to grow its business and operations.

### Data Source
Brazilian E-Commerce Data: 

olist_order_reviews_dataset.csv contains reviews and ratings provided by customers after they have received their orders.

olist_order_items_dataset.csv details product ID, product quantity, freight price, and product cost.

olist_order_customers_dataset.csv details the order ID, zipcode, cities, and states where customers live.

product_category_name_translation.csv provides English translation to Brazilian products.

olist_products_dataset.csv contains product ID, product information, such as its size, weight, name, and description length.

olist_orders_dataset.csv provides information on order status and order purchase timestamp, as well as shipment information such as estimated delivery date and actual delivery date.

### Tools Used
Power BI (Data Cleaning and Preparation in Power Query, Measures and Date table created in DAX)

Data Cleaning and Preparation
1. Data Loading and Inspection, such as ensuring correct column headers
   
2. Check for duplicates such as product_id in products dataset and order_id in orders dataset
   
3. Transforming abbreviations of state names into their official names

4. Reformatting data such as replacing _ in product_category_name_english in product_category_name with space for greater readability
   
5. Create new columns to assist with analysis:
- row_price, row_freight, and revenue(row_price + row_freight) in order items dataset
- estimated_delivery_time, actual_delivery_time, delivery_on_time, and delay in order dataset
    
6. Create a Date Table in DAX to assist with the analysis of data over Year and Month

7. Create Measures Table to group measures for easier access to various measures
