**Containerization**—a virtualization method used to deploy and run distributed applications without the need to launch an entire virtual machine for each application—is changing the way businesses develop and deploy applications in cloud environments. Containers decompose applications into small, manageable packages containing everything the application needs to run: code, core data, configuration files, interfaces, and dependencies.

The container approach allows developers to focus on applications and not be concerned with deployment and infrastructure management. From a development perspective, there are numerous benefits to the container approach.

Accelerate the development pipeline, including testing and debugging.
Facilitate **continuous integration (CI) **and **continuous deployment (CD)** workflows, automatically rebuilding whenever a new code revision is committed.

Containers run locally on desktop or laptop and are easily uploaded directly to the Cloud.
Consistent results when moving code from development to test to production systems.

No need to rewrite code for each OS and cloud platform, making it easy to move containers from one cloud provider to another.
The advantages of containers extend beyond the development cycle. Containers utilize compute resources more efficiently by eliminating the need for a hypervisor. 

They simply share OS kernel without impacting the performance of applications running inside the container. With a smaller footprint, more containers can run on a single host, resulting in better utilization of compute resources and lower costs. 

Additionally, containers can be configured with only the desired binaries and components, eliminating potential vulnerabilities that might be found in a full fledged OS. Containers that can run on **Amazon EC2 Spot Instances can obtain up to a 90% discount compared to On-Demand 
prices.**

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/00d9zw36vvqfaa57xap3.png)
 

*My Background: I am Cloud , DevOps & Big Data Enthusiast | 4x AWS Certified | 3x OCI Certified | 3x Azure Certified .*

The Introduction to AWS is a Series containing different articles that provide a basic introduction to different aws topics/categories. Each article covers the detailed guide on how to work with particular topic/category . This series aims at providing "A Getting Started Guide on Different aws topics / categories ."


There are a bunch of different ways to run your **containerized workloads on AWS.** This blog post compares the three most important ways to run Docker on AWS:

#### 1.)Amazon Elastic Container Service (ECS) with AWS Fargate 

#### 2.)Amazon Elastic Container Service for Kubernetes (EKS) 

#### 3.)AWS Elastic Beanstalk (EB) with Single Container Docker

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/jzo3tz8l9g0i3ukhp1vp.png)

## ECS with Fargate

First, let’s have a look at ECS, a **fully-managed container orchestration service.** ECS is a proprietary but free of charge solution offered by AWS. It is important to mention that ECS provides a high level of integration with the AWS infrastructure. For example, containers are 1st class citizens of the VPC with their network interface (ENI) and security groups.

ECS offers **service discovery** via a load balancer or DNS (Cloud Map).

Aside from that ECS is the only option to run Docker containers without running EC2 instances on AWS. Fargate is the compute engine for ECS. All the heavy lifting of **scaling** the number of EC2 instances and containers, rolling out updates to EC2 instances without affecting containers, and many more is gone.

**ECS is free of charge.** Fargate is billed per second based on CPU and memory allocated for your containers. A container with 1 vCPU and 4 GB is about USD 30 per month.

Keep in mind the following limitations of Fargate:

General purpose compute capacity only. Fargate does not support GPU, CPU/memory optimized configurations at the moment.
Persistent volumes are not supported out of the box (e.g., Docker volume driver).
No discounts for reserved capacity available.

## EKS (Kubernetes)

The 2nd option to run Docker containers on AWS is Kubernetes (K8s). In summary, K8s is an open-source container orchestration solution. AWS offers the K8s master layer as a service. The master layer is responsible for storing the state of the container cluster and deciding on which machines new containers should be placed. On top of that, you are responsible for managing a fleet of EC2 instances used to run the containers.

The **main selling point for K8s:** it is open-source and runs on AWS, Azure, Google Cloud, on-premises, or even on your local machine. The **resulting disadvantage** is that Kubernetes is not that well integrated with the AWS infrastructure.

**Kubernetes is designed for microservice architectures.** For example, a built-in service discovery allows containers to talk to each other easily by using a local proxy.

