Organizations across the globe face considerable pressure to innovate digitally to remain competitive. One of the key areas that many organizations have identified as a source of opportunity to improve their pace of innovation is their software development and operations, or Developing Machine Learning Applications.

* In this blog post, we will discuss some of the most important AWS machine learning services that helps customers solve real-world business problems in any industry. Use ready-made, purpose-built AI services or your own models with AWS ML services. This services helps you address common business problems to improve customer experience, optimize business processes, and accelerate innovation. 

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/wcgozxydp1vrowgjlfqg.png)

> **The Introduction to AWS** is a Series containing different articles that provide a basic introduction to different aws topics/categories. Each article covers the detailed guide on how to work with particular topic/category . This series aims at providing "A Getting Started Guide on Different aws topics / categories ."

# AWS Machine Learning Services

* AWS helps customers use ML to accurately forecast sales, financial, and demand data, and automatically identify anomalies and their root cause.
* AWS helps detect and prevent online fraud, such as fake accounts and payment fraud in real-time using ML.
* AWS helps build fast and innovate more with Next Gen DevOps.


# Amazon Augmented AI

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/r6kne22qsgtl9ld0exbw.png)
 
* Amazon Augmented AI (Amazon A2I) is a machine learning service which makes it easy to build the workflows required for human review. 
* Amazon A2I brings human review to all developers, removing the undifferentiated heavy lifting associated with building human review systems or managing large numbers of human reviewers whether it runs on AWS or not.

# Amazon CodeGuru

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ji9hk9e33r7bptapw56o.png)
 
* Amazon CodeGuru is a developer tool that provides intelligent recommendations to improve code quality and identify an application’s most expensive lines of code. 
* Integrate CodeGuru into your existing software development workflow to automate code reviews during application development and continuously monitor application's performance in production and provide recommendations and visual clues on how to improve code quality, application performance, and reduce overall cost.

* CodeGuru Reviewer uses machine learning and automated reasoning to identify critical issues, security vulnerabilities, and hard-to-find bugs during application development and provides recommendations to improve code quality.

* CodeGuru Profiler helps developers find an application’s most expensive lines of code by helping them understand the runtime behavior of their applications, identify and remove code inefficiencies, improve performance, and significantly decrease compute costs.

# Amazon DevOps Guru

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/katzocvngg6arrg9e0g6.png)
 
* Amazon DevOps Guru is a Machine Learning (ML) powered service that makes it easy to improve an application’s operational performance and availability. DevOps Guru detects behaviors that deviate from normal operating patterns so you can identify operational issues long before they impact your customers.

* DevOps Guru uses machine learning models informed by years of Amazon.com and AWS operational excellence to identify anomalous application behavior (e.g. increased latency, error rates, resource constraints, etc.) and surface critical issues that could cause potential outages or service disruptions. 
* When DevOps Guru identifies a critical issue, it automatically sends an alert and provides a summary of related anomalies, the likely root cause, and context about when and where the issue occurred. When possible DevOps Guru, also provides recommendations on how to remediate the issue.

* DevOps Guru automatically ingests operational data from your AWS applications and provides a single dashboard to visualize issues in your operational data. 
* You can get started with DevOps Guru by selecting coverage from your CloudFormation stacks or your AWS account to improve application availability and reliability with no manual setup or machine learning expertise.

# Amazon Elastic Inference

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ui0eud2581zszgk5ctpk.png)
 
* Amazon Elastic Inference allows you to attach low-cost GPU-powered acceleration to Amazon EC2 and Amazon SageMaker instances to reduce the cost of running deep learning inference by up to 75%. Amazon Elastic Inference supports TensorFlow, Apache MXNet, PyTorch, and ONNX models.

* In most deep learning applications, making predictions using a trained model—a process called inference—can drive as much as 90% of the compute costs of the application due to two factors. First, standalone GPU instances are designed for model training and are typically oversized for inference. 
* While training jobs batch process hundreds of data samples in parallel, most inference happens on a single input in real time that consumes only a small amount of GPU compute. 
* Even at peak load, a GPU's compute capacity may not be fully utilized, which is wasteful and costly. Second, different models need different amounts of GPU, CPU, and memory resources.  
* Selecting a GPU instance type that is big enough to satisfy the requirements of the least used resource often results in under-utilization of the other resources and high costs.

* Amazon Elastic Inference solves these problems by allowing you to attach just the right amount of GPU-powered inference acceleration to any EC2 or SageMaker instance type with no code changes. 
* With Amazon Elastic Inference, you can now choose the instance type that is best suited to the overall CPU and memory needs of your application, and then separately configure the amount of inference acceleration that you need to use resources efficiently and to reduce the cost of running inference.

# Amazon Fraud Detector

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rwfikjpmlv5xk2xl5nb9.png)
 
* Amazon Fraud Detector is a fully managed service that uses machine learning (ML) and more than 20 years of fraud detection expertise from Amazon, to identify potentially fraudulent activity so customers can catch more online fraud faster. 
* Amazon Fraud Detector automates the time consuming and expensive steps to build, train, and deploy an ML model for fraud detection, making it easier for customers to leverage the technology. 
* Amazon Fraud Detector customizes each model it creates to a customer’s own dataset, making the accuracy of models higher than current one-size fits all ML solutions. And, because you pay only for what you use, you avoid large upfront expenses.

# Amazon HealthLake

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/15zrcw18500sx16mtcv9.png)
 
* Amazon HealthLake is a HIPAA-eligible service that healthcare providers, health insurance companies, and pharmaceutical companies can use to store, transform, query, and analyze large-scale health data.

