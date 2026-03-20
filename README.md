# Git Flow Practice (DevOps Demo Project)

This repository demonstrates a complete Git Flow workflow using Git and GitHub from a Linux server over SSH.

## 🔧 Tech Stack

- Git (CLI)
- GitHub (SSH authentication)
- Linux (remote server via SSH)

## 🌿 Branching Strategy (Git Flow)

This project follows the classic Git Flow model:

- `main` — production-ready code
- `develop` — integration branch
- `feature/*` — feature development
- `release/*` — release preparation

## 🚀 Implemented Workflow

The following Git Flow cycle was executed:

1. Initialized repository locally on Linux server
2. Connected to GitHub using SSH keys
3. Created `develop` branch from `main`
4. Created `feature/login` branch from `develop`
5. Implemented feature and committed changes
6. Merged `feature/login` → `develop`
7. Created `release/1.0` branch
8. Merged `release/1.0` → `main`
9. Synced release changes back to `develop`

## 📦 Key Git Commands Used

```bash
git init
git checkout -b develop
git checkout -b feature/login
git merge feature/login
git checkout -b release/1.0
git merge release/1.0
git push -u origin mainlogin feature
login feature
