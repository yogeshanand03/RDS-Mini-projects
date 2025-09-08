# 📘 README – Connect to AWS RDS from EC2

## 🔹 Overview
This project explains how to connect to an **AWS RDS (MySQL)** instance using an **EC2 instance** via PuTTY.  
It includes steps to install MySQL client, connect, and view tables.

---

## 🔹 Prerequisites
- AWS Account  
- One **EC2 instance** (Amazon Linux 2023)  
- One **RDS MySQL instance** (Public/Private)  
- PuTTY (Windows) or any SSH client  
- RDS Security Group inbound rule allowing port **3306** from EC2  

---

## 🔹 Steps

### 1. Login to EC2 via PuTTY
- Open PuTTY → Enter **EC2 Public IP**  
- Add your **.ppk key file**  
- Login as:


---

### 2. Update EC2 and Install MySQL Client
For Amazon Linux 2023:
```bash


