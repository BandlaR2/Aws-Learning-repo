# Git Commit

## What is Git Commit?
`git commit` saves changes permanently in Git history.

Benefits:
- Saves project changes
- Creates version history
- Allows rollback to previous versions
- Helps track updates

Example:

```bash
git add .
git commit -m "Initial commit"
```

---

# Commit Messages

A commit message describes the changes made.

Good Examples:

```bash
git commit -m "Added login page"
git commit -m "Updated README file"
git commit -m "Fixed navbar issue"
```

Bad Examples:

```bash
git commit -m "Updated"
git commit -m "Fixed stuff"
```

---

# Git Log

`git log` shows commit history.

Example:

```bash
git log
```

Simplified view:

```bash
git log --oneline
```

Benefits:
- Shows previous commits
- Displays author details
- Helps in debugging

---

# Git Repository

A Git repository stores project files and tracks their history.

Types:

### Local Repository
Stored on your computer.

Benefits:
- Work offline
- Track project changes

### Remote Repository
Stored on platforms like GitHub.

Benefits:
- Collaboration
- Backup and security

---

# Initializing Git Repository

Step 1: Create project folder

```bash
mkdir Mini-Finance
```

Step 2: Move inside folder

```bash
cd Mini-Finance
```

Step 3: Initialize Git

```bash
git init
```

Step 4: Verify repository

```bash
ls -a
```

Output:

```text
.git
```

Benefits:
- Tracks changes
- Stores project history
- Enables collaboration