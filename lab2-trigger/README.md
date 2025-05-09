# Lab 2: Triggering GitHub Workflow Based on Repository Events

This lab demonstrates how to create a GitHub Actions workflow that responds to different events in the repository such as pushes, pull requests

##  Features
- Single workflow handles multiple event types.
- Logs event details for debugging and learning purposes.

## 🛠️ How It Works
The `event-trigger.yml` file under `.github/workflows` defines three triggers:
- `push` to main
- `pull_request` to main
- `issues` opened


