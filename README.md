
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

## 📝 Author
Vijaya Lakshmi Yallamanda

## 📄 License
This project is for educational/demo purposes.
