# AWS EKS Kubernetes Deployment

## 🚀 Overview
This project demonstrates the deployment of a containerized application on AWS Elastic Kubernetes Service (EKS) using a Jenkins-based CI/CD pipeline. It automates the build, image creation, and deployment process to achieve scalable and reliable application delivery.

---

## 🛠️ Tech Stack
- AWS EKS
- Docker
- Kubernetes
- Jenkins
- kubectl
- eksctl
- MongoDB

---

## 🏗️ Architecture Workflow
1. Developer pushes code to GitHub repository
2. Jenkins pipeline is triggered automatically
3. Docker image is built from application source
4. Image is pushed to Docker Hub
5. Jenkins deploys application to AWS EKS cluster
6. Kubernetes manages pods and services
7. MongoDB is used for application data storage

---

## ✨ Key Features
- End-to-end CI/CD automation
- Containerized application deployment
- Kubernetes orchestration on AWS EKS
- Scalable and highly available architecture

---

## ⚠️ Challenges Faced
- AWS EKS cluster setup and configuration
- Kubernetes deployment and service exposure
- Managing networking and pod communication
- Handling IAM roles and permissions

---

## 📊 Results
- Successfully deployed application on AWS EKS
- Achieved automated CI/CD pipeline using Jenkins
- Improved scalability and deployment reliability

---

## 📸 Output
Screenshots of pipeline execution, EKS cluster, and application output are available in the `screenshots/` folder.

---

## 📄 Documentation
Detailed implementation steps are available in `project-report.pdf`.
