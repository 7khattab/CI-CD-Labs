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

