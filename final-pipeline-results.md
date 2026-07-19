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

<img width="967" height="526" alt="image" src="https://github.com/user-attachments/assets/e2181adb-fac9-4c60-b3de-ff518e69b527" />


---

# Successful Workflow Screenshots

## Build, Push and Deploy

<img width="1377" height="288" alt="image" src="https://github.com/user-attachments/assets/c3739ed0-bcf0-4fa5-8844-d4a51b1c9cd3" />


## Create / Destroy Lab Infrastructure (Apply & Confirm)

<img width="1467" height="462" alt="image" src="https://github.com/user-attachments/assets/8fd84352-00db-4021-9dd8-7a50e3b6a040" />


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
