Difference between structured and unstructured data: Structured data is organized and formatted in a specific way, usually stored in tables with defined fields and types, while unstructured data has no set format and can be in various forms, such as text, audio, video, or images.

Most common file formats:  
CSV (Comma Separated Values) - used for storing tabular data in plain text format,    
JSON (JavaScript Object Notation) - used for storing structured data in a human-readable format,  
Parquet - a columnar storage format that is optimized for handling large amounts of data,  
Avro - a data serialization format used for storing data in a compact binary format,  
ORC (Optimized Row Columnar) - a high-performance columnar storage format used for big data processing,  
XML (Extensible Markup Language) - used for storing structured data in a hierarchical format.  

Relational database is a type of database that stores and organizes data in tables with predefined relationships between them. It offers several advantages, including data integrity, scalability, and standardization. They also provide a clear structure for storing data, which makes it easier to query and retrieve information. However,  relational databases can be inflexible when it comes to storing certain types of data, such as unstructured data. They can also be more difficult to scale horizontally than non-relational databases.

Non-relational database, also known as NoSQL database, is a type of database that does not use the traditional table-based structure of relational databases. Instead, it uses a more flexible data model and can store data in various formats, including key-value pairs, documents, graphs, and columns. It offers several advantages, including flexibility in data storage, faster performance for certain types of queries, and easier scalability. On the other hand it may lack the data consistency and standardization of relational databases. They can also be more complex to manage and require more specialized knowledge to use effectively.  

OLTP - database system designed to manage transaction-oriented applications. Its systems are used for transactional processing where large volumes of data transactions are processed in real-time. The main thing is to manage individual transactions, such as adding, updating, or deleting records in a database. Is for read/write operations. Provides ACID (Atomicity, Consistency, Isolation, and Durability) properties 

OLAP - systems are designed to support complex analysis of large volumes of data and enable users to explore data from different dimensions and perspectives.. It is used to support business decision-making and data analytics. OLAP systems store historical data, which enables users to analyze trends and patterns over time. Online Analytical Processing systems summarize data at different levels of aggregation, such as by day, week, or month, to provide a high-level overview of data.

So the prime difference between them is: OLTP handles transactional processing for business operations such as order processing, inventory management, and other day-to-day activities and OLAP is focused on analyzing and reporting data for business intelligence purposes. Important is also the volume difference OLTP databases typically handle large numbers of small transactions and are designed to handle high-volume, low-latency workloads.  

Data services:  
- Azure SQL: managed relational database service, it has several services like: Azure SQL Database, Azure SQL Managed Instance, Azure SQL VM,  
- Opensource databases: including Azure Database for MySQL, Azure Database for MariaDB, Azure Database for PostgreSQL,  
- Cosmos DB: fully managed NoSQL database service that offers global distribution, elastic scalability, and multiple APIs (e.g., SQL, MongoDB, Cassandra) to meet different data storage and access requirements,  
- Azure Storage: cloud storage service that offers scalable and durable storage for different types of data (e.g., blobs, files, queues, tables) and various access tiers (e.g., hot, cool, archive) based on the frequency of data access,  
- Data Factory: cloud-based data integration service that allows users to create, schedule, and manage workflows to move and transform data across various sources and destinations,  
- Synapse Analytics: combines big data and data warehousing to enable users to ingest, prepare, manage, and serve data for business intelligence and machine learning purposes,  
- Databricks: Apache Spark-based analytics service that allows users to build and train machine learning models at scale, using languages like Python, R, or Scala,  
- HDInsight: Enables users to process and analyze large-scale data using popular open-source frameworks such as Hadoop, Spark, Hive, or HBase, 
- Data explorer: designed for log and telemetry data analysis, providing real-time querying and visualization capabilities.  

Job roles in data:  
- Database administorator: responsible for managing and maintaining databases, ensuring data security and integrity, and optimizing database performance. They also monitor database usage to identify and resolve issues that impact performance.  
- Data engineer: responsible for designing, building, and maintaining the systems and infrastructure, working with data storage, processing, and integration technologies.  
- Data Analyst: collect and analyze data to help organizations make better decisions. They work with databases and analytical tools to find patterns and insights that can help improve business performance.  
