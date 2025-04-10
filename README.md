
# 🌟 I’m a Great Software Engineer

**Docker Pulls:** [https://hub.docker.com/r/mukeshjalwal/great-software-engineer](https://hub.docker.com/r/mukeshjalwal/great-software-engineer)  
**GitHub Stars:** [https://github.com/mukeshjalwal/great-software-engineer/stargazers](https://github.com/mukeshjalwal/great-software-engineer/stargazers)  
**MIT License:** [https://github.com/mukeshjalwal/great-software-engineer/blob/main/LICENSE](https://github.com/mukeshjalwal/great-software-engineer/blob/main/LICENSE)

---

Welcome to my personal statement to the world — a website in a Docker container that delivers a simple message:

> 🔥 I’m a Great Software Engineer. 🔥  
> Hire me. Thank me later.

---

## 📦 What's Inside?

- A minimal, stylish `index.html` homepage  
- A lightweight Nginx server to host it  
- A Dockerfile that wraps it all up into a deployable container

---

## 🚀 How to Run It

1. **Clone the repo:**
   ```bash
   git clone https://github.com/mukeshjalwal/great-software-engineer.git
   cd great-software-engineer
   ```

2. **Build the Docker image:**
   ```bash
   docker build -t mukeshjalwal/great-software-engineer .
   ```

3. **Run the container:**
   ```bash
   docker run -d -p 8080:80 mukeshjalwal/great-software-engineer
   ```

4. **Open your browser and go to:**  
   `http://localhost:8080`

---

## 🐳 Docker Hub

- Pull the pre-built image:
  ```bash
  docker pull mukeshjalwal/great-software-engineer
  ```

- [View on Docker Hub](https://hub.docker.com/r/mukeshjalwal/great-software-engineer)

---

## 🌐 Live Demo (Optional GitHub Pages)

1. Create a new branch named `gh-pages`  
2. Move `index.html` to the root of that branch  
3. Go to **Repo Settings → Pages**, and select `gh-pages` as the source  
4. GitHub will generate a live URL like:  
   `https://mukeshjalwal.github.io/great-software-engineer/`

---

## 🙋‍♂️ About Me

- GitHub: [https://github.com/mukeshjalwal](https://github.com/mukeshjalwal)  
- LinkedIn: [https://www.linkedin.com/in/mukeshjalwal/](https://www.linkedin.com/in/mukeshjalwal/)

---

## 🎨 Want to Customize?

Fork it. Remix it. Add your own flair, contact form, animations, or even a fancy backend.

---

## 📜 License

MIT — free to use, modify, and share.

---

Built by [Mukesh Jalwal](https://www.linkedin.com/in/mukeshjalwal/) with ❤️, Docker, and a clear message.


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

