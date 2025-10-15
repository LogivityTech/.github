# LogivityTech

Building reliable data flows and logistics visibility for modern supply chains.  
This GitHub organization hosts our developer-facing tooling, workflows, and documentation.

-  Website: https://logivity.com  
-  Developer Handbook (Wiki): https://github.com/LogivityTech/logivity-devops-toolkit/wiki

---

## 🚀 What’s in this org

-  logivity-devops-toolkit  
    Reusable GitHub Actions workflows, composite actions, automation scripts (TypeScript/Bun), and a Go-based CLI for repository setup, CI/CD, publishing, and deployment.

-  artifacts  
    Registry-backed repository for publishing and tracking our open-source or shared artifacts (Maven packages and NPM packages).

If you’re new here, start with the Developer Handbook (Wiki) above.

---

## 📚 Start Here (for developers)

-  Getting Started: install the CLI, verify tools, and run your first pipeline  
  https://github.com/LogivityTech/logivity-devops-toolkit/wiki/Getting-Started

-  VBS Migration: migrate existing repos to GitHub Actions  
  https://github.com/LogivityTech/logivity-devops-toolkit/wiki/VBS-Migration-Guide

-  Deployment: how to deploy services and configurations to dev/test/prod  
  https://github.com/LogivityTech/logivity-devops-toolkit/wiki/Deployment-Overview

-  Pipeline Architecture: CI, publish, deploy flows and quality gates  
  https://github.com/LogivityTech/logivity-devops-toolkit/wiki/Pipeline-Architecture-Overview

---

## 🧩 Highlights

-  Standardized CI/CD  
  Reusable workflows for Maven, Node.js, and configuration repositories. Quality gates via Sonar, security scanning with Trivy, and consistent versioning (SNAPSHOT → release → next SNAPSHOT).

-  Deployment via GitHub Actions  
  Manual and auto-deploy pipelines for services and config repos. PROD deployments use protected environments and approval gates.

-  Go CLI + TypeScript Automation  
  logivity-cli (Go) for repo setup and GitHub configuration; Bun-powered TypeScript scripts for build, versioning, publishing, and deployment.

---

## 🔐 Security and Environments (high level)

-  DEV/TEST secrets are configured at the organization level.  
-  PROD secrets live in each repository’s protected PROD environment and are usable from main only.  
-  Workflow and automation files are protected via CODEOWNERS and reviews.

Details in the wiki:  
https://github.com/LogivityTech/logivity-devops-toolkit/wiki/Secrets-Overview

---

## 🧭 Useful Links

-  Developer Handbook (Wiki)  
  https://github.com/LogivityTech/logivity-devops-toolkit/wiki

-  Main Toolkit Repo  
  https://github.com/LogivityTech/logivity-devops-toolkit

-  Artifacts Repo (Maven/NPM)  
  https://github.com/LogivityTech/artifacts

-  Organization on GitHub  
  https://github.com/LogivityTech

---

## 💬 Contact

For questions or contributions, open an issue in the relevant repository or reach out via the Platform/DevOps channel (internal).
