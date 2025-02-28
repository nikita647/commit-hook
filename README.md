# OT Microservices Project: GitLab, Jenkins, and BuildPiper Comparison

![CI/CD Status](https://img.shields.io/badge/CI/CD-Enabled-brightgreen) 
![License](https://img.shields.io/badge/License-MIT-blue)

This repository contains the **OT Microservices Project**, which includes three APIs: **Employee API**, **Attendance API**, and **Salary API**. The project is built using modern technologies and follows CI/CD best practices for automated testing and deployment. This document compares **GitLab**, **Jenkins**, and **BuildPiper** to help you choose the best CI/CD tool for your project.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Why We Need CI/CD in Our OT Microservice Project](#why-we-need-cicd-in-our-ot-microservice-project)
3. [Features Comparison](#features-comparison)
4. [Advantages](#advantages)
5. [Disadvantages](#disadvantages)
6. [Cost Comparison](#cost-comparison)
7. [Conclusion Table](#conclusion-table)
8. [Contacts](#contacts)
9. [References](#references)

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




**Final Recommendation:**
Jenkins is a great choice due to its customization, integration flexibility, and scalability. Although it has a learning curve, its vast plugin ecosystem and strong community support make it a reliable CI/CD solution.

---



---

## References

| **Name**        | **Links and Description**                                                                 |
|-----------------|------------------------------------------------------------------------------------------|
| **BuildPiper**  | [Official](https://buildpiper.io) | [Documentation](https://docs.buildpiper.io) |
| **GitLab CI**   | [Official](https://gitlab.com) | [Documentation](https://docs.gitlab.com)    |
| **Jenkins**     | [Official](https://jenkins.io) | [Documentation](https://www.jenkins.io/doc/)|

---

## Final Recommendation
Final Recommendation:
Jenkins is a great choice due to its customization, integration flexibility, and scalability. Although it has a learning curve, its vast plugin ecosystem and strong community support make it a reliable CI/CD solution.
