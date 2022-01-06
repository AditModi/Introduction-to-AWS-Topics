With AWS, customers can enable, provision, and operate their environment for both business agility and governance control. AWS provides services for end-to-end IT lifecycle management, helping customers control and secure their environments, reduce costs, simplify compliance, and enhance operational efficiency.

In this Blog Post, we will talk about AWS Management and Governance services. AWS Management and Governance services are built to manage highly dynamic cloud resources at massive scale. 

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xgsyhswelcds85rbsp1t.png)

> **The Introduction to AWS** is a Series containing different articles that provide a basic introduction to different aws topics/categories. Each article covers the detailed guide on how to work with particular topic/category . This series aims at providing "A Getting Started Guide on Different aws topics / categories ."

# AWS Management and Governance Services

* Customers can use AWS Management and Governance services to assess their resource utilization and identify ways to reduce costs.
* AWS reduces complexity, offering a single control plane for customers to manage and govern their resources on AWS and on-premises.
* AWS offers the broadest partner ecosystem for customers to extend and augment their management and governance system.

* **Usecases**:
 * Establish a centrally managed, secure, multi-account AWS environment.
 * Manage your operations on AWS and on-premises.
 * Audit and remediate your resource configurations.
 * Improve the health of infrastructure and applications.
 * Build, provision, and share AWS and third-party resources.
 * Transform your business with cost transparency, forecasting, and optimization.

## Amazon CloudWatch

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/q3uhgrb4anlef7k0te8k.png)
 
* Amazon CloudWatch is a monitoring and management service built for developers, system operators, site reliability engineers (SRE), and IT managers. 
* CloudWatch provides you with data and actionable insights to monitor your applications, understand and respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. 
* CloudWatch collects monitoring and operational data in the form of logs, metrics, and events, providing you with a unified view of AWS resources, applications and services that run on AWS, and on-premises servers. 
* You can use CloudWatch to set high resolution alarms, visualize logs and metrics side by side, take automated actions, troubleshoot issues, and discover insights to optimize your applications, and ensure they are running smoothly.

## AWS Auto Scaling

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/pnebrakm3eyi892j7b93.png)
 
* AWS Auto Scaling monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. 
* Using AWS Auto Scaling, it’s easy to setup application scaling for multiple resources across multiple services in minutes. The service provides a simple, powerful user interface that lets you build scaling plans for resources including Amazon EC2 instances and Spot Fleets, Amazon ECS tasks, Amazon DynamoDB tables and indexes, and Amazon Aurora Replicas. 
* AWS Auto Scaling makes scaling simple with recommendations that allow you to optimize performance, costs, or balance between them. If you’re already using Amazon EC2 Auto Scaling to dynamically scale your Amazon EC2 instances, you can now combine it with AWS Auto Scaling to scale additional resources for other AWS services. With AWS Auto Scaling, your applications always have the right resources at the right time.

## AWS Control Tower

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/t792nbhm49i790wb6ck1.png)
 
* AWS Control Tower automates the set-up of a baseline environment, or landing zone, that is a secure, well-architected multi-account AWS environment. 
* The configuration of the landing zone is based on best practices that have been established by working with thousands of enterprise customers to create a secure environment that makes it easier to govern AWS workloads with rules for security, operations, and compliance.

* As enterprises migrate to AWS, they typically have a large number of applications and distributed teams. They often want to create multiple accounts to allow their teams to work independently, while still maintaining a consistent level of security and compliance. 
* In addition, they use AWS’s management and security services, like AWS Organizations, AWS Service Catalog and AWS Config, that provide very granular controls over their workloads. 
* They want to maintain this control, but they also want a way to centrally govern and enforce the best use of AWS services across all the accounts in their environment.

* Control Tower automates the set-up of their landing zone and configures AWS management and security services based on established best practices in a secure, compliant, multi-account environment. 
* Distributed teams are able to provision new AWS accounts quickly, while central teams have the peace of mind knowing that new accounts are aligned with centrally established, company-wide compliance policies. 
* This gives you control over your environment, without sacrificing the speed and agility AWS provides your development teams.

## AWS Systems Manager

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/m22z3rkcy6hox43qgvbj.png)
 
