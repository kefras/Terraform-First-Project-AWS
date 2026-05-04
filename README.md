# 🚀 Terraform First Project — AWS S3 Bucket

A beginner Infrastructure as Code (IaC) project using Terraform to provision an AWS S3 bucket. This project demonstrates the core Terraform workflow: init → plan → apply → destroy.

![Terraform](https://img.shields.io/badge/Terraform-1.x-623CE4?style=for-the-badge&logo=terraform)
![AWS](https://img.shields.io/badge/AWS-S3-orange?style=for-the-badge&logo=amazon-aws)
![Infrastructure as Code](https://img.shields.io/badge/IaC-Terraform-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)

---

## 📸 Project Overview

This project demonstrates **Infrastructure as Code (IaC)** using Terraform to provision an AWS S3 bucket.

Instead of manually creating resources in AWS Console, everything is defined in code and deployed automatically.

---

## 🧠 What This Project Covers

✔ Terraform configuration basics  
✔ AWS provider setup  
✔ Variables & outputs  
✔ S3 bucket provisioning  
✔ Terraform workflow (init → plan → apply → destroy)  
✔ State management fundamentals  

---

## 🏗️ Architecture
terraform-first-project/
│
├── main.tf # Main Terraform configuration
├── terraform.tfvars # Input variables
├── .terraform/ # Auto-generated working directory
├── .terraform.lock.hcl # Provider lock file


---

## ⚙️ How It Works

### 1️⃣ Initialize Terraform
Downloads AWS provider plugins

```bash
terraform init

terraform plan

terraform apply

terraform destroy
