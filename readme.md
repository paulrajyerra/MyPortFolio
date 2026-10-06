# ☁️ Yerra Paul Raj — Azure DevOps & Cloud IaC Engineer Portfolio

[![Microsoft AZ-104 Certified](https://img.shields.io/badge/Microsoft%20Certified-AZ--104-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://learn.microsoft.com/)
[![Terraform IaC](https://img.shields.io/badge/IaC-Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io/)
[![Azure DevOps](https://img.shields.io/badge/CI%2FCD-Azure%20Pipelines-0078D4?style=for-the-badge&logo=azuredevops&logoColor=white)](https://azure.microsoft.com/en-us/products/devops/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

> **Live Portfolio:** [https://paulrajyerra.github.io](https://paulrajyerra.github.io) *(Replace with your live URL)*  
> **Contact:** [paulrajyerra@gmail.com](mailto:paulrajyerra@gmail.com) | [+91-8885351138](tel:+918885351138) | [LinkedIn Profile](https://linkedin.com/in/paulrajyerra)

---

## 📌 Executive Summary

High-performance, single-page cyber command-center portfolio built for **Yerra Paul Raj**, an **AZ-104 certified aspiring Azure DevOps Engineer** with **2.5+ years of frontline technical support and systems troubleshooting** experience (Blackbaud & Teleperformance).

This repository contains the complete interactive portfolio application featuring live cloud architecture visualizers, continuous integration simulation engines, and incident post-mortem debuggers.

---

## ✨ Key Interactive Features

### 1. 🏗️ Interactive 3-Tier Azure Architecture Visualizer
- **Subnet Explorer:** Deep-dive into each subnet tier (Azure Application Gateway/WAF, Azure Bastion, Tier 1 Web Presentation, Tier 2 App Logic, Tier 3 Database).
- **Live Spec & HCL Viewer:** Dynamic updates displaying subnet CIDR allocations, NSG least-privilege traffic flow rules, and modular HashiCorp Terraform configuration code.
- **One-Click Code Export:** Quick clipboard copier for production Terraform HCL blocks.

### 2. ⚡ Multi-Stage CI/CD Pipeline Simulator
- Live emulator running Azure DevOps YAML pipeline workflows:
  - `Stage 1: Terraform Lint & Format Check`
  - `Stage 2: Static Security Audit (Tfsec)`
  - `Stage 3: Terraform Spec Planning`
  - `Stage 4: Automated Azure Apply`
  - `Stage 5: Synthetic Healthcheck & Monitor Validation`
- Live streaming log terminal console with real-time timers and stage progression badges.

### 3. 🚨 Production RCA Incident Debugger
- Recreates real-world enterprise production troubleshooting based on Paul's experience at Blackbaud.
- Features genuine `.HAR` diagnostic dumps and HTTP 502 Bad Gateway logs.
- Interactive decision tree guiding reviewers through root-cause analysis (resolving misconfigured NSG inbound rules vs. red-herring DNS records).

### 4. 💻 In-Browser Cloud Shell (`paulraj-cli`)
- Interactive terminal emulator supporting commands:
  - `whoami` — Engineer credentials and profile
  - `certs` — AZ-104 and academic certifications
  - `terraform plan` — Dry-run deployment output
  - `cat skills.json` — Categorized technical matrix
  - `incident` — Blackbaud troubleshooting history
  - `contact` — Communication channels

### 5. 🔊 Web Audio API Synthesizer Dock
- Zero external MP3/WAV dependencies; uses browser native sound synthesis.
- Optional acoustic feedback for telemetry pulses, terminal executions, and pipeline state changes.

---

## 🛠️ Tech Stack & Architecture

- **Core:** Semantic HTML5, Vanilla JavaScript (ES6+)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (CDN) with custom cyber-glassmorphism theme
- **3D Graphics:** [Three.js](https://threejs.org/) (Constellation Cloud Node Mesh)
- **Icons & Fonts:** FontAwesome 6.5, Space Grotesk, JetBrains Mono, Inter
- **Audio:** Native Web Audio API

---

## 🚀 Local Development Setup

No complex build pipeline or `npm install` is required. The entire application runs natively in modern browsers.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/paulrajyerra/paulrajyerra.github.io.git
   cd paulrajyerra.github.io
   ```

2. **Open directly in your browser:**
   ```bash
   # On macOS
   open index.html

   # On Linux
   xdg-open index.html

   # On Windows
   start index.html
   ```

3. **Or run with a lightweight local HTTP server:**
   ```bash
   # Using Python 3
   python3 -m http.server 8080

   # Or using Node.js npx
   npx serve .
   ```
   Navigate to `http://localhost:8080`.

---

## 🌐 Free Hosting Deployment Guide

### Deploying to GitHub Pages (Recommended)
1. Fork or push this repository to GitHub under the name `username.github.io`.
2. Ensure `index.html` is in the root directory.
3. In GitHub, navigate to **Settings** → **Pages**.
4. Set **Source** to `Deploy from a branch`, choose branch `main` and folder `/ (root)`.
5. Click **Save**. Your site will be online at `https://<your-username>.github.io`.

---

## 👤 About Yerra Paul Raj

- **Role:** Azure DevOps & Infrastructure as Code Engineer
- **Certification:** Microsoft Certified: Azure Administrator Associate (AZ-104)
- **Background:** B.Tech in Aeronautical Engineering | 2.5+ Years Tech Support Analyst
- **LinkedIn:** [linkedin.com/in/paulrajyerra](https://linkedin.com/in/paulrajyerra)
- **Email:** [paulrajyerra@gmail.com](mailto:paulrajyerra@gmail.com)

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.