* AWS Systems Manager gives you visibility and control of your infrastructure on AWS. Systems Manager provides a unified user interface so you can view operational data from multiple AWS services and allows you to automate operational tasks across your AWS resources. 
* With Systems Manager, you can group resources, like Amazon EC2 instances, Amazon S3 buckets, or Amazon RDS instances, by application, view operational data for monitoring and troubleshooting, and take action on your groups of resources. 
* Systems Manager simplifies resource and application management, shortens the time to detect and resolve operational problems, and makes it easy to operate and manage your infrastructure securely at scale.

## AWS Systems Manager contains the following tools:

 * **Resource groups:** Lets you create a logical group of resources associated with a particular workload such as different layers of an application stack, or production versus development environments. For example, you can group different layers of an application, such as the frontend web layer and the backend data layer. Resource groups can be created, updated, or removed programmatically through the API.

 * **Insights Dashboard:** Displays operational data that the AWS Systems Manager automatically aggregates for each resource group. Systems Manager eliminates the need for you to navigate across multiple AWS consoles to view your operational data. With Systems Manager you can view API call logs from AWS CloudTrail, resource configuration changes from AWS Config, software inventory, and patch compliance status by resource group. You can also easily integrate your Amazon CloudWatch Dashboards, AWS Trusted Advisor notifications, and AWS Personal Health Dashboard performance and availability alerts into your Systems Manager dashboard. Systems Manager centralizes all relevant operational data, so you can have a clear view of your infrastructure compliance and performance.

 * **Run Command:** Provides a simple way of automating common administrative tasks like remotely executing shell scripts or PowerShell commands, installing software updates, or making changes to the configuration of OS, software, EC2 and instances and servers in your on-premises data center.

 * **State Manager:** Helps you define and maintain consistent OS configurations such as firewall settings and anti-malware definitions to comply with your policies. You can monitor the configuration of a large set of instances, specify a configuration policy for the instances, and automatically apply updates or configuration changes.

 * **Inventory:** Helps you collect and query configuration and inventory information about your instances and the software installed on them. You can gather details about your instances such as installed applications, DHCP settings, agent detail, and custom items. You can run queries to track and audit your system configurations.

 * **Maintenance Window:** Lets you define a recurring window of time to run administrative and maintenance tasks across your instances. This ensures that installing patches and updates, or making other configuration changes does not disrupt business-critical operations. This helps improve your application availability.

 * **Patch Manager:** Helps you select and deploy operating system and software patches automatically across large groups of instances. You can define a maintenance window so that patches are applied only during set times that fit your needs. These capabilities help ensure that your software is always up to date and meets your compliance policies.

 * **Automation:** Simplifies common maintenance and deployment tasks, such as updating Amazon Machine Images (AMIs). Use the Automation feature to apply patches, update drivers and agents, or bake applications into your AMI using a streamlined, repeatable, and auditable process.

 * **Parameter Store:** Provides an encrypted location to store important administrative information such as passwords and database strings. The Parameter Store integrates with AWS KMS to make it easy to encrypt the information you keep in the Parameter Store.

 * **Distributor:** Helps you securely distribute and install software packages, such as software agents. Systems Manager Distributor allows you to centrally store and systematically distribute software packages while you maintain control over versioning. You can use Distributor to create and distribute software packages and then install them using Systems Manager Run Command and State Manager. Distributor can also use AWS Identity and Access Management (IAM) policies to control who can create or update packages in your account. You can use the existing IAM policy support for Systems Manager Run Command and State Manager to define who can install packages on your hosts.

 * **Session Manager:** Provides a browser-based interactive shell and CLI for managing Windows and Linux EC2 instances, without the need to open inbound ports, manage SSH keys, or use bastion hosts. Administrators can grant and revoke access to instances through a central location by using AWS Identity and Access Management (IAM) policies. This allows you to control which users can access each instance, including the option to provide non-root access to specified users. Once access is provided, you can audit which user accessed an instance and log each command to Amazon S3 or Amazon CloudWatch Logs using AWS CloudTrail.

## AWS CloudFormation

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/i21ry7vmlai7pdvakwik.png)
 
* AWS CloudFormation gives developers and systems administrators an easy way to create and manage a collection of related AWS resources, provisioning and updating them in an orderly and predictable fashion.

