# Hi, I'm Yabesh 👋

### Cloud & DevOps Enthusiast | AWS | GCP | Docker | Linux | Python

I'm a Computer Science Engineering graduate focused on building practical skills in **Cloud Computing and DevOps**.

I enjoy designing and deploying cloud architectures, working with containers, networking, serverless applications, security, and highly available infrastructure.

Currently expanding my skills in **AWS, Google Cloud, Docker, Terraform, CI/CD, and Kubernetes**.

---

## 🚀 Featured Projects

### 🛒 CloudMart — Multi-AZ E-Commerce Application

Highly available three-tier e-commerce application deployed across multiple AWS Availability Zones with private application and database tiers.

**Technologies:**  
`AWS` `VPC` `EC2` `ALB` `Auto Scaling` `Aurora MySQL` `S3` `SQS` `Cognito` `IAM` `CloudWatch`

**Highlights:**
- Multi-AZ architecture
- Public and private subnet design
- Internet-facing Application Load Balancer
- EC2 Auto Scaling
- Aurora MySQL writer and reader
- Asynchronous order processing using Amazon SQS
- Cognito user authentication and admin authorization
- Private S3 storage with presigned URLs
- IAM role-based AWS access
- CloudWatch monitoring

[View Project](https://github.com/yabeshisaac/aws-cloudmart-multiaz-ecommerce)

---

### 🔐 AWS Client VPN — Secure Private VPC Access

Secure remote-access architecture allowing an authorized client to connect to a private EC2 instance without exposing the instance directly to the public internet.

**Technologies:**  
`AWS Client VPN` `VPC` `EC2` `ACM` `Mutual TLS` `Security Groups` `Private Networking`

**Highlights:**
- Mutual TLS authentication
- ACM-imported server and client certificates
- Private EC2 instance with no public IPv4 address
- Client VPN subnet association
- VPN authorization rules
- VPC routing configuration
- Security group controlled access
- Successful SSH access through the encrypted VPN tunnel

[View Project](https://github.com/yabeshisaac/aws-client-vpn-secure-access)

---

### 🐳 AWS Docker Multi-Web Server Deployment

Containerization project running multiple Apache and Nginx web servers on a single Amazon EC2 instance and working with container image registries.

**Technologies:**  
`Amazon EC2` `Docker` `Amazon ECR` `Docker Hub` `Apache` `Nginx` `Linux` `IAM`

**Highlights:**
- Six Docker containers running on one EC2 instance
- Apache and Nginx web server containers
- Docker port mapping
- Custom Docker images
- Docker Hub image publishing
- Private Amazon ECR repository
- IAM-based ECR authentication
- Container image push and pull workflow
- Application redeployment from Amazon ECR

[View Project](https://github.com/yabeshisaac/aws-docker-multi-web-server)

---

### ⚡ AWS Serverless Image Thumbnail Generator

Full-stack serverless image-processing web application that allows users to upload images from a browser, automatically generate optimized thumbnails, preview the result, and download the processed image.

**Technologies:**  
`AWS Lambda` `Amazon S3` `API Gateway` `Python` `Pillow` `JavaScript` `HTML` `CSS` `IAM` `CloudWatch`

**Highlights:**
- Interactive browser-based image upload and preview
- Static frontend hosted using Amazon S3
- API Gateway HTTP API
- API Gateway integration with AWS Lambda
- Secure direct-to-S3 uploads using presigned URLs
- S3 `ObjectCreated` event-driven processing
- Automatic Lambda invocation after image upload
- Python and Pillow image processing
- Thumbnail generation up to 300×300 while preserving aspect ratio
- Automatic thumbnail display without page refresh
- Browser-based thumbnail download
- Separate source and destination S3 buckets
- IAM-based access control
- CloudWatch logging and monitoring
- Fully serverless architecture with no EC2 servers

[View Project](https://github.com/yabeshisaac/aws-serverless-thumbnail-generator)

---

## 🛠️ Technical Skills

### ☁️ Cloud Platforms

`AWS` `Google Cloud`

### 🔶 AWS

`EC2` `S3` `Lambda` `VPC` `IAM` `API Gateway` `ALB` `Auto Scaling` `Aurora/RDS` `SQS` `ECR` `Cognito` `CloudWatch` `Client VPN` `ACM`

### ⚙️ DevOps & Infrastructure

`Docker` `Linux` `Git` `GitHub`

Currently learning:

`Terraform` `CI/CD` `Kubernetes`

### 💻 Programming

`Python` `JavaScript` `HTML` `CSS`

### 🗄️ Databases

`MySQL` `Amazon Aurora`

### 🔐 Cloud & Networking Concepts

`VPC Networking` `Public/Private Subnets` `Security Groups` `IAM` `Load Balancing` `Auto Scaling` `High Availability` `Serverless Architecture` `Event-Driven Architecture`

---

## 📚 Currently Learning

- AWS Solutions Architect Associate
- Google Cloud Associate Cloud Engineer
- Terraform
- CI/CD automation
- Kubernetes
- Infrastructure as Code
- Cloud architecture best practices
- Cloud security and networking

---

## 🎯 Current Focus

My current goal is to strengthen my practical knowledge across:

```text
Cloud Architecture
        +
Infrastructure as Code
        +
Containers
        +
CI/CD
        +
Cloud Networking
        +
Cloud Security

I'm continuing to build hands-on projects that combine these technologies into practical Cloud and DevOps solutions.

📂 What I'm Building

My projects currently focus on different areas of cloud engineering:

Project	Main Focus
CloudMart	Multi-AZ Architecture & High Availability
AWS Client VPN	Cloud Networking & Security
Docker Multi-Web Server	Containers & Container Registries
Serverless Thumbnail Generator	Serverless & Event-Driven Architecture

My next focus is expanding these skills into Infrastructure as Code, automated deployments, and container orchestration.

📫 Connect With Me
GitHub: yabeshisaac
LinkedIn: Yabesh J

Building practical cloud projects one architecture at a time. ☁️
