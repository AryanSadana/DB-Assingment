Answer 1 :
answer to question 1 will be One-to-Many 
-product contains category-id which is a foreign key and product category contains id which is a primary key.
-(Easy explanation - There can be many products under one product category)

Answer 2 :  
By utilizing a foreign key constraint in the "Product" table that references the "product_category" table's "id" field. This constraint will ensure that any value entered in the "category_id" field of the "Product" table must exist as a primary key in the "product_category" table.
