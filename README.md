# Large_file_processor
System which to handle long running processes in distributed systems.

# Deliverables: -
----------------
# 1. Steps to run your code. As less steps we are to run, better for you 
    To run this code: -
    1. Need to have SSMS and Anaconda
    2. Anacodea: - I Jupyter note book to write the python code.
    3. SSMS:- To check how data is inserting basically to test the workflow.
    
    
# 2. Details of all the tables and their schema, [with commands to recreate them]
   
   1. Initially I have created Database called PRODUCT which do not have any tables.
   
   
   
   ![image](https://user-images.githubusercontent.com/31444645/114305778-3b742880-9af7-11eb-84d5-ba8a5c30cfc1.png)
   
   
   
   2. Next I created python notebook called Large file processor_Assignment  
       1. Created Class as we need achieve OOPS concept
       2. The init method used to connect to the Server and database. Here I am passing Sever name and Database name as Parameter
       3. Other functions like create_table, drop_table, bulk_insert, update_by_sku functions also created to achieve the goal
       4. Everything explained in code itself, please refer:)

   
# 3. What is done from “Points to achieve” and number of entries in all your tables with sample 10 rows from each
       1.  Your code should follow concept of OOPS: -Yes!!!! It is achived........
       
       2. Support for regular non-blocking parallel ingestion of the given file into a table. Consider thinking about the scale of what should happen if the file is to be processed in 2 mins.

                    Time taken to insert the data to the table from CSV file:- 7-9 Secs
        
       3. Support for updating existing products in the table based on `sku` as the primary key. (Yes, we know about the kind of data in the file. You need to find a workaround for it)
                    Yes, It will support.Here is the one example
                    
                    
                    
                    ![image](https://user-images.githubusercontent.com/31444645/114306841-d7ebfa00-9afa-11eb-862b-b7967becbb6a.png)



                    
                    
                    

       5. All product details are to be ingested into a single table
       6. An aggregated table on above rows with `name` and `no. of products` as the columns

6. What is not done from “Points to achieve”. If not achieved write the possible reasons and current workarounds.
7. What would you improve if given more days



