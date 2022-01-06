**The serverless computing model** allows you to build and run applications and services without having to worry about infrastructure or servers. It eliminates infrastructure management tasks such as server provisioning, patching, operating system maintenance, scaling, and capacity provisioning. 

In this blogpost, I would like to give you an overview of some fully-managed serverless services provided by Amazon Web Services (AWS), which can be used to create fully cloud-native serverless applications.

Building native serverless applications means that developers can focus on the **core product** and on **innovating applications and solutions**, rather than spending a lot of time on setting up and maintaining infrastructure. This results in many benefits such as faster development, simplified operational management, scaling, and reduction in operational costs. Take a look at my last blogpost to get an impression on serverless architectures and how they impact the development process and the project business.

But how can we actually implement these serverless applications? What tools and services should I use to create a highly-available, scalable and performant backend solution? How can I benefit from managed infrastructure, variable operational costs that scale with my business? How can I increase speed and agility in my development process?

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/hvpqein4enwo53ft7geo.png)
 


*My Background: I am Cloud , DevOps & Big Data Enthusiast | 4x AWS Certified | 3x OCI Certified | 3x Azure Certified .* 

The Introduction to AWS is a Series containing different articles that provide a basic introduction to different aws topics/categories. Each article covers the detailed guide on how to work with particular topic/category . This series aims at providing "A Getting Started Guide on Different aws topics / categories ."


AWS provides a wide range of different cloud services (>165) which cover all aspects and requirements of backend solutions, like compute resources, different storage types, purpose-built databases, security services for authentication and encryption, big data stream processing, machine learning, messaging and monitoring services, and many more.

These services are tightly integrated with each other and provide a convenient way to build your application in a flexible and powerful way. This blogpost will give you an overview of the most important serverless services of AWS. 

An overview of serverless AWS services
![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/c203zd5t2tg8t8hxhs4w.png)
 
 

Compute provides you with the execution environment for your application code.

