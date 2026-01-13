# ☁️ GoHackersCloud – **AZURE HANDS-ON LABS README**

## (Silver Membership | Freshers 0–2 Years)

This repository contains **FREE, official Azure hands-on labs** curated and structured by **GoHackersCloud** to make freshers **job-ready Cloud Engineers / Cloud Support Engineers**.

> 🔑 **Design Principle**
> Same depth, discipline, and structure as our AWS lab repository —
> **concept → lab → documentation → portfolio**

---

## 🎯 Target Audience

* Freshers (0–2 years experience)
* Students & career switchers
* Cloud / DevOps beginners
* Azure support & operations aspirants

---

## 🧭 Learning Philosophy (Very Important)

* ❌ No random labs
* ❌ No certification-only learning
* ✅ Real deployments
* ✅ Service mapping (AWS ↔ Azure ↔ GCP)
* ✅ Interview-ready understanding

---

# 🟢 STAGE 1: Azure Fundamentals (Month 0–2)

### 🎯 Role Mapping: Cloud Trainee / Cloud Support – L1

![Image](https://learn.microsoft.com/en-us/azure/lab-services/media/classroom-labs-fundamentals/labservices-basic-architecture.png)

![Image](https://learn.microsoft.com/en-us/azure/azure-portal/media/azure-portal-dashboards/portal-menu-dashboard.png)

![Image](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/media/organize-resources/scope-levels.png)

### Concepts Covered

* What is Azure
* Global infrastructure (regions, availability zones)
* Resource Groups
* Subscription & billing basics
* Shared Responsibility Model

### ✅ FREE Azure Labs (Official)

(Microsoft Learn – Sandbox based)

* Explore Azure Portal
* Create & manage Resource Groups
* Understand Azure subscriptions & pricing
* Azure global infrastructure

📌 **Outcome:**
Student understands *how Azure is organized* and *how billing works*.

📂 Repo Path

```
00-foundations/
 └── azure-fundamentals/
```

---

# 🟢 STAGE 2: Compute & Storage (Month 2–4)

### 🎯 Role Mapping: Junior Cloud Engineer

![Image](https://miro.medium.com/0%2Au81MIp4malseGRFk)

![Image](https://www.element61.be/sites/default/files/img_competences/Azure%2520Blob%2520Storage.png)

![Image](https://learn.microsoft.com/en-us/azure/virtual-network/media/network-overview/load-balancer.png)

### Azure Services Covered

| Concept | Azure            |
| ------- | ---------------- |
| Compute | Virtual Machines |
| Storage | Blob Storage     |
| Access  | SSH / RDP        |

---

### ✅ FREE Azure Labs

#### 🔹 Compute

* Create Linux VM
* Create Windows VM
* Connect via SSH / RDP
* Stop, start & resize VM

#### 🔹 Storage

* Create Blob Storage account
* Upload & access blobs
* Public vs private containers

📌 **Portfolio Task**

* VM deployment README
* Architecture diagram
* Cost notes

📂 Repo Path

```
00-foundations/
 └── azure-compute-storage/
```

🎯 **Outcome:**
Student can deploy & manage Azure compute workloads.

---

# 🟡 STAGE 3: Networking & Security (Month 4–6)

### 🎯 Role Mapping: Cloud Support / Operations

![Image](https://learn.microsoft.com/en-us/azure/well-architected/service-guides/_images/v-net.png)

![Image](https://learn.microsoft.com/en-us/azure/bastion/media/bastion-nsg/figure-1.png)

![Image](https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/identity/images/azure-active-directory.svg)

### Azure Services Covered

| Concept    | Azure         |
| ---------- | ------------- |
| Networking | VNet, Subnets |
| Security   | NSG           |
| Identity   | Azure AD      |
| Access     | RBAC          |

---

### ✅ FREE Azure Labs

#### 🔹 Networking

* Create VNet & subnets
* Public vs private IP
* NSG inbound/outbound rules

#### 🔹 Identity & Security

* Azure AD users & groups
* Role-Based Access Control (RBAC)
* Secure VM access using roles

📌 **Interview Alignment**

> “How do you secure an Azure VM?”

📂 Repo Path

```
01-associate/
 └── azure-networking-security/
```

🎯 **Outcome:**
Student understands **enterprise-grade access control**.

---

# 🟡 STAGE 4: Monitoring, Cost & Operations (Month 6–8)

### 🎯 Role Mapping: Cloud Operations Engineer

![Image](https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/media/tutorial-logs-dashboards/log-analytics-portal-dashboard.png)

![Image](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/media/get-started-partners/customer-costs1.png)

![Image](https://www.cloudsma.com/wp-content/uploads/2018/05/azureloganalytics_small.png)

### Azure Services Covered

* Azure Monitor
* Log Analytics
* Cost Management & Budgets

---

### ✅ FREE Azure Labs

* Enable Azure Monitor on VM
* View metrics & logs
* Configure cost alerts
* Analyze resource usage

📌 **Critical Fresher Skill**

> “Why did your cloud bill increase?”

📂 Repo Path

```
01-associate/
 └── azure-monitoring-cost/
```

🎯 **Outcome:**
Student avoids **costly and insecure cloud mistakes**.

---

# 🟠 STAGE 5: Serverless & DevOps Basics (Month 8–10)

### 🎯 Role Mapping: Cloud / DevOps Associate

![Image](https://altkomsoftware.com/wp-content/uploads/2022/09/Azure-Functions-1.png)

![Image](https://learn.microsoft.com/en-us/azure/devops/pipelines/get-started/media/pipelines-overview.png?view=azure-devops)

![Image](https://learn.microsoft.com/en-us/azure/devops/pipelines/apps/cd/azure/media/data-pipeline-overview.png?view=azure-devops)

### Azure Services Covered

* Azure Functions
* Azure DevOps (CI/CD basics)
* GitHub integration

---

### ✅ FREE Azure Labs

* Create Azure Function (HTTP trigger)
* Deploy code via GitHub
* Basic CI/CD pipeline
* Application logs monitoring

📂 Repo Path

```
02-professional/
 └── azure-serverless-devops/
```

🎯 **Outcome:**
Student understands **modern cloud deployments**.

---

# 🔵 STAGE 6: Capstone & Portfolio (Month 10–12)

### 🎯 Role Mapping: Job-Ready Fresher

### Capstone Project (Mandatory)

**Secure Azure Web Application**

* VM / App Service
* Blob Storage
* VNet + NSG
* Azure AD access
* Monitoring enabled
* Cost controls applied

📂 Repo Path

```
04-capstone-projects/
 └── azure-secure-webapp/
```

---

# 📜 Certification Mapping (Optional – Smart Use)

Aligned with labs:

* **Microsoft – Azure Fundamentals (AZ-900)**
* **Amazon Web Services – Cloud Practitioner**
* **Google Cloud – Cloud Digital Leader**
* **CompTIA – Cloud+**

---

# 🔁 Multi-Cloud Skill Mapping (Instructor Mandate)

Every student must document:

| Concept    | AWS        | Azure         | GCP              |
| ---------- | ---------- | ------------- | ---------------- |
| Compute    | EC2        | VM            | Compute Engine   |
| Storage    | S3         | Blob          | Cloud Storage    |
| IAM        | IAM        | Azure AD      | IAM              |
| Monitoring | CloudWatch | Azure Monitor | Cloud Monitoring |

---

## 🧠 Final GoHackersCloud Lead Instructor Note

> AWS gets you hired.
> Azure keeps you employed.
> Multi-cloud makes you future-proof.

This **combined AWS + Azure lab structure** ensures:
✔ fresher clarity
✔ enterprise relevance
✔ real job readiness

---