* You can use the AWS CloudFormation sample templates or create your own templates to describe your AWS resources, and any associated dependencies or runtime parameters, required to run your application. 
* You don’t need to figure out the order for provisioning AWS services or the subtleties of making those dependencies work. CloudFormation takes care of this for you. 
* After the AWS resources are deployed, you can modify and update them in a controlled and predictable way, in effect applying version control to your AWS infrastructure the same way you do with your software. 
* You can also visualize your templates as diagrams and edit them using a drag-and-drop interface with the AWS CloudFormation Designer.

## AWS CloudTrail

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/id6koxoom9dykih0na7q.png)
 
* AWS CloudTrail is a web service that records AWS API calls for your account and delivers log files to you. The recorded information includes the identity of the API caller, the time of the API call, the source IP address of the API caller, the request parameters, and the response elements returned by the AWS service.

* With CloudTrail, you can get a history of AWS API calls for your account, including API calls made using the AWS Management Console, AWS SDKs, command line tools, and higher-level AWS services (such as AWS CloudFormation). 
* The AWS API call history produced by CloudTrail enables security analysis, resource change tracking, and compliance auditing.

## AWS Config

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ue3t7zm90mq9vnthyru9.png)
 
* AWS Config is a fully managed service that provides you with an AWS resource inventory, configuration history, and configuration change notifications to enable security and governance. The Config Rules feature enables you to create rules that automatically check the configuration of AWS resources recorded by AWS Config.

* With AWS Config, you can discover existing and deleted AWS resources, determine your overall compliance against rules, and dive into configuration details of a resource at any point in time. These capabilities enable compliance auditing, security analysis, resource change tracking, and troubleshooting.

## AWS OpsWorks

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/uc186g9kow9a9hrruc11.png)
 
* AWS OpsWorks is a configuration management service that provides managed instances of Chef and Puppet. Chef and Puppet are automation platforms that allow you to use code to automate the configurations of your servers. 
* OpsWorks lets you use Chef and Puppet to automate how servers are configured, deployed, and managed across your Amazon EC2 instances or on-premises compute environments. 
* OpsWorks has three offerings, AWS OpsWorks for Chef Automate, AWS OpsWorks for Puppet Enterprise, and AWS OpsWorks Stacks.

## AWS Service Catalog

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/471ifkcoh5oced1uruvh.png)
 
* AWS Service Catalog allows organizations to create and manage catalogs of IT services that are approved for use on AWS. These IT services can include everything from virtual machine images, servers, software, and databases to complete multi-tier application architectures. 
* AWS Service Catalog allows you to centrally manage commonly deployed IT services and helps you achieve consistent governance and meet your compliance requirements, while enabling users to quickly deploy only the approved IT services they need.

## AWS Trusted Advisor

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/l4e8h760fpigw6vbtczl.png)
 
* AWS Trusted Advisor is an online resource to help you reduce cost, increase performance, and improve security by optimizing your AWS environment. Trusted Advisor provides real-time guidance to help you provision your resources following AWS best practices.

## AWS Personal Health Dashboard

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/pqp94s2v7dx670iyigqu.png)
 
* AWS Personal Health Dashboard provides alerts and remediation guidance when AWS is experiencing events that might affect you. While the Service Health Dashboard displays the general status of AWS services, Personal Health Dashboard gives you a personalized view into the performance and availability of the AWS services underlying your AWS resources. 
* The dashboard displays relevant and timely information to help you manage events in progress, and provides proactive notification to help you plan for scheduled activities. 
* With Personal Health Dashboard, alerts are automatically triggered by changes in the health of AWS resources, giving you event visibility and guidance to help quickly diagnose and resolve issues.

## AWS Managed Services

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/3iytopiwi0kzu0zvi7i4.png)
 
* AWS Managed Services provides ongoing management of your AWS infrastructure so you can focus on your applications. By implementing best practices to maintain your infrastructure, AWS Managed Services helps to reduce your operational overhead and risk. 
* AWS Managed Services automates common activities such as change requests, monitoring, patch management, security, and backup services, and provides full-lifecycle services to provision, run, and support your infrastructure. 
* Our rigor and controls help to enforce your corporate and security infrastructure policies, and enables you to develop solutions and applications using your preferred development approach. 
* AWS Managed Services improves agility, reduces cost, and unburdens you from infrastructure operations so you can direct resources toward differentiating your business.

