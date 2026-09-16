# CI/CD Pipeline for Java & Kubernetes Deployment

An automated GitHub Actions CI/CD pipeline that compiles, tests, containerizes, and deploys a Java Maven application to a Kubernetes cluster.

---

## 🛠️ Tech Stack & Tools

* **Language/Framework:** Java 21 (Eclipse Temurin)
* **Build Tool:** Apache Maven
* **Containerization:** Docker & Docker Buildx
* **Orchestration:** Kubernetes (`kubectl`)
* **CI/CD:** GitHub Actions

---

## ⚙️ Pipeline Overview

The workflow is triggered automatically on **push** or **pull request** events targeting the `main` branch.
