While companies increasingly look to cloud computing as a means to expand, modernize and stay competitive, so too do those companies expose themselves to new risks. In fact, Ermetic and IDC report that 80% of CISOs claim their company has had a cloud data breach in the past 18 months. Nearly half of those (43%) had experienced 10 or more breaches.

The benefits of cloud computing are numerous, but organizations cannot make the switch to this modern platform without understanding the risks involved and, more importantly, how to protect themselves, their staff and their customers.

Amazon Web Services (AWS) is a cloud service provider that’s on almost every company’s radar today. But many AWS customers today wonder what the best approach to security is and how to get there.

companies often struggle to understand how they can protect and secure their data, their customers, and their very existence before moving to (or while expanding on) AWS. 

In this blog post, we will discuss some of the most important AWS security services that protect your data, accounts, and workloads from unauthorized access.

![Introduction to Developer Tools with AWS (2)](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/tzjc1a0bneocif3qol2i.png)
 
*My Background: Cloud Engineer | AWS Community Builder | AWS Educate Cloud Ambassador | 4x AWS Certified | 3x OCI Certified | 3x Azure Certified.*

The Introduction to AWS is a Series containing different articles that provide a basic introduction to different aws topics/categories. Each article covers the detailed guide on how to work with particular topic/category . This series aims at providing "A Getting Started Guide on Different aws topics / categories ."

# Security, Identity, and Compliance 

Using AWS, you will gain the control and confidence you need to securely run your business with the most flexible and secure cloud computing environment available today. As an AWS customer, you will benefit from AWS data centers and a network architected to protect your information, identities, applications, and devices. With AWS, you can improve your ability to meet core security and compliance requirements, such as data locality, protection, and confidentiality with our comprehensive services and features.

AWS allows you to automate manual security tasks so you can shift your focus to scaling and innovating your business. Plus, you pay only for the services that you use. All customers benefit from AWS being the only commercial cloud that has had its service offerings and associated supply chain vetted and accepted as secure enough for top-secret workloads.

## AWS Security Hub

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/889xibs9c607uns5own2.png)
 
 
AWS Security Hub gives you a comprehensive view of your high-priority security alerts and compliance status across AWS accounts. 

There are a range of powerful security tools at your disposal, from firewalls and endpoint protection to vulnerability and compliance scanners. But oftentimes this leaves your team switching back-and-forth between these tools to deal with hundreds, and sometimes thousands, of security alerts every day. With Security Hub, you now have a single place that aggregates, organizes, and prioritizes your security alerts, or findings, from multiple AWS services, such as Amazon GuardDuty, Amazon Inspector, and Amazon Macie, as well as from AWS Partner solutions. 

Your findings are visually summarized on integrated dashboards with actionable graphs and tables. You can also continuously monitor your environment using automated compliance checks based on the AWS best practices and industry standards your organization follows. Get started with AWS Security Hub just a few clicks in the Management Console and once enabled, Security Hub will begin aggregating and prioritizing findings.

## Amazon Cloud Directory

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/6tkffqs1njeq2tbpdo38.png)
 
 
Amazon Cloud Directory enables you to build flexible, cloud-native directories for organizing hierarchies of data along multiple dimensions. With Cloud Directory, you can create directories for a variety of use cases, such as organizational charts, course catalogs, and device registries. 

While traditional directory solutions, such as Active Directory Lightweight Directory Services (AD LDS) and other LDAP-based directories, limit you to a single hierarchy, Cloud Directory offers you the flexibility to create directories with hierarchies that span multiple dimensions. For example, you can create an organizational chart that can be navigated through separate hierarchies for reporting structure, location, and cost center.

Amazon Cloud Directory automatically scales to hundreds of millions of objects and provides an extensible schema that can be shared with multiple applications. As a fully-managed service, Cloud Directory eliminates time-consuming and expensive administrative tasks, such as scaling infrastructure and managing servers. You simply define the schema, create a directory, and then populate your directory by making calls to the Cloud Directory API.

## AWS Identity and Access Management


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xq2j403zyou516on07lg.png)
 
 
AWS Identity and Access Management (IAM) enables you to securely control access to AWS services and resources for your users. Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources. IAM allows you to do the following:

Manage IAM users and their access: You can create users in IAM, assign them individual security credentials (access keys, passwords, and multi-factor authentication devices), or request temporary security credentials to provide users access to AWS services and resources. You can manage permissions in order to control which operations a user can perform.

