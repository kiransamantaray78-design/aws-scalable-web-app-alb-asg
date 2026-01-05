# aws-scalable-web-app-alb-asg

# AWS Scalable Web Application using ALB & Auto Scaling Group

## 📌 Project Overview
This project demonstrates the design of a highly available and scalable web application on AWS using Application Load Balancer (ALB) and Auto Scaling Group (ASG) to handle dynamic traffic efficiently.

---

## 🏗 Architecture Components
- Amazon EC2
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- Target Groups
- VPC, Subnets (Multi-AZ)
- Security Groups
- IAM Roles
- Amazon CloudWatch

---

## ⚙️ Key Features
- High availability across multiple Availability Zones
- Automatic scaling based on traffic demand
- Load-balanced traffic distribution
- Fault tolerance with health checks
- Cost optimization through dynamic scaling

---

## 🔐 Security
- Security Groups for instance-level access control
- IAM Roles for secure AWS service access
- No hardcoded credentials
- Optional integration with AWS WAF

---

## 📊 Monitoring & Scaling
- CloudWatch metrics for CPU utilization and request count
- Auto Scaling policies for scale-in and scale-out
- ALB health checks for instance monitoring

---

## 📁 Repository Structure
