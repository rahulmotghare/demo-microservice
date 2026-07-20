# ☁️ Cloud-Native Platform Engineering on AWS

> A production-inspired Platform Engineering project demonstrating Infrastructure as Code (IaC), GitOps, Kubernetes, and Observability on AWS.

---

## 📖 Project Overview

Modern Platform Engineering focuses on building and maintaining the internal platforms that enable developers to ship software quickly, reliably, and securely.

This project demonstrates a production-inspired cloud-native platform built on AWS using Infrastructure as Code, GitOps, Kubernetes, and modern observability tools.

The platform provisions infrastructure with Terraform, deploys containerized applications to Amazon EKS through ArgoCD and Helm, stores container images in Amazon ECR, and provides centralized monitoring and logging using Prometheus, Grafana, and Loki.

The objective is to showcase end-to-end platform engineering practices, including reproducible infrastructure provisioning, declarative application delivery, and operational visibility across a Kubernetes environment.

---

# 🏗 Architecture

![Platform Architecture](docs/architecture/platform-architecture.png)

---

# ⭐ Key Highlights

- Provisioned AWS infrastructure using Terraform
- Built a production-inspired Amazon EKS Kubernetes platform
- Implemented GitOps deployment workflows using ArgoCD
- Packaged and deployed applications with Helm
- Containerized a Spring Boot microservice using Docker
- Stored container images in Amazon ECR
- Implemented centralized metrics collection using Prometheus
- Built Grafana dashboards for platform observability
- Centralized Kubernetes logs using Loki
- Designed a reproducible and cloud-native deployment workflow

---

# 🛠 Technology Stack

| Category | Technology |
|-----------|------------|
| Cloud | AWS |
| Infrastructure as Code | Terraform |
| Containerization | Docker |
| Container Registry | Amazon ECR |
| Container Orchestration | Amazon EKS (Kubernetes) |
| GitOps | ArgoCD |
| Package Management | Helm |
| Monitoring | Prometheus |
| Visualization | Grafana |
| Logging | Loki |
| Backend | Spring Boot |
| Language | Java 21 |
| Build Tool | Maven |

---

# 🚀 Platform Workflow

```text
Developer
      │
      ▼
Spring Boot Application
      │
      ▼
Docker Build
      │
      ▼
Amazon ECR
      │
      ▼
Update GitOps Repository
      │
      ▼
ArgoCD
      │
      ▼
Helm
      │
      ▼
Amazon EKS
      │
      ▼
Running Application
      ├────────► Prometheus (Metrics)
      ├────────► Loki (Logs)
      ▼
Grafana (Dashboards)
```

---

# 📂 Repository Structure

```text
.
├── docs/
│   ├── architecture/
│   └── screenshots/
├── src/
├── Dockerfile
├── pom.xml
├── README.md
└── ...
```

---

# ⚙️ Features

### Infrastructure

- Infrastructure provisioning using Terraform
- Amazon VPC networking
- Amazon EKS cluster deployment
- Managed Kubernetes worker nodes
- Remote Terraform state management

### GitOps

- Declarative Kubernetes deployments
- Continuous synchronization using ArgoCD
- Helm-based application releases

### Application Platform

- Dockerized Spring Boot microservice
- Container image management with Amazon ECR
- Kubernetes-native deployments

### Observability

- Metrics collection with Prometheus
- Dashboard visualization using Grafana
- Centralized logging with Loki

---

# 📸 Screenshots

## Architecture

![Architecture](docs/architecture/platform-architecture.png)

---

## ArgoCD

![ArgoCD](docs/screenshots/argocd.png)

---

## Grafana Dashboard

![Grafana](docs/screenshots/grafana-dashboard.png)

---

## Prometheus Targets

![Prometheus](docs/screenshots/prometheus-targets.png)

---

## Loki Logs

![Loki](docs/screenshots/loki-explore.png)

---

## Amazon EKS Cluster

![Amazon EKS](docs/screenshots/eks-cluster.png)

---

## Amazon ECR Repository

![Amazon ECR](docs/screenshots/ecr-repository.png)

---

# 🧠 Challenges & Lessons Learned

Building this platform involved solving several real-world platform engineering challenges, including:

- Configuring IAM permissions for the Amazon EBS CSI Driver
- Troubleshooting Kubernetes Persistent Volume provisioning
- Resolving ArgoCD synchronization issues
- Fixing Docker image architecture incompatibilities between Apple Silicon and Amazon EKS
- Managing Helm chart configurations for GitOps deployments
- Integrating Prometheus, Grafana, and Loki into the Kubernetes platform
- Understanding Kubernetes networking and service discovery
- Debugging cloud-native infrastructure deployments

These challenges provided practical experience with production-inspired cloud infrastructure, Kubernetes operations, and modern platform engineering workflows.

---

# 🎯 Skills Demonstrated

- Platform Engineering
- DevOps
- Cloud Infrastructure
- Amazon Web Services (AWS)
- Kubernetes
- Amazon EKS
- Infrastructure as Code (IaC)
- Terraform
- GitOps
- ArgoCD
- Helm
- Docker
- Amazon ECR
- Monitoring & Observability
- Prometheus
- Grafana
- Loki
- Spring Boot
- Java
- Linux
- IAM
- Kubernetes Networking
- Troubleshooting

---

# 🛣 Roadmap

## ✅ Completed

- Infrastructure provisioning with Terraform
- Amazon EKS Kubernetes cluster
- Dockerized Spring Boot application
- Amazon ECR integration
- Helm-based application deployment
- GitOps workflow using ArgoCD
- Prometheus monitoring
- Grafana dashboards
- Loki centralized logging

---

## 🚧 Planned Enhancements

- GitHub Actions CI/CD pipeline
- Automated image deployment
- Container image security scanning
- Kubernetes policy enforcement
- Multi-environment deployments (Dev / Stage / Prod)
- Secrets management
- Ingress Controller
- Horizontal Pod Autoscaler (HPA)
- AI-assisted operational workflows

---

# 📚 Future Learning Goals

This project will continue evolving with additional production-grade capabilities, including automated CI/CD, platform security, Kubernetes policy management, and multi-environment deployment strategies.

---

# 👨‍💻 Author

**Rahul Motghare**

Platform Engineer • DevOps Engineer • Cloud Infrastructure

- GitHub: https://github.com/rahulmotghare
- LinkedIn: https://www.linkedin.com/in/motghare/

---

## ⭐ Support

If you found this project interesting, feel free to explore the repository, review the architecture, or connect with me on LinkedIn.
