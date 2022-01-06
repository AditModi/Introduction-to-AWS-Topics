The past fifteen years have seen an incredible shift of application workloads from on-premises data centers or colocation facilities to cloud-based computing by using services from Amazon Web Services (AWS). Companies have been able to innovate faster, serve customers better, and keep their IT spend lower by migrating to cloud-based computing.

But a simple "lift and shift" to the cloud is not enough. More and more customers are looking for ways to innovate even faster by focusing on their core competencies. They are looking for a cloud provider that can be a partner as they work to deliver customer value. For many, this means more than simple compute and storage options. As a result, companies are using higher level services such as fully managed databases and serverless compute to get the most out of their cloud provider. 

In the previous blog post, we discussed some of the most important AWS Analytics services. In this blog post, We will talk about AWS Database services and Blockchain services. AWS Database services that help us build use case-driven, highly scalable, distributed applications suited to our specific needs. Developing blockchain and ledger applications is simpler, faster, and more efficient with AWS. 

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/7k5jbz04va6i189nwi3k.png)

> **The Introduction to AWS** is a Series containing different articles that provide a basic introduction to different aws topics/categories. Each article covers the detailed guide on how to work with particular topic/category . This series aims at providing "A Getting Started Guide on Different aws topics / categories ."

# AWS Database services

AWS fully managed database services provide continuous monitoring, self-healing storage, and automated scaling to help you focus on application development. We will discuss some of the most used AWS Database services.


## Amazon Aurora

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/vqdkon9a0hg17gbnawc6.png)
 
* Amazon Aurora is a MySQL and PostgreSQL compatible relational database engine that combines the speed and availability of high-end commercial databases with the simplicity and cost-eﬀectiveness of open source databases.

* Amazon Aurora is up to five times faster than standard MySQL databases and three times faster than standard PostgreSQL databases. It provides the security, availability, and reliability of commercial databases at 1/10th the cost. 

* Amazon Aurora is fully managed by Amazon Relational Database Service (RDS), which automates time-consuming administration tasks like hardware provisioning, database setup, patching, and backups.

* Amazon Aurora features a distributed, fault-tolerant, self-healing storage system that auto-scales up to 128TB per database instance. It delivers high performance and availability with up to 15 low-latency read replicas, point-in-time recovery, continuous backup to Amazon S3, and replication across three Availability Zones (AZs).

## Amazon Relational Database Service

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/2aiad4qh8d4v4dr2ejhn.png)
 
* Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching and backups. 

* It frees you to focus on your applications so you can give them the fast performance, high availability, security and compatibility they need.

* Amazon RDS is available on several database instance types - optimized for memory, performance or I/O - and provides you with six familiar database engines to choose from, including Amazon Aurora, PostgreSQL, MySQL, MariaDB, Oracle Database, and SQL Server. You can use the AWS Database Migration Service to easily migrate or replicate your existing databases to Amazon RDS.

## Amazon RDS on VMware

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/dd7pw9k337lyf4eeydpn.png)
 
* Amazon Relational Database Service (Amazon RDS) on VMware lets you deploy managed databases in on-premises VMware environments using the Amazon RDS technology enjoyed by hundreds of thousands of AWS customers. 

* Amazon RDS provides cost-efficient and resizable capacity while automating time-consuming administration tasks including hardware provisioning, database setup, patching, and backups, freeing you to focus on your applications. 

* RDS on VMware brings these same benefits to your on-premises deployments, making it easy to set up, operate, and scale databases in VMware vSphere private data centers, or to migrate them to AWS.

* Amazon RDS on VMware allows you to utilize the same simple interface for managing databases in on-premises VMware environments as you would use in AWS. You can easily replicate RDS on VMware databases to RDS instances in AWS, enabling low-cost hybrid deployments for disaster recovery, read replica bursting, and optional long-term backup retention in Amazon Simple Storage Service (Amazon S3).

## Amazon DynamoDB

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/0fozt93c2jn9ixhve1lw.png)
 
* Amazon DynamoDB is a key-value and document database that delivers single-digit millisecond performance at any scale. It's a fully managed, multiregion, multimaster database with built-in security, backup and restore, and in-memory caching for internet-scale applications. 

* DynamoDB can handle more than 10 trillion requests per day and support peaks of more than 20 million requests per second.