EKS is about USD 144 per month for the master layer. Besides, you are paying for the EC2 instances powering your containers. A t3.medium instance provides 2 CPUs with 4 GiB of memory and costs around USD 30 USD per month.

You should not underestimate the complexity of operating EKS and EC2. For example, the way EKS integrates with the VPC comes with a few unexpected limitations (see EKS vs. ECS: orchestrating containers on AWS for more details).

## Elastic Beanstalk

Another option to run Docker containers on AWS is Elastic Beanstalk. Some say Elastic Beanstalk is the PaaS (Platform-as-a-Service) offering from AWS. Nevertheless, Elastic Beanstalk is very easy to use. There are a bunch of environments to deploy your web application with Elastic Beanstalk. One of them is called **Single Container Docker.** This environment deploys a single Docker container to one or multiple EC2 instances.

Elastic Beanstalk is not only deploying your application; it is also creating the needed infrastructure consisting of a database, a load balancer, and EC2 instances. Important to note: Elastic Beanstalk creates EC2 instances automatically. But you are still responsible for these virtual machines they are not fully-managed by AWS.

Elastic Beanstalk is a proprietary but free of charge solution offered by AWS. You are only paying for the underlying infrastructure. For example, a t3.medium instance provides 2 CPUs with 4 GiB of memory and costs around USD 30 USD per month.

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/j0cb7pfjop11c8ywtvm5.png)
 

## When Is Elastic Beanstalk The Best Method For Managing Docker Containers On AWS?
For businesses new to AWS or new to the containerization concept, just getting started with Docker, or developing new applications, Elastic Beanstalk may be the best approach to support Docker containers. Elastic Beanstalk offers a simple interface, allows Docker images to be pulled from public or private registries, and coordinates the deployment of multiple Docker containers to Amazon ECS clusters. Elastic Beanstalk gives you less control over application scaling and capacity but makes deploying Docker containers on AWS ever so straightforward.

## When Is Elastic Container Service The Best Method For Managing Docker Containers On AWS?

In comparison to Elastic Beanstalk, Elastic Container Service provides greater control over application architectures and orchestration of Docker containers. You specify the size and number of cluster nodes and determine if auto-scaling should be used.

Elastic Container Service uses tasks to launch Docker containers. A task includes the container definition, providing the ability to group containers in sets that launch together then terminate simultaneously. ECS provides significantly greater flexibility and customization in scheduling and CPU and memory utilization. In addition, ECS does not require special integration efforts to work with many other AWS services.

Elastic Container Service is appropriate when you need to run microservices that require integration with other AWS services, or use custom or managed schedulers to run batch workloads on EC2 On-Demand, Reserved, or Spot Instances. Businesses wanting to containerize legacy code and migrate it to AWS without needing to rewrite code should take the ECS option. Applications or workflows comprised of loosely coupled, distributed services running on various platforms or accessing widely-distributed data source can also benefit by using Elastic Container Service.

## When Is Elastic Kubernetes Service The Best Method For Managing Docker Containers On AWS?

 If you want the flexibility to integrate externally with the open-source Kubernetes community, spending the additional effort on setting up EKS may be the better option. Kubernetes is preferred for legacy workloads. It allows you to build a dev/test/production environment on-premises, and then move it to the cloud if and when required. Kubernetes is best known for its true enterprise-level cluster and container management. It is extremely valuable when your containerized workloads begin to scale. If you are already running workloads on Kubernetes, EKS is going to be a familiar and simple route to moving to an AWS environment. 

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/3nu6x8k14gl8chm8mgc8.png)
 

Hope this guide helps you understand containers on aws, feel free to connect with me on [LinkedIn.](https://www.linkedin.com/in/adit-modi-2a4362191/)
You can view my badges [here.](https://www.youracclaim.com/users/adit-modi/badges)
If you are interested in learning more about AWS then follow me on [github.](https://github.com/AditModi)
If you liked this content then do clap and share it . Thank You . 