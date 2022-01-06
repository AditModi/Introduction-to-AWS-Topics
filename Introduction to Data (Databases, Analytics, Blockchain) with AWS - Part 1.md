Data is a strategic asset of every organisation. As data continues to grow, databases are becoming increasingly pivotal to understanding data and converting it to valuable insights. IT leaders and entrepreneurs need to look at different flavours of data and based on it look for ways to get more value from their data. With the rapid growth of data — Not just in volume and velocity but also in flavours, complexity and interconnectedness — the needs of data analytics and its corresponding databases have changed.

In this blog post, we will discuss some of the most important AWS analytics services that are built to handle large amounts of data at scale and automate many manual and time-consuming tasks. This services are purpose-built to give you the best performance, scale, and cost for your needs.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/o75qds6xhf8by98buvzl.png)

> **The Introduction to AWS** is a Series containing different articles that provide a basic introduction to different aws topics/categories. Each article covers the detailed guide on how to work with particular topic/category . This series aims at providing "A Getting Started Guide on Different aws topics / categories ."

# AWS Analytics Services

* AWS is the fastest and most cost-effective place to store and analyze data. AWS provides a comprehensive set of tools that go beyond standard security functionality, like encryption and access control, to offer unified security policy management and proactive monitoring. AWS offers built-in ML integration as part of our purpose-built analytics services.

## Amazon Athena


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/drigofz9l0dhlkvkboj4.png)
 
* Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run.

* Athena is easy to use. Simply point to your data in Amazon S3, deﬁne the schema, and start querying using standard SQL. Most results are delivered within seconds. With Athena, there’s no need for complex extract, transform, and load (ETL) jobs to prepare your data for analysis. This makes it easy for anyone with SQL skills to quickly analyze large-scale datasets.

* Athena is out-of-the-box integrated with AWS Glue Data Catalog, allowing you to create a unified metadata repository across various services, crawl data sources to discover schemas and populate your Catalog with new and modified table and partition definitions, and maintain schema versioning. 

* You can also use Glue’s fully-managed ETL capabilities to transform data or convert it into columnar formats to optimize cost and improve performance.

## Amazon EMR


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/bwpubkmlhgv3p5q0ek3q.png)
 
* Amazon EMR provides a managed Hadoop framework that makes it easy, fast, and cost-eﬀective to process vast amounts of data across dynamically scalable Amazon EC2 instances. 

* You can also run other popular distributed frameworks such as Apache Spark, HBase, Presto, and Flink in Amazon EMR, and interact with data in other AWS data stores such as Amazon S3 and Amazon DynamoDB. 

* EMR Notebooks, based on the popular Jupyter Notebook, provide a development and collaboration environment for ad hoc querying and exploratory analysis.

* Amazon EMR securely and reliably handles a broad set of big data use cases, including log analysis, web indexing, data transformations (ETL), machine learning, ﬁnancial analysis, scientiﬁc simulation, and bioinformatics.

## Amazon CloudSearch


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/m4wbqt8u0hbcic7erbn2.png)
 
* Amazon CloudSearch is a managed service in the AWS Cloud that makes it simple and cost-effective to set up, manage, and scale a search solution for your website or application. 

* Amazon CloudSearch supports 34 languages and popular search features such as highlighting, autocomplete, and geospatial search.

## Amazon Elasticsearch Service


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/97kzqg16jga5xr6d4wrv.png)
 
* Amazon Elasticsearch Service makes it easy to deploy, secure, operate, and scale Elasticsearch to search, analyze, and visualize data in real-time. 

* With Amazon Elasticsearch Service, you get easy-to-use APIs and real-time analytics capabilities to power use-cases such as log analytics, full-text search, application monitoring, and clickstream analytics, with enterprise-grade availability, scalability, and security. 

* The service oﬀers integrations with open-source tools like Kibana and Logstash for data ingestion and visualization. It also integrates seamlessly with other AWS services such as Amazon Virtual Private Cloud (Amazon VPC), AWS Key Management Service (AWS KMS), Amazon Kinesis Data Firehose, AWS Lambda, AWS Identity and Access Management (IAM), Amazon Cognito, and Amazon CloudWatch, so that you can go from raw data to actionable insights quickly.

## Amazon Kinesis


* Amazon Kinesis makes it easy to collect, process, and analyze real-time, streaming data so you can get timely insights and react quickly to new information. 

* Amazon Kinesis offers key capabilities to cost-effectively process streaming data at any scale, along with the flexibility to choose the tools that best suit the requirements of your application. 

* With Amazon Kinesis, you can ingest real-time data such as video, audio, application logs, website clickstreams, and IoT telemetry data for machine learning, analytics, and other applications. 

* Amazon Kinesis enables you to process and analyze data as it arrives and respond instantly instead of having to wait until all your data is collected before the processing can begin.