* Health data is frequently incomplete and inconsistent. It's also often unstructured, with information contained in clinical notes, lab reports, insurance claims, medical images, recorded conversations, and time-series data (for example, heart ECG or brain EEG traces).

* Healthcare providers can use HealthLake to store, transform, query, and analyze data in the AWS Cloud. Using the HealthLake integrated medical natural language processing (NLP) capabilities, you can analyze unstructured clinical text from diverse sources. 
* HealthLake transforms unstructured data using natural language processing models, and provides powerful query and search capabilities. You can use HealthLake to organize, index, and structure patient information in a secure, compliant, and auditable manner.



# Amazon Kendra

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/f5qh7i3vro4diea5hmox.png)
 
* Amazon Kendra is an intelligent search service powered by machine learning. Kendra reimagines enterprise search for your websites and applications so your employees and customers can easily find the content they are looking for, even when it’s scattered across multiple locations and content repositories within your organization.

* Using Amazon Kendra, you can stop searching through troves of unstructured data and discover the right answers to your questions, when you need them. Amazon Kendra is a fully managed service, so there are no servers to provision, and no machine learning models to build, train, or deploy.

# Amazon Lookout for Equipment

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/yuuh4t0g5qe3mqb9vyq1.png)
 
* Amazon Lookout for Equipment analyzes the data from the sensors on your equipment (e.g. pressure in a generator, flow rate of a compressor, revolutions per minute of fans), to automatically train a machine learning model based on just your data, for your equipment – with no ML expertise required. 
* Lookout for Equipment uses your unique ML model to analyze incoming sensor data in real-time and accurately identify early warning signs that could lead to machine failures. This means you can detect equipment abnormalities with speed and precision, quickly diagnose issues, take action to reduce expensive downtime, and reduce false alerts.

# Amazon Lookout for Metrics

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/odf69rbolwvhha7mxq8c.png)
 
* Amazon Lookout for Metrics uses machine learning (ML) to automatically detect and diagnose anomalies (i.e. outliers from the norm) in business and operational data, such as a sudden dip in sales revenue or customer acquisition rates. 
* In a couple of clicks, you can connect Amazon Lookout for Metrics to popular data stores like Amazon S3, Amazon Redshift, and Amazon Relational Database Service (RDS), as well as third-party SaaS applications, such as Salesforce, Servicenow, Zendesk, and Marketo, and start monitoring metrics that are important to your business. 
* Amazon Lookout for Metrics automatically inspects and prepares the data from these sources to detect anomalies with greater speed and accuracy than traditional methods used for anomaly detection. You can also provide feedback on detected anomalies to tune the results and improve accuracy over time. 
* Amazon Lookout for Metrics makes it easy to diagnose detected anomalies by grouping together anomalies that are related to the same event and sending an alert that includes a summary of the potential root cause. It also ranks anomalies in order of severity so that you can prioritize your attention to what matters the most to your business.

# Amazon Lookout for Vision

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9y6mlx1qnz6fik9zs6e4.png)
 
* Amazon Lookout for Vision is a machine learning (ML) service that spots defects and anomalies in visual representations using computer vision (CV). With Amazon Lookout for Vision, manufacturing companies can increase quality and reduce operational costs by quickly identifying differences in images of objects at scale. 
* For example, Amazon Lookout for Vision can be used to identify missing components in products, damage to vehicles or structures, irregularities in production lines, miniscule defects in silicon wafers, and other similar problems. 
* Amazon Lookout for Vision uses ML to see and understand images from any camera as a person would, but with an even higher degree of accuracy and at a much larger scale. 
* Amazon Lookout for Vision allows customers to eliminate the need for costly and inconsistent manual inspection, while improving quality control, defect and damage assessment, and compliance. 
* In minutes, you can begin using Amazon Lookout for Vision to automate inspection of images and objects–with no machine learning expertise required.

# Amazon Monitron

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/sks28htpz6nhwvks2f6m.png)
 
* Amazon Monitron is an end-to-end system that uses machine learning (ML) to detect abnormal behavior in industrial machinery, enabling you to implement predictive maintenance and reduce unplanned downtime.

* Installing sensors and the necessary infrastructure for data connectivity, storage, analytics, and alerting are foundational elements for enabling predictive maintenance. However, in order to make it work, companies have historically needed skilled technicians and data scientists to piece together a complex solution from scratch. 
* This included identifying and procuring the right type of sensors for their use cases and connecting them together with an IoT gateway (a device that aggregates and transmits data). As a result, few companies have been able to successfully implement predictive maintenance.

* Amazon Monitron includes sensors to capture vibration and temperature data from equipment, a gateway device to securely transfer data to AWS, the Amazon Monitron service that analyzes the data for abnormal machine patterns using machine learning, and a companion mobile app to set up the devices and receive reports on operating behavior and alerts to potential failures in your machinery. 
* You can start monitoring equipment health in minutes without any development work or ML experience required, and enable predictive maintenance with the same technology used to monitor equipment in Amazon Fulfillment Centers.

---

Hope this guide helps you with the Introduction to Machine Learning with AWS - Part-2. In the Next Blog Post, we will discuss more about remaining Machine learning Services that are available with AWS.

Let me know your thoughts in the comment section 👇
And if you haven't yet, make sure to follow me on below handles:

👋 **connect with me on [LinkedIn](https://www.linkedin.com/in/adit-modi-2a4362191/)**
🤓 **connect with me on [Twitter](https://twitter.com/adi_12_modi)**
🐱‍💻 **follow me on [github](https://github.com/AditModi)**
✍️ **Do Checkout [my blogs](https://aditmodi.hashnode.dev)** 

Like, share and follow me 🚀 for more content.

{% user aditmodi %}