## AWS Console Mobile Application

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/l6xm83scec4tcxdbhajt.png)
 
* The AWS Console Mobile Application lets customers view and manage a select set of resources to support incident response while on-the-go.

* The Console Mobile Application allows AWS customers to monitor resources through a dedicated dashboard and view configuration details, metrics, and alarms for select AWS services. 
* The Dashboard provides permitted users with a single view a resource's status, with real-time data on Amazon CloudWatch, Personal Health Dashboard, and AWS Billing and Cost Management. 
* Customers can view ongoing issues and follow through to the relevant CloudWatch alarm screen for a detailed view with graphs and configuration options. 
* In addition, customers can check on the status of specific AWS services, view detailed resource screens, and perform select actions.

## AWS License Manager

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/hj2dkhvos0edvan86oc2.png)
 
* AWS License Manager makes it easier to manage licenses in AWS and on-premises servers from software vendors such as Microsoft, SAP, Oracle, and IBM. 
* AWS License Manager lets administrators create customized licensing rules that emulate the terms of their licensing agreements, and then enforces these rules when an instance of Amazon EC2 gets launched. 
* Administrators can use these rules to limit licensing violations, such as using more licenses than an agreement stipulates or reassigning licenses to different servers on a short-term basis. 
* The rules in AWS License Manager enable you to limit a licensing breach by physically stopping the instance from launching or by notifying administrators about the infringement. 
* Administrators gain control and visibility of all their licenses with the AWS License Manager dashboard and reduce the risk of non-compliance, misreporting, and additional costs due to licensing overages.

* AWS License Manager integrates with AWS services to simplify the management of licenses across multiple AWS accounts, IT catalogs, and on-premises, through a single AWS account. 
* License administrators can add rules in AWS Service Catalog, which allows them to create and manage catalogs of IT services that are approved for use on all their AWS accounts. 
* Through seamless integration with AWS Systems Manager and AWS Organizations, administrators can manage licenses across all the AWS accounts in an organization and on-premises environments. 
* AWS Marketplace buyers can also use AWS License Manager to track bring your own license (BYOL) software obtained from the Marketplace and keep a consolidated view of all their licenses.

## AWS Well-Architected Tool

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/3j4rs0dyd9hntim319cv.png)
 
* The AWS Well-Architected Tool helps you review the state of your workloads and compares them to the latest AWS architectural best practices. 
* The tool is based on the AWS Well-Architected Framework, developed to help cloud architects build secure, high-performing, resilient, and efficient application infrastructure. 
* This Framework provides a consistent approach for customers and partners to evaluate architectures, has been used in tens of thousands of workload reviews conducted by the AWS solutions architecture team, and provides guidance to help implement designs that scale with application needs over time.

* To use this free tool, available in the AWS Management Console, just define your workload and answer a set of questions regarding operational excellence, security, reliability, performance efficiency, and cost optimization. 
* The AWS Well-Architected Tool then provides a plan on how to architect for the cloud using established best practices.

# Conclusion

* In the past, organizations have had to choose between innovating faster and maintaining control over cost, compliance, and security. 
* With AWS Management and Governance services, customers don’t have to choose between innovation and control—they can have both. * With AWS, customers can enable, provision, and operate their environment for both business agility and governance control.

Hope this guide helps you with the Introduction to Management, Governance and Migration with AWS- Part-1. In the next blog post, we will discuss some of the most important Migration services in AWS.

Let me know your thoughts in the comment section 👇
And if you haven't yet, make sure to follow me on below handles:

👋 **connect with me on [LinkedIn](https://www.linkedin.com/in/adit-modi-2a4362191/)**
🤓 **connect with me on [Twitter](https://twitter.com/adi_12_modi)**
🐱‍💻 **follow me on [github](https://github.com/AditModi)**
✍️ **Do Checkout [my blogs](https://aditmodi.hashnode.dev)** 

Like, share and follow me 🚀 for more content.

{% user aditmodi %}