### 1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram. ###
In the provided diagram, the relationship between "Product" and "Product_Category" entities is depicted through a foreign key. 
The "Product" entity has an attribute called category_id which references the id in the "Product_Category" entity. T
his is a one-to-many relationship, meaning that one product category can be associated with many products, but each product can belong to only one product category.

### 2. How could you ensure that each product in the "Product" table has a valid category assigned to it? ###
To ensure that each product in the "Product" table has a valid category assigned to it, the category_id column in the 
"Product" table should be set as a foreign key that references the id of the "Product_Category" table. Additionally, 
the category_id field should be marked as NOT NULL to enforce the presence of a category for each product. 
This database constraint will prevent the addition of products without a valid category.
