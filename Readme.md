#Resources
* [AWS Certified Solutions Architect Professional Level Exam Blueprint](https://d0.awsstatic.com/Train%20%26%20Cert/docs/AWS_certified_solutions_architect_professional_blueprint.pdf)

# Six Advantages of Cloud Computing
* Trade capital expenses for variable expense
* Benefit from massive economics of scale
* Stop guessing about capacity
* Increase speed and agility
* Stop spending money running and maintaining data centers.
* Go global in minutes

# Cloud Computing Models
## Infrastructure as Service(__IasS__)
* Provide access to network features, computers and data storage space.
* Highest level of flexibility and management control

## Platform as Service(__PasS__)
* Removes the need to manage the underlying infrastructure
* Focus on the deployment and management of your application

## Software as a Service(__SaaS__)
* Provides you with a completed product that is run and managed by the service provider.
* You do not have to think about how the service is maintained or how the  underlying infrastructure is managed;you only need to think about how you will use that particular piece of software.
* ex: web-based email , payment service

# Services
## Compute
### EC2
### EC2 Container Service
### EC2 Container Registry
### Amazon Lightsail
* way to launch and manage a virtual private server with AWS.
### AWS Batch
### AWS Elastic Beanstalk
* service for deploying and scaling web applications and services.
### AWS Lambda
* lets y ou run code without provisioning or managing servers.
### AWS Scaling
* Helps you maintain application availability and allows you to scale your Amazon EC2 capacity up or down automatically according to conditions that you define.
### Amazon S3
### Amazon Elastic Block Store
* Provides persistent block storage volumes for use with Amazon Ec2 instances 
### Amazon Elastic File System
### Amazon Glacier
* For data archiving
### AWS Storage Gateway
* enables hybrid storage between on-premises storage environments and the AWS Cloud.

## Database
### Amazon Aurora
* is a MySQL and PostgreSQL compatible relational database engine.
### Amazon RDS
* A relational database in the cloud.
### Amazon DynamoDB
* NoSQL database service
* supports both document and key-value data models.
### Amazon ElastiCache
* in memory cache in the cloud.
* supports Redis,Memcached.

## Migration
### AWS Application Discovery Service
* Helps systems integrators quickly and reliably plan application migration projects by automatically identifying applications running in on-premisses data centers, their associated dependencies, and their performance profiles.
### AWS Database Migration service
* Helps you migrate databases to AWS.
### AWS Server migration service.
* Migrate on-premisses workloads to AWS.
### AWS Snowball
* Pegabyte-scale data transport solution that uses secure appliances to transfer large amounts od data into and out of AWS. 
### AWS Snowball Edge
### AWS Snowmobile

## Network and Content Deliver
### Amazon VPC
* lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define.
### Amazon CloudFront
* Global content delivery network(CDN) service that accelerates delivery of your websites, APIs, video content , or other web assets.
### Amazon Route 53
* Cloud Domain Name System(DNS) web service.
### AWS Direct Connect
* Makes it easy to establish a dedicated network connection from on premises to AWS.
### Elastic Load Balancing
* Automatically distributes incoming application traffic across multiple EC2 instances.
### AWS CodeCommit
* Managed source control service  (works with Git tools)
### AWS CodeBuild
* Automates code deployments to any instance.
### AWS CodePipeline
* Continuous integration and continuous delivery.
### AWS X-Ray
* Helps developers analyze and debug distributed applications in production or under development.

## Management Tools
### Amazon CloudWatch
* Monitor service for AWS Cloud resources and the applications.
### Amazon EC2 System Manager
*  management service that helps you automatically collect
software inventory, apply operating system (OS) patches, create system images, and configure
Windows and Linux operating systems

### AWS CloudFormation
* Gives developers and systems administrators an easy way to create and manage a collection of related AWS resources, provisioning and updating them in an orderly and predictable fashion

### AWS CloudTrail
* is a web service that records AWS API calls for your account and delivers log files to you.69 The recorded information includes the identity of the API caller, the time of the API call, the source IP address of the API caller, the request parameters, and the response elements returned by the AWS service

### AWS Config
* is a fully managed service that provides you with an AWS resource inventory,configuration history, and configuration change notifications to enable security and governance

### AWS OpsWorks
* Configuration management service that uses Chef, an automation platform that treats the server configuration as code.

### AWS Service Catalog
* allows organizations to create and manage catalogs of IT services that are approved for use on AWS

### AWS Trusted Advisor
*  is an online resource to help you reduce cost, increase performance, and improve security by optimizing your AWS environment.

### AWS Personnel Health Dashboard
* provides alerts and remediation guidance when AWS is experiencing events that might affect you

### AWS Management Services
* provides ongoing management of your AWS infrastructure so you can focus on your applications

## Security, Identity, and Compliance

### Amazon Cloud Directory
* enables you to build flexible, cloud-native directories for organizing hierarchies of data along multiple dimensions

### AWS Identity and Access Management
* enables you to securely control access to AWS services and resources for your users.77 Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources

### Amazon Inspector
* is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS

### AWS Certificate Manager
* is a service that lets you easily provision, manage, and deploy Secure Sockets Layer/Transport Layer Security (SSL/TLS) certificates for use with AWS services.

### AWS CloudHSM
* service helps you meet corporate, contractual, and regulatory compliance requirements for data security by using dedicated Hardware Security Module (HSM) appliances within the AWS Cloud

### AWS Directory Service
* for Microsoft Active Directory (Enterprise Edition), also known as AWS Microsoft AD, enables your directory-aware workloads and AWS resources to use managed Active Directory in the AWS Cloud

### AWS Key Management Service
* is a managed service that makes it easy for you to create and control the encryption keys used to encrypt your data

### AWS Organizations
* allows you to create groups of AWS accounts that you can use to more easily manage security and automation settings.

### AWS Shield
* is a managed Distributed Denial of Service (DDoS) protection service that safeguards web applications running on AWS

### AWS WAF(Web Application Firewall)
* is a web application firewall that helps protect your web applications from common web exploits that could affect application availability, compromise security, or consume excessive resources

## Analytics

### AWS Athena
* is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL.94 Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run

### Amazon EMR
* provides a managed Hadoop framework that makes it easy, fast, and cost effective to process vast amounts of data across dynamically scalable EC2 instances

### Amazon CloudSearch
* is a managed service in the AWS Cloud that makes it simple and cost effective to set up, manage, and scale a search solution for your website or application

### Amazon Elastic Search
* makes it easy to deploy, operate, and scale Elastic search for log analytics, full text search, application monitoring, and more.

### Amazon Kinesis
* is a platform for streaming data on AWS, offering powerful services to make it easy to load and analyze streaming data, and also providing the ability for you to build custom streaming data applications for specialized needs

### Amazon Redshift     
* is a fast, fully managed, peta byte-scale data warehouse that makes it simple and cost-effective to analyze all your data using your existing business intelligence tools

### Amazon QuickSight
* is a fast, cloud-powered business analytics service that makes it easy to build visualizations, perform ad-hoc analysis, and quickly get business insights from your data

### AWS Data Pipeline
* is a web service that helps you reliably process and move data between different AWS compute and storage services, as well as on-premises data sources, at specified intervals

### AWS Glue
* is a fully managed ETL service that makes it easy to move data between your data stores

## Artificial Intelligence

### Amazon Lex
* Amazon Lex is a service for building conversational interfaces into any application using voice and tex

### Amazon Polly
* is a service that turns text into lifelike speech

### Amazon Rekognition
* is a service that makes it easy to add image analysis to your applications

### Amazon Machine Learning
* is a service that makes it easy for developers of all skill levels to use machine learning technology

## Mobile Services

### 

### 

### 

### 
[Source](https://d0.awsstatic.com/whitepapers/aws-overview.pdf)
