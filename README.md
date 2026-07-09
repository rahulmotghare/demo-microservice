# ☁️ Cloud-Native DevOps Platform

A production-inspired cloud-native platform built on **AWS** that demonstrates modern **DevOps, GitOps, CI/CD, and DevSecOps** practices.

This project provisions infrastructure using **Terraform**, deploys a **Spring Boot** microservice to **Amazon EKS** using **Helm** and **Argo CD**, automates delivery with **GitHub Actions**, and secures the software supply chain using **Trivy**, **SBOM generation**, and **Cosign image signing**.

> **Goal:** Build an end-to-end production-style platform while learning the architecture, engineering decisions, and operational concepts behind modern cloud-native systems.

---

## 🚀 Platform Overview

| Layer | Technology |
|--------|------------|
| Cloud | AWS |
| Infrastructure as Code | Terraform |
| Container Orchestration | Amazon EKS (Kubernetes) |
| Package Management | Helm |
| GitOps | Argo CD |
| CI/CD | GitHub Actions |
| Container Registry | GitHub Container Registry (GHCR) |
| Security | Trivy, SBOM, Cosign |
| Application | Spring Boot (Java 21) |