* Amazon Kinesis currently oﬀers four services: Kinesis Data Firehose, Kinesis Data Analytics, Kinesis Data Streams, and Kinesis Video Streams.

### Amazon Kinesis Data Firehose


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/i5dszm1u0misr2kk4i72.png)
 

* Amazon Kinesis Firehose is the easiest way to reliably load streaming data into data stores and analytics tools. It can capture, transform, and load streaming data into Amazon S3, Amazon Redshift, Amazon Elasticsearch Service, and Splunk, enabling near real-time analytics with existing business intelligence tools and dashboards you’re already using today. 

* It is a fully managed service that automatically scales to match the throughput of your data and requires no ongoing administration. It can also batch, compress, transform, and encrypt the data before loading it, minimizing the amount of storage used at the destination and increasing security.

* You can easily create a Firehose delivery stream from the AWS Management Console, conﬁgure it with a few clicks, and start sending data to the stream from hundreds of thousands of data sources to be loaded continuously to AWS—all in just a few minutes. 

* You can also configure your delivery stream to automatically convert the incoming data to columnar formats like Apache Parquet and Apache ORC, before the data is delivered to Amazon S3, for cost-effective storage and analytics.

### Amazon Kinesis Data Analytics


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/e0hx3ewv2fg8ysjvq0ex.png)
 
* Amazon Kinesis Data Analytics is the easiest way to analyze streaming data, gain actionable insights, and respond to your business and customer needs in real time. 

* Amazon Kinesis Data Analytics reduces the complexity of building, managing, and integrating streaming applications with other AWS services. SQL users can easily query streaming data or build entire streaming applications using templates and an interactive SQL editor. 

* Java developers can quickly build sophisticated streaming applications using open source Java libraries and AWS integrations to transform and analyze data in real-time.

* Amazon Kinesis Data Analytics takes care of everything required to run your queries continuously and scales automatically to match the volume and throughput rate of your incoming data.

### Amazon Kinesis Data Streams


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lhryhl2t3daifdmbh4na.png)
 
* Amazon Kinesis Data Streams is a massively scalable and durable real-time data streaming service. KDS can continuously capture gigabytes of data per second from hundreds of thousands of sources such as website clickstreams, database event streams, financial transactions, social media feeds, IT logs, and location-tracking events. 

* The data collected is available in milliseconds to enable real-time analytics use cases such as real-time dashboards, real-time anomaly detection, dynamic pricing, and more.

### Amazon Kinesis Video Streams


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lrgyzzj9645fhrp3cs7e.png)
 
* Amazon Kinesis Video Streams makes it easy to securely stream video from connected devices to AWS for analytics, machine learning (ML), playback, and other processing. Kinesis Video Streams automatically provisions and elastically scales all the infrastructure needed to ingest streaming video data from millions of devices. 

* It also durably stores, encrypts, and indexes video data in your streams, and allows you to access your data through easy-to-use APIs. Kinesis Video Streams enables you to playback video for live and on-demand viewing, and quickly build applications that take advantage of computer vision and video analytics through integration with Amazon Recognition Video, and libraries for ML frameworks such as Apache MxNet, TensorFlow, and OpenCV.

## Amazon Redshift


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/hiutpiufatxhexhsu7cy.png)
 
* Amazon Redshift is a fast, scalable data warehouse that makes it simple and cost-effective to analyze all your data across your data warehouse and data lake. Redshift delivers ten times faster performance than other data warehouses by using machine learning, massively parallel query execution, and columnar storage on high-performance disk. 

* You can setup and deploy a new data warehouse in minutes, and run queries across petabytes of data in your Redshift data warehouse, and exabytes of data in your data lake built on Amazon S3. You can start small for just $0.25 per hour and scale to $250 per terabyte per year, less than one-tenth the cost of other solutions.

# Amazon QuickSight


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/igv4cb2ei5ag1trye5ef.png)
 
* Amazon QuickSight is a fast, cloud-powered business intelligence (BI) service that makes it easy for you to deliver insights to everyone in your organization. QuickSight lets you create and publish interactive dashboards that can be accessed from browsers or mobile devices. 

* You can embed dashboards into your applications, providing your customers with powerful self-service analytics. QuickSight easily scales to tens of thousands of users without any software to install, servers to deploy, or infrastructure to manage.

## AWS Data Pipeline


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/l1ad84y0vvfxa5n1xb3h.png)
 
* AWS Data Pipeline is a web service that helps you reliably process and move data between diﬀerent AWS compute and storage services, as well as on-premises data sources, at speciﬁed intervals. 

* With AWS Data Pipeline, you can regularly access your data where it’s stored, transform and process it at scale, and eﬃciently transfer the results to AWS services such as Amazon S3, Amazon RDS, Amazon DynamoDB, and Amazon EMR.

