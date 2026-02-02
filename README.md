# techsavia-SQL
# Question 1
I have created an ENUM data type that allows only 'Yes' or 'No' as valid values. I have named this data type “presence”.
 <img width="976" height="611" alt="image" src="https://github.com/user-attachments/assets/d4b86333-682a-4e65-8627-3c5840b26d57" />

 
# Question 2
I have created a table called products with the columns product_id, product_name, “Cholesterol”, “Recyclable”, and “Fat”. I have used “Serial” data type for the product_id so that it can auto-generate. I have used the earlier created “presence” data type for the columns Cholesterol, Recyclable, and Fat so that these can only have the values ‘yes’ or ‘no’.
 <img width="976" height="611" alt="image" src="https://github.com/user-attachments/assets/cab7e04e-3b1f-41c2-afcb-9b84e51535c7" />

 
# Question 3
I have inserted 10 records into the products table with a unique product ID for each of the products. The second photo shows all 10 records for the table.

<img width="521" height="478" alt="image" src="https://github.com/user-attachments/assets/815f61ba-06b4-4a39-8ba0-f127dc682034" />

<img width="436" height="478" alt="image" src="https://github.com/user-attachments/assets/4f2e263e-c5ba-4732-a147-4688637a29bb" />


 
# Question 4
I wrote a SQL query to display all columns for products that have no fat.

 <img width="972" height="608" alt="image" src="https://github.com/user-attachments/assets/669eacda-7820-4f4a-820b-c3a5b8c23850" />


 
# Question 5
I wrote a SQL query to show all the names of the products we have without repetition. This allows us to know what unique products we have.



 
# Question 6
I wrote a SQL query to count the products sold



 
# Question 7
I wrote a SQL query to display only the product IDs of products that are recyclable.
 

 
# Question 8
I wrote a SQL query to find the names of products that have no fat and have no cholesterol.
 

 
# Question 9
I wrote a SQL query to display all products sorted by product_id in ascending order.

 

 
# Question 10
I wrote a SQL query to show the first 3 names of products on our dataset
 

 
# Question 11
I wrote a SQL query to display only the first 5 rows from the products table.
 
 
# Question 12
I wrote a SQL query to display all recyclable products, sorted by product_id in descending order.
 
 
# Question 13
I wrote a SQL query to display the top 3 newest products by ordering it to display product_id in descending order as a higher product_id means a newer product.


 
 
# Question 14
I wrote a SQL query to display the first 2 products that have no fat and are recyclable, sorted by product_id in ascending order.
 
 
# Question 15
Using an ENUM data type for fats, cholesterol, and recyclable is better than allowing free text values because this prevents unwanted errors from occurring. For example, someone may make typing mistakes and write “yws” instead of “yes”. This would result in a faulty query and would prevent the model from showing valuable insights. Additionally, this also results in uniformity of data when the administrator changes. Some new employees may come in and assume that the column should include the percentage of fat instead of the presence of it. But using the ENUM data type makes sure that this column only contains the “yes” or “no” values.
