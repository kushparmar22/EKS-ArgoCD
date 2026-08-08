# 🚀 ArgoCD GitHub OAuth on Amazon EKS

![Kubernetes](https://img.shields.io/badge/Kubernetes-v1.33-blue?logo=kubernetes)
![ArgoCD](https://img.shields.io/badge/ArgoCD-GitOps-orange?logo=argo)
![AWS](https://img.shields.io/badge/AWS-EKS-FF9900?logo=amazonaws)
![GitHub](https://img.shields.io/badge/GitHub-OAuth-black?logo=github)

Configure **GitHub OAuth authentication** for **ArgoCD** running on **Amazon EKS** using **Dex**, **NGINX Ingress**, and **Let's Encrypt TLS**.

---

# 🏗️ Architecture

<p align="center">
<img src="screenshots/architecture.png" width="900">
</p>

---

# 📸 Project Demo

## ArgoCD Login

<p align="center">
<img src="screenshots/argocd-login.png" width="850">
</p>

---

## GitHub OAuth Login

<p align="center">
<img src="screenshots/github-login.png" width="850">
</p>

---

## Applications Dashboard

<p align="center">
<img src="screenshots/applications.png" width="850">
</p>

---

## Successful Sync

<p align="center">
<img src="screenshots/sync-success.png" width="850">
</p>

---

# 📂 Project Files

- config-github.yml
- ingress.yml
- lets-encrypt.yml
- rbac.yml
- secret-example.yml

---

# ⚙️ Technologies

- Amazon EKS
- Kubernetes
- ArgoCD
- GitHub OAuth
- Dex
- NGINX Ingress
- cert-manager
- Let's Encrypt

---

# 🔐 Security

✔ Secrets excluded from Git

✔ OAuth Authentication

✔ TLS Enabled

✔ RBAC Configured

---

# 👨‍💻 Author

**Kush Parmar**

