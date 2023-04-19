# Data Modelling with Apache Cassandra

## Modelling your NoSQL database or Apache Cassandra database
1. Design tables to answer the queries outlined in the project notebook
2. Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements
3. Develop your CREATE statement for each of the tables to address each question
4. Load the data with INSERT statement for each of the tables
5. Include IF NOT EXISTS clauses in your CREATE statements to create tables only if the tables do not already exist.
6. Test by running the proper select statements with the correct WHERE clause

## Build ETL Pipeline
1. Implement logic to iterate through each event file in event_data to process and create a new CSV file in Python
2. Include Apache Cassandra CREATE and INSERT statements to load processed records into relevant tables in your data model
3. Test by running SELECT statements after running the queries on your database

## Data Set
This projects uses one dataset: event_data. The directory of CSV files partitioned by date. 
