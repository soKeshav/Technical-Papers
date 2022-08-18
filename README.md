# NoSql 
![image](https://www.ingeniux.com/Images/Blog/Blog%20Images/Uncategorized%20Images/no-sql-blog-image.fw.png)
## abstract
* NoSQL databases store data in documents rather than relational tables. Accordingly, we classify them as "not only SQL" and subdivide them by a variety of flexible data models. Types of NoSQL databases include pure document databases, key-value stores, wide-column databases, and graph databases.
# contents
* What is a NoSQL database?
* Types of NoSQL databases 
* When should NoSQL be used?
* Key characteristics of MongoDB
* Comparing performance & speed for MongoDB and MySQL
* MongoDB Advantages
* Performance analysis of MongoDB and RDBMS
* Why Adopt OpenEBS for NoSQL?
* Reduced Storage Costs
* Translating NoSQL Knowledge to Graphs
* Summary
* Reference
# What is a NoSQL database?
* When people use the term “NoSQL database,” they typically use it to refer to any non-relational database. Some say the term “NoSQL” stands for “non SQL” while others say it stands for “not only SQL.” Either way, most agree that NoSQL databases are databases that store data in a format other than relational tables.
# Types of NoSQL databases 
* Document databases store data in documents similar to JSON (JavaScript Object Notation) objects. Each document contains pairs of fields and values. The values can typically be a variety of types including things like strings, numbers, booleans, arrays, or objects.
* Key-value databases are a simpler type of database where each item contains keys and values.
* Wide-column stores store data in tables, rows, and dynamic columns.
* Graph databases store data in nodes and edges. Nodes typically store information about people, places, and things, while edges store information about the relationships between the nodes
# When should NoSQL be used?
When deciding which database to use, decision-makers typically find one or more of the following factors that lead them to select a NoSQL database:

    Fast-paced Agile development
    Storage of structured and semi-structured data
    Huge volumes of data
    Requirements for scale-out architecture
    Modern application paradigms like microservices and real-time streaming
# Key characteristics of MongoDB

   * Ad Hoc queries in MongoDB are flexible, providing a schema enabling optimized real-time analytics for enterprise applications.
   * Enhanced indexing allows MongoDB to optimize performance and improve query execution speed.
   * Data replications allow you to replace the primary node with a secondary one in case of failure.
   * Distributed server shards carrying a portion of the dataset form a single comprehensive database providing higher availability and horizontal scalability.
   * Load balancing support by MongoDB enables your systems to handle multiple concurrent read and write operations.
# Comparing performance & speed for MongoDB and MySQL
![image](https://www.simform.com/wp-content/uploads/2017/11/Query-performance.png)
![image](https://www.simform.com/wp-content/uploads/2017/11/MongoDB-performance.png)
# MongoDB Advantages
* MongoDB is schema-less. It is a document database in which one collection holds different documents.
* There may be a difference between the number of fields, content and size of the document from one to the other.
* Structure of a single object is clear in MongoDB.
* There is no complex joins in MongoDB.
* MongoDB provides the facility of deep query because it supports a powerful dynamic query on documents.
* It is very easy to scale.
* It uses internal memory for storing working sets and this is the reason for its fast access
# Performance analysis of MongoDB and RDBMS
* In relational database (RDBMS) tables are used as storing elements, while in MongoDB collection is used.
* In the RDBMS, we have multiple schemas and in each schema, we create tables to store data while MongoDB is a document-oriented database in which data is written in BSON format which is a JSON-like format.
* MongoDB is almost 100 times faster than traditional database systems
![image](https://intellipaat.com/blog/wp-content/uploads/2022/01/image-117.png)
# Why Adopt OpenEBS for NoSQL?
Many organizations and users have adopted OpenEBS to deploy and provision storage for their stateful workloads, including those who use NoSQL. Some of the following reasons to adopt OpenEBS for NoSQL databases include
# No Cloud Lock-in
With OpenEBS, application data is written into storage engines, creating a data abstraction layer. This allows developers to move data easily between multiple Kubernetes environments. OpenEBS can be deployed on-premises, local storage or managed cloud services -- thereby allowing NoSQL applications to simultaneously access data stored on different deployment platforms.
# Reduced Storage Costs
The dynamic nature of NoSQL data often necessitates the over-provision of cloud storage resources to achieve higher performance and a lower risk of disruption. To help with this, OpenEBS relies on thin provisioning mechanisms to pool storage and grow data volumes when the NoSQL database needs it. While adjusting storage on the fly without disrupting volumes attached to workloads, OpenEBS enables cost savings of up to 60% by leveraging thin, dynamic provisioning.
# Low Scaling Costs
We’ve talked about the importance of NoSQL databases for structured content, experience data and big content; now let’s look at the operating aspects of a NoSQL database.

NoSQL databases have much lower operating costs than relational databases. A relational database cannot be scaled out easily. Instead, it needs to be scaled up (you have to get a bigger better server) so it requires a highly sophisticated server in terms of performance and database size. A NoSQL database can be installed on standard commoditized servers (either physical or virtual) and can easily scale out as data and performance requirements increase.

NoSQL databases also have integrated caching. This means data is loaded into the cache automatically reducing latency and increasing the throughput of data. With a relational database, separate server technology is required for caching.

Another feature of some NoSQL databases is auto-sharding. Auto-sharding means that data can be spread across some servers automatically, and developers and administrators don’t need to do anything to support it.
# Translating NoSQL Knowledge to Graphs


With the advent of the NoSQL movement, businesses of all sizes have a variety of modern options from which to build solutions relevant to their use cases.

    Calculating average income? Ask for a relational database.

    Building a shopping cart? Use a key-value Store.

    Storing structured product information? Store as a document.

    Describe how a user got from point A to point B? Follow a graph.

The chart below shows how each database type stacks up on a spectrum measuring depth and size. While key-value stores can handle massive sizes, they are designed for a high-level view (low depth) of the data. Graph databases retain minimum sizing, even at a greater depth of data than other types of databases.
# Summary
NoSQL databases provide a variety of benefits including flexible data models, horizontal scaling, lightning-fast queries, and ease of use for developers. NoSQL databases come in a variety of types including document databases, key-values databases, wide-column stores, and graph databases.

MongoDB is the world's most popular NoSQL database. Learn more about MongoDB Atlas, and give the free tier a try.

Are excited to learn more now that you have your own Atlas account. Head over to MongoDB University where you can get free online training from MongoDB engineers and earn a MongoDB certification. The Quick Start Tutorials are another great place to begin; they will get you up and running quickly with your favourite programming language.
# Reference
* https://www.mongodb.com/nosql-explained
* https://www.simform.com/blog/mongodb-vs-mysql-databases/
* https://www.javatpoint.com/mongodb-advantages-over-rdbms