* Many of the world's fastest growing businesses such as Lyft, Airbnb, and Redfin as well as enterprises such as Samsung, Toyota, and Capital One depend on the scale and performance of DynamoDB to support their mission-critical workloads.

* More than 100,000 AWS customers have chosen DynamoDB as their key-value and document database for mobile, web, gaming, ad tech, IoT, and other applications that need low-latency data access at any scale. Create a new table for your application and let DynamoDB handle the rest.

## Amazon ElastiCache

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rgb5uhaxp98v8i7ybaz8.png)
 
* Amazon ElastiCache is a web service that makes it easy to deploy, operate, and scale an in-memory cache in the cloud. The service improves the performance of web applications by allowing you to retrieve information from fast, managed, in-memory caches, instead of relying entirely on slower disk-based databases.

* Amazon ElastiCache supports two open-source in-memory caching engines:

**Redis -** a fast, open source, in-memory data store and cache. Amazon ElastiCache for Redis is a Redis-compatible in-memory service that delivers the ease-of-use and power of Redis along with the availability, reliability, and performance suitable for the most demanding applications. Both single-node and up to 15-shard clusters are available, enabling scalability to up to 3.55 TiB of in-memory data. ElastiCache for Redis is fully managed, scalable, and secure. This makes it an ideal candidate to power high-performance use cases such as web, mobile apps, gaming, ad-tech, and IoT.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/wdyilo2ubq7kvnh02smb.png)
 

**Memcached -** a widely adopted memory object caching system. ElastiCache for Memcached is protocol compliant with Memcached, so popular tools that you use today with existing Memcached environments will work seamlessly with the service.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/k5uq903q0tc6ez468xpo.png)
 

## Amazon Neptune

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/qz2yj777v6mt8jrobf7q.png)
 
* Amazon Neptune is a fast, reliable, fully-managed graph database service that makes it easy to build and run applications that work with highly connected datasets. 

* The core of Amazon Neptune is a purpose-built, high-performance graph database engine optimized for storing billions of relationships and querying the graph with milliseconds latency.

* Amazon Neptune supports popular graph models Property Graph and W3C's RDF, and their respective query languages Apache TinkerPop Gremlin and SPARQL, allowing you to easily build queries that efficiently navigate highly connected datasets. 

* Neptune powers graph use cases such as recommendation engines, fraud detection, knowledge graphs, drug discovery, and network security.

* Amazon Neptune is highly available, with read replicas, point-in-time recovery, continuous backup to Amazon S3, and replication across Availability Zones. 

* Neptune is secure with support for encryption at rest. Neptune is fully-managed, so you no longer need to worry about database management tasks such as hardware provisioning, software patching, setup, configuration, or backups.

## Amazon Quantum Ledger Database (QLDB)

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ek6dwq39ohnkr2c1cvlb.png)
 
* Amazon QLDB is a fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log ‎owned by a central trusted authority. 

* Amazon QLDB tracks each and every application data change and maintains a complete and verifiable history of changes over time.

* Ledgers are typically used to record a history of economic and financial activity in an organization. Many organizations build applications with ledger-like functionality because they want to maintain an accurate history of their applications' data, for example, tracking the history of credits and debits in banking transactions, verifying the data lineage of an insurance claim, or tracing movement of an item in a supply chain network. 

* Ledger applications are often implemented using custom audit tables or audit trails created in relational databases. However, building audit functionality with relational databases is time-consuming and prone to human error. 

* It requires custom development, and since relational databases are not inherently immutable, any unintended changes to the data are hard to track and verify. 

* Alternatively, blockchain frameworks, such as Hyperledger Fabric and Ethereum, can also be used as a ledger. However, this adds complexity as you need to set-up an entire blockchain network with multiple nodes, manage its infrastructure, and require the nodes to validate each transaction before it can be added to the ledger.

* Amazon QLDB is a new class of database that eliminates the need to engage in the complex development effort of building your own ledger-like applications. 

* With QLDB, your data’s change history is immutable – it cannot be altered or deleted – and using cryptography, you can easily verify that there have been no unintended modifications to your application’s data. 

* QLDB uses an immutable transactional log, known as a journal, that tracks each application data change and maintains a complete and verifiable history of changes over time. QLDB is easy to use because it provides developers with a familiar SQL-like API, a flexible document data model, and full support for transactions.

* QLDB is also serverless, so it automatically scales to support the demands of your application. There are no servers to manage and no read or write limits to configure. With QLDB, you only pay for what you use.

