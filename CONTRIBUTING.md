# Contributing Guidelines
This document explains how external contributors should prepare and submit changes to this repository.

## Getting Started

1. Fork the repository to your own GitHub account.
2. Clone your fork to your local computer.
3. Create a separate branch for your changes instead of working directly on `main`.
4. Stage and commit your changes with a clear message.

   ```bash
   git add .
   git commit -m "Describe the changes"
5. Push the branch to your fork on GitHub.

   ```bash
   git push -u origin branch-name
6. Open a pull request from the branch in your fork to the original repository's `main` branch.
7. The repository owner reviews the diff, requests corrections if necessary, and merges the pull request when the changes are correct.
8. After the pull request is merged, update your local `main` branch from the original repository and synchronize your fork.

   ```bash
   git switch main
   git fetch upstream
   git pull upstream main
   git push origin main