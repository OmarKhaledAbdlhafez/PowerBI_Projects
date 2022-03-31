# AdventureWorks
 ## working with AdventureWorks database 

### it is an oltp database with snowflake schema get it into power bi and start modeling it into star schema with one fact table (orders) and dimension tables throw those steps :

-Rename Tables, columns

-Remove unused columns 

-one table (Merge M Language)

Production.Product , Production.ProductSubcategory , Production.ProductCategory into Product table 

- salesorderHeader , salesorderDetails into orders table (fact table )

- create Date table & status table (using Dax  

- create Product Hierarchy & date Hierarchy 

-  Number of Orders Measure

-   Number of Orders Per due date Measure

-  Number of Orders Per ship date Measure 

-  Number of Orders Deatils Measure 

-  Number of Customer Measure 

- Total Amount Measure  

- Total Qty

 ###  Visuals:

-  Number of Orders by OrderDate vs. ShipDate vs. DueDate with Drill Down

-  Number of Orders by Status

-  Number of Orders by Shipmethod

-  Number of Orders by Category, subCategory, Product with Drill Down

-  Number of Orders by FlagOnlineOffline

-  Number of Orders vs. Total Amount by Territory

- Top 10 Sales Perosns (# Orders and Total Amount ) (Filter filter pane)

- using Drill Through to get all Details order 

