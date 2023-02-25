Relational database works by modeling real-world entities as tables. Each table contains rows that represent a single instance of an entity, and each row has the same columns, which store data of a specific datatype.  
Not all columns need to have a value, and the available datatypes depend on the database system being used.  
The example of a retail system is used to illustrate how tables can be created for customers, products, orders, and line items within an order.  

Normalization: process of organizing data in a relational database to reduce data redundancy and improve data integrity.  
It is typically achieved by organizing data into a set of tables, each of which contains a primary key and one or more attributes.  
The primary key is used to identify each record in the table,  while the attributes describe the data associated with each record.  
By organizing data into separate tables, it becomes easier to update and maintain, and it also helps to reduce the risk of errors and inconsistencies.  

SQL statements:  
- Data Manipulation Language (DML) statements are used to modify data in a table, such as INSERT, UPDATE, and DELETE.  
- Data Definition Language (DDL) statements are used to define the structure of a table, such as CREATE, ALTER, and DROP.  
- Data Control Language (DCL) statements are used to manage access to data, such as GRANT and REVOKE.  

Database objects that frequently used:  
- Tables: store data in rows and columns.  
- Views: virtual tables based on the result set of an SQL statement.  
- Indexes: improve the performance of database queries by allowing faster access to specific data.  
- Stored procedures: precompiled SQL statements that can be reused and executed on demand.
