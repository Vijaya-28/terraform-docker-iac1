
# Terraform Docker IaC

This project demonstrates Infrastructure as Code (IaC) using **Terraform** to provision a local **Docker** container.

## 🔧 Tools Used
- [Terraform](https://developer.hashicorp.com/terraform)
- [Docker](https://www.docker.com/)

## 📁 Files Included
- `main.tf` - Terraform configuration to create an Nginx container.
- `README.md` - This file.

## 🚀 What It Does
- Pulls the `nginx:latest` Docker image.
- Creates a container named `nginx-server`.
- Exposes container port 80 to host port 8080.

## ✅ How to Use

### 1. Prerequisites
- Docker installed and running.
- Terraform installed.

### 2. Initialize Terraform
```bash
terraform init
```

### 3. Preview the Plan
```bash
terraform plan
```

### 4. Apply Configuration
```bash
terraform apply
```
Then visit: http://localhost:8080

### 5. Inspect State
```bash
terraform state list
```

### 6. Destroy Infrastructure
```bash
terraform destroy
```

### &.Output Screenshot
<img width="1335" height="694" alt="Screenshot 2025-08-07 165953" src="https://github.com/user-attachments/assets/63786684-54f5-438e-adf1-e43677a7dd67" />


## 📝 Author
Vijaya Lakshmi Yallamanda


## 📄 License
This project is for educational/demo purposes.
