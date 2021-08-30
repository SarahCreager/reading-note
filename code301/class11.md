# Mongo and Mongoose

## nosql vs sql

*The information below was provided from [The Geek Stuff](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)*

### Fill in the chart below with five differences between SQL and NoSQL databases:

| SQL      | NoSQL |
| ----------- | ----------- |
| MySQL Community Edition      | MongoDB       |
| MS-SQL Server Express Edition   | CouchDB        |
| Oracle Express Edition   | Redis        |

### What kind of data is a good fit for an SQL database?
SQL is a table based database that is vertically scalable. SQL databases are used for complex queries.

### Give a real world example.

* cloud back-up uses SQL

### What kind of data is a good fit a NoSQL database?
NoSQL uses hierarchical data storage using key-value pairs. They are horizontally scalable and preferred for large data sets.

### Give a real world example.

* Adobe uses NoSQL

### Which type of database is best for hierarchical data storage?
NoSQL

### Which type of database is best for scalability?
SQL


## sql vs nosql (Video)

*The information below was provided from [Academind](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)*

### What does SQL stand for?
SQL (structured query language)

### What is a relational database?
A relational database works with certain assumptions and organizes data with defined relationships.

### What type of structure does a relational database work with?
Tables.

### What is a ‘schema’?
"A schema has strict requirements for the data being stored in the database. In a table, the schema is defined by fields."

### What is a NoSQL database?
NoSQL databases can stores and retrieves data without defining its structure first.

### How does it work?
NoSQL is able to store lots of data in an efficient way.Within the NoSQL database you have collections rather than tables. In the collection, you have documents, similar to the rows in a table. However, these documents don't have to use a strict schema. 

### What is inside of a Mongo database?
Data with no schema or relations. You can have completely different formatted documents in your database. (see above for more details)

### Which is more flexible - SQL or MongoDB? and why.
MongoDB is more flexible because it does not rely on strict schema. As your data grows over time, you can add more useful data to your database without needing schema. You can have different documents with different formats without needing to format before storing.  

### What is the disadvantage of a NoSQL database?
You will have data in many different formats and you may not be sure if the data you are trying to pull, adheres to the format you need it in.

[Back to Homepage](../README.md)