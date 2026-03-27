## 🚀 Agentic DevOps with Claude Code

### 📌 Project Overview

This project demonstrates how AI agents can be integrated into DevOps workflows using structured context and automation techniques.

The goal was to explore how tools like Claude Code can be guided using configuration files such as `CLAUDE.md` to enforce engineering standards and improve development efficiency.

---

## 🧠 Problem Statement

Traditional DevOps workflows rely heavily on manual scripting and tool-based automation.

This project explores:

* How to **guide AI behaviour** in a codebase
* How to enforce **project constraints using context**
* How to integrate AI into **real DevOps workflows**

---

## ⚙️ Technologies Used

* AWS (S3, CloudFront, EC2)
* Terraform
* GitHub Actions (CI/CD)
* OpenID Connect (OIDC)
* Claude Code
* Model Context Protocol (MCP)

---

## 🏗️ Architecture

The project follows a **static web deployment architecture**:

* Frontend built with HTML & CSS
* Hosted on AWS (S3 + CloudFront OR EC2 + Nginx)
* CI/CD pipeline using GitHub Actions
* Infrastructure provisioned with Terraform

AI integration layer:

* `CLAUDE.md` defines project rules and constraints
* Claude Code reads and follows these instructions
* AI agents assist with automation and validation

---

## 🤖 Key Features

### 1. AI Behaviour Control with CLAUDE.md

Defined project rules such as:

* No JavaScript frameworks
* Static website architecture only
* Nginx-compatible deployment

Result:
Claude refused invalid requests (e.g., adding React), proving rule enforcement.

---

### 2. AI-Powered DevOps Workflows

Used Claude Code to:

* Analyse repository structure
* Suggest improvements
* Automate DevOps tasks using commands

---

### 3. Secure CI/CD Pipeline

Implemented:

* GitHub Actions for deployment
* OIDC authentication (no long-lived credentials)
* Automated build and deployment process

---

### 4. Infrastructure as Code

Used Terraform to:

* Provision AWS resources
* Maintain consistent infrastructure
* Enable repeatable deployments

---

### 5. MCP Server Integration (Exploration)

Attempted to connect AI agents to real infrastructure using MCP servers.

Although challenges were encountered, this provided insight into:

* AI system integration
* Real-world DevOps complexity
* Debugging distributed systems

---

## 🌍 Real Outcome

Successfully built and deployed:

👉 A **static portfolio website on AWS**

Key highlights:

* Lightweight and scalable
* Secure deployment pipeline
* AI-assisted development workflow

---

## ⚠️ Challenges & Solutions

| Challenge                    | Solution                                               |
| ---------------------------- | ------------------------------------------------------ |
| Claude Code permission loop  | Moved project to a directory without spaces            |
| MCP server connection issues | Documented troubleshooting steps and fallback approach |
| Authentication token errors  | Re-authenticated and refreshed credentials             |
| AI behaviour inconsistencies | Improved `CLAUDE.md` with stricter conventions         |

---

## 💡 Key Learnings

* AI requires **clear context and constraints** to be effective
* Documentation is now a **control mechanism**, not just reference
* DevOps is evolving into **AI-assisted system design**
* Security (OIDC, guardrails) is critical in automated workflows
* Problem-solving is a core DevOps skill

---

## 🔮 Future Improvements

* Fully functional MCP server integration
* Advanced Terraform modules
* Multi-environment deployment (dev/staging/prod)
* Monitoring and observability integration

---

## 🙌 Acknowledgment

This project was completed as part of the *Ultimate Agentic DevOps with Claude Code* course by **Pravin Mishra**.

---

