# 🚀 GitOps Deployment with ArgoCD and Helm on AWS EKS

## 📌 Overview

This project demonstrates a **GitOps-based deployment strategy** using ArgoCD and Helm on AWS EKS.

Instead of manually deploying applications, the system continuously synchronizes the cluster state with a Git repository.

---

## 🧩 Client Scenario

A company needed to:

* Eliminate manual deployments
* Ensure consistency across environments
* Enable automatic recovery from configuration drift

---

## ✅ Solution

Implemented a GitOps workflow where:

* Git acts as the single source of truth
* ArgoCD monitors repository changes
* Kubernetes is automatically updated
* Rollbacks and history are managed visually

---

## 🏗️ Architecture

GitHub → ArgoCD → Helm → AWS EKS

---

## ⚙️ Tech Stack

* Kubernetes (AWS EKS)
* ArgoCD
* Helm
* Docker
* GitHub

---

## 🔄 GitOps Workflow

1. Developer updates configuration in Git
2. ArgoCD detects changes
3. ArgoCD syncs application state
4. Kubernetes performs rolling update
5. Application remains available (zero downtime)

---

## 🚀 Key Features

* Fully automated deployments (GitOps)
* Helm-based configuration management
* Zero-downtime rolling updates
* Self-healing (auto-sync enabled)
* Visual deployment tracking via ArgoCD UI

---

## 🧪 Demo

* ArgoCD shows application health and sync status
* Automatic rollout triggered by Git commit
* Previous version safely terminated after new deployment

---

## 📊 Results

* Reduced deployment errors
* Faster release cycles
* Improved system reliability
* Full traceability of changes

---

## 💡 What I Learned

* GitOps principles and workflows
* ArgoCD application management
* Helm chart templating
* Kubernetes deployment strategies
* Observability of deployment lifecycle

---

## 📬 Contact

If you need help implementing GitOps, Kubernetes deployments, or cloud automation, feel free to reach out.
