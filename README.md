# Data-Model-and-Database

In this project, I created database and tables using PostgreSQL and Python. 

Initially, I tried to build a Data Model to organise the elemnets of data and standardizes how they relate to each other and the properties of real world
entities. Data Modelling is really important to organize data which determines later data use. 

Relational Model : Organizes data into one or more tables of columns and rows, with a unique key identifying each row. 

Relational Database : It is a digital database based on the relational model of data. Here, a software system is used to maintain relational databases is
                      a Relational Database Management System (RDBMS). PostgreSQL is one of the open souce RDBMS. 

# Advantages of Relational Database: 
  
  1. Ease of use 
  2. Ability to do Joins 
  3. Ability to do aggregations and analytics
  4. Smaller Data Volumes
  5. Flexibility of queries. 
  6. Data Integrity


Step 1.  Creating a table with PostgreSQl
         Initially, I created a connection to the database and used the connection to get a cursor that can be used to execute queries. I set automatic            commit to save the transaction changes to the database. Additionally, a database is created to work in and added the database name in the
         connect statemnet. 

Step 2. Creating table for studentswith some columns and insert the rows in the table. Finally validate the data which was insert into the table and
        close cursor and connection. 

Step 3. I took three different datasets and build data model using the database. To do all these steps, I used python to create table structure and 
        insert data from files to database.  






