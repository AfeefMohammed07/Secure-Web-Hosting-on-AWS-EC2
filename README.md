# Secure-Web-Hosting-on-AWS-EC2

Project Link: https://drive.google.com/file/d/13WkmeEGk4pOQwUPQHR31NhlciKby8X0e/view?usp=sharing

**Overview**

Deployed a GitHub-hosted HTML website on an AWS EC2 (t3.micro – Amazon Linux 2) instance inside a custom VPC with secure networking and monitoring.

**Tech Stack**

EC2 (t3.micro)

Custom VPC

Security Groups & NACLs

IAM Roles

Apache

Let’s Encrypt SSL (HTTPS)

CloudWatch

Auto Scaling

**Security**

Only ports 22 (SSH – trusted IPs), 80 (HTTP), 443 (HTTPS) allowed

HTTPS enabled with SSL

IAM roles (no hardcoded credentials)

Unauthorized traffic blocked

**Automation & Monitoring**

EC2 User Data for automated setup (70% faster deployment)

CloudWatch metrics & alarms

Auto Scaling for 99.9% uptime
