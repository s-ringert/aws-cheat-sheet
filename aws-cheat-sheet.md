# AWS CCP & SAA Cheat Sheet

- [AWS CCP \& SAA Cheat Sheet](#aws-ccp--saa-cheat-sheet)
  - [Services](#services)
    - [🤖 AI \& Machine Learning](#-ai--machine-learning)
      - [Amazon Comprehend](#amazon-comprehend)
      - [Amazon Forecast](#amazon-forecast)
      - [Amazon Fraud Detector](#amazon-fraud-detector)
      - [Amazon Kendra](#amazon-kendra)
      - [Amazon Lex](#amazon-lex)
      - [Amazon Polly](#amazon-polly)
      - [Amazon Rekognition](#amazon-rekognition)
      - [Amazon SageMaker](#amazon-sagemaker)
      - [Amazon Textract](#amazon-textract)
      - [Amazon Transcribe](#amazon-transcribe)
      - [Amazon Translate](#amazon-translate)
      - [Amazon Q](#amazon-q)
    - [📊 Analytics \& Big Data](#-analytics--big-data)
      - [Kinesis](#kinesis)
      - [Glue](#glue)
      - [EMR](#emr)
      - [Athena](#athena)
      - [QuickSight](#quicksight)
      - [AWS Data Exchange](#aws-data-exchange)
      - [AWS Data Pipeline](#aws-data-pipeline)
      - [AWS Lake Formation](#aws-lake-formation)
      - [Amazon Managed Streaming for Apache Kafka (Amazon MSK)](#amazon-managed-streaming-for-apache-kafka-amazon-msk)
      - [Amazon OpenSearch Service](#amazon-opensearch-service)
    - [🧩 App Integration](#-app-integration)
      - [Amazon MQ](#amazon-mq)
      - [Amazon AppFlow](#amazon-appflow)
      - [AWS AppSync](#aws-appsync)
      - [Amazon EventBridge](#amazon-eventbridge)
      - [AWS Step Functions](#aws-step-functions)
      - [Amazon Simple Notification Service (Amazon SNS)](#amazon-simple-notification-service-amazon-sns)
      - [Amazon Simple Queue Service (Amazon SQS)](#amazon-simple-queue-service-amazon-sqs)
    - [💾 Compute](#-compute)
      - [EC2](#ec2)
      - [Amazon EC2 Auto Scaling](#amazon-ec2-auto-scaling)
      - [Lambda](#lambda)
      - [Fargate](#fargate)
      - [Elastic Beanstalk](#elastic-beanstalk)
      - [AWS Batch](#aws-batch)
      - [AWS Outposts](#aws-outposts)
      - [AWS Serverless Application Repository](#aws-serverless-application-repository)
      - [VMware Cloud on AWS](#vmware-cloud-on-aws)
      - [AWS Wavelength](#aws-wavelength)
      - [Amazon Lightsail](#amazon-lightsail)
    - [🐋 Container](#-container)
      - [Amazon ECS Anywhere](#amazon-ecs-anywhere)
      - [Amazon EKS Anywhere](#amazon-eks-anywhere)
      - [Amazon EKS Distro](#amazon-eks-distro)
      - [Amazon Elastic Container Registry (Amazon ECR)](#amazon-elastic-container-registry-amazon-ecr)
      - [Amazon Elastic Container Service (Amazon ECS)](#amazon-elastic-container-service-amazon-ecs)
      - [Amazon Elastic Kubernetes Service (Amazon EKS)](#amazon-elastic-kubernetes-service-amazon-eks)
      - [Amazon Aurora](#amazon-aurora)
      - [Amazon Aurora Serverless](#amazon-aurora-serverless)
      - [Amazon DocumentDB (with MongoDB compatibility)](#amazon-documentdb-with-mongodb-compatibility)
      - [Amazon DynamoDB](#amazon-dynamodb)
      - [Amazon ElastiCache](#amazon-elasticache)
      - [Amazon Keyspaces (for Apache Cassandra)](#amazon-keyspaces-for-apache-cassandra)
      - [Amazon Neptune](#amazon-neptune)
      - [Amazon Quantum Ledger Database (Amazon QLDB)](#amazon-quantum-ledger-database-amazon-qldb)
      - [Amazon RDS](#amazon-rds)
      - [Amazon Redshift](#amazon-redshift)
    - [🧰 Developer Tools](#-developer-tools)
      - [CodeCommit](#codecommit)
      - [CodeBuild](#codebuild)
      - [CodeDeploy](#codedeploy)
      - [CodePipeline](#codepipeline)
      - [CodeArtifact](#codeartifact)
      - [AWS X-Ray](#aws-x-ray)
    - [🌐 Edge \& IoT](#-edge--iot)
      - [AWS IoT Core](#aws-iot-core)
      - [AWS Greengrass](#aws-greengrass)
    - [🧑‍💻 End User \& Business Applications](#-end-user--business-applications)
      - [Amazon WorkSpaces](#amazon-workspaces)
      - [Amazon WorkSpaces Secure Browser](#amazon-workspaces-secure-browser)
      - [Amazon AppStream](#amazon-appstream)
      - [Amazon Connect](#amazon-connect)
      - [Amazon Simple Email Service (Amazon SES)](#amazon-simple-email-service-amazon-ses)
    - [📱 Front-End-Web and Mobile:](#-front-end-web-and-mobile)
      - [AWS Amplify](#aws-amplify)
      - [Amazon API Gateway](#amazon-api-gateway)
      - [AWS Device Farm](#aws-device-farm)
      - [Amazon Pinpoint](#amazon-pinpoint)
    - [🧰 Management \& Governance](#-management--governance)
      - [AWS Cost Explorer](#aws-cost-explorer)
      - [AWS Budgets](#aws-budgets)
      - [AWS Auto Scaling](#aws-auto-scaling)
      - [AWS CloudFormation](#aws-cloudformation)
      - [AWS CloudTrail](#aws-cloudtrail)
      - [Amazon CloudWatch](#amazon-cloudwatch)
      - [AWS Command Line Interface (AWS CLI)](#aws-command-line-interface-aws-cli)
      - [AWS Compute Optimizer](#aws-compute-optimizer)
      - [AWS Config](#aws-config)
      - [AWS Control Tower](#aws-control-tower)
      - [AWS Health Dashboard](#aws-health-dashboard)
      - [AWS License Manager](#aws-license-manager)
      - [Amazon Managed Grafana](#amazon-managed-grafana)
      - [Amazon Managed Service for Prometheus](#amazon-managed-service-for-prometheus)
      - [AWS Management Console](#aws-management-console)
      - [AWS Organizations](#aws-organizations)
      - [AWS Proton](#aws-proton)
      - [AWS Service Catalog](#aws-service-catalog)
      - [AWS Systems Manager](#aws-systems-manager)
      - [AWS Trusted Advisor](#aws-trusted-advisor)
      - [AWS Well-Architected Tool](#aws-well-architected-tool)
      - [AWS Cost and Usage Reports (AWS CUR)](#aws-cost-and-usage-reports-aws-cur)
      - [AWS Marketplace](#aws-marketplace)
      - [AWS Service Quotas](#aws-service-quotas)
    - [🎬 Media Services](#-media-services)
      - [Amazon Elastic Transcoder](#amazon-elastic-transcoder)
      - [Amazon Kinesis Video Streams](#amazon-kinesis-video-streams)
    - [🔄 Migration \& Transfer](#-migration--transfer)
      - [AWS Application Discovery Service](#aws-application-discovery-service)
      - [AWS Application Migration Service (MGN)](#aws-application-migration-service-mgn)
      - [AWS Database Migration Service (AWS DMS)](#aws-database-migration-service-aws-dms)
      - [AWS DataSync](#aws-datasync)
      - [AWS Migration Hub](#aws-migration-hub)
      - [AWS Snow Family](#aws-snow-family)
      - [AWS Transfer Family](#aws-transfer-family)
      - [Migration Evaluator](#migration-evaluator)
      - [AWS Schema Conversion Tool (AWS SCT)](#aws-schema-conversion-tool-aws-sct)
    - [🌐 Networking \& CDN](#-networking--cdn)
      - [AWS Client VPN](#aws-client-vpn)
      - [Amazon CloudFront](#amazon-cloudfront)
      - [AWS Direct Connect](#aws-direct-connect)
      - [Elastic Load Balancing (ELB)](#elastic-load-balancing-elb)
      - [AWS Global Accelerator](#aws-global-accelerator)
      - [AWS PrivateLink](#aws-privatelink)
      - [Amazon Route 53](#amazon-route-53)
      - [AWS Site-to-Site VPN](#aws-site-to-site-vpn)
      - [AWS Transit Gateway](#aws-transit-gateway)
      - [Amazon VPC (Virtual Private Cloud)](#amazon-vpc-virtual-private-cloud)
    - [📦 Storage \& Backup](#-storage--backup)
      - [AWS Backup](#aws-backup)
      - [Amazon Elastic Block Store (Amazon EBS)](#amazon-elastic-block-store-amazon-ebs)
      - [Amazon Elastic File System (Amazon EFS)](#amazon-elastic-file-system-amazon-efs)
      - [Amazon FSx (for Windows, Lustre, NetApp, OpenZFS)](#amazon-fsx-for-windows-lustre-netapp-openzfs)
      - [Amazon S3](#amazon-s3)
      - [Amazon S3 Glacier](#amazon-s3-glacier)
      - [AWS Storage Gateway](#aws-storage-gateway)
    - [🔒 Security, Identity \& Compliance](#-security-identity--compliance)
      - [AWS Artifact](#aws-artifact)
      - [AWS Audit Manager](#aws-audit-manager)
      - [AWS Certificate Manager (ACM)](#aws-certificate-manager-acm)
      - [AWS CloudHSM](#aws-cloudhsm)
      - [Amazon Cognito](#amazon-cognito)
      - [Amazon Detective](#amazon-detective)
      - [AWS Directory Service](#aws-directory-service)
      - [AWS Firewall Manager](#aws-firewall-manager)
      - [Amazon GuardDuty](#amazon-guardduty)
      - [AWS IAM Identity Center](#aws-iam-identity-center)
      - [AWS Identity and Access Management (IAM)](#aws-identity-and-access-management-iam)
      - [Amazon Inspector](#amazon-inspector)
      - [AWS Key Management Service (AWS KMS)](#aws-key-management-service-aws-kms)
      - [Amazon Macie](#amazon-macie)
      - [AWS Network Firewall](#aws-network-firewall)
      - [AWS Resource Access Manager (AWS RAM)](#aws-resource-access-manager-aws-ram)
      - [AWS Secrets Manager](#aws-secrets-manager)
      - [AWS Security Hub](#aws-security-hub)
      - [AWS Shield](#aws-shield)
      - [AWS WAF (Web Application Firewall)](#aws-waf-web-application-firewall)
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
    - [Amazon SageMaker Savings Plans](#amazon-sagemaker-savings-plans)
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
  - [AWS Well-Architected Framework Pillars](#aws-well-architected-framework-pillars)
    - [🧠 Operational Excellence](#-operational-excellence)
    - [🔐 Security](#-security)
    - [🔁 Reliability](#-reliability)
    - [⚙️ Performance Efficiency](#️-performance-efficiency)
    - [💰 Cost Optimization](#-cost-optimization)
    - [🌱 6. Sustainability (added in 2021)](#-6-sustainability-added-in-2021)
  - [AWS Cloud Adoption Framework](#aws-cloud-adoption-framework)
    - [🧩 Business Perspective](#-business-perspective)
    - [🧑‍🤝‍🧑 People Perspective](#-people-perspective)
    - [🏛️ Governance Perspective](#️-governance-perspective)
    - [🧱 Platform Perspective](#-platform-perspective)
    - [🔐 Security Perspective](#-security-perspective)
    - [🔧 Operations Perspective](#-operations-perspective)

## Services

### 🤖 AI & Machine Learning

#### Amazon Comprehend

Natural language processing (NLP) service.

> Amazon Comprehend uses machine learning to extract insights from unstructured text. It supports sentiment analysis, entity recognition, language detection, and topic modeling -- useful for analyzing documents, emails, or customer feedback.

#### Amazon Forecast

Time-series forecasting service.

> Amazon Forecast is a fully managed service that uses machine learning to generate accurate forecasts based on historical time-series data. It requires no ML experience and is often used for capacity planning, financial forecasts, and inventory optimization.

#### Amazon Fraud Detector

Real-time fraud detection service.

> Amazon Fraud Detector uses machine learning to identify potentially fraudulent activities in real time, such as online payment fraud or account takeover attempts. It's designed for use in finance, gaming, and e-commerce applications.

#### Amazon Kendra

Intelligent enterprise search.

> Amazon Kendra is a highly accurate enterprise search service powered by machine learning. It enables users to search across internal documents using natural language queries and delivers precise, context-aware answers.

#### Amazon Lex

Build conversational interfaces (chatbots).

> Amazon Lex provides advanced natural language understanding (NLU) and automatic speech recognition (ASR), making it easy to build voice and text chatbots for applications such as customer support, help desks, and IVR systems. It powers Alexa.

#### Amazon Polly

Convert text to lifelike speech.

> Amazon Polly is a text-to-speech (TTS) service that uses deep learning to synthesize natural-sounding human speech. It supports dozens of languages and voices, enabling voice features for apps, assistive tools, or content narration.

#### Amazon Rekognition

Analyze images and videos using ML.

> Amazon Rekognition provides image and video analysis capabilities like face detection, object recognition, content moderation, text detection, and facial comparison. It's used in security, media management, and customer analytics.

#### Amazon SageMaker

Build, train, and deploy ML models.

> Amazon SageMaker is an end-to-end machine learning platform that provides tools for data labeling, training, tuning, deploying, and monitoring models. It supports popular frameworks like TensorFlow and PyTorch and includes features like AutoML and model explainability.

#### Amazon Textract

Extract text and data from documents.

> Amazon Textract uses machine learning to automatically extract printed and handwritten text, tables, and forms from scanned documents -- going beyond OCR to understand layout and data context.

#### Amazon Transcribe

Automatic speech-to-text transcription.

> Amazon Transcribe converts spoken language into written text using deep learning. It supports real-time and batch transcription, speaker identification, custom vocabulary, and timestamps -- ideal for captions, call center transcripts, and voice interfaces.

#### Amazon Translate

Language translation with neural networks.

> Amazon Translate is a real-time and batch translation service that uses neural machine translation to deliver high-quality results. It supports dozens of languages and is useful for localization of apps, websites, and content.

#### Amazon Q

Generative AI assistant for AWS and enterprise tasks.

> Amazon Q is a generative AI-powered assistant designed to help users build, operate, and troubleshoot AWS applications more efficiently. It integrates with the AWS Console, IDEs (like VS Code), and documentation, enabling developers and IT teams to ask natural-language questions about AWS resources, code, or cloud operations. It also supports enterprise integrations to help employees query internal data securely using natural language.

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

#### AWS Data Exchange

Find and subscribe to third-party data.

> AWS Data Exchange allows you to easily find, subscribe to, and use third-party data in the cloud. It provides access to datasets from data providers such as Reuters, Foursquare, or Nasdaq. Data is delivered directly to Amazon S3, enabling integration with analytics and ML tools.

#### AWS Data Pipeline

Data workflow orchestration.

> AWS Data Pipeline is a web service that helps process and move data between different AWS compute and storage services and on-premises data sources. It allows scheduling, dependency management, and retry logic for workflows like ETL, backups, and log analysis.

#### AWS Lake Formation

Build secure data lakes quickly.

> Lake Formation simplifies setting up secure data lakes on AWS. It automates tasks like data ingestion, cataloging, transformation, and security configuration. It integrates with AWS Glue, IAM, and analytics tools to help you centralize and govern data for analytics and ML.

#### Amazon Managed Streaming for Apache Kafka (Amazon MSK)

Managed Apache Kafka service.

> Amazon MSK is a fully managed service for Apache Kafka that lets you build real-time data streaming applications. MSK handles provisioning, patching, and scaling while integrating with AWS security, monitoring, and data services like Lambda, Kinesis, and S3.

#### Amazon OpenSearch Service

Search and analytics engine.

> Amazon OpenSearch Service is a managed service that makes it easy to deploy, operate, and scale OpenSearch (formerly Elasticsearch) clusters. It's used for log analytics, real-time application monitoring, full-text search, and observability use cases.

### 🧩 App Integration

#### Amazon MQ

Managed message broker (ActiveMQ, RabbitMQ).

> Used for migrating legacy message-based apps that use traditional protocols like AMQP or STOMP.

#### Amazon AppFlow

Managed integration and data transfer between SaaS apps and AWS.

> Amazon AppFlow is a fully managed service that enables secure data transfer between SaaS applications (like Salesforce, Slack, Google Analytics) and AWS services like S3 and Redshift. It supports data transformation, filtering, and mapping as part of the flow and enforces security and compliance policies.

#### AWS AppSync

Managed GraphQL API service.

> AWS AppSync is a serverless service that simplifies building scalable GraphQL APIs. It integrates with DynamoDB, Lambda, Elasticsearch/OpenSearch, and other data sources. AppSync handles real-time subscriptions, offline data sync, and conflict resolution for mobile and web apps.

#### Amazon EventBridge

Event bus for decoupled app communication.

> Amazon EventBridge is a serverless event bus that connects application components using events from AWS services, SaaS apps, or custom sources. It routes events based on rules and helps build loosely coupled, event-driven architectures.

#### AWS Step Functions

Orchestrate workflows with visual state machines.

> AWS Step Functions lets you coordinate multiple AWS services into serverless workflows. It uses a visual JSON-based state machine to define tasks, branches, retries, and error handling -- ideal for automation, batch processing, and microservices orchestration.

#### Amazon Simple Notification Service (Amazon SNS)

Pub/Sub messaging for event-driven apps.

> Amazon SNS is a fully managed publish/subscribe messaging service that enables decoupled communication between components. It allows publishers to send messages to multiple subscribers (email, SMS, Lambda, SQS, HTTP) in real time. Common use cases include fan-out messaging, alerts, and notifications.

#### Amazon Simple Queue Service (Amazon SQS)

Message queuing for decoupled systems.

> Amazon SQS is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless apps. It offers two types of queues: Standard (best-effort ordering, high throughput) and FIFO (first-in-first-out, exactly-once delivery). SQS improves fault tolerance and load distribution.

### 💾 Compute

#### EC2

Scalable virtual servers in the cloud.

> Amazon EC2 lets you launch virtual machines with customizable OS, CPU, memory, and storage. You manage networking, scaling, and updates. It supports Auto Scaling and Load Balancers for high availability.

#### Amazon EC2 Auto Scaling

Automatically scale EC2 instances.

> EC2 Auto Scaling ensures your application always has the right number of instances by scaling up during demand spikes and down when not needed. It maintains high availability and optimizes cost, based on defined policies or target metrics.

#### Lambda

Run code without managing servers.

> Lambda is a serverless compute service that executes code in response to events (e.g., S3 uploads, API calls). You only pay for execution time, and there's no need to manage infrastructure. Ideal for microservices and event-driven architectures.

#### Fargate

Serverless containers for ECS and EKS.

> AWS Fargate runs containers without managing EC2 instances. You define the CPU and memory for your container tasks, and Fargate handles provisioning and scaling. It's great for simplifying container operations.

#### Elastic Beanstalk

Platform-as-a-Service for web apps.

> Beanstalk handles deployment and management of applications using EC2, RDS, S3, and more. You upload your code, and it takes care of provisioning, scaling, and health monitoring. It supports Java, .NET, Python, PHP, Node.js, and more.

#### AWS Batch

Run batch computing jobs at any scale.

> AWS Batch enables you to efficiently run hundreds to thousands of batch computing jobs. It automatically provisions the optimal compute resources based on volume and requirements, integrating with ECS or EC2 Spot for cost savings. Great for rendering, simulations, and data processing.

#### AWS Outposts

Run AWS infrastructure on-premises.

> AWS Outposts extends AWS infrastructure, services, APIs, and tools to on-premises environments for hybrid cloud use cases. It's ideal for workloads requiring low latency, local data processing, or on-site data residency.

#### AWS Serverless Application Repository

Discover and deploy serverless apps.

> The Serverless Application Repository is a curated collection of serverless apps built using AWS SAM. Developers can publish, share, and deploy Lambda-based applications with just a few clicks, accelerating reuse and development.

#### VMware Cloud on AWS

Run VMware workloads on AWS infrastructure.

> VMware Cloud on AWS allows businesses to migrate and run VMware-based workloads natively on AWS. It integrates vSphere, NSX, and vSAN with AWS compute, storage, and networking services -- simplifying hybrid cloud adoption.

#### AWS Wavelength

Low-latency applications at the network edge.

> AWS Wavelength brings AWS compute and storage services to the edge of telecom networks. It minimizes latency to deliver ultra-low-latency applications like AR/VR, live video streaming, and real-time gaming -- often below 10ms.

#### Amazon Lightsail

Simplified cloud platform for small apps and projects.

> Amazon Lightsail is an easy-to-use cloud platform that provides virtual servers (instances), managed databases, storage, networking, and more -- all bundled with predictable pricing. It's ideal for small businesses, quick prototypes, WordPress sites, or developers new to AWS who want a simplified experience without deep AWS service integration.

### 🐋 Container

#### Amazon ECS Anywhere

Run ECS workloads on your own infrastructure.

> Amazon ECS Anywhere extends the Amazon ECS control plane to manage and run container workloads on non-AWS environments, including on-premises servers or other cloud providers. It helps maintain consistent orchestration and monitoring across hybrid environments.

#### Amazon EKS Anywhere

Deploy EKS clusters on-premises.

> Amazon EKS Anywhere lets you create and operate Kubernetes clusters on your own infrastructure using VMware vSphere. It provides tooling for lifecycle management and integrates with AWS services like IAM and CloudWatch.

#### Amazon EKS Distro

Open-source Kubernetes distribution used by EKS.

> Amazon EKS Distro (EKS-D) is the same Kubernetes distribution that powers Amazon EKS. It provides the same secure, tested, and supported components for those who want to self-manage Kubernetes clusters on-premises or in other environments.

#### Amazon Elastic Container Registry (Amazon ECR)

Managed Docker container registry.

> Amazon ECR is a fully managed container image registry that integrates with ECS, EKS, and CI/CD tools. It supports Docker and OCI images, offering image scanning, IAM-based access control, and high availability.

#### Amazon Elastic Container Service (Amazon ECS)

Managed container orchestration.

> Amazon ECS is a fully managed container orchestration service for deploying Docker containers. It supports running containers on EC2 instances or serverless via AWS Fargate and integrates with IAM, CloudWatch, ALB, and Auto Scaling.

#### Amazon Elastic Kubernetes Service (Amazon EKS)

Managed Kubernetes on AWS.

> Amazon EKS is a managed service to run Kubernetes workloads in the AWS cloud or on-prem. It automates cluster provisioning, upgrades, and scalability while integrating tightly with other AWS services for networking, logging, and security.

> ### 🛢️ Database

#### Amazon Aurora

High-performance, MySQL- and PostgreSQL-compatible database.

> Amazon Aurora is a managed relational database engine that combines the speed and availability of high-end commercial databases with the simplicity of open-source MySQL and PostgreSQL. It offers up to 5x performance improvement over MySQL, automated backups, replication, and fault-tolerant storage.

#### Amazon Aurora Serverless

Auto-scaling version of Amazon Aurora.

> Aurora Serverless automatically adjusts database capacity based on usage. It's ideal for variable or intermittent workloads, and you only pay for what you use. It eliminates the need for manual provisioning or scaling.

#### Amazon DocumentDB (with MongoDB compatibility)

Managed document database compatible with MongoDB.

> Amazon DocumentDB is a fully managed NoSQL database that supports MongoDB workloads. It enables you to store, query, and index JSON-like documents and integrates with AWS security and monitoring tools.

#### Amazon DynamoDB

Serverless NoSQL key-value and document database.

> DynamoDB provides single-digit millisecond performance at any scale. It's a fully managed, serverless database supporting key-value and document models, with built-in security, backup, caching, and multi-region replication.

#### Amazon ElastiCache

In-memory caching with Redis or Memcached.

> ElastiCache is a fully managed in-memory data store service that improves application performance by retrieving data from fast, managed caches. It supports Redis and Memcached and is often used for caching, session management, or real-time analytics.

#### Amazon Keyspaces (for Apache Cassandra)

Managed Apache Cassandra-compatible database.

> Amazon Keyspaces lets you run Cassandra workloads on AWS without managing servers. It offers scalability, availability, and pay-as-you-go pricing, while using Cassandra Query Language (CQL) for compatibility.

#### Amazon Neptune

Managed graph database.

> Amazon Neptune is a fully managed graph database service optimized for storing and querying highly connected data. It supports popular graph models like Property Graph and RDF, and query languages such as Gremlin and SPARQL.

#### Amazon Quantum Ledger Database (Amazon QLDB)

Immutable and cryptographically verifiable ledger.

> Amazon QLDB provides a centralized, immutable ledger with full change history. It's designed for applications that require a trusted record of transactions, such as supply chain, finance, or regulatory compliance.

#### Amazon RDS

Managed relational database service.

> Amazon RDS makes it easy to set up, operate, and scale relational databases in the cloud. It supports MySQL, PostgreSQL, Oracle, SQL Server, and MariaDB, and automates backups, patching, and scaling.

#### Amazon Redshift

Fully managed cloud data warehouse.

> Redshift enables fast, SQL-based querying and analytics on large datasets using columnar storage and parallel processing. It integrates with BI tools and supports data lake queries with Redshift Spectrum.

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

#### AWS X-Ray

Distributed tracing and analysis.

> AWS X-Ray helps developers analyze and debug distributed applications, such as those built using microservices or serverless architectures. It provides insights into request flows, latencies, and errors by tracing requests as they travel through services.

### 🌐 Edge & IoT

#### AWS IoT Core

> Managed service for IoT device connectivity. AWS IoT Core allows you to securely connect, manage, and ingest data from billions of IoT devices. It supports device communication protocols and integrates with other AWS services for data processing and analytics.

#### AWS Greengrass

> IoT edge computing software. AWS Greengrass extends AWS functionality to edge devices so they can collect and analyze data locally, respond quickly to local events, and operate offline while syncing with the cloud when connected.

### 🧑‍💻 End User & Business Applications

#### Amazon WorkSpaces

Virtual desktops in the cloud.

> WorkSpaces provides Windows/Linux desktops on demand, accessible from any device. Good for remote work, secure environments, or temporary staff.

#### Amazon WorkSpaces Secure Browser

Secure, isolated browser access to web apps.

> Amazon WorkSpaces Secure Browser is a managed, isolated browser service that lets users securely access internal websites and SaaS apps without a VPN or exposing the network. It runs in a containerized environment on AWS, reducing the risk of malware or data leaks from unmanaged or compromised endpoints. Ideal for contractors, BYOD users, or remote access to sensitive apps.

#### Amazon AppStream

App streaming to user devices.

> AppStream streams desktop applications via browser without installing them locally. Ideal for training, demos, or remote access to desktop software.

#### Amazon Connect

Cloud-based contact center.

> Amazon Connect is an omnichannel contact center platform with voice, chat, and analytics. Fully managed and integrates with other AWS services like Lambda and S3.

#### Amazon Simple Email Service (Amazon SES)

Scalable, cloud-based email sending service.

> Amazon SES is a cost-effective, flexible, and scalable email service designed to help businesses send transactional, marketing, and bulk emails. It supports SMTP and API-based sending, real-time delivery metrics, reputation management, and email receiving. Common use cases include password resets, order confirmations, and promotional emails.

### 📱 Front-End-Web and Mobile:

#### AWS Amplify

Frontend and mobile app development platform.

> AWS Amplify is a set of tools and services that enables developers to quickly build, deploy, and scale full-stack web and mobile applications. It includes hosting, authentication, GraphQL/REST APIs, file storage, analytics, and CI/CD pipelines -- all designed to integrate with frameworks like React, Angular, iOS, and Android.

#### Amazon API Gateway

Create and manage APIs at scale.

> Amazon API Gateway is a fully managed service that allows you to create RESTful and WebSocket APIs. It acts as a front door for applications to access data and logic via Lambda, EC2, or other backends. API Gateway handles throttling, authentication, authorization, caching, and monitoring -- simplifying API development and scaling.

#### AWS Device Farm

Test mobile and web apps on real devices.

> AWS Device Farm is an app testing service that lets you test Android, iOS, and web applications on a wide range of real devices hosted in AWS. It supports manual testing and automated test scripts, helping to improve app quality and reduce testing time.

#### Amazon Pinpoint

User engagement and messaging service.

> Amazon Pinpoint enables you to send targeted push notifications, emails, SMS messages, and in-app messages to engage users across platforms. It's useful for marketing, user analytics, and transactional messaging, and supports segmentation, A/B testing, and campaign tracking.

### 🧰 Management & Governance

#### AWS Cost Explorer

Visualize and analyze AWS costs.

> Provides cost trends and forecasts to help manage budgets. Supports tagging and filtering.

#### AWS Budgets

Set custom cost and usage alerts.

> Budgets notify you when your usage or costs exceed a threshold. Can trigger automation via SNS.

#### AWS Auto Scaling

Automatically scale multiple AWS resources.

> AWS Auto Scaling monitors your applications and adjusts capacity across services like EC2, ECS, DynamoDB, and Aurora. It ensures high availability and performance while optimizing costs through dynamic scaling policies.

#### AWS CloudFormation

Infrastructure as Code using templates.

> AWS CloudFormation allows you to model and provision your cloud infrastructure using YAML or JSON templates. It automates resource creation, dependency management, and version control -- enabling repeatable, consistent deployments.

#### AWS CloudTrail

Logs all API calls in your account.

> CloudTrail records AWS API calls made through the console, CLI, SDKs, and services. It provides visibility into user activity and governance, helping with security analysis, compliance auditing, and troubleshooting.

#### Amazon CloudWatch

Monitor logs, metrics, and alarms.

> CloudWatch collects and tracks metrics, logs, and events for AWS resources and custom applications. It supports alerting, dashboards, and automated responses -- essential for observability and operational health.

#### AWS Command Line Interface (AWS CLI)

Command-line tool for AWS.

> The AWS CLI is a unified tool that enables you to manage AWS services from the command line. It supports scripting, automation, and integrates into CI/CD workflows, covering nearly all AWS functionality.

#### AWS Compute Optimizer

Recommends cost and performance improvements.

> Compute Optimizer uses machine learning to analyze historical usage of EC2, EBS, Lambda, and more -- providing actionable recommendations to reduce cost and improve performance by right-sizing your resources.

#### AWS Config

Track resource configurations and changes.

> AWS Config continuously records configuration changes of AWS resources and evaluates them against compliance rules. It enables auditing, security analysis, and operational troubleshooting over time.

#### AWS Control Tower

Set up and govern secure multi-account AWS environments.

> Control Tower automates the setup of secure landing zones based on best practices for multi-account AWS environments. It integrates with AWS Organizations, IAM, and Config to enforce governance and compliance at scale.

#### AWS Health Dashboard

Personalized view into AWS service health.

> The AWS Health Dashboard provides alerts and notifications about events that directly affect your AWS resources. It offers detailed, account-specific insights into outages, maintenance, and planned changes.

#### AWS License Manager

Track and manage software licenses.

> AWS License Manager helps you manage licenses for software like Microsoft, Oracle, or SAP across AWS and on-prem environments. It reduces licensing risk and prevents overspending through tracking and enforcement.

#### Amazon Managed Grafana

Managed Grafana dashboards on AWS.

> Amazon Managed Grafana provides a fully managed deployment of Grafana for observability dashboards. It integrates with CloudWatch, Prometheus, and other data sources, offering secure, scalable visualization with IAM-based access control.

#### Amazon Managed Service for Prometheus

Managed Prometheus monitoring.

> This service offers a scalable and highly available version of the open-source Prometheus monitoring system. It's ideal for collecting metrics from containerized workloads and integrates with Amazon Managed Grafana.

#### AWS Management Console

Web interface for AWS services.

> The AWS Management Console provides a user-friendly web interface to access and manage AWS services. It supports resource browsing, billing, IAM, deployment, and monitoring, with region switching and service documentation built-in.

#### AWS Organizations

Manage multiple AWS accounts centrally.

> AWS Organizations lets you create and manage multiple AWS accounts under one umbrella. It supports consolidated billing, policy control (SCPs), and account automation -- improving governance, compliance, and financial visibility.

#### AWS Proton

Automate infrastructure and CI/CD for microservices.

> AWS Proton enables platform teams to create reusable templates for microservices infrastructure and CI/CD. It ensures that application teams follow organizational standards while simplifying lifecycle management.

#### AWS Service Catalog

Curated product catalog for self-service.

> AWS Service Catalog allows organizations to create and manage approved products such as EC2 configurations, CloudFormation stacks, or serverless apps. It enables self-service deployments with governance and access control.

#### AWS Systems Manager

Unified operational hub for AWS resources.

> Systems Manager helps you manage EC2 instances and AWS resources at scale. It provides automation, patching, inventory, session management, parameter storage, and operational insights -- acting as a centralized admin console.

#### AWS Trusted Advisor

Recommendations for best practices.

> Trusted Advisor provides insights across five categories: cost optimization, performance, security, fault tolerance, and service limits. It analyzes your environment and recommends improvements to follow AWS best practices.

#### AWS Well-Architected Tool

Evaluate workloads against AWS best practices.

> The Well-Architected Tool helps you review your architecture using the five pillars of the AWS Well-Architected Framework. It provides actionable guidance to improve workloads across security, performance, cost, and more.

#### AWS Cost and Usage Reports (AWS CUR)

Detailed billing and usage data.

> AWS Cost and Usage Reports provide comprehensive data on your AWS usage and charges. They deliver detailed line-item reports to an S3 bucket in CSV or Parquet format, enabling deep analysis using tools like Athena, QuickSight, or Redshift. Useful for budgeting, chargebacks, and cost optimization.

#### AWS Marketplace

Curated catalog of third-party software.

> AWS Marketplace is a digital catalog where you can find, test, and deploy third-party software that runs on AWS. It includes AMIs, SaaS apps, container images, ML models, and data products. It simplifies procurement and billing with pay-as-you-go and BYOL options.

#### AWS Service Quotas

View and manage service limits for your AWS resources.\

> AWS Service Quotas help you monitor and manage the maximum usage limits for AWS services in your account. These quotas include soft limits (which you can request to increase) and hard limits (which are fixed). The Service Quotas console and API let you track usage against limits and submit increase requests where applicable. This ensures you avoid disruptions or failures when scaling applications.

### 🎬 Media Services

#### Amazon Elastic Transcoder

Convert media files into different formats.

> Amazon Elastic Transcoder is a media transcoding service in the cloud. It converts video and audio files from one format to another for compatibility across devices like smartphones, tablets, and browsers. It supports presets for popular formats and integrates with S3 and SNS for notifications.

#### Amazon Kinesis Video Streams

Ingest and process video streams.

> Amazon Kinesis Video Streams makes it easy to securely stream video from connected devices to AWS for analytics, machine learning, and playback. It supports real-time and batch processing, with automatic encryption, indexing, and integration with services like SageMaker and Rekognition.

### 🔄 Migration & Transfer

#### AWS Application Discovery Service

Discover on-premises infrastructure before migration.

> AWS Application Discovery Service collects information about your on-premises servers to help you plan your migration to AWS. It gathers data on CPU, memory, processes, and dependencies, which can be used for right-sizing and cost estimation in tools like Migration Hub.

#### AWS Application Migration Service (MGN)

Lift-and-shift server migration to AWS.

> AWS MGN replicates on-premises or cloud-based physical and virtual servers into AWS for rehosting (lift-and-shift) workloads. It automates replication, cutover, and testing, reducing manual steps during large-scale migrations.

#### AWS Database Migration Service (AWS DMS)

Migrate databases with minimal downtime.

> AWS DMS helps you migrate databases to AWS quickly and securely. It supports homogeneous (e.g., MySQL to MySQL) and heterogeneous (e.g., Oracle to PostgreSQL) migrations with ongoing replication. It minimizes downtime and data loss during transition.

#### AWS DataSync

Automate online data transfer to AWS.

> AWS DataSync is a service for transferring large amounts of data between on-premises storage and AWS services like S3, EFS, and FSx. It automates and accelerates file transfer while handling encryption, validation, and network optimization.

#### AWS Migration Hub

Central dashboard for migration tracking.

> Migration Hub provides a unified view to monitor and manage application migrations across multiple AWS and partner tools. It consolidates status tracking, progress reporting, and dependency mapping in one place.

#### AWS Snow Family

Physical devices for offline data transfer.

> The AWS Snow Family (Snowcone, Snowball, Snowmobile) enables edge computing and large-scale data migration. Devices are rugged, secure, and encrypted -- ideal for environments with limited or no connectivity, or petabyte-scale transfers.

#### AWS Transfer Family

Managed file transfer via SFTP, FTPS, FTP.

> AWS Transfer Family provides fully managed support for transferring files directly into and out of Amazon S3 using standard file transfer protocols like SFTP, FTPS, and FTP. It enables seamless integration with legacy systems and partners.

#### Migration Evaluator

Assess on-premises costs vs. AWS migration.

> AWS Migration Evaluator provides insights into your current on-premises environment and delivers data-driven cost projections for moving workloads to AWS. It collects usage data from existing infrastructure and generates a business case for cloud migration, including right-sizing and cost optimization recommendations.

#### AWS Schema Conversion Tool (AWS SCT)

Convert database schemas for migration.

> AWS Schema Conversion Tool helps convert database schemas and code objects (like stored procedures and functions) from one database engine to another (e.g., Oracle to PostgreSQL). It's used with AWS DMS to simplify heterogeneous database migrations by automating schema transformation and identifying manual conversion needs.

### 🌐 Networking & CDN

#### AWS Client VPN

Secure remote access to AWS and on-prem networks.

> AWS Client VPN is a fully managed, scalable VPN service that enables users to securely connect to AWS and on-premises networks from any location. It supports OpenVPN-based clients, authentication via IAM or Active Directory, and integrates with AWS networking services.

#### Amazon CloudFront

Global content delivery network (CDN).

> Amazon CloudFront delivers static and dynamic content, APIs, and video securely with low latency via a network of global edge locations. It integrates with S3, Lambda\@Edge, and Shield for DDoS protection and supports customizable caching and SSL.

#### AWS Direct Connect

Dedicated network connection to AWS.

> AWS Direct Connect establishes a private, high-bandwidth network link between your on-premises environment and AWS. It provides consistent performance, reduces bandwidth costs, and enhances security compared to public internet traffic.

#### Elastic Load Balancing (ELB)

Distribute traffic across resources.

> ELB automatically distributes incoming traffic across multiple targets such as EC2 instances, containers, and IP addresses. It includes Application Load Balancer (HTTP/HTTPS), Network Load Balancer (TCP/UDP), and Gateway Load Balancer (appliance-based use cases).

#### AWS Global Accelerator

Improve global application performance.

> AWS Global Accelerator uses the AWS global network to route user traffic to the optimal AWS endpoint based on health, geography, and routing policies. It improves availability and performance for global users by bypassing public internet bottlenecks.

#### AWS PrivateLink

Secure private connectivity to AWS services.

> AWS PrivateLink enables private access to AWS services and VPC endpoints without exposing traffic to the public internet. It enhances security by keeping traffic within the AWS network and supports services like S3, EC2, and custom applications.

#### Amazon Route 53

Scalable and reliable DNS service.

> Route 53 is AWS's domain name system (DNS) service, offering domain registration, routing, and health checks. It supports latency-based, weighted, and geolocation routing to optimize application availability and performance.

#### AWS Site-to-Site VPN

Connect on-prem networks to AWS via VPN.

> Site-to-Site VPN provides secure, encrypted communication between your on-premises network and AWS VPC over the public internet. It supports automatic failover and integrates with AWS Direct Connect and Transit Gateway.

#### AWS Transit Gateway

Central hub for VPC and on-prem network routing.

> Transit Gateway simplifies network architecture by acting as a central hub for connecting multiple VPCs, VPNs, and Direct Connect links. It improves scalability, reduces complexity, and supports inter-region peering.

#### Amazon VPC (Virtual Private Cloud)

Isolated cloud network environment.

> Amazon VPC lets you define and manage a logically isolated section of the AWS cloud. You control IP ranges, subnets, routing, firewalls (security groups and NACLs), internet access, and VPN connections to build secure, scalable network environments.

### 📦 Storage & Backup

#### AWS Backup

Centralized backup management.

> AWS Backup automates and centrally manages backups across AWS services like EFS, RDS, DynamoDB, EC2 (via EBS), and S3\. It enforces backup policies, supports compliance requirements, and allows cross-region and cross-account backup.

#### Amazon Elastic Block Store (Amazon EBS)

Block storage for EC2 instances.

> Amazon EBS provides persistent, high-performance block storage volumes for use with EC2\. It supports SSD and HDD volume types, encryption, snapshots, and can be attached or detached independently of the EC2 lifecycle.

#### Amazon Elastic File System (Amazon EFS)

Scalable shared file storage.

> Amazon EFS is a managed NFS file system that scales elastically with demand. It can be accessed concurrently from thousands of EC2 instances and integrates with Lambda, ECS, and on-prem systems via AWS Direct Connect.

#### Amazon FSx (for Windows, Lustre, NetApp, OpenZFS)

Managed high-performance file systems.

> Amazon FSx offers fully managed file storage optimized for different workloads: FSx for Windows File Server: SMB-based file storage for Windows apps. FSx for Lustre: High-speed file storage for HPC and ML. FSx for NetApp ONTAP: Hybrid storage with ONTAP features. FSx for OpenZFS: Open-source ZFS for Linux-based workloads.

#### Amazon S3

Scalable object storage.

> Amazon Simple Storage Service (S3) is object storage built for high durability, availability, and security. It stores data in buckets, supports lifecycle policies, event triggers, and is used for backups, static hosting, and data lakes.

#### Amazon S3 Glacier

Archival storage for long-term data.

> Amazon S3 Glacier and Glacier Deep Archive offer secure, durable, and low-cost storage for long-term backups and archives. It supports retrieval options ranging from minutes to hours depending on the tier.

#### AWS Storage Gateway

Hybrid cloud storage integration.

> AWS Storage Gateway connects on-premises environments with cloud storage, providing file, volume, and tape-based interfaces. It caches frequently accessed data locally and backs it up to S3 or Glacier, enabling cloud-based backup and disaster recovery.

### 🔒 Security, Identity & Compliance

#### AWS Artifact

Access compliance reports and agreements.

> AWS Artifact is a self-service portal for on-demand access to AWS's compliance documentation, including SOC, ISO, PCI, and HIPAA reports. It supports audit readiness, vendor assessments, and regulatory requirements.

#### AWS Audit Manager

Automate evidence collection for audits.

> AWS Audit Manager helps you continuously audit your AWS usage. It automatically collects evidence from AWS services to simplify compliance assessments for standards like GDPR, HIPAA, and ISO 27001.

#### AWS Certificate Manager (ACM)

Manage SSL/TLS certificates.

> ACM handles the provisioning, deployment, and renewal of public and private SSL/TLS certificates. It supports integration with services like CloudFront and ELB to enable HTTPS without manual cert management.

#### AWS CloudHSM

Dedicated hardware security module.

> AWS CloudHSM provides FIPS 140-2 Level 3-compliant hardware security modules for cryptographic key storage and operations. It offers full control over keys and integrates with custom security applications via standard APIs.

#### Amazon Cognito

User sign-up, sign-in, and identity management.

> Amazon Cognito enables you to add authentication, authorization, and user management to your web and mobile apps. It supports social logins (Google, Facebook), SAML, and user pools with fine-grained access control.

#### Amazon Detective

Analyze and visualize security investigations.

> Amazon Detective helps investigate and analyze potential security issues using data from GuardDuty, CloudTrail, and VPC Flow Logs. It provides visualizations and context to identify root causes and relationships across events.

#### AWS Directory Service

Manage directories in AWS.

> AWS Directory Service enables integration with Microsoft Active Directory for identity and access control. It supports applications that require AD and allows seamless AWS authentication and SSO integration.

#### AWS Firewall Manager

Centralized firewall and policy management.

> Firewall Manager simplifies security policy management across multiple AWS accounts and resources. It manages rules for AWS WAF, Shield, and VPC security groups from a central admin account in AWS Organizations.

#### Amazon GuardDuty

Threat detection and monitoring.

> GuardDuty is a threat detection service that uses ML and threat intelligence to identify suspicious behavior and potential threats in your AWS accounts. It analyzes logs from CloudTrail, VPC Flow Logs, and DNS activity.

#### AWS IAM Identity Center

Centralized identity and access control.

> IAM Identity Center enables single sign-on (SSO) to AWS accounts and cloud apps. It integrates with identity providers and supports role-based access control across multiple AWS accounts through AWS Organizations.

#### AWS Identity and Access Management (IAM)

Manage users, roles, and permissions.

> IAM lets you define who can access what in your AWS environment. It supports fine-grained access control through users, groups, roles, and policies -- foundational for secure cloud operations.

#### Amazon Inspector

Automated security assessment.

> Amazon Inspector is a vulnerability scanner for EC2, Lambda, and container workloads. It automatically assesses your infrastructure for security flaws, missing patches, and policy violations using CVE databases.

#### AWS Key Management Service (AWS KMS)

Manage encryption keys.

> AWS KMS allows you to create and control cryptographic keys used for data encryption across AWS services. It supports integrated key rotation, auditing, and fine-grained access controls.

#### Amazon Macie

Discover and protect sensitive data.

> Amazon Macie uses ML to automatically detect sensitive data such as PII and financial records in S3\. It classifies, tags, and monitors data to help ensure data privacy and regulatory compliance.

#### AWS Network Firewall

Managed network traffic filtering.

> AWS Network Firewall is a stateful, managed firewall for VPCs. It enables traffic inspection, rule enforcement, intrusion detection, and logging to protect VPC-level network boundaries.

#### AWS Resource Access Manager (AWS RAM)

Share AWS resources across accounts.

> AWS RAM lets you securely share AWS resources like subnets, Transit Gateways, or License Manager configurations across AWS accounts in your organization -- reducing duplication and increasing efficiency.

#### AWS Secrets Manager

Store and rotate secrets securely.

> AWS Secrets Manager manages secrets such as database credentials, API keys, and tokens. It automates rotation, access control, and auditing -- enhancing security for sensitive data.

#### AWS Security Hub

Centralized view of security findings.

> AWS Security Hub aggregates and prioritizes security alerts from AWS services like GuardDuty, Inspector, and Macie, as well as third-party tools. It helps you monitor compliance and overall security posture.

#### AWS Shield

DDoS protection for applications.

> AWS Shield offers always-on protection against DDoS attacks. Shield Standard is free for all customers, while Shield Advanced includes enhanced detection, 24/7 support, and cost protection.

#### AWS WAF (Web Application Firewall)

Protect applications from web threats.

> AWS WAF lets you create security rules to filter malicious web traffic to services like CloudFront, ALB, or API Gateway. It defends against threats like SQL injection, cross-site scripting (XSS), and bot traffic.

## Support Pläne

### 🟢 1\. Basic Support

- Zugriff auf AWS-Dokumentation, Whitepapers, Foren, Trusted Advisor – Core Checks

- Kein direkter technischer Support

### 🔵 2\. Developer Support

- E-Mail-Support während Geschäftszeiten

- 1 Benutzer kann Support-Anfragen stellen

- Antwortzeit < 24 Stunden bei allgemeinen Problemen

- Antwortzeit < 12 Stunden bei Systemausfall

### 🟠 3\. Business Support

- Rund-um-die-Uhr Support per E-Mail, Chat und Telefon

- Zugriff auf alle Trusted Advisor Checks

- Support für Drittanbieter-Software (z. B. Ubuntu, Docker, etc.)

- Nutzung von AWS Personal Health Dashboard

- Antwortzeit < 1 Stunde bei „Production System Down"

- Antwortzeit < 12–24 Stunden bei weniger kritischen Problemen

### 🔴 4\. Enterprise Support

- Technischer Account Manager (TAM) – dein persönlicher AWS-Ansprechpartner

- Architektur-Reviews, operative Reviews

- Zugang zu Infrastructure Event Management (IEM) – z. B. bei großen Releases oder Migrationsprojekten

- Antwortzeit < 15 Minuten bei „Business-Critical System Down"

--------------------------------------------------------------------------------

## EC2 Instanz Typen

### Spot

Spot Instances can be interrupted, making them unsuitable for production workloads requiring 24/7 availability.

### Reserved

Reserved Instances provide up to 72% discount for predictable, steady-state workloads with 1 or 3-year commitments.

### On Demand

On-Demand pricing offers flexibility but costs more for 24/7 workloads compared to commitment-based options.

--------------------------------------------------------------------------------

## EC2 Pricing Plans

### Compute Savings Plans

Most flexible option.

Applies to any EC2 instance, regardless of region, instance family, OS, or tenancy.

Also applies to Fargate and AWS Lambda.

Example: You can switch from c5 to m6g, or from us-east-1 to eu-west-1 without losing your discount.

Use case: Best for dynamic or evolving workloads.

### EC2 Instance Savings Plans

Less flexible, but more savings than Compute Savings Plans.

Applies to a specific instance family in a specific region (e.g., m5 in us-east-1).

Flexibility within: OS , Size (e.g., from m5.large to m5.4xlarge) , Tenancy (shared/dedicated), Availability Zone

Use case: Best when workloads are stable in terms of instance family and region.

### Amazon SageMaker Savings Plans

Applies specifically to Amazon SageMaker services (e.g., training, hosting).

Commitment to a consistent usage ($/hr).

Applies across all SageMaker instance types and usage types.

Use case: Cost-effective for organizations using SageMaker for ML model training and inference.

--------------------------------------------------------------------------------

## Disaster Recovery

![](https://docs.aws.amazon.com/images/whitepapers/latest/disaster-recovery-workloads-on-aws/images/disaster-recovery-strategies.png)

--------------------------------------------------------------------------------

## S3 Storage Klassen

### S3 Standard

- **Use case:** Frequently accessed ("hot") data.
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

Storage Class                 | Access Frequency | Availability | Durability | Cost     | Retrieval Time                | Use Case
----------------------------- | ---------------- | ------------ | ---------- | -------- | ----------------------------- | ----------------------------------
S3 Standard                   | Frequent         | 99.99%       | 11 nines   | High     | Milliseconds                  | Active data, websites
S3 Intelligent-Tiering        | Variable         | 99.9%+       | 11 nines   | Medium   | Milliseconds                  | Unknown access patterns
S3 Standard-IA                | Infrequent       | 99.9%        | 11 nines   | Lower    | Milliseconds + retrieval fees | Backups, DR
S3 One Zone-IA                | Infrequent       | 99.5% (1 AZ) | 11 nines   | Lowest   | Milliseconds + retrieval fees | Secondary backups, cost-sensitive
S3 Glacier Instant Retrieval  | Rare             | 99.99%       | 11 nines   | Low      | Milliseconds                  | Long-term archive with fast access
S3 Glacier Flexible Retrieval | Rare             | 99.99%       | 11 nines   | Very Low | Minutes to hours              | Compliance archives
S3 Glacier Deep Archive       | Very Rare        | 99.99%       | 11 nines   | Cheapest | Up to 12 hours or more        | Long-term legal/regulatory archive

--------------------------------------------------------------------------------

## AWS Well-Architected Framework Pillars

### 🧠 Operational Excellence

Focus: Operations monitoring, automation, and improvement.

- Perform operations as code

- Make frequent, small, reversible changes

- Anticipate failure and learn from it

- Evolve procedures with experience

### 🔐 Security

Focus: Protecting data, systems, and assets.

- Identity and access management (IAM)

- Detective controls (e.g., CloudTrail, GuardDuty)

- Infrastructure protection

- Data protection (encryption, KMS, Secrets Manager)

- Incident response

### 🔁 Reliability

Focus: System recovery and failure prevention.

- Distributed system design

- Recovery planning

- Monitoring and failure detection

- Auto scaling and self-healing

### ⚙️ Performance Efficiency

Focus: Optimal resource usage and architecture.

- Serverless and managed services

- Monitoring and autoscaling

- Experimentation and evolutionary design

- Global infrastructure usage

### 💰 Cost Optimization

Focus: Eliminating unnecessary costs.

- Right-sizing resources

- Using pricing models (e.g., Savings Plans, Spot)

- Measuring and monitoring cost

- Eliminating unused resources

### 🌱 6\. Sustainability (added in 2021)

Focus: Environmental impact of cloud workloads.

- Optimizing resource use for energy efficiency

- Selecting efficient architectures

- Reducing downstream impacts (e.g., data transfer, hardware)

- Measuring sustainability metrics

--------------------------------------------------------------------------------

## AWS Cloud Adoption Framework

### 🧩 Business Perspective

Focus: Business goals and outcomes.

Who's involved: Executives, finance, strategy leaders.

- Business case development

- Cloud value realization

- Risk management

- KPIs and success metrics

### 🧑‍🤝‍🧑 People Perspective

Focus: Organizational change management.

Who's involved: HR, training, leadership.

- Culture and change enablement

- Skill development and training

- Roles and responsibilities alignment

### 🏛️ Governance Perspective

Focus: Cloud governance, compliance, and controls.

Who's involved: Risk, compliance, finance, and audit teams.

- Policies and guardrails

- Budgeting and cost control

- Compliance and legal considerations

### 🧱 Platform Perspective

Focus: Technical architecture and infrastructure.

Who's involved: Architects, engineers, ops.

- Cloud architecture

- Deployment automation (IaC)

- Network and compute design

### 🔐 Security Perspective

Focus: Protection of data and systems.

Who's involved: Security teams, compliance officers.

- Identity and access management

- Data protection and encryption

- Threat detection and response

### 🔧 Operations Perspective

Focus: Monitoring and operations management.

Who's involved: DevOps, operations, support.

- Monitoring and observability

- Incident management

- Continuous improvement
