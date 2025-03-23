
# 📌 AWS Application Load Balancer (ALB) Setup 🚀  

Welcome to my AWS Load Balancer setup! This project demonstrates a **scalable and highly available** architecture using **AWS Application Load Balancer (ALB)** to efficiently distribute traffic among multiple instances.  

---

## 🏗️ Architecture Overview  

The AWS setup consists of:  

✅ **VPC (Virtual Private Cloud)** - The isolated network for our cloud resources.  
✅ **Public Subnets** - Two public subnets for high availability.  
✅ **Application Load Balancer (ALB)** - To distribute incoming traffic across backend instances.  
✅ **Target Group** - The backend instances handling user requests.  
✅ **User Access** - Requests are routed through ALB to ensure better performance and reliability.  

📌 **VPC CIDR:** `12.0.0.0/16`  
📌 **Subnet CIDRs:**  
  - `12.0.1.0/24` (Public Subnet 1)  
  - `12.0.2.0/24` (Public Subnet 2)  

> Check out the architecture diagram in this repository for a visual representation! 📜 

![Image](https://github.com/user-attachments/assets/592a853b-b718-463f-9e12-f79e98c7435d)

---

## 🔧 Technologies Used  

🔹 **AWS Services**: ALB, VPC, EC2, Target Groups  
🔹 **Networking Concepts**: Subnets, Routing, Security Groups  
🔹 **Scalability**: Load balancing for high availability  

---

## 🚀 How to Use  

1️⃣ Deploy instances in the **Target Group**.  
2️⃣ Ensure that instances are in the **public subnets** with correct security group rules.  
3️⃣ Configure **ALB** with the target group.  
4️⃣ Access the ALB **DNS Name** to verify traffic routing.  

---

## 🎯 Key Benefits  

✨ **Improved Availability** – Traffic is distributed across multiple instances.  
✨ **Scalability** – ALB handles increasing traffic efficiently.  
✨ **Security** – ALB ensures better traffic management and access control.  

---


