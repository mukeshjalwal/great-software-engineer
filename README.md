# 🌟 I’m a Great Software Engineer

Welcome to my **"Hire Me" website in a Docker container**. This project is a bold, beautiful, and blazing-fast way to tell the world one simple truth:

> 🔥 I’m a Great Software Engineer. 🔥  
> Hire me. Thank me later.

## 🚀 What's Inside?

This repo contains:
- A simple `index.html` page styled with some love
- A lightweight [Nginx](https://hub.docker.com/_/nginx) container to serve it
- A Dockerfile to package it all up

## 📦 How to Run It

### 1. Clone the repo
```bash
git clone https://github.com/mukeshjalwal/great-software-engineer.git
cd great-software-engineer


## Useful Kubernetes Commands

### Apply Configurations
```sh
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
```

### Cluster and Node Information
```sh
kubectl get nodes
kubectl cluster-info
kubectl get svc
```

### Managing Pods
```sh
kubectl get pods
kubectl describe pod <pod>
kubectl exec -it <pod> -- /bin/sh  # Open shell inside the pod
kubectl logs <pod>                 # View logs of a pod
```

### Managing Deployments
```sh
kubectl delete deployment <deployment>
```

### Connect `kubectl` to Azure AKS
```sh
az aks get-credentials --resource-group <resource-group-name> --name <aks-cluster-name> --overwrite-existing
```

### Helm Chart
```sh
helm package .;helm install myapp ./myapp-<ver>.tgz;kubectl get pod
```

