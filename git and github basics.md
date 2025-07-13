# 🔧 Module 4: Introduction to Git and Version Control

This module covers the basics of Git, its purpose, and its internal architecture — including how Git tracks files across different states.

---

## 🟢 What is Git?

Git is a **distributed version control system** that helps developers track changes in code, collaborate with others, and manage source code history.

### ✨ Why use Git?

- Tracks every version of your project.
- Enables collaboration across teams.
- Helps roll back to previous versions.
- Allows branching and merging.

---

## 🟢 Git Architecture: Workspace, Staging, Repositories

Git works in multiple areas/stages. Here's how files move through the Git system:

### 📊 Git Architecture Diagram:

![WhatsApp Image 2025-07-11 at 10 31 06_1470ac03](https://github.com/user-attachments/assets/3ecb825f-faec-4ef0-9420-fc29ecffc73e)


---

### 🔹 1. **Workspace**  
Your local working directory where files are created or edited.

```bash
# Make changes in your project files
git status       # Check file changes
git diff         # See exact line-by-line differences
```

---

### 🔹 2. **Staging Area**  
A temporary area where you list files to be committed.

```bash
git add file.txt           # Add file to staging
git add .                  # Add all files
git reset file.txt         # Remove file from staging
```

---

### 🔹 3. **Local Repository**  
This is where the actual commits are stored locally.

```bash
git commit -m "Message"    # Save staged files to local repo
git log                    # Show commit history
git reset <commit>         # Undo commits
```

---

### 🔹 4. **Remote Repository**  
A cloud-based repository (like GitHub) where code is pushed and shared with others.

```bash
git push origin main       # Upload code to remote
git pull origin main       # Fetch + merge latest from remote
git fetch                  # Fetch changes (but don’t merge)
git clone <repo_url>       # Copy full project to your machine
```

---
| Command                | Purpose                                        |
|------------------------|------------------------------------------------|
| `git init`             | Initialize a new Git repository                |
| `git status`           | Show modified/staged files                     |
| `git add <file>`       | Add file to staging area                       |
| `git commit -m "msg"`  | Commit staged changes with a message           |
| `git log`              | View commit history                            |
| `git reset <file>`     | Remove file from staging                       |
| `git reset <commit>`   | Revert to specific commit                      |
| `git diff`             | Show file changes not yet staged               |
| `git diff HEAD`        | Compare working dir to last commit             |
| `git push`             | Upload commits to remote repo                  |
| `git pull`             | Download and merge from remote repo            |
| `git fetch`            | Download changes from remote (no merge)        |
| `git clone <URL>`      | Copy entire remote repo to local machine       |

# Core Git Operations, Branching, Remotes & GitHub/GitLab Basics

---

##  1. Core Git Operations

Git uses a simple yet powerful workflow involving initializing a repository, adding files, committing changes, and checking the status.

### 🔹 `git init`
Initializes a new Git repository in your project folder.

```bash
git init
```

📌 Creates a hidden `.git` folder to start tracking versions.

---

### 🔹 `git status`
Shows the current state of the working directory and staging area.

```bash
git status
```

📌 Tells you which files are modified, staged, or untracked.

---

### 🔹 `git add`
Adds files to the staging area (preparing them to be committed).

```bash
git add index.html      # add one file
git add .               # add all changes
```

---

### 🔹 `git commit`
Commits the staged files with a message, saving a snapshot to local history.

```bash
git commit -m "Initial commit"
```

---

### 🔹 `git log`
Displays the history of commits.

```bash
git log
```

📌 Shows commit hashes, author info, and messages.

---

## 📋 Summary Table: Core Git Commands

---
| Command                | Description                                  |
|------------------------|----------------------------------------------|
| `git init`             | Start a new Git repo                         |
| `git status`           | Show file states                             |
| `git add <file>`       | Add file to staging                          |
| `git commit -m "msg"`  | Save snapshot to local repo                  |
| `git log`              | View commit history                          |


---

## 🟢 2. Branching and Merging

Git allows you to work on multiple versions of your code using **branches**.

### 🔹 Create a New Branch
```bash
git branch feature-login
```

### 🔹 Switch to a Branch
```bash
git checkout feature-login
```

### 🔹 Create and Switch
```bash
git checkout -b new-feature
```

### 🔹 Merge Branches
```bash
git checkout main
git merge feature-login
```

### 🔹 Delete a Branch
```bash
git branch -d feature-login
```

---

## 📋 Summary Table: Branching

---
| Command                       | Description                             |
|-------------------------------|-----------------------------------------|
| `git branch <name>`           | Create a new branch                     |
| `git checkout <name>`         | Switch to a branch                      |
| `git checkout -b <name>`      | Create and switch to a new branch       |
| `git merge <branch>`          | Merge branch into current               |
| `git branch -d <name>`        | Delete a branch                         |
```

---

## 🟢 3. Remote Operations (push, pull, remote)

Remote repositories allow you to share code using platforms like GitHub/GitLab.

---

### 🔹 `git remote add`
Link your local project with a remote repo.

```bash
git remote add origin https://github.com/karan/project.git
```

---

### 🔹 `git push`
Push commits to the remote repo.

```bash
git push origin main
```

---

### 🔹 `git pull`
Pull latest changes from remote and merge.

```bash
git pull origin main
```

---

### 🔹 `git fetch`
Fetch latest changes without merging.

```bash
git fetch origin
```

---

## 📋 Summary Table: Remote Operations

---
| Command                              | Description                            |
|--------------------------------------|----------------------------------------|
| `git remote add origin <url>`        | Link local repo to remote              |
| `git push origin <branch>`           | Upload changes to remote               |
| `git pull origin <branch>`           | Download + merge from remote           |
| `git fetch origin`                   | Download without merge                 |
```

---

## 🟢 4. GitHub / GitLab Basics

### 🔹 What is GitHub?
- A hosting service for Git repositories.
- Helps manage code, collaborate, and deploy projects.

### 🔹 Common GitHub Operations:

1. **Create Repository**  
   Go to [github.com](https://github.com) → New Repository → Name it → Create.

2. **Push Local Project**
```bash
git init
git remote add origin https://github.com/username/repo.git
git add .
git commit -m "First commit"
git push -u origin main
```

3. **Clone Repo**
```bash
git clone https://github.com/username/repo.git
```

---

