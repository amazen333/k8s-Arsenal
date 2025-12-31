# 🚀 k8s-Arsenal-Arsenal Kubernetes Scripts

Welcome to **k8s-Arsenal-Arsenal** — a collection of automation scripts for Kubernetes clusters across **AWS EC2** and **WSL2** environments.

---

## 🐳 Docker Runtime
Scripts and instructions for installing and configuring Docker or containerd.

---

## ☸️ Kubernetes Setup
- `k8s-EC2-RHL-master.sh` → Bootstrap Kubernetes **master node**.
- `k8s-EC2-RHL-worker.sh` → Prepare Kubernetes **worker node**.
- `k8s-EC2-RHL-clones.ps1` → Clone Rocky/AlmaLinux distros in WSL2.

---

## 🌐 Terraform Integration
Infrastructure as code examples for provisioning AWS EC2 clusters.

---

## 🐚 Shell Scripts
Automation scripts for **Ubuntu/Debian (Community Linux)** clusters.

---

## 💠 PowerShell Scripts
WSL2 automation scripts for **Rocky/AlmaLinux (Enterprise Linux)**.

---

## 🏛️ Architecture
High-level diagrams and design documents for cluster topology.

---

## 🎨 Design
Guidelines for repo structure, documentation style, and naming conventions.

---

## 🔧 Implementation
Step-by-step instructions for setting up Kubernetes clusters.

---

## 🚀 Deployment
CI/CD pipeline scripts and cluster rollout automation.

---

## ⚖️ Comparison Tables

### Community vs Enterprise Linux
| Aspect        | Community Linux (Ubuntu/Debian) | Enterprise Linux (Rocky/AlmaLinux) |
|---------------|---------------------------------|------------------------------------|
| **Support**   | Community-driven, fast updates  | Vendor-backed, long-term support   |
| **Flexibility**| Highly customizable, rapid prototyping | Standardized configs, enterprise governance |
| **Cost**      | Free, community support only    | Free base, optional enterprise subscriptions |
| **Use Cases** | Developer onboarding, staging clusters | Mission-critical workloads |
| **Demand**    | Broad adoption in startups/devs | Strong demand in enterprises       |
---------------------------------------------------------------------------------------+

### EC2 vs EKS
| Factor        | EC2 + Scripts (DIY Kubernetes) | EKS (Managed Kubernetes) |
|---------------|--------------------------------|---------------------------|
| **Control**   | Full control over master/worker setup | AWS manages control plane |
| **Complexity**| Higher — you maintain everything | Lower — AWS handles upgrades |
| **Cost**      | Pay only for EC2 + infra | Extra per-cluster fee + EC2 costs |
| **Use Cases** | Training, custom networking | Production workloads |
| **Demand**    | Niche but steady | Broad demand across enterprises |
-------------------------------------------------------------------------------------

```
## 📖 Documentation
- [Icons Reference](../docs/icons.md)
- [CLx README](./AWS/CLx/README.md)
- [RHL README](./AWS/RHL/README.md)

---
