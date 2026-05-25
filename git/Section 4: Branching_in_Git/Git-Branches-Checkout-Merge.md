# Git Branches

## What is a Git Branch?

A Git branch is a separate version of a project where developers can work independently without affecting the main code.

Benefits:
- Work on new features safely
- Fix bugs independently
- Collaborate with teams
- Avoid affecting the main project

Example:

```text
master
   │
   ├── develop
   ├── profile-page
```

Create a branch:

```bash
git branch develop
```

View branches:

```bash
git branch
```

---

# Git Checkout

`git checkout` is used to switch between branches.

Switch branch:

```bash
git checkout develop
```

Create and switch at once:

```bash
git checkout -b develop
```

Check commit history:

```bash
git log
```

Switch to previous commit:

```bash
git checkout commit-hash
```

Return to main branch:

```bash
git checkout master
```

---

# Git Merge

`git merge` combines changes from one branch into another.

Switch to main branch:

```bash
git checkout master
```

Merge another branch:

```bash
git merge develop
```

Benefits:
- Combines features
- Supports teamwork
- Keeps workflow organized

---

# Merge Conflict

Merge conflict occurs when multiple branches modify the same part of a file.

Resolve conflict:

```bash
git add filename
git commit -m "Resolved merge conflict"
```
