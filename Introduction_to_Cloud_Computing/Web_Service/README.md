# 📘 Summary: Web Services & AWS Overview

## 🌐 What is a Web Service?
- A **web service** is any software that is accessible over the internet or a private network.
- Uses **standardized formats** like **XML** or **JSON** for API requests and responses.
- Is **platform-independent** (not tied to any OS or programming language).
- **Self-describing** via interface definition files and **discoverable** by others.

---

## ☁️ What is Amazon Web Services (AWS)?
- A **secure cloud platform** offering a wide range of global cloud-based products.
- Provides **on-demand access** to compute, storage, network, database, and more.
- AWS resources can be **provisioned in minutes**.
- Services are **flexible**, **scalable**, and **cost-effective**.
- Charges become **operational expenses**, not capital expenses.
- AWS services act like **building blocks** to build scalable solutions.

---

## 🧮 AWS Service Categories and Examples

### 🚀 Compute Services:
- Amazon EC2
- AWS Lambda
- AWS Elastic Beanstalk
- Amazon ECS, EKS, ECR
- AWS Fargate

### 🔐 Security, Identity, and Compliance:
- AWS IAM
- Amazon Cognito
- AWS Shield
- AWS KMS, Artifact

### 🗄️ Storage Services:
- Amazon S3, S3 Glacier
- Amazon EFS, EBS

### 🗃️ Database Services:
- Amazon RDS
- Amazon DynamoDB
- Amazon Redshift
- Amazon Aurora

### 🌐 Networking & Content Delivery:
- Amazon VPC
- Route 53
- CloudFront
- Elastic Load Balancing

### 🧰 Management & Governance:
- AWS CloudWatch
- AWS CloudTrail
- AWS Trusted Advisor
- AWS Config
- AWS Management Console, CLI, Well-Architected Tool, Organizations

### 💰 Cost Management:
- AWS Budgets
- AWS Cost Explorer
- AWS Cost & Usage Report

---

## 🛠️ How to Access AWS Services
1. **AWS Management Console** – Web-based UI for interacting with AWS.
2. **AWS CLI (Command Line Interface)** – Terminal-based access for scripting and automation.
3. **AWS SDKs** – Programming language-specific tools to use AWS in code.


#  AWS Cloud Practitioner – Sample Questions with Explanations

---

### 1.  Which of the following are true about web services? *(Select TWO)*

-  Use standardized formats like XML and JSON  
-  Can be accessed via the internet or private network  
-  Are tied to a specific operating system  
-  Require installation on the user’s local device  

<details>
  <summary>Click to view answer and explanation</summary>
   **Correct Answers:**
  - Web services use formats like **XML/JSON** for API communication.
  - They are accessible over the **internet or intranet**.

  ❌ **Incorrect Options:**
  - Web services are **platform-independent**.
  - They do **not require installation** on a user's device; they are accessed remotely.
</details>

---

### 2.  Which AWS compute services allow you to run code without managing servers? *(Select TWO)*

-  AWS Lambda  
-  AWS Fargate  
-  Amazon RDS  
-  Amazon S3  

<details>
  <summary>Click to view answer and explanation</summary>
   **Correct Answers:**
  - **AWS Lambda** runs code serverlessly in response to events.
  - **AWS Fargate** allows you to run containers without managing infrastructure.

  ❌ **Incorrect Options:**
  - **Amazon RDS** is a **database** service.
  - **Amazon S3** is an **object storage** service.
</details>

---

### 3.  Which methods can be used to access and manage AWS resources? *(Select THREE)*

-  AWS Management Console  
-  AWS CLI (Command Line Interface)  
-  AWS SDKs  
-  AWS CloudFormation Templates  

<details>
  <summary>Click to view answer and explanation</summary>
   **Correct Answers:**
  - AWS resources can be managed through:
    - **AWS Management Console**
    - **AWS CLI**
    - **AWS SDKs**

  ❌ **Incorrect Option:**
  - **CloudFormation** is used to define infrastructure as code, not directly manage it.
</details>

---

### 4.  Which of the following are advantages of using AWS Cloud over traditional IT infrastructure? *(Select THREE)*

-  Pay-as-you-go pricing  
-  Global deployment in minutes  
-  Ability to scale automatically  
-  Higher capital expense up front  

<details>
  <summary>Click to view answer and explanation</summary>
   **Correct Answers:**
  - **Pay-as-you-go** means you pay only for what you use.
  - **Global deployment** is fast with AWS's many regions.
  - **Auto-scaling** allows infrastructure to adapt to demand.

  ❌ **Incorrect Option:**
  - AWS **reduces** capital expense by using **operational expense (OpEx)** model.
</details>

---

### 5.  Which AWS services belong under the **Security, Identity, and Compliance** category? *(Select TWO)*

-  AWS IAM  
-  Amazon Cognito  
-  Amazon CloudWatch  
-  Amazon S3  

<details>
  <summary>Click to view answer and explanation</summary>
   **Correct Answers:**
  - **IAM**: Controls access to AWS services.
  - **Cognito**: Manages user authentication and sign-in.

  ❌ **Incorrect Options:**
  - **CloudWatch** is used for **monitoring and observability**.
  - **S3** is a **storage** service.
</details>
