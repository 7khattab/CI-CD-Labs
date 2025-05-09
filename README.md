# 🚀 GitHub Actions Labs for DevOps Automation

This repository contains a series of practical labs focused on mastering **GitHub Actions** and integrating CI/CD pipelines for real-world DevOps scenarios.

---

## 📁 Repository Structure

labs/
├── lab1-manual-workflow/
│ └── .github/workflows/manual.yml
├── lab2-repo-event-trigger/
│ └── .github/workflows/on-push.yml
├── lab3-cross-repo-dispatch/
│ ├── sender/
│ │ └── dispatch_trigger.sh
│ └── receiver/
│ └── .github/workflows/receive_dispatch.yml
├── lab4-scheduled-and-manual/
│ └── .github/workflows/schedule_manual.yml
|---lab5-run workflow on Docker container
|    |-- .github/workflows/workflow-on-docker.yml
|    
└── README.md
|---APP/
     | -- hello.py

---

## 🛠 Tools & Technologies

- **GitHub Actions** — CI/CD pipelines
- **Bash / Shell scripting** — triggering workflows via `curl`
- **GitHub REST API v3** — `repository_dispatch` for cross-repo workflows
- **CRON Jobs** — for scheduled workflows
- **YAML** — defining workflow logic

---

## 📌 Labs Overview

### ✅ Lab 1: Hello World (GitHub Actions)
> This is the first GitHub Actions workflow to verify that the GitHub CI/CD pipeline is triggered correctly and runs a basic script.

### 🔁 Lab 2: Trigger by GitHub Events
> Execute CI/CD tasks when specific repository events occur (e.g., `push`, `pull_request`).

### 🔗 Lab 3: Cross-Repo Dispatch with GitHub API
> Use `repository_dispatch` to trigger workflows across repositories using GitHub API and Personal Access Tokens (PAT).

### ⏰ Lab 4: Schedule and Manual Triggers
> Combine scheduled CRON triggers and manual UI/API triggers in one workflow.

### 🐳 Lab 5: Run Workflow Jobs in Docker Containers

Run GitHub Actions jobs inside Docker containers using the container keyword.

Use a Python Docker image to verify version and run scripts.

---

🧰 Tools & Technologies Used

GitHub Actions

GitHub REST API

Git

Docker

Python

GitLab (for cross-CI testing)



## 📄 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/github-actions-labs.git


👤 Author

Mohamed Khattab
DevOps & Cloud Enthusiast | Egypt

