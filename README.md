# 🚀 Terraform S3 Bucket CI/CD with GitHub Actions

This repository contains a **GitHub Actions pipeline** that provisions an **AWS S3 bucket** using **Terraform**.  
It also manages **Terraform state** in an S3 backend with **DynamoDB state locking**.

---

## 📦 Features
- 🌍 **Terraform Remote Backend** (S3 + DynamoDB)  
- 🔒 **State Locking** with DynamoDB  
- 🤖 **GitHub Actions CI/CD** for `init → validate → plan → apply`  
- 📝 **Auto-updating README** with Terraform outputs  
- ♻️ **Reusable workflow** for multiple environments  

---

## 📂 Repository Structure

