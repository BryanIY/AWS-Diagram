E-Commerce Diagram

Cloud Front – Securely deliver content with low latency and high transfer speeds 

AWS Route 53 - Amazon Route 53 is a highly available and scalable Domain Name System (DNS) web service. Route 53 connects user requests to internet applications running on AWS or on-premises. 

AWS WAF - AWS WAF helps you protect against common web exploits and bots that can affect availability, compromise security, or consume excessive resources. 

Cognito - With Amazon Cognito, you can add user sign-up and sign-in features and control access to your web and mobile applications.  

S3 
- From Cloudfront – Host static content such as e-commerce website, HTML, JavaScript, and images.  

API Gateaway – APIs act as the "front door" for applications to access data, business logic, or functionality from your backend services. 

Lambda 
- Order Service - receives requests related to orders such as create new/cancel/return an order
- Inventory Service – return information about available inventory for a product.
- Cart Service - can add or remove items from a cart
- Search Service – return a search from index content 

Workflow/ AWS Step Functions 
- Order will be made by - Step Functions is a visual workflow service that helps developers use AWS services to build distributed applications, automate processes, orchestrate microservices, and create data and machine learning (ML) pipelines.
- New Order
- Cancel Order
- Return Order 

SNS - provides high-throughput, push-based, many-to-many messaging between distributed systems, microservices, and event-driven serverless applications 

SQS - lets you send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available. 

DynamoDB – Amazon DynamoDB is a serverless, NoSQL database service that enables you to develop modern applications at any scale. 

Kinesis- Amazon Kinesis is a significant feature in AWS for easy collection, processing, and analysis of video and data streams in real-time environments.  

Data Stream - serverless streaming data service that makes it easy to capture, process, and store data streams at any scale. 

Firehose - provides the easiest way to acquire, transform, and deliver data streams within seconds to data lakes, data warehouses, and analytics services. Firehose also helps in streaming to RedShift, S3, or ElasticSearch service, to copy data for processing by using additional services. 

Open Search - Amazon OpenSearch Service makes it easy for you to perform interactive log analytics, real-time application monitoring, website search, and more.  

S3 – from kinesis – it saves the data into S3 

SageMaker – Amazon SageMaker is a fully managed service that brings together a broad set of tools to enable high-performance, low-cost machine learning (ML) for any use case. To understand the trend.  

Quick Sight – Amazon QuickSight powers data-driven organizations with unified business intelligence (BI) at hyperscale. Visualise the data from Athena.  

Athena - Amazon Athena is a serverless, interactive analytics service built on open-source frameworks, supporting open-table and file formats. It query s3 data 

Ref: https://www.youtube.com/watch?v=M-l7gVm69KI 
