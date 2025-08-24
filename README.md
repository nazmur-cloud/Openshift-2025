# 🚀 OpenShift 2025 – Learning & Practice Repo

This repository contains my notes, hands-on examples, and best practices while learning and working with **Kubernetes & OpenShift** in 2025.  

---

## 🌐 Namespace in Kubernetes

Namespaces in Kubernetes provide a way to **logically divide cluster resources**.  

### ✨ Key Benefits
- 🔒 **Resource Isolation** – Segregate resources for different projects, teams, or environments.  
- 📊 **Better Organization** – Group workloads logically to avoid conflicts.  
- 🚀 **Multi-Tenancy Support** – Allow multiple teams/users to share the same cluster securely.  
- ⚡ **Scoped Resource Management** – Apply quotas, limits, and policies per namespace.  

---

### 🖥️ Example Commands
```bash
# Create a new namespace
kubectl create namespace dev

# List all namespaces
kubectl get namespaces

# Delete a namespace
kubectl delete namespace dev



