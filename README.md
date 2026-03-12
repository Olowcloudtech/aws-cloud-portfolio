# AWS Cloud Architecture Portfolio
Author: Ahmed O.

This repository contains hands-on AWS cloud architecture projects built to strengthen practical knowledge of Amazon Web Services (AWS) and prepare for real-world cloud engineering and solutions architect responsibilities.

The projects in this portfolio demonstrate core AWS architecture patterns including networking, compute, storage, serverless design, decoupled systems, and high availability.

---

## Architecture Overview

![AWS Architecture](diagrams/aws_portfolio_master_clean.png)

---

## Projects

### 1. VPC + EC2 Web Server Architecture

Built a web server on Amazon EC2 inside a VPC and configured internet access using a public IP address. Installed Apache and deployed a simple web page to validate connectivity.

**Services used:**
- Amazon VPC
- Amazon EC2
- Security Groups
- Public IP addressing

**Concepts practiced:**
- VPC networking
- Public subnet access
- Web server deployment
- Basic compute architecture

---

### 2. Application Load Balancer + EC2 Architecture

Built a load-balanced web architecture by placing an Application Load Balancer in front of an EC2 web server and registering the instance in a target group.

**Services used:**
- Application Load Balancer
- Target Groups
- Amazon EC2
- Health Checks

**Concepts practiced:**
- Traffic distribution
- High availability design
- Health checks
- Load balancing architecture

---

### 3. Serverless REST API

Built a serverless API using API Gateway, AWS Lambda, and DynamoDB to process and return data.

**Architecture:**

API Gateway → Lambda → DynamoDB

**Services used:**
- Amazon API Gateway
- AWS Lambda
- Amazon DynamoDB
- Amazon CloudWatch

**Concepts practiced:**
- Serverless backend architecture
- API integrations
- NoSQL database usage
- Event-driven compute

---

### 4. Decoupled Queue Processing Architecture

Built a decoupled serverless architecture where one Lambda function sends messages to Amazon SQS, a second Lambda function processes the queue messages, and the results are stored in DynamoDB.

**Architecture:**

Lambda (Producer) → SQS → Lambda (Consumer) → DynamoDB

**Services used:**
- AWS Lambda
- Amazon SQS
- Amazon DynamoDB
- Amazon CloudWatch
- IAM Roles

**Concepts practiced:**
- Decoupled architecture
- Asynchronous processing
- Queue-based workloads
- Event-driven messaging

---

### 5. Static Website Hosting

Hosted a static website using Amazon S3 and validated public access configuration.

**Services used:**
- Amazon S3

**Concepts practiced:**
- Static website hosting
- Object storage
- Public website delivery

---

### 6. Event-Driven Data Processing Pipeline

Built an event-driven architecture where data upload and processing services work together using AWS managed services.

**Services used:**
- Amazon S3
- AWS Lambda
- Amazon OpenSearch
- Amazon CloudWatch
- IAM Roles

**Concepts practiced:**
- Event-driven architecture
- Serverless data processing
- Search and indexing workflows

---

## AWS Services Used

- Amazon VPC
- Amazon EC2
- Application Load Balancer
- Target Groups
- Security Groups
- Amazon S3
- Amazon API Gateway
- AWS Lambda
- Amazon DynamoDB
- Amazon SQS
- Amazon OpenSearch
- Amazon CloudWatch
- AWS IAM

---

## Key Architecture Patterns Practiced

- Web server deployment on EC2
- Load-balanced web architecture
- Serverless API design
- Decoupled queue-based systems
- Static website hosting
- Event-driven processing pipelines

---

## Repository Structure

aws-cloud-portfolio

├── diagrams  
│   ├── aws_portfolio_master_clean.png  
│   ├── aws-cloud-portfolio-architecture.png  
│   ├── aws-cloud-portfolio-architecture2.png  
│   ├── aws-cloud-portfolio-architecture3.png  
│   └── aws-cloud-portfolio-architecture4.png  

├── vpc-architecture  
├── s3-static-website  
├── lambda-serverless-api  
├── sqs-lambda-dynamodb-lab  
├── alb-ec2-webserver-lab  

└── README.md

---

## Author

Ahmed O.  
AWS Cloud Architecture Portfolio
# Author

Ahmed O.  
AWS Cloud Architecture Portfolio
