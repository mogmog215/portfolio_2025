# portfolio_2025

・a practice architecture for learning Terraform
  https://chatgpt.com/share/68174319-713c-8003-9000-a48362eb95be

## 📚 Overview
This repository contains a Terraform-based infrastructure template designed for learning and demonstration purposes.  
It is focused on deploying a simple, modular, and reusable AWS environment including VPC, EC2, and S3 setup.

## 🧱 Architecture
- **Cloud Provider**: AWS
- **Main Components**:
  - VPC with public/private subnets
  - EC2 instance with key pair and security groups
  - S3 bucket with versioning enabled
  - Optional: CloudWatch, IAM roles

## 📂 Project Structure
terraform/
├── main.tf
├── variables.tf
├── outputs.tf
├── modules/
│ └── ec2/
│ └── main.tf
