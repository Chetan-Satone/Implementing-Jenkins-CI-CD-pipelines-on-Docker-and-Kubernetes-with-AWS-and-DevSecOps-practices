# 🚀 Implementing Jenkins CI/CD pipelines on Docker and Kubernetes with AWS and DevSecOps practices

## 📌 Introduction
In today's fast-paced software development world, deploying applications quickly and securely is crucial.  
This project leverages **Docker, Kubernetes, Jenkins CI/CD, and DevSecOps** best practices to simplify deployment while ensuring security and reliability.

## 🔹 Key Features
- **Container Orchestration with Kubernetes**: Efficient application management across environments.
- **CI/CD Automation with Jenkins**: Faster releases and reduced manual effort.
- **Security Integration**: Uses *SonarQube, Trivy, and OWASP* to detect vulnerabilities.
- **Helm for Package Management**: Simplifies Kubernetes deployments.
- **Monitoring with Prometheus & Grafana**: Provides real-time metrics.

## ✅ Benefits
- 🚀 **Streamlined Deployments**: Automates processes, reducing manual work.
- 🔄 **Continuous Delivery**: Frequent updates enhance user experience.
- 🔒 **Enhanced Security**: Detects vulnerabilities early in development.
- 📈 **Scalability & High Availability**: Kubernetes dynamically scales applications.
- ☁ **Cloud-Based Infrastructure**: AWS provides a cost-effective and flexible solution.

## 🛠 System Development and Design

### 📌 System Architecture
![architecture](https://github.com/user-attachments/assets/7c5faaa7-1e40-4780-b33f-d552419febba)

The system comprises two **Amazon EC2** instances:
- A **t2.large** instance running *Jenkins, OWASP Scan, Docker, Trivy*, and *Amazon Ubuntu AMI*.
- A **t2.medium** instance for hosting *Prometheus & Grafana* for monitoring.

### 🛠 Workflow Overview
1. **Jenkins** automates the CI/CD pipeline.
 ![Screenshot 2025-02-27 223237](https://github.com/user-attachments/assets/35543202-6f45-42bd-b60c-8d01acd04517)

2. **Docker** builds and containerizes applications
 ![Screenshot 2025-02-27 223146](https://github.com/user-attachments/assets/808e11c9-114a-40c2-bc33-ba5c174f0d30)

3. **Amazon EKS** orchestrates deployment.
4. **OWASP Scan & Trivy** perform security scans.
5. **Helm & ArgoCD** automate Kubernetes deployments.
6. **Prometheus & Grafana** provide real-time monitoring.
![Screenshot 2025-02-27 223520](https://github.com/user-attachments/assets/42c6a4f7-2c20-4647-91b0-c2286f2c8e40)

7. **Sonarqube** analyzes the code
![Screenshot 2025-02-27 223313](https://github.com/user-attachments/assets/93d73bb7-4d0d-44bc-a4de-337c8cebbc12)

## 🚀 Technology Stack
- 💻 **Amazon EC2**: Cloud-based infrastructure.
- ![Screenshot 2025-02-27 223036](https://github.com/user-attachments/assets/855c0927-fd8f-4acc-821c-08964246d623)

- 🔗 **Git**: Version control system.
- 📦 **Docker**: Containerization platform.
- 🔄 **Jenkins**: CI/CD automation tool.
- ☁ **Amazon EKS**: Kubernetes orchestration.
- 🔍 **SonarQube**: Code quality and security analysis.
- 🛡 **OWASP Scan**: Web security assessment.
- 🛠 **Trivy**: Vulnerability scanner.
- 📊 **Prometheus**: Monitoring and alerting.
- 📈 **Grafana**: Visualization and analytics.

## 🌍 Final Output
After successful deployment, the web application runs securely on **AWS EKS**, ensuring high availability, performance, and security.
![Screenshot 2025-02-27 221440](https://github.com/user-attachments/assets/9956479e-30b3-4ce6-a8a6-b1f2e4e3e3e9)


## 📌 Getting Started

### 📋 Prerequisites
- AWS CLI
- Docker
- Kubernetes (kubectl)
- Helm
- Jenkins
- Git

### 📥 Setup Steps

## Clone the repository:
```sh
git clone https://github.com/Chetan-Satone/Implementing-Jenkins-CI-CD-pipelines-on-Docker-and-Kubernetes-with-AWS-and-DevSecOps-practices.git