[**With AWS Lambda**](https://aws.amazon.com/lambda/), you can execute code as a function triggered by various event sources like, e.g., HTTP requests on AWS API Gateway, file updates on S3, or metric alarms in AWS Cloudwatch. Lambda is the FaaS solution from AWS where you can run code for any type of application or backend service. It runs the code on a fully-managed, high-available infrastructure and performs all administration tasks of the compute resources, including server and system maintenance, capacity provisioning and automatic scaling, code monitoring and logging. You pay only for the compute time your application actually consumes. Lambda can be combined with many other AWS services and is used in many scenarios, like authorizing a HTTP request by validating a JSON web token, real-time filtering and transforming streaming data, processing data in S3, managing database handling, and many more.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/hwceran5uneaz0pumash.png)
 

[**With AWS Fargate**](https://aws.amazon.com/fargate/), you can run docker containers without any management of servers or clusters. It is a container orchestration solution that makes it easy to deploy, manage, and scale containerized applications. You don’t need to define EC2 instance types, manage cluster scheduling, optimize server utilization, or define cloud watch metrics to scale the instances. Fargate manages the infrastructure needed to run your containers in a highly-available manner. To launch your application, you need to package your containers, specify CPU and memory requirements, and define networking and IAM policies.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/g0e5lbkv748iy4o0p62g.png)
 

## Messaging


 
[**AWS Simple Notification Service (SNS)**](https://aws.amazon.com/sns/) is a fully-managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications.

You can send notifications between various services, applications, devices and platforms over multiple transport protocols. SNS allows you to publish messages from one application to a large number of subscribers for parallel processing. Besides push notifications to mobile devices, you can deliver notifications by email, SMS, SQS, Lambda, or to any HTTP endpoint.

[**Amazon Simple Queue Service (SQS)**](https://aws.amazon.com/sqs/) is a fully-managed distributed message queueing service that enables you to decouple and scale microservice distributed systems and serverless applications. You can send, receive and cache messages between software components to resolve issues introduced by the producer-consumer problem. SQS offers two types of message queues: Standard queues have maximum throughput, best-effort ordering, and at-least-once delivery. Additionally, you can use FIFO queues, which guarantee exactly-once message delivery with strict order.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/mrzonqlyon7785xhgvuu.png)

## Integration

[**Amazon API Gateway**](https://aws.amazon.com/api-gateway/) is a fully-managed service for creating, publishing, maintaining, monitoring, and securing REST and WebSocket APIs at any scale. It handles the processing of up to hundreds of thousands concurrent API calls, including traffic management, authorization, access control, and API version management. You can create your API within the management console UI and access data, business logic, or functionality from your backend services, such as workloads running on EC2 or code running in a Lambda function. You pay only for the API calls you receive and for the amount of outgoing data, transmitted by AWS.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kycb7vn7qec37ztljgs9.png)
 

[**With AWS Step Functions**](https://aws.amazon.com/step-functions/), you can orchestrate the components of your application as a series of steps to create complex serverless workflows using Lambda functions. The workflow is modeled as a state machine diagram, where each state represents a component of the application. Using a graphical viewer, you can visualize these components and check the execution flow in real time. All steps are automatically triggered, tracked and retried in case of errors, so that the application executes in order and as expected.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/sn035wgssqedzkoc0ks5.png)
 

## Security

[**Amazon Cognito**](https://aws.amazon.com/cognito/) is a fully-managed, scalable, and cost-effective sign-up/sign-in service, which provides user authentication, authorization, and management for web and mobile applications. The two main components of Amazon Cognito are user pools and identity pools. A user pool is a user directory, which provides sign-up and sign-in services, based on its own or an external identity provider that implements the SAML, OAuth2, or OpenID Connect protocol, like Facebook or Google. You can use a customizable web UI for the user sign-in, which can be integrated in your existing webpage. With an identity pool, your authorized user or anonymous guest can exchange user pool tokens for temporary AWS credentials to access AWS resources. Based on IAM role policies, you can grant your users or groups fine-grained access to your resources or AWS services. Cognito has advanced security features, such as e-mail, phone verification, and multi-factor authentication.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5quvwkwv76exxx1vwee0.png)
 

[**AWS Key Management Service (KMS)**](https://aws.amazon.com/kms/) is a fully-managed service which allows you to create and manage your security keys and control the use of encryption across a wide range of AWS services and in your applications. KMS is integrated with many AWS services to simplify encryption handling across your application. It enables developers to easily add encryption functionality to the application, either directly through the service APIs or with the AWS Encryption SDK. Customer master keys (CMK) are used to control access to data encryption keys that encrypt and decrypt the data. You can provide and manage your own CMK including your custom cryptographic material or using a CMK provided and managed by AWS. 

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9b51zh3cxweazt7damji.png)
 

[**With AWS CloudHSM**](https://aws.amazon.com/cloudhsm/) you can additionally use a cloud-based hardware security module (HSM) that enables you to easily generate and use your own encryption keys on the AWS Cloud. The encryption keys that you generate and use with CloudHSM are accessible only by the HSM users that you specify. AWS has no visibility or access to your encryption keys.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/or6fk33k9vrvor7swsz1.png)
 

## Monitoring

[**AWS CloudWatch**](https://aws.amazon.com/cloudwatch/) is a monitoring and management service for AWS resources and custom applications. CloudWatch enables you to collect metrics and logs from all your AWS resources, applications, and services that run on AWS and on-premises servers. It provides real-time monitoring and visibility into resource utilization of your EC2 instances, your applications’ performance, and operational health. CloudWatch is natively integrated with many AWS services that can publish detailed metrics with up to 1 second granularity. Additionally, you can define alarms based on CloudWatch metrics and perform actions based on its value. You can, e.g., set a threshold on a key utilization metrics and trigger an automated auto scaling action to add or remove EC2 instances.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ov61p7hwbr6z4umzv890.png)
 

[**AWS Quicksight**](https://aws.amazon.com/quicksight/) is a fully-managed business intelligence service, which allows you to create visualisations of data and to design interactive dashboards for application analysis. These dashboards can be accessed from any mobile device or browser. You can embed them into your applications, portals or websites, providing you with powerful self-service analytics. QuickSight allows you to connect to and import data from a wide variety of cloud or on-premises data sources and scales to tens of thousands of users without any infrastructure to manage.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/3mrxyl7k798r4qiatcsk.png)
 

## Database

[**Amazon DynamoDB**](https://aws.amazon.com/dynamodb/) is a NoSQL database service which supports key-value pairs and document data structures. As it is a fully-managed service, you don’t have to worry about hardware provisioning, setup and configuration, replication, backups, software patching, or cluster scaling. It provides features like high availability and durability, automatic and infinite read-write I/O scaling, on demand backup with point-in-time recovery, encryption at rest, and single-digit millisecond latency. With its pay-per-use pricing model and integration with many other AWS services, DynamoDB is a great database service for many serverless application on AWS.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/yi1gg5sn8a4j9l6ejmqz.png)
 

[**Amazon Aurora**](https://aws.amazon.com/rds/aurora/) is a fully-managed relational database engine that’s compatible with MySQL and PostgreSQL. It automates and standardizes database clustering and replication to remove time-consuming administration tasks, like hardware provisioning, storage autoscaling, database setup, patching, and backups. Aurora is also available as an on-demand configuration, called Aurora Serverless, with autoscaling for compute capacity, which is a cost-effective way to support infrequent and unpredictable workloads.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/racs5myh1gzb9n0b1w00.png)
 
 
## Analytics

[**Amazon Kinesis**](https://aws.amazon.com/kinesis/) is a is fully-managed and highly scalable streaming service to collect, process, and analyze real-time streaming data, such as website clickstreams, database event streams, financial transactions, social media feeds, application logs, IoT telemetry data, or location-tracking events. It enables you to process and analyze data as it arrives and to respond instantly, so that you can create real-time applications. Amazon Kinesis consists of 3 services, which can be used to process the streaming data. **With Amazon Kinesis Data Streams**, you can ingest and store large data streams in real-time without managing the infrastructure, storage, networking, and configuration. Applications can consume data from a stream, so that multiple actions, like data analysis, archiving, or processing, can take place concurrently and independently. **Amazon Kinesis Data Firehose** can be used to load streaming data into data lakes (Amazon Redshift), data stores (S3), and analytics tools (Amazon Elasticsearch). It allows you to to capture, transform, and load (ETL) streaming data in real-time from many data sources simultaneously and send it automatically to the specified destination. **With Amazon Kinesis Data Analytics** you can filter, aggregate, and transform streaming data for advanced analytics. You can run standard SQL queries against streaming data to perform time series analytics, provide data to real-time dashboards, and extract metrics.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xrb43or6xwscgoyfvq7s.png)
 

[**Amazon Athena**](https://www.amazonaws.cn/en/athena/) is a query service which provides a standard SQL language to analyze large-scale datasets in AWS Simple Storage Service (S3). There is no infrastructure to manage, and you pay only for the executed queries. Athena scales automatically by executing queries in parallel. This makes it simple to do ad-hoc analysis or more complex analysis that contain large joins.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/najg3g9bk3ypns8dxl1e.png)
 

## Conclusion

AWS provides many services which can be used as building blocks to create cloud infrastructures for virtually any workload. Solution architects and developers have a huge range of tools and services to design and implement backend applications in a very effective way with great flexibility. 

Most services provided by AWS are fully-managed and can be used without time-consuming administrative tasks, infrastructure provisioning or server maintenance. Developers can focus on creating their core applications, which increases development speed and business growth. Important aspects like high availability, automatic scalability, security, and durability are built in. 

This is a huge advantage compared to using open-source services hosted on manually provisioned server infrastructures. With the pay-as-you-go pricing model you have no upfront costs or long-term contracts and pay only for the consumed resources, which makes serverless architectures very cost effective.

Hope this guide helps you with the Introduction to Serverless with AWS, feel free to connect with me on [LinkedIn.](https://www.linkedin.com/in/adit-modi-2a4362191/)
You can view my badges [here.](https://www.youracclaim.com/users/adit-modi/badges)
If you are interested in learning more about AWS then follow me on [github.](https://github.com/AditModi)
If you liked this content then do clap and share it . Thank You .