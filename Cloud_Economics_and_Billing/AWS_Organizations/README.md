# 🏢 AWS Organizations Summary

## 📦 Overview

AWS Organizations is a **free account management service** that allows you to consolidate multiple AWS accounts into a single organization.  
It offers:

- Centrally managed access policies
- Controlled service access
- Automated account creation
- Consolidated billing

---

## 🌳 Terminology: Organizational Units (OUs)

- An **OU** is a container within the organization root that can group accounts or other OUs.
- Hierarchical structure like an **inverted tree**: root → OUs → accounts.
- **Policies** attached to any node flow downward and affect all child nodes.
- Each account belongs to only **one OU**.

---

## 🛠️ Key Features & Benefits

- Create **Service Control Policies (SCPs)** to manage service access across accounts.
- Use **groups of accounts** for policy management.
- Automate account creation with **APIs**.
- Simplify billing with **consolidated billing**:
  - View charges in one place
  - Get pricing benefits from usage aggregation

---

## 🔐 Security with IAM & SCPs

- **IAM policies** manage access within individual AWS accounts.
- IAM allows or denies access to specific users, roles, or groups.
- IAM **does not** restrict the root user.
- **SCPs** in AWS Organizations:
  - Manage access across multiple accounts or OUs
  - Apply to **all IAM entities**, including the **root user**

---

## 🧭 Setup Steps

1. **Create** your organization with a primary account
2. **Create OUs** and assign accounts
3. **Create SCPs** to apply service restrictions
4. **Test** restrictions using test accounts or IAM policy simulator

🔗 IAM Policy Simulator: [Test IAM policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_testing-policies.html)

---

## 🚫 Limits in AWS Organizations

- Max name length: **250 Unicode characters**
- Limits include:
  - **1 root**
  - **1,000 OUs**
  - **1,000 policies**
  - **Max SCP size**: 5,120 bytes
  - **Max BU nesting**: 5 levels
  - **20 invitations/day**
  - **5 concurrent account creations**

---

## 🧑‍💻 Access Methods

AWS Organizations can be accessed via:

- 🖥️ **AWS Management Console** – GUI-based access
- 🧾 **AWS CLI** – Command-line access
- 💻 **AWS SDKs** – For multiple programming languages
- 🔐 **HTTPS Query API** – Programmatic access with request signing

---

# ❓ AWS Organizations – Questions & Answers

---

### 1️⃣ What is the main purpose of AWS Organizations?

- A. To provide compute resources for developers
- B. To consolidate multiple AWS accounts into a centrally managed organization
- C. To replace AWS Identity and Access Management (IAM)
- D. To monitor AWS budgets and alarms

<details>
<summary><strong>Answer</strong></summary>
<strong>B. To consolidate multiple AWS accounts into a centrally managed organization</strong>  
AWS Organizations helps manage multiple AWS accounts with consolidated billing and centralized policy control.
</details>

---

### 2️⃣ Which of the following is a feature of **Service Control Policies (SCPs)** in AWS Organizations?

- A. They apply only to IAM users and groups
- B. They control costs and budgets across accounts
- C. They allow or deny access to AWS services for accounts or organizational units
- D. They automatically encrypt all resources in the OU

<details>
<summary><strong>Answer</strong></summary>
<strong>C. They allow or deny access to AWS services for accounts or organizational units</strong>  
SCPs provide centralized control over AWS services across accounts within an organization.
</details>

---

### 3️⃣ Which of the following does **consolidated billing** in AWS Organizations enable?

- A. Automatic resource provisioning
- B. One invoice for all accounts and potential volume discounts
- C. Free usage of all AWS services
- D. Security automation across all AWS accounts

<details>
<summary><strong>Answer</strong></summary>
<strong>B. One invoice for all accounts and potential volume discounts</strong>  
Consolidated billing allows organizations to manage charges centrally and benefit from usage aggregation.
</details>

---

### 4️⃣ How can developers automate AWS account management in AWS Organizations?

- A. By using CloudFormation templates
- B. By using application programming interfaces (APIs)
- C. By using CloudWatch dashboards
- D. By enabling IAM MFA

<details>
<summary><strong>Answer</strong></summary>
<strong>B. By using application programming interfaces (APIs)</strong>  
APIs allow the automation of account creation and management tasks in AWS Organizations.
</details>

---

### 5️⃣ Which of the following statements about IAM and SCPs is **TRUE**?

- A. SCPs only apply to IAM users, not the root account
- B. IAM policies can override SCPs
- C. SCPs affect all IAM users, groups, and even the root user
- D. IAM replaces the need for SCPs in AWS Organizations

<details>
<summary><strong>Answer</strong></summary>
<strong>C. SCPs affect all IAM users, groups, and even the root user</strong>  
Unlike IAM policies, SCPs apply to **all** entities in an account, including the root user.
</details>

---
