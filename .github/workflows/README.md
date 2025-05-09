# Lab 01 – Hello World (GitHub Actions)

## Purpose

This is the first GitHub Actions workflow to verify that the GitHub CI/CD pipeline is triggered correctly and runs a basic script.

## Trigger

- This workflow runs on every push to the repository.

## Workflow File

Location: `.github/workflows/hello-world.yml`

## Output

The job will simply print:





# Lab 2: Triggering GitHub Workflow Based on Repository Events

This lab demonstrates how to create a GitHub Actions workflow that responds to different events in the repository such as pushes, pull requests.

## 🚀 Features
- Single workflow handles multiple event types.
- Logs event details for debugging and learning purposes.

## 🛠️ How It Works
The `event-trigger.yml` file under `.github/workflows` defines three triggers:
- `push` to main
- `pull_request` to main





# Lab 3: Repository Dispatch and Cross-Repo Workflows

## 📝 Description
This lab simulates how to trigger GitHub Actions workflows in one repository from another using the `repository_dispatch` API event. Useful for decoupling source and CI/CD logic.

## 🔄 Flow
1. Repo A pushes code
2. A script or GitHub Action calls the GitHub API
3. Repo B receives the `repository_dispatch` and runs a workflow

## 🛠️ Requirements
- GitHub Personal Access Token with repo/workflow scope
- The receiving repo must listen for `repository_dispatch` events


# .gitlab-ci.yml
stages:
  - check

listener_job:
  stage: check
  script:
    - echo "Pipeline triggered"
    - echo "Received event type: $EVENT_TYPE"




# Lab 4: Schedule Time and Manual Workflow Dispatch

## 🎯 Objective
This lab demonstrates how to:
- Manually trigger a GitHub Actions workflow using `workflow_dispatch`.
- Automatically run the same workflow on a schedule using `cron`.
- Use user-defined inputs when triggering the workflow manually.

## 📅 Scheduled Time
The workflow runs every 3 minute.

## 🛠 Manual Trigger
You can trigger the workflow from GitHub's "Actions" tab and optionally provide a **reason**.

