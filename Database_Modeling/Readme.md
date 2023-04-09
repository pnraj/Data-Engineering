### This sub repo contains all the database schema and database modeling methods and types:

- There are different types of database that are used in different usecase
- I want to create database that can help data analyst or data scientist in terms of better quering 
- these are suggestion given by CHATGPT:
```
There are several strategies that can be used to create such a database:

Choose the right database system:
There are several database systems that are optimized for data analysis, such as columnar databases and in-memory databases. 
These databases are designed to handle large volumes of data and support complex queries.

Choose the right database schema: 
The database schema should be designed to support the queries that will be run against it. For example, 
if there are certain fields that will be used in many queries, these fields should be indexed for faster access.

Normalize the database: 
Normalizing the database can improve query performance by reducing the amount of redundant data in the database. 
However, this can also make the database more complex and difficult to manage.

Denormalize the database: 
Denormalizing the database can improve query performance by reducing the number of joins that need to be performed. 
However, this can also lead to redundant data in the database.

Use partitioning: 
Partitioning the database can improve query performance by allowing queries to be executed on a smaller subset of the data. 
This can be particularly useful for large databases.

Use indexing: 
Indexing the database can improve query performance by allowing queries to be executed more quickly. 
However, indexing can also increase the size of the database and slow down insert and update operations.

```
