![CI/CD](https://github.com/shashishekhar0001/aws-devops-cicd/actions/workflows/deploy.yml/badge.svg)

# AWS DevOps CI/CD Pipeline Project

## Project Overview

This project demonstrates a complete **CI/CD pipeline for a containerized web application** using modern DevOps tools and AWS services.

Whenever new code is pushed to GitHub, the pipeline automatically:

* Builds a Docker image
* Pushes the image to **Amazon ECR**
* Deploys the container to **Kubernetes**

---

## Technologies Used

* Docker
* Kubernetes (Minikube)
* AWS ECR
* GitHub Actions
* Python Flask

---

## Architecture

```
Developer
   │
   ▼
GitHub Repository
   │
   ▼
GitHub Actions CI/CD
   │
   ├── Build Docker Image
   ├── Push to AWS ECR
   ▼
Kubernetes Cluster
   │
   ▼
Running Web Application
```

---

## Project Structure

```
aws-devops-cicd
│
├── app.py
├── Dockerfile
├── requirements.txt
│
├── deployment.yaml
├── service.yaml
│
└── .github/workflows
    └── deploy.yml
```

---

## Setup Instructions

1. Clone the repository
2. Build the Docker image
3. Push the image to AWS ECR
4. Deploy to Kubernetes

---

## Learning Outcomes

* Building containerized applications with Docker
* Managing container images using AWS ECR
* Deploying applications to Kubernetes
* Automating deployments using GitHub Actions