Manage IAM roles and their permissions: You can create roles in IAM and manage permissions to control which operations can be performed by the entity, or AWS service, that assumes the role. You can also define which entity is allowed to assume the role.

Manage federated users and their permissions: You can enable identity federation to allow existing identities (users, groups, and roles) in your enterprise to access the AWS Management Console, call AWS APIs, and access resources, without the need to create an IAM user for each identity.

## Amazon GuardDuty

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/x6raxo7c32spblqjigx3.png)
 
Amazon GuardDuty is a threat detection service that continuously monitors for malicious or unauthorized behavior to help you protect your AWS accounts and workloads. It monitors for activity such as unusual API calls or potentially unauthorized deployments that indicate a possible account compromise. GuardDuty also detects potentially compromised instances or reconnaissance by attackers.

Enabled with a few clicks in the AWS Management Console, Amazon GuardDuty can immediately begin analyzing billions of events across your AWS accounts for signs of risk. GuardDuty identifies suspected attackers through integrated threat intelligence feeds and uses machine learning to detect anomalies in account and workload activity. When a potential threat is detected, the service delivers a detailed security alert to the GuardDuty console and Amazon CloudWatch Events. This makes alerts actionable and easy to integrate into existing event management and workflow systems.

Amazon GuardDuty is cost effective and easy. It does not require you to deploy and maintain software or security infrastructure, meaning it can be enabled quickly with no risk of negatively impacting existing application workloads. There are no upfront costs with GuardDuty, no software to deploy, and no threat intelligence feeds required. Customers pay for the events analyzed by GuardDuty and there is a 30-day free trial available for every new account to the service.

## Amazon Inspector

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/6r791sblh8pkg2r4e61h.png)
 
Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. After performing an assessment, Amazon Inspector produces a detailed list of security findings prioritized by level of severity. These findings can be reviewed directly or as part of detailed assessment reports which are available via the Amazon Inspector console or API.

Amazon Inspector security assessments help you check for unintended network accessibility of your Amazon EC2 instances and for vulnerabilities on those EC2 instances. Amazon Inspector assessments are offered to you as pre-defined rules packages mapped to common security best practices and vulnerability definitions. Examples of built-in rules include checking for access to your EC2 instances from the internet, remote root login being enabled, or vulnerable software versions installed. These rules are regularly updated by AWS security researchers.

## Amazon Macie

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/l85cbtps1ycl72zdvok8.png)
 
Amazon Macie is a security service that uses machine learning to automatically discover, classify, and protect sensitive data in AWS. Amazon Macie recognizes sensitive data such as personally identifiable information (PII) or intellectual property, and provides you with dashboards and alerts that give visibility into how this data is being accessed or moved. The fully managed service continuously monitors data access activity for anomalies, and generates detailed alerts when it detects risk of unauthorized access or inadvertent data leaks. Today, Amazon Macie is available to protect data stored in Amazon S3, with support for additional AWS data stores coming later this year.

## AWS Artifact

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/wjdopew82vny5li5vpro.png)
 
AWS Artifact is your go-to, central resource for compliance-related information that matters to you. It provides on-demand access to AWS’ security and compliance reports and select online agreements. Reports available in AWS Artifact include our Service Organization Control (SOC) reports, Payment Card Industry (PCI) reports, and certifications from accreditation bodies across geographies and compliance verticals that validate the implementation and operating effectiveness of AWS security controls. Agreements available in AWS Artifact include the Business Associate Addendum (BAA) and the Nondisclosure Agreement (NDA).

## AWS Certificate Manager

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/s2qwx6t65qh1pdkq6g1r.png)
 
AWS Certificate Manager is a service that lets you easily provision, manage, and deploy Secure Sockets Layer/Transport Layer Security (SSL/TLS) certiﬁcates for use with AWS services and your internal connected resources. SSL/TLS certiﬁcates are used to secure network communications and establish the identity of websites over the Internet as well as resources on private networks. AWS Certificate Manager removes the time-consuming manual process of purchasing, uploading, and renewing SSL/TLS certiﬁcates.

