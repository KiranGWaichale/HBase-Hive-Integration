# HBase-Hive-Integration

Step 1. Create Table in HBase [sales_order]
Step 2.	Create Table in Hive with Storage Handler [hbase_sales_order]
Step 3.	Create Stage Table in Hive [hbase_stg_sales_order]
Step 4.	Load data to Stage table
Step 5.	Create a temporary fuction row_sequence()
Step 6.	Insert data from Stage table to Hive Table with key as row_sequence()
Step 7.	Select data from Hbase table
Step 8.	Select data from Hive table
