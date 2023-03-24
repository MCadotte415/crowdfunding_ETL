# crowdfunding_ETL
For the ETL mini project, you will work with a partner to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After you transform the data, you'll create four CSV files and use the CSV file data to create an ERD and a table schema. Finally, you’ll upload the CSV file data into a Postgres database.

Instructions
The project instructions are divided into the following subsections:


Create the Category and Subcategory DataFrames
Export the<img width="165" alt="category" src="https://user-images.githubusercontent.com/118322641/227386320-78bad39f-84f3-4faf-8b40-77273ea31ecb.png">
 



<img width="221" alt="subcategory" src="https://user-images.githubusercontent.com/118322641/227386298-f67107ee-7ede-4241-9c41-a97aedb406fc.png">




Create the Campaign DataFrame


<img width="683" alt="campaign" src="https://user-images.githubusercontent.com/118322641/227386280-35b136dd-720f-409b-90e8-a0822466fdd2.png">



Create the Contacts DataFrame



<img width="389" alt="contacts" src="https://user-images.githubusercontent.com/118322641/227386251-d8d0dc3d-75df-4967-8277-d5b551fbeb78.png">




Use the information from the ERD to create a table schema for each CSV file.

Note: Remember to specify the data types, primary keys, foreign keys, and other constraints.

Save the database schema as a Postgres file named crowdfunding_db_schema.sql, and save it to your GitHub repository.

Create a new Postgres database, named crowdfunding_db.

Using the database schema, create the tables in the correct order to handle the foreign keys.

Verify the table creation by running a SELECT statement for each table.

Import each CSV file into its corresponding SQL table.

Verify that each table has the correct data by running a SELECT statement for each.

Create and import the tables in the following order; contacts, category, subcategory and last campaign