With AWS Certificate Manager, you can quickly request a certificate, deploy it on ACM-integrated AWS resources, such as Elastic Load Balancing, Amazon CloudFront distributions, and APIs on API Gateway, and let AWS Certificate Manager handle certificate renewals. It also enables you to create private certificates for your internal resources and manage the certificate lifecycle centrally. Public and private certificates provisioned through AWS Certificate Manager for use with ACM-integrated services are free. You pay only for the AWS resources you create to run your application. With AWS Certificate Manager Private Certificate Authority, you pay monthly for the operation of the private CA and for the private certificates you issue.

## AWS CloudHSM

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/nda7h942yoe0n0z9ksug.png)
 
The AWS CloudHSM is a cloud-based hardware security module (HSM) that enables you to easily generate and use your own encryption keys on the AWS Cloud. With CloudHSM, you can manage your own encryption keys using FIPS 140-2 Level 3 validated HSMs. CloudHSM offers you the flexibility to integrate with your applications using industry-standard APIs, such as PKCS#11, Java Cryptography Extensions (JCE), and Microsoft CryptoNG (CNG) libraries.

CloudHSM is standards-compliant and enables you to export all of your keys to most other commercially-available HSMs, subject to your configurations. It is a fully-managed service that automates time-consuming administrative tasks for you, such as hardware provisioning, software patching, high-availability, and backups. CloudHSM also enables you to scale quickly by adding and removing HSM capacity on-demand, with no up-front costs.

## AWS Directory Service

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/6ufge1r5a7z1nuhwf80b.png)
 
AWS Directory Service for Microsoft Active Directory, also known as AWS Managed Microsoft AD, enables your directory-aware workloads and AWS resources to use managed Active Directory in the AWS Cloud. AWS Managed Microsoft AD is built on actual Microsoft Active Directory and does not require you to synchronize or replicate data from your existing Active Directory to the cloud. You can use standard Active Directory administration tools and take advantage of built-in Active Directory features such as Group Policy and single sign-on (SSO). With AWS Managed Microsoft AD, you can easily join Amazon EC2 and Amazon RDS for SQL Server instances to a domain, and use AWS Enterprise IT applications such as Amazon WorkSpaces with Active Directory users and groups.

## AWS Firewall Manager

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/0xgknrtefv3sltz4lqaa.png)
 
AWS Firewall Manager is a security management service that makes it easier to centrally configure and manage AWS WAF rules across your accounts and applications. Using Firewall Manager, you can easily roll out AWS WAF rules for your Application Load Balancers and Amazon CloudFront distributions across accounts in AWS Organizations. As new applications are created, Firewall Manager also makes it easy to bring new applications and resources into compliance with a common set of security rules from day one. Now you have a single service to build firewall rules, create security policies, and enforce them in a consistent, hierarchical manner across your entire Application Load Balancers and Amazon CloudFront infrastructure.

## AWS Key Management Service

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4e7ipxdkapt48ygqs12k.png)
 
AWS Key Management Service (KMS) makes it easy for you to create and manage keys and control the use of encryption across a wide range of AWS services and in your applications. AWS KMS is a secure and resilient service that uses FIPS 140-2 validated hardware security modules to protect your keys. AWS KMS is integrated with AWS CloudTrail to provide you with logs of all key usage to help meet your regulatory and compliance needs.


## AWS Secrets Manager

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/6oxotiztcccxyr7imyz2.png)

 
AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. Users and applications retrieve secrets with a call to Secrets Manager APIs, eliminating the need to hardcode sensitive information in plain text. Secrets Manager offers secret rotation with built-in integration for Amazon RDS for MySQL, PostgreSQL, and Amazon Aurora. Also, the service is extensible to other types of secrets, including API keys and OAuth tokens. In addition, Secrets Manager enables you to control access to secrets using fine-grained permissions and audit secret rotation centrally for resources in the AWS Cloud, third-party services, and on-premises.

## AWS Shield

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/jio6hk584xksrmmz4wuj.png)

 
AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards web applications running on AWS. AWS Shield provides always-on detection and automatic inline mitigations that minimize application downtime and latency, so there is no need to engage AWS Support to benefit from DDoS protection. There are two tiers of AWS Shield: Standard and Advanced.

All AWS customers beneﬁt from the automatic protections of AWS Shield Standard, at no additional charge. AWS Shield Standard defends against most common, frequently occurring network and transport layer DDoS attacks that target your website or applications. When you use AWS Shield Standard with Amazon CloudFront and Amazon Route 53, you receive comprehensive availability protection against all known infrastructure (Layer 3 and 4) attacks.

