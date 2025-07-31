# AWS CCP & SAA Cheat Sheet
- [AWS CCP \& SAA Cheat Sheet](#aws-ccp--saa-cheat-sheet)
  - [Services](#services)
    - [🧠 Identity \& Access Management](#-identity--access-management)
      - [IAM](#iam)
      - [AWS Identity Center](#aws-identity-center)
      - [AWS Organizations](#aws-organizations)
    - [💾 Compute](#-compute)
      - [EC2](#ec2)
      - [Lambda](#lambda)
      - [Fargate](#fargate)
      - [Elastic Beanstalk](#elastic-beanstalk)
      - [Lightsail](#lightsail)
    - [📦 Storage](#-storage)
      - [S3](#s3)
      - [EBS](#ebs)
      - [EFS](#efs)
      - [AWS Snowball](#aws-snowball)
      - [CloudEndure](#cloudendure)
      - [AWS Backup](#aws-backup)
      - [🛢️ Database](#️-database)
      - [RDS](#rds)
      - [Aurora](#aurora)
      - [DynamoDB](#dynamodb)
      - [DocumentDB](#documentdb)
      - [Neptune](#neptune)
      - [ElastiCache](#elasticache)
      - [Athena](#athena)
      - [Redshift](#redshift)
    - [🌐 Networking \& CDN](#-networking--cdn)
      - [VPC](#vpc)
      - [CloudFront](#cloudfront)
      - [Route 53](#route-53)
      - [Elastic Load Balancer (ELB)](#elastic-load-balancer-elb)
      - [Global Accelerator](#global-accelerator)
      - [Direct Connect \& VPN](#direct-connect--vpn)
      - [AWS Transit Gateway](#aws-transit-gateway)
    - [🔒 Security \& Compliance](#-security--compliance)
      - [AWS Config](#aws-config)
      - [CloudTrail](#cloudtrail)
      - [CloudWatch](#cloudwatch)
      - [Amazon Inspector](#amazon-inspector)
      - [Amazon GuardDuty](#amazon-guardduty)
      - [Amazon Detective](#amazon-detective)
      - [AWS Shield](#aws-shield)
      - [Trusted Advisor](#trusted-advisor)
      - [Control Tower](#control-tower)
      - [AWS WAF (Web Application Firewall)](#aws-waf-web-application-firewall)
      - [Secrets Manager](#secrets-manager)
      - [KMS (Key Management Service)](#kms-key-management-service)
    - [🧰 Developer Tools](#-developer-tools)
      - [CodeCommit](#codecommit)
      - [CodeBuild](#codebuild)
      - [CodeDeploy](#codedeploy)
      - [CodePipeline](#codepipeline)
      - [CodeArtifact](#codeartifact)
    - [📊 Analytics \& Big Data](#-analytics--big-data)
      - [Kinesis](#kinesis)
      - [Glue](#glue)
      - [EMR](#emr)
      - [Athena](#athena-1)
      - [QuickSight](#quicksight)
    - [🧑‍💻 End User \& Business Applications](#-end-user--business-applications)
      - [Amazon WorkSpaces](#amazon-workspaces)
      - [Amazon AppStream](#amazon-appstream)
      - [Amazon Connect](#amazon-connect)
    - [🧰 Management \& Governance](#-management--governance)
      - [AWS Cost Explorer](#aws-cost-explorer)
      - [AWS Budgets](#aws-budgets)
    - [🧠 AI/ML](#-aiml)
      - [Amazon Rekognition](#amazon-rekognition)
      - [Amazon SageMaker](#amazon-sagemaker)
    - [🧩 App Integration](#-app-integration)
      - [Amazon MQ](#amazon-mq)
  - [Support Pläne](#support-pläne)
    - [🟢 1. Basic Support](#-1-basic-support)
    - [🔵 2. Developer Support](#-2-developer-support)
    - [🟠 3. Business Support](#-3-business-support)
    - [🔴 4. Enterprise Support](#-4-enterprise-support)
  - [EC2 Instanz Typen](#ec2-instanz-typen)
    - [Spot](#spot)
    - [Reserved](#reserved)
    - [On Demand](#on-demand)
    - [EC2 Pricing Plans](#ec2-pricing-plans)
    - [Compute Savings Plans](#compute-savings-plans)
    - [EC2 Instance Savings Plans](#ec2-instance-savings-plans)
    - [Standard Reserved Instances](#standard-reserved-instances)
    - [Convertible Reserved Instances](#convertible-reserved-instances)
  - [Disaster Recovery](#disaster-recovery)
  - [S3 Storage Klassen](#s3-storage-klassen)
    - [S3 Standard](#s3-standard)
    - [S3 Intelligent-Tiering](#s3-intelligent-tiering)
    - [S3 Standard-Infrequent Access (Standard-IA)](#s3-standard-infrequent-access-standard-ia)
    - [S3 One Zone-Infrequent Access (One Zone-IA)](#s3-one-zone-infrequent-access-one-zone-ia)
    - [S3 Glacier Instant Retrieval](#s3-glacier-instant-retrieval)
    - [S3 Glacier Flexible Retrieval (formerly Glacier)](#s3-glacier-flexible-retrieval-formerly-glacier)
    - [S3 Glacier Deep Archive](#s3-glacier-deep-archive)
    - [Summary Table](#summary-table)

## Services

### 🧠 Identity & Access Management

#### IAM

Manages access to AWS resources securely

> IAM (Identity and Access Management) allows you to define who can access what in your AWS environment. You can create users, groups, and roles and assign permissions using policies. IAM supports MFA, temporary credentials, and fine-grained access control.

#### AWS Identity Center

Centralized SSO across AWS accounts and external apps.
> AWS Identity Center (formerly AWS SSO) lets you manage workforce access from a single place. You can assign users to multiple AWS accounts or cloud apps with a single sign-on experience. It integrates with external identity providers like Microsoft Entra ID (Azure AD).

#### AWS Organizations

Manage multiple AWS accounts centrally.
> Organizations let you group accounts for billing, security, and policy control. You can apply Service Control Policies (SCPs) and consolidate billing. It’s used in enterprise setups to create logical account structures (e.g., dev, test, prod).

### 💾 Compute

#### EC2

Scalable virtual servers in the cloud.
> Amazon EC2 lets you launch virtual machines with customizable OS, CPU, memory, and storage. You manage networking, scaling, and updates. It supports Auto Scaling and Load Balancers for high availability.

#### Lambda

Run code without managing servers.
> Lambda is a serverless compute service that executes code in response to events (e.g., S3 uploads, API calls). You only pay for execution time, and there’s no need to manage infrastructure. Ideal for microservices and event-driven architectures.

#### Fargate

Serverless containers for ECS and EKS.
> AWS Fargate runs containers without managing EC2 instances. You define the CPU and memory for your container tasks, and Fargate handles provisioning and scaling. It's great for simplifying container operations.

#### Elastic Beanstalk

Platform-as-a-Service for web apps.
> Beanstalk handles deployment and management of applications using EC2, RDS, S3, and more. You upload your code, and it takes care of provisioning, scaling, and health monitoring. It supports Java, .NET, Python, PHP, Node.js, and more.

#### Lightsail

Easy-to-use virtual private servers.
> Lightsail is designed for developers who need a simple VPS solution. It bundles compute, storage, and networking at a fixed monthly price. Ideal for basic websites, blogs, and dev/test environments.

### 📦 Storage

#### S3

Object storage for any amount of data.
> Amazon S3 stores data as objects within buckets, offering durability, scalability, and availability. It supports versioning, lifecycle policies, and fine-grained access controls. Frequently used for backups, static websites, and big data.

#### EBS

Block storage for EC2 instances.
> Amazon EBS provides persistent block-level storage volumes for use with EC2. It's suitable for databases and applications that require fast, consistent IOPS. Volumes can be encrypted, snapshotted, and resized.

#### EFS

Scalable file storage for EC2.
> Amazon EFS is a shared file system accessible by multiple EC2 instances. It's serverless and grows/shrinks automatically. Ideal for workloads requiring a common file repository like CMS or analytics apps.

#### AWS Snowball

Data transfer via physical appliance.
> AWS Snowball helps transfer large data volumes (TBs–PBs) to AWS using secure physical devices. It’s faster and more cost-effective than internet uploads. Supports offline migration and edge computing scenarios.

#### CloudEndure

Disaster recovery service.
> CloudEndure replicates on-premise workloads to AWS for business continuity. It allows quick failover in case of disaster and supports minimal RTO/RPO. Often used in DR planning and legacy app migrations.

#### AWS Backup

Centralized backup service.
> Manages and automates backups across AWS services like EFS, RDS, DynamoDB, and EBS. Ensures compliance and centralized backup policy enforcement.

#### 🛢️ Database

#### RDS

Managed relational database service.
> Amazon RDS supports MySQL, PostgreSQL, SQL Server, MariaDB, and Oracle. AWS handles backups, patching, scaling, and high availability (Multi-AZ). It's ideal for applications needing traditional SQL databases.

#### Aurora

High-performance cloud-native RDBMS.
> Aurora is a MySQL- and PostgreSQL-compatible database designed for the cloud, offering better performance and availability than RDS. It auto-scales storage and supports serverless deployments. Suitable for high-demand transactional systems.

#### DynamoDB

Serverless NoSQL key-value database.
> DynamoDB delivers millisecond latency at any scale and supports auto-scaling, backups, and DAX (in-memory caching). It’s used for gaming, IoT, and real-time bidding applications. Fully managed and highly available.

#### DocumentDB

Managed document database compatible with MongoDB.
> Amazon DocumentDB supports document-oriented data using MongoDB APIs. Ideal for apps using flexible, semi-structured data. AWS manages patching, backups, and replication.

#### Neptune

Fully managed graph database.
> Amazon Neptune supports property and RDF graph models (Gremlin/SPARQL). Used in social networking, fraud detection, and recommendation systems. It’s optimized for fast traversals across large datasets.

#### ElastiCache

In-memory cache for low-latency apps.
> ElastiCache supports Redis and Memcached engines for caching and session storage. It improves app performance by reducing database load. AWS handles maintenance and failover.

#### Athena

Query S3 data using SQL.
> Amazon Athena is a serverless, pay-per-query service that allows you to analyze S3 data using standard SQL. No infrastructure needed. Ideal for quick analytics and ad hoc queries.

#### Redshift

Scalable data warehouse.
> Amazon Redshift enables complex analytical queries across large datasets. It supports SQL and integrates with BI tools like QuickSight. Ideal for reporting, data lakes, and business intelligence.

### 🌐 Networking & CDN

#### VPC

Isolated cloud network environment.
> Virtual Private Cloud allows you to define IP ranges, subnets, route tables, and security groups. It’s like a traditional network but in the cloud. You can connect VPCs using VPC Peering or Transit Gateway.

#### CloudFront

Global content delivery network (CDN).
> CloudFront caches content at edge locations for faster delivery. It integrates with S3, Lambda\@Edge, and Route 53. Often used to speed up websites, APIs, and video streams.

#### Route 53

Managed DNS and domain registration.
> Route 53 provides DNS services with routing policies (e.g., failover, geolocation). It also supports domain registration and health checks. Used for both internal and public-facing applications.

#### Elastic Load Balancer (ELB)

Distributes traffic across instances.
> ELB automatically distributes incoming app traffic across multiple targets (EC2, Lambda). Supports Application, Network, and Gateway Load Balancers. Enables high availability and fault tolerance.

#### Global Accelerator

Optimizes global traffic routing.
> AWS Global Accelerator improves performance by routing users through the AWS global network. It assigns static IPs and can improve latency and availability for global apps.

#### Direct Connect & VPN

Private or encrypted connections to AWS.
> AWS Direct Connect establishes a dedicated physical line to AWS, reducing bandwidth costs and improving speed. VPN provides encrypted tunnels over the internet. Often used for hybrid cloud setups.

#### AWS Transit Gateway

Connects multiple VPCs and on-premises networks.
> Acts as a central hub for inter-VPC and hybrid network routing. Scales better than VPC Peering for large organizations.

### 🔒 Security & Compliance

#### AWS Config

Tracks resource configurations & compliance.
> AWS Config continuously monitors AWS resource changes and evaluates them against compliance rules. It provides a historical record of configuration changes. Useful for audits and governance.

#### CloudTrail

Logs all API activity in AWS.
> CloudTrail captures every API call (console, SDK, CLI) in your AWS environment. Logs are stored in S3 and can be sent to CloudWatch or analyzed via Athena. Crucial for security and auditing.

#### CloudWatch

Monitoring service for AWS & apps.
> Amazon CloudWatch collects metrics, logs, and events from resources and applications. You can set alarms, create dashboards, and automate actions. It also supports custom metrics and anomaly detection.

#### Amazon Inspector

Automated vulnerability scanning.
> Inspector scans EC2, Lambda, and container workloads for vulnerabilities and misconfigurations. It supports CIS Benchmarks and CVE detection. Ideal for proactive security compliance.

#### Amazon GuardDuty

Threat detection and monitoring.
> GuardDuty uses machine learning and threat intelligence to detect suspicious activity (e.g., port scans, unusual API calls). It requires no agents and integrates with AWS security tools.

#### Amazon Detective

Investigate security incidents deeply.
> Detective helps security analysts investigate and understand the root causes of suspicious activity. It visualizes relationships and timelines between users, IPs, and resources.

#### AWS Shield

DDoS protection for web applications.
> AWS Shield provides automatic protection against common DDoS attacks. The advanced tier offers extra protection and response support. Works with CloudFront and ELB.

#### Trusted Advisor

Recommends best practices for AWS accounts.
> Trusted Advisor evaluates your account for cost optimization, performance, security, fault tolerance, and service limits. Some checks are only available with Business or Enterprise support plans.

#### Control Tower

Automated multi-account setup and governance.
> Control Tower simplifies setting up secure, compliant AWS environments using Landing Zones. It integrates with Organizations, SCPs, and guardrails. Useful for enterprises managing many accounts.

#### AWS WAF (Web Application Firewall)

Protects web apps from common exploits.
> AWS WAF filters HTTP traffic and defends against threats like SQL injection and XSS. Works with CloudFront, API Gateway, and ALB.

#### Secrets Manager

Manages secrets like passwords and API keys.
> Securely stores and rotates secrets. Integrates with Lambda, RDS, and custom apps.

#### KMS (Key Management Service)

Manages encryption keys.
> KMS lets you create, manage, and audit encryption keys for AWS and app data. Integrated with S3, EBS, RDS, and more.

### 🧰 Developer Tools

#### CodeCommit

Git-based source control.
> AWS CodeCommit hosts private Git repositories securely. It integrates with CodePipeline and IAM for access control. A good alternative to GitHub or GitLab for AWS-native teams.

#### CodeBuild

Build automation service (CI).
> CodeBuild compiles code, runs tests, and produces artifacts. It scales automatically and supports custom build environments via Docker. Used in CI/CD pipelines.

#### CodeDeploy

Automates application deployment.
> AWS CodeDeploy deploys applications to EC2, Lambda, or on-prem servers. It supports in-place and blue/green deployments. Useful for minimizing downtime and automating rollbacks.

#### CodePipeline

CI/CD orchestration tool.
> CodePipeline automates build, test, and deploy stages. It integrates with CodeBuild, CodeDeploy, GitHub, and more. Changes are pushed through pipelines automatically.

#### CodeArtifact

Package manager for dependencies.
> CodeArtifact stores and shares software packages across teams. It supports npm, Maven, PyPI, and more. Helps centralize package management with fine-grained access control.

### 📊 Analytics & Big Data

#### Kinesis

Real-time data streaming.
> Kinesis ingests and processes real-time streaming data like logs, IoT events, and clicks. Includes Kinesis Streams, Firehose, Analytics, and Video Streams. Used in monitoring, ML pipelines, and analytics.

#### Glue

Serverless ETL & data catalog.
> AWS Glue transforms and moves data between stores. It includes a metadata catalog, jobs, and crawlers. Commonly used to prepare data for analytics or load it into Redshift.

#### EMR

Managed Hadoop/Spark cluster.
> EMR provides a scalable platform to run big data frameworks like Hadoop, Spark, Hive, and Presto. It can read/write from S3 and integrate with data lakes.

#### Athena

Query service for S3 using SQL.
> Serverless service for querying structured data in S3 using Presto SQL engine. You only pay per query scanned. No infrastructure to manage.

#### QuickSight

Business intelligence and dashboards.
> QuickSight creates interactive dashboards and visualizations from AWS data sources. It supports ML insights, serverless scaling, and embeds in apps.

### 🧑‍💻 End User & Business Applications

#### Amazon WorkSpaces

Virtual desktops in the cloud.
> WorkSpaces provides Windows/Linux desktops on demand, accessible from any device. Good for remote work, secure environments, or temporary staff.

#### Amazon AppStream

App streaming to user devices.
> AppStream streams desktop applications via browser without installing them locally. Ideal for training, demos, or remote access to desktop software.

#### Amazon Connect

Cloud-based contact center.
> Amazon Connect is an omnichannel contact center platform with voice, chat, and analytics. Fully managed and integrates with other AWS services like Lambda and S3.

### 🧰 Management & Governance

#### AWS Cost Explorer

Visualize and analyze AWS costs.
> Provides cost trends and forecasts to help manage budgets. Supports tagging and filtering.

#### AWS Budgets

Set custom cost and usage alerts.
> Budgets notify you when your usage or costs exceed a threshold. Can trigger automation via SNS.

### 🧠 AI/ML

#### Amazon Rekognition

Image and video analysis.
> Detects objects, scenes, and faces. Can recognize celebrities, text in images, and unsafe content.

#### Amazon SageMaker

Build, train, and deploy ML models.
> End-to-end ML service that supports data prep, model training, deployment, and monitoring.

### 🧩 App Integration

#### Amazon MQ

Managed message broker (ActiveMQ, RabbitMQ).
> Used for migrating legacy message-based apps that use traditional protocols like AMQP or STOMP.

---

## Support Pläne

### 🟢 1. Basic Support

(immer kostenlos)

Zugriff auf AWS-Dokumentation, Whitepapers, Foren, Trusted Advisor – Core Checks

Kein direkter technischer Support

### 🔵 2. Developer Support

ab $29/Monat

E-Mail-Support während Geschäftszeiten

Antwortzeit:

< 24 Stunden bei allgemeinen Problemen

< 12 Stunden bei Systemausfall

1 Benutzer kann Support-Anfragen stellen

### 🟠 3. Business Support

ab $100/Monat (skaliert mit Nutzung)

Rund-um-die-Uhr Support per E-Mail, Chat und Telefon

Antwortzeit:

< 1 Stunde bei „Production System Down“

< 12–24 Stunden bei weniger kritischen Problemen

Zugriff auf alle Trusted Advisor Checks

Support für Drittanbieter-Software (z. B. Ubuntu, Docker, etc.)

Nutzung von AWS Personal Health Dashboard

### 🔴 4. Enterprise Support

ab $15.000/Monat
Enthält alles aus Business, plus:

Technischer Account Manager (TAM) – dein persönlicher AWS-Ansprechpartner

Architektur-Reviews, operative Reviews

Zugang zu Infrastructure Event Management (IEM) – z. B. bei großen Releases oder Migrationsprojekten

Antwortzeit:

< 15 Minuten bei „Business-Critical System Down“

---

## EC2 Instanz Typen

### Spot

Spot Instances can be interrupted, making them unsuitable for production workloads requiring 24/7 availability.

### Reserved

Reserved Instances provide up to 72% discount for predictable, steady-state workloads with 1 or 3-year commitments.

### On Demand

On-Demand pricing offers flexibility but costs more for 24/7 workloads compared to commitment-based options.

### EC2 Pricing Plans

### Compute Savings Plans

Compute Savings Plans provide discounts across any EC2 instance family, size, OS, or Region with maximum flexibility.

### EC2 Instance Savings Plans

EC2 Instance Savings Plans limit flexibility to specific instance families within a Region.

### Standard Reserved Instances

Standard RIs lock you to specific instance types with no flexibility across families.

### Convertible Reserved Instances

Convertible RIs allow some changes but Compute Savings Plans offer greater flexibility across instance families.

---

## Disaster Recovery

![](https://docs.aws.amazon.com/images/whitepapers/latest/disaster-recovery-workloads-on-aws/images/disaster-recovery-strategies.png)

---

## S3 Storage Klassen
### S3 Standard
- **Use case:** Frequently accessed (“hot”) data.
- **Characteristics:**  
  - High availability (99.99%)  
  - Very low latency  
  - High durability (11 nines, 99.999999999%)  
- **Examples:** Websites, apps, dynamic content, frequently accessed backups.


### S3 Intelligent-Tiering
- **Use case:** Data with unknown or changing access patterns.
- **Characteristics:**  
  - Automatically moves data between frequent and infrequent access tiers  
  - No performance impact  
  - Small monitoring and automation fees  
- **Examples:** Data with unpredictable usage, cost optimization for unknown patterns.



### S3 Standard-Infrequent Access (Standard-IA)
- **Use case:** Data accessed less frequently but requires rapid access when needed.
- **Characteristics:**  
  - Lower storage cost than Standard  
  - Retrieval fees apply  
  - Same durability and availability as Standard  
- **Examples:** Backups, disaster recovery, infrequently accessed data.



### S3 One Zone-Infrequent Access (One Zone-IA)
- **Use case:** Less critical data, rarely accessed, stored in a single Availability Zone.
- **Characteristics:**  
  - Stores data in one AZ only (lower availability, 99.5%)  
  - Lower cost than Standard-IA  
  - Higher risk if AZ fails  
- **Examples:** Reproducible data, secondary backups, non-critical data.



### S3 Glacier Instant Retrieval
- **Use case:** Long-term archive data requiring immediate retrieval.
- **Characteristics:**  
  - Low-cost storage  
  - Millisecond retrieval  
- **Examples:** Archives that need quick access occasionally.



### S3 Glacier Flexible Retrieval (formerly Glacier)
- **Use case:** Long-term archives with retrieval times from minutes to hours.
- **Characteristics:**  
  - Very low storage cost  
  - Retrieval fees apply  
  - Retrieval times: minutes to hours  
- **Examples:** Compliance archives, backups rarely accessed.



### S3 Glacier Deep Archive
- **Use case:** Data accessed very rarely (maybe once a year) with lowest storage cost.
- **Characteristics:**  
  - Cheapest storage  
  - Retrieval times: up to 12 hours or more  
  - Retrieval fees apply  
- **Examples:** Long-term legal archives, regulatory data retention.


### Summary Table

| Storage Class                 | Access Frequency        | Availability     | Durability   | Cost          | Retrieval Time          | Use Case                          |
|------------------------------|------------------------|------------------|--------------|---------------|------------------------|----------------------------------|
| S3 Standard                  | Frequent               | 99.99%           | 11 nines     | High          | Milliseconds           | Active data, websites             |
| S3 Intelligent-Tiering       | Variable               | 99.9%+           | 11 nines     | Medium        | Milliseconds           | Unknown access patterns           |
| S3 Standard-IA               | Infrequent             | 99.9%            | 11 nines     | Lower         | Milliseconds + retrieval fees | Backups, DR                   |
| S3 One Zone-IA               | Infrequent             | 99.5% (1 AZ)     | 11 nines     | Lowest        | Milliseconds + retrieval fees | Secondary backups, cost-sensitive |
| S3 Glacier Instant Retrieval | Rare                   | 99.99%           | 11 nines     | Low           | Milliseconds           | Long-term archive with fast access |
| S3 Glacier Flexible Retrieval| Rare                   | 99.99%           | 11 nines     | Very Low      | Minutes to hours       | Compliance archives              |
| S3 Glacier Deep Archive      | Very Rare              | 99.99%           | 11 nines     | Cheapest      | Up to 12 hours or more | Long-term legal/regulatory archive|

---