* AWS Data Pipeline helps you easily create complex data processing workloads that are fault tolerant, repeatable, and highly available. 

* You don’t have to worry about ensuring resource availability, managing inter-task dependencies, retrying transient failures or timeouts in individual tasks, or creating a failure notification system. AWS Data Pipeline also allows you to move and process data that was previously locked up in on-premises data silos.

## AWS Glue


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/8jkwxj5mb3a876neksih.png)
 

* AWS Glue is a fully managed extract, transform, and load (ETL) service that makes it easy for customers to prepare and load their data for analytics. You can create and run an ETL job with a few clicks in the AWS Management Console. 

* You simply point AWS Glue to your data stored on AWS, and AWS Glue discovers your data and stores the associated metadata (e.g. table definition and schema) in the AWS Glue Data Catalog. Once cataloged, your data is immediately searchable, queryable, and available for ETL.

## AWS Lake Formation


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/0lor1g58vhqttk383wbz.png)
 
* AWS Lake Formation is a service that makes it easy to set up a secure data lake in days. A data lake is a centralized, curated, and secured repository that stores all your data, both in its original form and prepared for analysis. 

* A data lake enables you to break down data silos and combine different types of analytics to gain insights and guide better business decisions.

* However, setting up and managing data lakes today involves a lot of manual, complicated, and time-consuming tasks. This work includes loading data from diverse sources, monitoring those data flows, setting up partitions, turning on encryption and managing keys, defining transformation jobs and monitoring their operation, re-organizing data into a columnar format, configuring access control settings, deduplicating redundant data, matching linked records, granting access to data sets, and auditing access over time.

* Creating a data lake with Lake Formation is as simple as defining where your data resides and what data access and security policies you want to apply. 

* Lake Formation then collects and catalogs data from databases and object storage, moves the data into your new Amazon S3 data lake, cleans and classifies data using machine learning algorithms, and secures access to your sensitive data. 

* Your users can then access a centralized catalog of data which describes available data sets and their appropriate usage. Your users then leverage these data sets with their choice of analytics and machine learning services, like Amazon EMR for Apache Spark, Amazon Redshift, Amazon Athena, SageMaker, and Amazon QuickSight.

## Amazon Managed Streaming for Apache Kafka (Amazon MSK)


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/desbyzwcnnqx2lwkagst.png)
 

* Amazon Managed Streaming for Apache Kafka (Amazon MSK) is a fully managed service that makes it easy for you to build and run applications that use Apache Kafka to process streaming data.

* Apache Kafka is an open-source platform for building real-time streaming data pipelines and applications. With Amazon MSK, you can use Apache Kafka APIs to populate data lakes, stream changes to and from databases, and power machine learning and analytics applications.

* Apache Kafka clusters are challenging to setup, scale, and manage in production. When you run Apache Kafka on your own, you need to provision servers, configure Apache Kafka manually, replace servers when they fail, orchestrate server patches and upgrades, architect the cluster for high availability, ensure data is durably stored and secured, setup monitoring and alarms, and carefully plan scaling events to support load changes. 

* Amazon MSK makes it easy for you to build and run production applications on Apache Kafka without needing Apache Kafka infrastructure management expertise. That means you spend less time managing infrastructure and more time building applications.

* With a few clicks in the Amazon MSK console you can create highly available Apache Kafka clusters with settings and configuration based on Apache Kafka’s deployment best practices.

* Amazon MSK automatically provisions and runs your Apache Kafka clusters. Amazon MSK continuously monitors cluster health and automatically replaces unhealthy nodes with no downtime to your application. In addition, Amazon MSK secures your Apache Kafka cluster by encrypting data at rest.

# Conclusion

* AWS provides the broadest selection of analytics services that fit all your data analytics needs and enables organizations of all sizes and industries to reinvent their business with data. 

* From data movement, data storage, data lakes, big data analytics, and machine learning (ML) to anything in between, AWS offers purpose-built services that provide the best price performance, scalability, and lowest cost.

Hope this guide helps you with the Introduction to Data (Databases, Analytics, Blockchain) with AWS  Part - 1. In the Next Blog Post, we will discuss more about Different Database and Blockchain Services that are available with AWS.

Let me know your thoughts in the comment section 👇
And if you haven't yet, make sure to follow me on below handles:

👋 **connect with me on [LinkedIn](https://www.linkedin.com/in/adit-modi-2a4362191/)**
🤓 **connect with me on [Twitter](https://twitter.com/adi_12_modi)**
🐱‍💻 **follow me on [github](https://github.com/AditModi)**
✍️ **Do Checkout [my blogs](https://aditmodi.hashnode.dev)** 

Like, share and follow me 🚀 for more content.

{% user aditmodi %}