## Amazon Timestream

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ha7ilp8bakub29iglbzj.png)
 
* Amazon Timestream is a fast, scalable, fully managed time series database service for IoT and operational applications that makes it easy to store and analyze trillions of events per day at 1/10th the cost of relational databases. 

* Driven by the rise of IoT devices, IT systems, and smart industrial machines, time-series data — data that measures how things change over time — is one of the fastest growing data types. 

* Time-series data has specific characteristics such as typically arriving in time order form, data is append-only, and queries are always over a time interval. While relational databases can store this data, they are inefficient at processing this data as they lack optimizations such as storing and retrieving data by time intervals. 

* Timestream is a purpose-built time series database that efficiently stores and processes this data by time intervals. With Timestream, you can easily store and analyze log data for DevOps, sensor data for IoT applications, and industrial telemetry data for equipment maintenance. 

* As your data grows over time, Timestream’s adaptive query processing engine understands its location and format, making your data simpler and faster to analyze. Timestream also automates rollups, retention, tiering, and compression of data, so you can manage your data at the lowest possible cost. 

* Timestream is serverless, so there are no servers to manage. It manages time-consuming tasks such as server provisioning, software patching, setup, configuration, or data retention and tiering, freeing you to focus on building your applications.

## Amazon DocumentDB (with MongoDB compatibility)

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/tpkgvcxac6lt03a261sw.png)
 
* Amazon DocumentDB (with MongoDB compatibility)  is a fast, scalable, highly available, and fully managed document database service that supports MongoDB workloads.

* Amazon DocumentDB (with MongoDB compatibility) is designed from the ground-up to give you the performance, scalability, and availability you need when operating mission-critical MongoDB workloads at scale. 

* Amazon DocumentDB (with MongoDB compatibility) implements the Apache 2.0 open source MongoDB 3.6 API by emulating the responses that a MongoDB client expects from a MongoDB server, allowing you to use your existing MongoDB drivers and tools with Amazon DocumentDB (with MongoDB compatibility) .

# AWS Blockchain Services

* AWS Blockchain is the perfect example of fully managed services for using blockchain technology. Blockchain on AWS refers to a small yet powerful assortment of offerings that support the enterprise blockchain initiatives of organizations. 

* The Amazon Quantum Ledger Database, Amazon Managed Blockchain, AWS Blockchain Partners, and AWS Blockchain Templates are the prominent entries when it comes to discussions about blockchain on AWS.

## Amazon Managed Blockchain

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/iar9j93e5hocaifkh3gl.png)
 
* Amazon Managed Blockchain is a fully managed service that makes it easy to create and manage scalable blockchain networks using the popular open source frameworks Hyperledger Fabric and Ethereum.

* Blockchain makes it possible to build applications where multiple parties can execute transactions without the need for a trusted, central authority. 

* Today, building a scalable blockchain network with existing technologies is complex to set up and hard to manage. To create a blockchain network, each network member needs to manually provision hardware, install software, create and manage certificates for access control, and configure networking components. 

* Once the blockchain network is running, you need to continuously monitor the infrastructure and adapt to changes, such as an increase in transaction requests, or new members joining or leaving the network.

# Conclusion

* AWS databases deliver the high availability, reliability, and security you need for business-critical, enterprise workloads.
They support multi-region, multi-primary replication, and provide full data oversight with multiple levels of security, including network isolation and end-to-end encryption.

* More customers trust AWS for their blockchain and ledger technology workloads than any other cloud vendor. AWS has over 70+ validated blockchain solutions from partners who provide support to all major blockchain protocols including Hyperledger Sawtooth, Corda, DAML, Ethereum and many more.
 

Hope this guide helps you with Introduction to Data (Databases, Analytics, Blockchain) with AWS  Part - 2. 

Let me know your thoughts in the comment section 👇
And if you haven't yet, make sure to follow me on below handles:

👋 **connect with me on [LinkedIn](https://www.linkedin.com/in/adit-modi-2a4362191/)**
🤓 **connect with me on [Twitter](https://twitter.com/adi_12_modi)**
🐱‍💻 **follow me on [github](https://github.com/AditModi)**
✍️ **Do Checkout [my blogs](https://aditmodi.hashnode.dev)** 

Like, share and follow me 🚀 for more content.

{% user aditmodi %}