# Multi-Cloud CI/CD Pipeline Automation

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Terraform](https://img.shields.io/badge/terraform-v1.5.0-blue)
![Kubernetes](https://img.shields.io/badge/k8s-v1.27-blue)

## Project Overview
Automated CI/CD pipeline across **AWS, Azure, and GCP** using GitHub Actions, Terraform, and Kubernetes. Deployed containerized applications with minimal manual intervention.

## Tech Stack
- **CI/CD:** GitHub Actions  
- **Infrastructure as Code:** Terraform  
- **Containerization:** Docker, Kubernetes  
- **Cloud Providers:** AWS (EKS), Azure (AKS), GCP (GKE)

## Features
- Automated build, test, and deployment pipelines  
- Multi-cloud deployment orchestration  
- Infrastructure as Code (IaC) for reproducible environments  
- Containerized microservices deployment

## Setup Guide
1. Clone the repository  
2. Configure cloud provider credentials  
3. Run Terraform scripts:  
   ```bash
   terraform init
   terraform apply
