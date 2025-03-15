# Amazon EC2 Guide

## Overview 
This repository provides a step-by-step guide to launching and configuring an Amazon EC2 instance on AWS. It covers essential topics such as selecting the Amazon Machine Image (AMI), configuring networking (VPC, Security Groups), setting up a key pair, resizing storage, and automating tasks with User Data scripts.
## Table of Contents 
   
- [Introduction](#introduction) 
- [Prerequisites](#prerequisites)   
- [Launching an EC2 Instance](#launching-an-ec2-instance)
- [Networking and Security](#networking-and-security)
- [Configuring Storage](#configuring-storage)
- [Automation with User Data](#automation-with-user-data)
- [Conclusion](#conclusion)

## Introduction
Amazon Elastic Compute Cloud (EC2) is a cloud service that enables users to rent scalable virtual servers on AWS. This guide walks you through the setup process, ensuring a secure and efficient configuration.

## Prerequisites
- An **AWS Free Tier** account (750 hours/month free for t2.micro instances)
- Basic knowledge of cloud computing and Linux/Windows environments
- An SSH client (e.g., PuTTY, OpenSSH, MobaxTerm) for connecting to instances

## Launching an EC2 Instance
1. **Create an AWS Free Tier Account**  
   - Sign up for AWS and access the **AWS Management Console**.
   
2. **Launch an EC2 Instance**  
   - Navigate to `EC2 Dashboard > Launch Instance`
   - **Naming the Instance:** Assign a meaningful name for easy identification.
   - **Choosing AMI:** Select a pre-configured image like Amazon Linux or Windows Server.
   - **Selecting Instance Type:** Choose `t2.micro` for Free Tier eligibility.

3. **Configuring Key Pair**  
   - Generate a new key pair for secure SSH access.
   - Download the `.pem` file (Linux/macOS) or `.ppk` file (Windows PuTTY).

## Networking and Security
- **VPC & Subnet:** Defines the network environment.
- **Security Groups:** Acts as a firewall to allow/restrict inbound and outbound traffic.
- **Elastic IP:** Assigns a static public IP for accessibility.
- **Auto-assign Public IP:** Enables internet access.

## Configuring Storage
- Choose **EBS (Elastic Block Store)** for persistent storage.
- Adjust volume size and type (e.g., SSD, HDD).
- Enable **Termination Protection** to prevent accidental deletions.

## Automation with User Data
- Add scripts during instance creation to **install software, update packages, or configure services** automatically.
- Navigate to `Advanced Details > User Data` and input your script.

## Conclusion
Launching an EC2 instance involves selecting an AMI, configuring networking, setting up security, and enabling automation. With AWS EC2, users can scale computing power on demand, ensuring efficiency and cost-effectiveness.

---

🔗 **Author:** Daniel Mwendwa | Cybersecurity Analyst & Cloud Enthusiast  
📧 Contact: [danielmwendwa234@gmail.com](mailto:danielmwendwa234@gmail.com)  
🌍 Follow: [LinkedIn](https://www.linkedin.com/in/daniel-mwendwa-mwithui) | [GitHub](https://github.com/daniel-mwendwa)  
