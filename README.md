# 🚀 End-to-End CI/CD Pipeline - Register App

This repository contains the source code and CI pipeline configuration for a production-style DevOps project.

## 📌 Overview

A complete CI pipeline built using Jenkins to automate:
- Build
- Test
- Code analysis
- Docker image creation
- Security scanning
- Image push to Docker Hub

---

## 🧱 Tech Stack

- Java (Maven)
- Jenkins
- SonarQube
- Docker
- Trivy

---

## ⚙️ CI Pipeline Flow

1. Developer pushes code to GitHub
2. GitHub Webhook triggers Jenkins
3. Jenkins pipeline executes:
   - Build & Unit Testing (Maven)
   - Static Code Analysis (SonarQube)
   - Docker Image Build
   - Security Scan (Trivy)
   - Push Image to Docker Hub

---

## 📂 Project Structure

- `webapp/` → Application code
- `Dockerfile` → Container build
- `Jenkinsfile` → CI pipeline definition
- `pom.xml` → Maven configuration

---

## 🔗 Related GitOps Repository

👉 https://github.com/Khaled-elnabawy/gitops-register-app

---

## 💡 Note

This project is part of a complete DevOps pipeline deployed on AWS EKS with GitOps, monitoring, logging, and alerting.

