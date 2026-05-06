# Hey, I'm Gilleady Daboit 👋

**Cloud Architect / DevOps** focused on building scalable, well-structured infrastructure on AWS. I care about clean code, solid automation, and solving problems the right way.

I'm an ownership-driven engineer — I take the lead, figure out the problem, design the solution, and ship it.

## 👨‍💻 What I do

- Design and implement **multi-account AWS architectures** (Organizations, IAM, Identity Center, SCPs)
- Build and maintain infrastructure as code with **OpenTofu / Terraform / Terragrunt**
- Deploy and operate containers on **EKS** and **ECS** with **Helm Charts**, **ArgoCD**, and CNCF addons
- Create CI/CD pipelines and IssueOps workflows with **GitHub Actions** to make infra self-service
- Enforce **security guardrails**, end-to-end encryption, and compliance standards (ISO 27001, SOC 2)
- Build **Golden AMIs**, manage EC2 fleets, and automate database operations with **PL/SQL**

## 💻 Stack

### ☁️ Cloud & Infrastructure

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-web-services&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![Terragrunt](https://img.shields.io/badge/Terragrunt-%23232F3E.svg?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white)
![Cognito](https://img.shields.io/badge/Cognito-%23FF9900.svg?style=for-the-badge&logo=amazon-web-services&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### ⚙️ DevOps & CI/CD

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-%230F1689.svg?style=for-the-badge&logo=helm&logoColor=white)
![Crossplane](https://img.shields.io/badge/Crossplane-4A90D9?style=for-the-badge&logo=crossplane&logoColor=white)

### 💻 Languages & Scripting

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Bash](https://img.shields.io/badge/Bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-F80000?style=for-the-badge&logo=oracle&logoColor=white)

### 📊 Observability

![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-CC0000?style=for-the-badge&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

### 🛢️ Databases

![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

---

## 🧭 Background

I started my career in support, climbed fast to L2, and transitioned to cloud in 2021. I got here by understanding systems from the ground up:

- **Application support** — Tomcat tuning, Oracle DB troubleshooting, PL/SQL scripts for production fixes
- **Infrastructure operations** — hands-on management of EC2 fleets, networking, security groups, manual provisioning before IaC
- **AWS Organizations** — multi-account governance, IAM roles, Identity Center, SCPs
- **Golden AMIs** — building hardened, standardized images from scratch for consistent deployments
- **IaC evolution** — migrated manual infra to Terraform/OpenTofu, adopted Terragrunt, built layered state architectures

5 years experience in cloud. Today my focus is **100% automation**: OpenTofu modules, GitHub Actions workflows, IssueOps pipelines, and making infrastructure self-service for development teams.

---

## 🎓 Certification

[![AWS Certified Solutions Architect – Associate](https://images.credly.com/size/80x80/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png)](https://www.credly.com/badges/9fe066a2-eaad-4d9a-a06f-4e7c87d0fcf3 "AWS Certified Solutions Architect – Associate")

---

## 📂 Portfolio

Public repos showcasing how I build and organize infrastructure:

| Project | Description | Stack |
|:---|:---|:---|
| [**tofu-aws-infra**](https://github.com/ggdaboit/tofu-aws-infra) | Multi-account AWS infrastructure with layered state isolation (global → regional → vpc-scoped → app) | `OpenTofu` `AWS` `GitHub Actions` |
| [**tofu-aws-core-infra**](https://github.com/ggdaboit/tofu-aws-core-infra) | Reusable OpenTofu module for core AWS resources (IAM, VPC, ECS, ALB, Valkey) | `OpenTofu` `AWS` `ECS` `EKS` |
| [**tofu-aws-application**](https://github.com/ggdaboit/tofu-aws-application) | OpenTofu module for application-level resources (RDS, ECS services, secrets, S3, EventBridge) | `OpenTofu` `AWS` `RDS` `S3` |
| [**tofu-aws-modules**](https://github.com/ggdaboit/tofu-aws-modules) | Shared OpenTofu utility modules (Route53 domain delegation, platform state readers) | `OpenTofu` `AWS` `HCL` |

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gilleadydaboit/)
