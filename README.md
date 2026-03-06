# 🚀 GitHub Tutorial & Basic Git Commands

![Git](https://img.shields.io/badge/Git-Version%20Control-orange?logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Code%20Hosting-black?logo=github)
![Beginner](https://img.shields.io/badge/Level-Beginner-green)

A **beginner-friendly guide** to understanding **Git and GitHub**, including installation, configuration, and the most commonly used commands used in real development workflows.

---

# 📑 Table of Contents

* [What is GitHub](#-what-is-github)
* [Install Git](#️-install-git)
* [Configure Git](#-configure-git-first-time-setup)
* [Create Repository](#-create-a-repository)
* [Clone Repository](#-clone-a-repository)
* [Basic Git Workflow](#-basic-git-workflow)
* [Branching](#-branching)
* [Pull Requests](#-pull-requests)
* [Undo Changes](#-undo-changes)
* [Best Practices](#-best-practices)
* [Git Cheat Sheet](#-git-command-cheat-sheet)

---

# 📌 What is GitHub?

GitHub is a **cloud-based platform built on Git** that allows developers to:

* Store and manage code repositories
* Track code changes using version control
* Collaborate with developers worldwide
* Manage issues, pull requests, and project workflows

### Git vs GitHub

| Tool       | Description                                       |
| ---------- | ------------------------------------------------- |
| **Git**    | Version control system used to track code changes |
| **GitHub** | Cloud platform that hosts Git repositories        |

---

# ⚙️ Install Git

Download Git from:

https://git-scm.com/

Check installation:

```bash
git --version
```

Example output:

```bash
git version 2.x.x
```

---

# 🔧 Configure Git (First-Time Setup)

Set your username and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

Verify configuration:

```bash
git config --list
```

---

# 📂 Create a Repository

### Method 1 — From GitHub Website

1. Go to GitHub
2. Click **New Repository**
3. Enter repository name
4. Click **Create Repository**

---

# 📥 Clone a Repository

Clone a repository to your local machine:

```bash
git clone https://github.com/username/repository-name.git
```

Example:

```bash
git clone https://github.com/username/project.git
```

---

# 🔄 Basic Git Workflow

Typical developer workflow:

```bash
git status
git add .
git commit -m "Added new feature"
git push origin main
```

### Workflow Steps

1️⃣ Modify files
2️⃣ Add changes
3️⃣ Commit changes
4️⃣ Push to GitHub

---

# 1️⃣ Check Repository Status

```bash
git status
```

Shows:

* Modified files
* Staged files
* Untracked files

---

# 2️⃣ Add Files

Add a single file:

```bash
git add file.py
```

Add all files:

```bash
git add .
```

---

# 3️⃣ Commit Changes

```bash
git commit -m "Added login detection module"
```

A commit acts as a **snapshot of your project**.

---

# 4️⃣ Push Code to GitHub

```bash
git push origin main
```

This uploads your code to GitHub.

---

# 📦 Full Example Workflow

```bash
git clone repo-url
cd project-folder

git add .
git commit -m "Initial project setup"

git push origin main
```

---

# ⬇️ Pull Latest Changes

If updates are pushed to the repository:

```bash
git pull origin main
```

This downloads and merges the latest changes.

---

# 🌿 Branching

Branches allow developers to work on features independently.

Create a new branch:

```bash
git branch feature-login
```

Switch branch:

```bash
git checkout feature-login
```

Create and switch branch:

```bash
git checkout -b feature-login
```

Push branch to GitHub:

```bash
git push origin feature-login
```

---

# 🔁 Pull Requests

Pull requests allow developers to propose changes before merging.

Workflow:

1. Create a branch
2. Push branch to GitHub
3. Open Pull Request
4. Code review
5. Merge into main branch

---

# 📜 View Commit History

```bash
git log
```

Short version:

```bash
git log --oneline
```

Example output:

```
a23f1 Added ML detection model
d82f3 Updated dashboard UI
```

---

# ↩️ Undo Changes

Discard file changes:

```bash
git checkout -- file.py
```

Undo the last commit:

```bash
git reset HEAD~1
```

---

# 🌐 Check Remote Repository

```bash
git remote -v
```

Example output:

```
origin https://github.com/user/repo.git
```

---

# 📁 Example Project Structure

```
project/
│
├── app.py
├── requirements.txt
├── README.md
├── src/
└── data/
```

---

# ✅ Best Practices

✔ Commit frequently
✔ Write meaningful commit messages
✔ Use branches for features
✔ Maintain a clear README file

Example commit message:

```
Added anomaly detection model for login attacks
```

Avoid messages like:

```
update code
```

---

# 📊 Git Command Cheat Sheet

| Command         | Description             |
| --------------- | ----------------------- |
| `git clone`     | Download repository     |
| `git status`    | Check changes           |
| `git add .`     | Stage files             |
| `git commit -m` | Save snapshot           |
| `git push`      | Upload changes          |
| `git pull`      | Download latest updates |
| `git branch`    | Create branch           |
| `git checkout`  | Switch branch           |
| `git log`       | View commit history     |

---

# 🚀 Conclusion

Git and GitHub are **essential tools for modern software development**. Mastering these commands allows developers to:

* Manage code efficiently
* Collaborate with teams
* Maintain project history
* Build strong developer portfolios

Learning Git workflows is a **core skill for every software engineer**.

