# Creating and Tracking Files in Git

## Creating a File

Move to project folder:

```bash
cd Mini-Finance
```

Create a file:

```bash
touch index.html
```

Check created files:

```bash
ls
```

Edit file:

```bash
code index.html
```

---

# Git Status

`git status` shows the current state of the repository.

It displays:

- Untracked files
- Modified files
- Staged files

Example:

```bash
git status
```

Output:

```text
Untracked files:
    index.html
```

Meaning:
Git recognizes the file but is not tracking it yet.

---

# Git Add

`git add` moves files into the staging area.

Example:

Add one file:

```bash
git add index.html
```

Add all files:

```bash
git add .
```

Check status:

```bash
git status
```

Output:

```text
Changes to be committed:
    new file: index.html
```

Benefits:

- Prepares files for commit
- Organizes changes
- Helps review before saving
