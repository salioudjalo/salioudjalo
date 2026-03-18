# 👋 Saliou Djalo — Cloud & DevOps Engineer

> *If it can't be versioned and automated, it shouldn't exist.*

Building production-grade AWS and Kubernetes platforms with a focus on
reliability, automation, and operational excellence.

---

## 🎓 Certifications

[![AWS Solutions Architect](https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=flat&logo=amazon-aws&logoColor=white)](https://www.credly.com)
[![Terraform Associate](https://img.shields.io/badge/HashiCorp-Terraform_Associate_003-7B42BC?style=flat&logo=terraform&logoColor=white)](https://www.credly.com/badges/4470e647-544b-433c-87c8-28bf06c33c39/public_url)
[![AWS Cloud Practitioner](https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=flat&logo=amazon-aws&logoColor=white)]([https://www.credly.com](https://www.credly.com/badges/8b468d49-c4a1-4a97-a2c3-bc06d3a55fa6/public_url))

---

## 🛠 Core Stack

| Domain | Tools |
|---|---|
| **Cloud** | AWS (EC2, VPC, IAM, S3, EKS, ECS/Fargate, RDS, Lambda, CloudWatch) |
| **Infrastructure as Code** | Terraform (modules, remote state, workspaces) · Ansible |
| **Containers & Orchestration** | Docker · Kubernetes (EKS) · Helm |
| **CI/CD** | GitHub Actions · GitLab CI/CD |
| **Observability** | Prometheus · Grafana · Alertmanager · Datadog · CloudWatch |
| **Scripting** | Python · Bash |
| **OS** | Linux (Ubuntu · Amazon Linux) |

---

## 🔥 Featured Projects

### 📊 Kubernetes SRE Observability Platform
> Production-oriented Kubernetes observability stack with SLO dashboards, alerting and incident runbooks.

**Stack:** Kubernetes · Prometheus · Node Exporter · Grafana · Alertmanager

**Features:**
- Full cluster and node metrics collection pipeline
- Grafana SLO dashboards with RED method (Rate, Errors, Duration)
- Prometheus alerting rules with severity tiering
- Alertmanager routing and notification configuration
- Production incident runbooks for common failure scenarios

**Why it matters:** Observability is not an afterthought — this platform is designed the way SRE teams build it in production.

🔗 [View Repository](https://github.com/salioudjalo/sre-observability-platform)

---

### ☸️ EKS Production Platform
> Production-style Kubernetes environment on AWS EKS with full CI/CD automation.

**Stack:** Terraform · AWS EKS · Docker · ECR · GitHub Actions

**Features:**
- Terraform-managed VPC and EKS cluster
- Dockerised FastAPI application
- ALB Ingress via AWS Load Balancer Controller
- Horizontal Pod Autoscaler (HPA)
- Liveness & Readiness probes with resource limits
- Full CI/CD pipeline: build → push → deploy

**Why it matters:** Demonstrates real-world Kubernetes operations on AWS — infrastructure, application, and delivery all as code.

🔗 [View Repository](https://github.com/salioudjalo/eks-mini-platform)

---

### 🐳 Docker → ECS/Fargate Deployment Pipeline
> Fully automated container lifecycle from code commit to production deployment.

**Stack:** Docker · Amazon ECS (Fargate) · ECR · GitHub Actions

**Features:**
- Dockerised application with optimised multi-stage build
- ECR image registry with tagging strategy
- ECS Fargate service deployment
- Automated CI/CD pipeline: build → push → deploy
- Environment promotion gates

**Why it matters:** End-to-end delivery automation without managing servers — the modern container deployment pattern.

🔗 [View Repository](https://github.com/salioudjalo/docker-to-ecs-real)

---

### 🏗️ Terraform AWS Foundations
> Modular, production-grade AWS infrastructure built entirely with Terraform.

**Stack:** Terraform · AWS (VPC, IAM, EC2, RDS, S3)

**Features:**
- Custom VPC with public/private subnet architecture
- NAT Gateway, Internet Gateway, route tables
- Secure IAM roles and least-privilege policies
- Remote backend with state locking
- Modular architecture — reusable across environments

**Why it matters:** Infrastructure foundations done right — the base layer every production AWS environment needs.

🔗 [View Repository](https://github.com/salioudjalo/terraform-aws-foundations)

---

## 📐 Engineering Philosophy

- **Infrastructure is code** — versioned, reviewed, tested, deployed like software
- **Security by design** — IAM least-privilege, private subnets, encryption at rest by default
- **Observability first** — if you can't measure it, you can't operate it
- **Automation over documentation** — runbooks are for what can't be automated yet

---

## 🌍 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Saliou_Djalo-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salioudjalo)
[![Email](https://img.shields.io/badge/Email-saliou.apps@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:saliou.apps@gmail.com)
