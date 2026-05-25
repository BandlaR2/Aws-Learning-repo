# Introduction to GitHub

## What is GitHub?

GitHub is a cloud platform used to store, manage, and collaborate on Git repositories.

Benefits:
- Store code online
- Collaborate with teams
- Track project changes
- Contribute to open-source projects

---

# How GitHub Works

Workflow:

```text
Local Repository
       ↓
git push
       ↓
GitHub Repository
       ↓
git pull / git clone
       ↓
Team Collaboration
```

Steps:
1. Create a local repository
2. Push code to GitHub
3. Team members clone the project
4. Make changes and push updates
5. Merge updates into the main project

---

# Local vs Remote Repository

## Local Repository
Stored on your computer.

Benefits:
- Work offline
- Track changes locally

## Remote Repository
Stored online (GitHub).

Benefits:
- Backup code
- Team collaboration

---

# Public vs Private Repository

## Public Repository
- Visible to everyone
- Supports open-source projects

## Private Repository
- Restricted access
- Used for company or personal projects

---

# GitHub Features

- Repository → Stores project files
- Branches → Separate development versions
- Pull Requests → Suggest changes
- Issues → Track bugs and tasks
- Code Review → Review code changes

---

# Creating GitHub Account

Steps:

1. Open https://github.com
2. Click Sign Up
3. Enter email
4. Create password
5. Choose username
6. Verify account
7. Create account

---

# Git Authentication

Authentication allows secure access to repositories.

## HTTPS Authentication

Clone repository:

```bash
git clone https://github.com/username/repository.git
```

Save credentials:

```bash
git config --global credential.helper store
```

---

## SSH Authentication

Generate SSH key:

```bash
ssh-keygen -t rsa -b 4096 -C "your-email@example.com"
```

Copy SSH key:

```bash
cat ~/.ssh/id_rsa.pub
```

Test connection:

```bash
ssh -T git@github.com
```

Clone using SSH:

```bash
git clone git@github.com:username/repository.git
```
