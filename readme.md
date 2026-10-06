# Yerra Paul Raj — Azure DevOps & Cloud Infrastructure Portfolio

[![Microsoft Certified: Azure Administrator Associate](https://img.shields.io/badge/Certification-AZ--104-0078D4?logo=microsoft&logoColor=white)](https://learn.microsoft.com/)
[![Terraform IaC](https://img.shields.io/badge/IaC-Terraform-844FBA?logo=terraform&logoColor=white)](https://www.terraform.io/)
[![CI/CD Pipelines](https://img.shields.io/badge/DevOps-Azure%20Pipelines-0078D4?logo=azure-devops&logoColor=white)](https://azure.microsoft.com/products/devops/)
[![GitHub](https://img.shields.io/badge/GitHub-MyPortFolio-181717?logo=github&logoColor=white)](https://github.com/paulrajyerra/MyPortFolio)

Interactive, zero-dependency, single-page cloud engineering portfolio showcasing enterprise-grade Azure DevOps practices, Terraform multi-tier infrastructure as code, automated YAML CI/CD pipelines, and high-severity production incident triage.

---

## 🚀 Live Hosting Options

### Option 1: GitHub Pages (Recommended for `MyPortFolio`)
This repository is configured for immediate one-click hosting via GitHub Pages:
1. Push `index.html` and `README.md` to the `main` branch of [https://github.com/paulrajyerra/MyPortFolio](https://github.com/paulrajyerra/MyPortFolio).
2. Go to **Settings** > **Pages** in your GitHub repository.
3. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
4. Your portfolio will be live at: `https://paulrajyerra.github.io/MyPortFolio/`

### Option 2: Azure Static Web Apps (Free Tier)
1. In the Azure Portal, create an **Azure Static Web App**.
2. Connect your GitHub account and select repository `MyPortFolio` and branch `main`.
3. Set **App location** to `/` and leave **Output location** blank.
4. Azure automatically generates an Azure DevOps / GitHub Actions workflow that deploys on every push.

---

## 🛠 Features & Interactive Simulators
- **Three.js 3D Cloud Mesh**: Real-time canvas rendering of interconnected Azure virtual network nodes.
- **Interactive 3-Tier Architecture**: Clickable topology breakdown (App Gateway, Azure Bastion, Web Subnet, App Subnet, Database Subnet) with dynamic HCL snippet viewer.
- **Live YAML CI/CD Simulator**: 5-stage deployment stream (Lint, Tfsec Security Scan, Terraform Plan, Azure Apply, Synthetic Healthcheck).
- **Production Incident RCA Debugger**: Real-world triage scenario based on 2.5+ years of Blackbaud support experience (.HAR log inspection & NSG resolution).
- **Interactive `paulraj-cli` Shell**: Cloud-shell console with custom commands (`whoami`, `certs`, `skills`, `terraform plan`, `incident`, `contact`, `github`).
- **Web Audio API Sound Engine**: Custom synthesized acoustic feedback for telemetry and deployment triggers without external audio assets.
