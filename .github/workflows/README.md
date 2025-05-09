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
