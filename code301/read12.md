# Mongo and Mongoose

## differences between SQL and NoSQL databases

 SQL  |  NoSQL
------| ---------
 called as Relational Databases (RDBMS) | called as non-relational or distributed database
 SQL databases are table based databases|NoSQL databases are document based, key-value pairs, graph databases or wide-column stores
SQL databases have predefined schema | NoSQL databases have dynamic schema for unstructured data.
SQL databases are vertically scalable |  NoSQL databases are horizontally scalable
SQL databases uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful|In NoSQL database, queries are focused on collection of documents. Sometimes it is also called as UnQL (Unstructured Query Language)

![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20191104165821/SQL-Vs-NoSQL1.png)

## What kind of data is a good fit for an SQL database?

 SQL databases are not best fit for hierarchical data storage.
 SQL databases are best fit for heavy duty transactional type applications, as it is more stable and promises the atomicity as well as integrity of the data.
 SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server.

## Give a real world example

SQL database examples: MySql, Oracle, Sqlite, Postgres and MS-SQL. NoSQL

## What kind of data is a good fit a NoSQL database?

NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data. NoSQL database are highly preferred for large data set (i.e for big data). Hbase is an example for this purpose.
 NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.

## Give a real world examples

database examples: MongoDB, BigTable, Redis, RavenDb, Cassandra, Hbase, Neo4j and CouchDb

![](https://pbs.twimg.com/media/ErXtH3nXAAE42ls.png)

## Which type of database is best for hierarchical data storage?

NoSQL dataBase.

## Which type of database is best for scalability?

SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server.

## What does SQL stand for?

SQL stands for Structured Query Language. SQL is used to communicate with a database. According to ANSI (American National Standards Institute), it is the standard language for relational database management systems.

## What is a realational database?

A relational database is a type of database that stores and provides access to data points that are related to one another. Relational databases are based on the relational model, an intuitive, straightforward way of representing data in tables. In a relational database, each row in the table is a record with a unique ID called the key. The columns of the table hold attributes of the data, and each record usually has a value for each attribute, making it easy to establish the relationships among data points.

## What type of structure does a relational database work with?

The relational model means that the logical data structures—the data tables, views, and indexes—are separate from the physical storage structures. This separation means that database administrators can manage physical data storage without affecting access to that

## What is a ‘schema’?

A schema, or scheme, is an abstract concept proposed by J. Piaget to refer to our, well, abstract concepts. Schemas (or schemata) are units of understanding that can be hierarchically categorized as well as webbed into complex relationships with one another. For example, think of a house

## What is inside of a Mongo database?

MongoDB stores data records as documents (specifically BSON documents) which are gathered together in collections. A database stores one or more collections of documents.
In MongoDB, databases hold one or more collections of documents.

## Which is more flexible - SQL or MongoDB? and why?

While MongoDB is more flexible and ensures high and diverse data availability, a SQL Database operates with the ACID (Atomicity, Consistency, Isolation, and Durability)

## What is the disadvantage of a NoSQL database?

Disadvantages: NoSQL databases don't have the reliability functions which Relational Databases have (basically don't support ACID). This also means that NoSQL databases offer consistency in performance and scalability