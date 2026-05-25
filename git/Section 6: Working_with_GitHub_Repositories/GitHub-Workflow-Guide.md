# Linking Local and GitHub Repositories

## What is a GitHub Repository?

A GitHub repository is a cloud-based storage location used to store and manage project files online.

Benefits:
- Store code online
- Collaborate with teams
- Backup projects
- Track changes

---

# Creating a GitHub Repository

Steps:

1. Login to GitHub
2. Click "+"
3. Select "New Repository"
4. Enter repository name
5. Select Public or Private
6. Click "Create Repository"

---

# Linking Local Repository with GitHub

Move to project directory:

```bash
cd ~/Documents/Mini-Finance
```

Add remote repository:

```bash
git remote add origin https://github.com/username/repository.git
```

Verify remote:

```bash
git remote -v
```

Output:

```text
origin https://github.com/username/repository.git (fetch)
origin https://github.com/username/repository.git (push)
```

---

# Git Push

`git push` uploads local changes to GitHub.

Stage and commit:

```bash
git add .
git commit -m "Added new files"
```

Push code:

```bash
git push origin main
```

---

# Git Pull

`git pull` downloads and merges changes from GitHub.

```bash
git pull origin main
```

Benefits:
- Updates local repository
- Syncs with latest changes

---

# Git Clone

`git clone` creates a local copy of a GitHub repository.

Clone repository:

```bash
git clone https://github.com/username/repository.git
```

Move into project:

```bash
cd repository
```

---

# Git Clone vs Git Pull

| Command | Purpose |
|-----------|----------|
| git clone | Creates a new local copy |
| git pull | Updates existing local repository |
