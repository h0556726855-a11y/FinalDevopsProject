# Final DevOps Project

## Student Information

**Name:** HODAYA ILYABAYEV

**GitHub Repository:**  
https://github.com/h0556726855-a11y/FinalDevopsProject

**Application URL:**  
http://34.254.222.2:30080

---

# Project Overview

This project demonstrates a complete DevOps CI/CD pipeline using **GitHub Actions**, **Docker**, **Terraform**, **AWS EC2**, **Ansible**, **Minikube**, **Kubernetes**, and **GitHub Container Registry (GHCR)**.

---

# GitHub Actions Workflows

This project uses three GitHub Actions workflows to fully automate the deployment process.

## 1. Build, Push and Deploy

**Workflow:**  
https://github.com/h0556726855-a11y/FinalDevopsProject/actions/runs/29691712808

### Jobs

- **Build Backend**  
  https://github.com/h0556726855-a11y/FinalDevopsProject/actions/runs/29691712808/job/88205512074

- **Build Frontend**  
  https://github.com/h0556726855-a11y/FinalDevopsProject/actions/runs/29691712808/job/88205512102

- **Verify Images in GHCR**  
  https://github.com/h0556726855-a11y/FinalDevopsProject/actions/runs/29691712808/job/88205547988

- **Deploy Application**  
  https://github.com/h0556726855-a11y/FinalDevopsProject/actions/runs/29691712808/job/88205583406

---

## 2. Create / Destroy Lab Infrastructure

### Create Infrastructure (Apply)

**Workflow:**  
https://github.com/h0556726855-a11y/FinalDevopsProject/actions/runs/29691866966/job/88205916475

### Confirm Infrastructure (Confirm)

**Workflow:**  
https://github.com/h0556726855-a11y/FinalDevopsProject/actions/runs/29691966137/job/88206178694

---

# Application Screenshot

![ShopList Application](image-1.png)

---

# Successful Workflow Screenshots

## Build, Push and Deploy

![Build Pipeline](image-2.png)

## Create / Destroy Lab Infrastructure (Apply & Confirm)

![Infrastructure Pipeline](image-3.png)

---

# Project Status

- ✅ Backend Docker image built successfully
- ✅ Frontend Docker image built successfully
- ✅ Docker images pushed to GitHub Container Registry (GHCR)
- ✅ AWS infrastructure provisioned using Terraform
- ✅ EC2 instance created successfully
- ✅ Minikube installed automatically using Ansible
- ✅ Kubernetes resources deployed successfully
- ✅ ShopList application running successfully

---

# Repository

https://github.com/h0556726855-a11y/FinalDevopsProject
