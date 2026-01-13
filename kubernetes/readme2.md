# ☸️ GoHackersCloud – Kubernetes Hands-On Labs
## AKS | EKS | GKE (Silver Membership – Freshers 0–2 Years)

This repository provides **step-by-step Kubernetes hands-on labs** using **managed Kubernetes services** from all three major cloud providers:
- AWS EKS
- Azure AKS
- Google GKE

> 🎯 Goal: Make freshers **confident with Kubernetes basics**, not overwhelmed  
> ❌ No deep YAML overload  
> ❌ No production-level complexity  
> ✅ Core concepts + real deployments

---

## 🎯 Target Roles
- Cloud Engineer (Junior)
- DevOps / Cloud Associate
- Platform Support Engineer
- SRE Trainee

---

## 🧭 Learning Rules (Must Read)
1. Learn **Kubernetes concepts first**, cloud second
2. Do **one cloud at a time**
3. Document every lab:
   - What you deployed
   - Why it’s needed
   - What Kubernetes handled automatically
4. Focus on **Pods, Deployments, Services**

---

# 🟢 STAGE 1: Kubernetes Core Concepts (Week 1–2)
### 🎯 Objective: Understand what Kubernetes actually does

### Concepts Covered
- Containers vs Kubernetes
- Cluster, Node, Pod
- Deployment
- Service
- kubectl basics

### Labs (Local / Any Cloud)
- kubectl installation
- Connect to cluster
- List nodes & pods
- Deploy sample NGINX app

📂 Repo Path
```

00-foundations/k8s-basics/

```

🎯 Outcome:
> Student understands **how Kubernetes runs containers**.

---

# 🟢 STAGE 2: AWS EKS Hands-On Labs (Week 3–5)
### 🎯 Objective: Deploy apps on AWS-managed Kubernetes

## Services Used
- Amazon EKS
- EC2 worker nodes
- kubectl
- IAM (basic awareness)

---

### ✅ Labs
1. Create EKS cluster (managed)
2. Configure kubectl access
3. Deploy NGINX using Deployment
4. Expose app using Service (LoadBalancer)
5. Scale replicas
6. Delete resources (cost control)

📂 Repo Path
```

01-associate/eks/
├── cluster-setup/
├── app-deployment/
├── service-expose/
└── scaling/

```

🎯 Outcome:
> Student can explain **how Kubernetes runs on AWS**.

---

# 🟢 STAGE 3: Azure AKS Hands-On Labs (Week 6–8)
### 🎯 Objective: Learn enterprise-style Kubernetes on Azure

## Services Used
- Azure Kubernetes Service (AKS)
- Azure CLI
- kubectl
- Azure Load Balancer

---

### ✅ Labs
1. Create AKS cluster
2. Connect using kubectl
3. Deploy sample app
4. Expose using Service
5. View pods & logs
6. Scale application

📂 Repo Path
```

01-associate/aks/
├── cluster-setup/
├── app-deployment/
├── service-expose/
└── scaling/

```

🎯 Outcome:
> Student understands **Azure AKS workflow**.

---

# 🟢 STAGE 4: Google GKE Hands-On Labs (Week 9–11)
### 🎯 Objective: Learn clean & automated Kubernetes experience

## Services Used
- Google Kubernetes Engine (GKE)
- Cloud Shell
- kubectl

---

### ✅ Labs
1. Create GKE cluster
2. Connect via Cloud Shell
3. Deploy containerized app
4. Expose application
5. Scale pods
6. Clean up resources

📂 Repo Path
```

01-associate/gke/
├── cluster-setup/
├── app-deployment/
├── service-expose/
└── scaling/

```

🎯 Outcome:
> Student sees **cloud-agnostic Kubernetes behavior**.

---

# 🟡 STAGE 5: Core Kubernetes Operations (Week 12–14)
### 🎯 Objective: Think like a DevOps engineer

### Labs
- View pod logs
- Describe pods & deployments
- Restart failed pods
- Rolling updates
- Rollbacks

📂 Repo Path
```

02-professional/k8s-operations/

```

🎯 Outcome:
> Student understands **self-healing & rolling updates**.

---

# 🔵 STAGE 6: Kubernetes Capstone Project
### 🎯 Objective: Portfolio-ready Kubernetes project

## Capstone: Multi-Replica Web Application
**Must Include**
- Deployment (multiple replicas)
- Service exposure
- Scaling
- Logs & monitoring check
- Clean YAML files
- README explanation

📂 Repo Path
```

04-capstone-projects/k8s-webapp/

```

---

# 🔁 Multi-Cloud Kubernetes Comparison

| Concept | AWS EKS | Azure AKS | GCP GKE |
|------|--------|----------|--------|
| Managed Control Plane | ✅ | ✅ | ✅ |
| Worker Nodes | EC2 | VM Scale Sets | Compute Engine |
| Load Balancer | ELB | Azure LB | Cloud LB |
| kubectl | Same | Same | Same |

📌 Instructor Rule:
> Kubernetes concepts never change — **only cloud integration does**.

---

# 📜 Certification Alignment (Optional)
- Kubernetes basics → CKA foundation
- Cloud DevOps associate roles
- Supports AWS / Azure / GCP cloud paths

---

## 🧠 GoHackersCloud Lead Instructor Note
> Freshers don’t need to master Kubernetes.  
> They need to **understand how it works and talk confidently**.

If a student can:
✔ deploy one app  
✔ scale it  
✔ explain Pods, Deployments, Services  

👉 They are **interview-ready**.

---

🚀 Welcome to Kubernetes with GoHackersCloud