For higher levels of protection against attacks targeting your applications running on Amazon Elastic Compute Cloud (Amazon EC2), Elastic Load Balancing (ELB), Amazon CloudFront, and Amazon Route 53 resources, you can subscribe to AWS Shield Advanced. In addition to the network and transport layer protections that come with Standard, AWS Shield Advanced provides additional detection and mitigation against large and sophisticated DDoS attacks, near real-time visibility into attacks, and integration with AWS WAF, a web application firewall. AWS Shield Advanced also gives you 24x7 access to the AWS DDoS Response Team (DRT) and protection against DDoS related spikes in your Amazon Elastic Compute Cloud (Amazon EC2), Elastic Load Balancing (ELB), Amazon CloudFront, and Amazon Route 53 charges.

AWS Shield Advanced is available globally on all Amazon CloudFront and Amazon Route 53 edge locations. You can protect your web applications hosted anywhere in the world by deploying Amazon CloudFront in front of your application. Your origin servers can be Amazon S3, Amazon Elastic Compute Cloud (Amazon EC2), Elastic Load Balancing (ELB), or a custom server outside of AWS. You can also enable AWS Shield Advanced directly on an Elastic IP or Elastic Load Balancing (ELB) in the following AWS Regions: Northern Virginia, Oregon, Ireland, Tokyo, and Northern California.

## AWS Single Sign-On

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/qfobjd9b78rms2lbdvxv.png)

AWS Single Sign-On (SSO) is a cloud SSO service that makes it easy to centrally manage SSO access to multiple AWS accounts and business applications. With just a few clicks, you can enable a highly available SSO service without the upfront investment and on-going maintenance costs of operating your own SSO infrastructure. With AWS SSO, you can easily manage SSO access and user permissions to all of your accounts in AWS Organizations centrally. AWS SSO also includes built-in SAML integrations to many business applications, such as Salesforce, Box, and Office 365. Further, by using the AWS SSO application configuration wizard, you can create Security Assertion Markup Language (SAML) 2.0 integrations and extend SSO access to any of your SAML-enabled applications. Your users simply sign in to a user portal with credentials they configure in AWS SSO or using their existing corporate credentials to access all their assigned accounts and applications from one place.

## AWS WAF

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kww4zi9to51thz43s8zh.png)
 
AWS WAF is a web application ﬁrewall that helps protect your web applications from common web exploits that could aﬀect application availability, compromise security, or consume excessive resources. AWS WAF gives you control over which traﬃc to allow or block to your web application by deﬁning customizable web security rules. You can use AWS WAF to create custom rules that block common attack patterns, such as SQL injection or cross-site scripting, and rules that are designed for your speciﬁc application. New rules can be deployed within minutes, letting you respond quickly to changing traﬃc patterns. Also, AWS WAF includes a full-featured API that you can use to automate the creation, deployment, and maintenance of web security rules.

## AWS Organizations

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rfovnz2mp7lh0trbogd8.png)
  
AWS Organizations offers policy-based management for multiple AWS accounts. With Organizations, you can create groups of accounts, automate account creation, apply and manage policies for those groups. Organizations enables you to centrally manage policies across multiple accounts, without requiring custom scripts and manual processes.

Using AWS Organizations, you can create Service Control Policies (SCPs) that centrally control AWS service use across multiple AWS accounts. You can also use Organizations to help automate the creation of new accounts through APIs. Organizations helps simplify the billing for multiple accounts by enabling you to setup a single payment method for all the accounts in your organization through consolidated billing. AWS Organizations is available to all AWS customers at no additional charge.


# Conclusion

AWS provides services that help you protect your data, accounts, and workloads from unauthorized access. AWS provide encryption and key management and threat detection that continuously monitors and protects your accounts and workloads.
AWS identifies threats by continuously monitoring the network activity and account behavior within your cloud environment.
AWS gives you a comprehensive view of your compliance status and continuously monitors your environment using automated compliance checks based on the AWS best practices and industry standards your organization follows.

![2021-06-22 (1)](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/1kqmaghkoz2a35z36q3w.png)
 

Hope this guide helps you with the Introduction to Security, Identity, and Compliance with AWS, feel free to connect with me on [LinkedIn] (https://www.linkedin.com/in/adit-modi-2a4362191/)|[Twitter](https://twitter.com/adi_12_modi).
If you are interested in learning more about AWS Services then follow me on [github.](https://github.com/AditModi)
If you liked this content then do clap and share it . Thank You .