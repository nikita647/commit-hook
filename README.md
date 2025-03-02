
# **Comparison table and final tool recommendation**

![image](https://github.com/user-attachments/assets/b1c0db62-a249-41e5-9f1c-5e7d4fcd8a9d)


| **Author** | **Created on** | **Version** | **Last updated by**|**Last Edited On**|**Level** |**Reviewer** |
|------------|---------------------------|-------------|----------------|-----|-------------|-------------|
| Nikita Joshi|  26-02-2025           | v1         | Nikita Joshi    |26-02-2025    |  internal review | komal jaiswal | 
---

## Table of Contents
1. [Introduction](#introduction)
2. [Why We Need CI/CD in Our OT Microservice Project](#why-we-need-cicd-in-our-ot-microservice-project)
3. [Features Comparison](#features-comparison)
4. [Cost Analysis](#cost-analysis)
5. [Conclusion Table](#conclusion-table)
6. [Conclusion](#conclusion)
7. [Contact Information](#contact-information)
8. [References](#references)

---

## Introduction
This document compares **GitLab**, **Jenkins**, and **BuildPiper** — three popular DevOps tools used for CI/CD, deployment, and orchestration. Each tool has unique strengths, and the choice depends on your project needs, team expertise, and budget.

---

## Why We Need CI/CD in Our OT Microservice Project
Our **OT Microservices** project consists of three APIs:
- **Employee API**: RESTful service built with Golang and Gin, integrated with ScyllaDB.
- **Attendance API**: Developed in Python, uses PostgreSQL for data storage.
- **Salary API**: Built in Java, uses Golang and ScyllaDB for efficient data handling.

**CI/CD** automates the workflow from code integration to testing and deployment. This ensures:
- Faster development cycles.
- Improved code quality and reliability.
- Automated testing and deployment to appropriate environments.

---

## Features Comparison

| **Feature**               | **GitLab**                          | **Jenkins**                          | **BuildPiper**                        |
|---------------------------|-------------------------------------|--------------------------------------|---------------------------------------|
| **Version Control**        | ✅ Built-in Git repository          | ❌ Requires external integration      | ❌ Requires external integration       |
| **CI/CD**                  | ✅ GitLab CI/CD                     | ✅ Pipeline support via plugins       | ✅ Built-in CI/CD                      |
| **Self-hosted Option**     | ✅ (GitLab CE/EE)                   | ✅ Jenkins server                     | ✅ Self-hosted or managed              |
| **Plugins/Extensions**     | ✅ Native integrations              | ✅ 1,500+ plugins                     | ❌ Limited integrations                |
| **Container Registry**     | ✅ Built-in                         | ❌ Requires external tools            | ✅ Built-in registry                   |
| **Kubernetes Support**     | ✅ Native                           | ✅ Supported via plugins              | ✅ Integrated Kubernetes support       |
| **Ease of Use**            | ✅ User-friendly UI                 | ❌ Requires manual configuration       | ✅ Simplified workflows                |
| **Security Scanning**      | ✅ Dependency and SAST              | ❌ Requires plugins                   | ✅ Integrated security features        |
| **Monitoring**             | ✅ Built-in                         | ❌ Requires external tools            | ✅ Built-in monitoring                 |
| **Marketplace/Ecosystem**  | ✅ GitLab Integrations              | ✅ Jenkins Plugin Marketplace         | ❌ Limited marketplace options         |
| **Automation**             | ✅ Integrated automation            | ✅ Highly customizable                 | ✅ Pre-built automation features       |
| **User Limit**             | ✅ Free tier with 5 users           | ✅ Unlimited                          | ❌ Licensing required                  |
| **Unique Selling Point**   | ✅ Complete DevOps platform         | ✅ Highly extensible via plugins      | ✅ Streamlined Kubernetes and CI/CD workflows |

___




## Cost Analysis

| **Tool**      | **Free Tier**                     | **Paid Plans**                                                                 | **Self-Hosted Cost**                                                                 |
|---------------|-----------------------------------|-------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| **GitLab**    | ✅ Free for 5 users               | Starts at $19/user/month (Premium) and $99/user/month (Ultimate)              | Free (Community Edition) or $10/user/month (Enterprise Edition)                     |
| **Jenkins**   | ✅ Completely free and open-source| ❌ No paid plans (but hosting costs apply for self-hosted servers)             | Free (but requires server setup and maintenance costs)                              |
| **BuildPiper**| ❌ No free tier                   | Starts at $500/month (basic plan)                                             | Custom pricing for self-hosted options (contact vendor for details)                 |

---


## Conclusion Table  

| **Tool**        | **When to Use**                                                                                    | **When to Avoid**                                                                                   |
|------------------|---------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| **GitLab**       | - For end-to-end DevOps workflows. <br> - Teams needing robust CI/CD, version control, and security.| - For small teams needing only basic CI/CD.<br> - When cost is a concern.                          |
| **Jenkins**      | - For highly customizable CI/CD workflows. <br> - Open-source enthusiasts needing plugin flexibility.| - When simplicity and native Kubernetes support are priorities.                                    |
| **BuildPiper**   | - For Kubernetes-centric and microservices-based applications. <br> - Teams with Kubernetes expertise.| - For projects not involving Kubernetes.<br> - Teams unfamiliar with containerized deployments.   |


## **Conclusion**
Jenkins is a great choice due to its customization, integration flexibility, and scalability. Although it has a learning curve, its vast plugin ecosystem and strong community support make it a reliable CI/CD solution.

---

## **Contact Information**

| **Name** | **Email address**            | **Github ID**
|----------|-------------------------------|-------------------|
| Nikita joshi    | Nikita.Joshi@mygurukulam.co    | https://github.com/jnikita19  |


---

## References

| **Name**        | **Links and Description**                                                                 |
|-----------------|------------------------------------------------------------------------------------------|
| **BuildPiper**  | [BuildPiper Doc](https://buildpiper.io) |
| **GitLab**   | [GitLab Doc](https://gitlab.com) |
| **Jenkins**     | [Jenkins Doc](https://jenkins.io) |

---



