# 🚀 Scalable Web Application on AWS (EC2 + ALB + ASG)

## 📌 Project Overview
This project demonstrates the deployment of a **highly available and scalable web application** on AWS using:

- **EC2 Instances**
- **Application Load Balancer (ALB)**
- **Auto Scaling Groups (ASG)**
- **Amazon RDS** (Optional for DB)
- **CloudWatch & SNS** for monitoring

The solution follows **AWS best practices** for scalability, fault tolerance, and cost optimization.

---

## 🏗️ Solution Architecture
**Architecture Diagram** (see `architecture-diagram.png`)

**Flow:**
1. Users access the application via the **Application Load Balancer**.
2. The ALB distributes traffic across multiple **EC2 instances** inside an **Auto Scaling Group**.
3. **Auto Scaling** adjusts capacity based on demand (CPU utilization or traffic).
4. (Optional) **Amazon RDS** provides a reliable, Multi-AZ database backend.
5. **CloudWatch & SNS** monitor health and send alerts.
6. **IAM Roles** ensure secure access to AWS resources.

---

## 🔧 AWS Services Used
- **Amazon EC2** – Hosts the web application.  
- **Elastic Load Balancer (ALB)** – Distributes incoming traffic.  
- **Auto Scaling Group (ASG)** – Scales EC2 instances automatically.  
- **Amazon RDS (Optional)** – Database backend (MySQL/PostgreSQL).  
- **Amazon CloudWatch** – Monitoring metrics.  
- **Amazon SNS** – Alerts/notifications.  
- **IAM** – Secure access control.  

---

## 🎯 Learning Outcomes
- Deploying a secure and scalable EC2-based web application.  
- Configuring ALB and ASG for high availability.  
- Using Auto Scaling policies to optimize costs and performance.  
- Implementing monitoring & alerting with CloudWatch & SNS.  

---

## 📂 Repository Structure

```
aws-scalable-webapp/
│── README.md
│── architecture-diagram.png
│── docs/
│   └── project-documentation.md
│── src/
    └── index.html
```

---

## 🚀 Deployment
1. Launch infrastructure using **AWS Console** or **IaC (CloudFormation/Terraform)**.  
2. Deploy sample web app code to **EC2 instances**.  
3. Access the application via the **ALB DNS name**.  

---

## 📹 Optional Deliverable
- **Live Demo URL**: `http://<ALB-DNS-Name>`  
- Or **Recorded Video Walkthrough**  

---

## 👨‍💻 Author
**Ahmed Daoud**  
AWS Cloud Practitioner | Aspiring Solutions Architect  
