GitHub Tutorial & Basic Git Commands

A beginner-friendly guide to understanding Git and GitHub, including installation, configuration, and the most commonly used commands in real development workflows.

---

📌 What is GitHub?

GitHub is a cloud-based platform built on Git that allows developers to:

- Store code repositories
- Track code changes (version control)
- Collaborate with other developers
- Manage projects with issues and pull requests

Git vs GitHub

Tool| Description
Git| Version control system used to track code changes
GitHub| Cloud platform that hosts Git repositories

---

⚙️ Install Git

Download Git from:

https://git-scm.com/

Check if Git is installed:

git --version

Example output:

git version 2.x.x

---

🔧 Configure Git (First-Time Setup)

Set your username and email:

git config --global user.name "Your Name"
git config --global user.email "your@email.com"

Verify configuration:

git config --list

---

📂 Create a Repository

Method 1 — From GitHub Website

1. Go to GitHub
2. Click New Repository
3. Enter repository name
4. Click Create Repository

---

📥 Clone a Repository

Clone a repository to your local machine:

git clone https://github.com/username/repository-name.git

Example:

git clone https://github.com/username/project.git

---

🔄 Basic Git Workflow

A typical development workflow follows these steps:

1. Modify files
2. Add changes
3. Commit changes
4. Push changes to GitHub

---

1️⃣ Check Repository Status

git status

Shows:

- Modified files
- Staged files
- Untracked files

---

2️⃣ Add Files

Add a single file:

git add file.py

Add all files:

git add .

---

3️⃣ Commit Changes

git commit -m "Added login detection module"

A commit acts as a snapshot of your project.

---

4️⃣ Push Code to GitHub

git push origin main

This uploads your code to GitHub.

---

📦 Full Example Workflow

git clone repo-url
cd project-folder

git add .
git commit -m "Initial project setup"

git push origin main

---

⬇️ Pull Latest Changes

If new updates are pushed to the repository:

git pull origin main

This downloads and merges the latest changes.

---

🌿 Branching

Branches allow developers to work on features independently.

Create a new branch:

git branch feature-login

Switch branch:

git checkout feature-login

Create and switch branch:

git checkout -b feature-login

Push branch to GitHub:

git push origin feature-login

---

🔁 Pull Requests

Pull requests allow developers to propose code changes.

Workflow:

1. Create a branch
2. Push branch to GitHub
3. Open Pull Request
4. Code review
5. Merge into main branch

---

📜 View Commit History

git log

Short version:

git log --oneline

Example output:

a23f1 Added ML detection model
d82f3 Updated dashboard UI

---

↩️ Undo Changes

Discard changes in a file:

git checkout -- file.py

Undo the last commit:

git reset HEAD~1

---

🌐 Check Remote Repository

git remote -v

Example output:

origin https://github.com/user/repo.git

---

📁 Example Project Structure

project/
│
├── app.py
├── requirements.txt
├── README.md
├── src/
└── data/

---

✅ Best Practices

✔ Commit frequently
✔ Write meaningful commit messages

Example:

Added anomaly detection model for login attacks

Avoid messages like:

update code

✔ Use branches for features
✔ Maintain a clear README file

---

📊 Git Command Cheat Sheet

Command| Description
"git clone"| Download repository
"git status"| Check changes
"git add ."| Stage files
"git commit -m"| Save snapshot
"git push"| Upload changes
"git pull"| Download latest updates
"git branch"| Create branch
"git checkout"| Switch branch
"git log"| View commit history

---

🚀 Conclusion

Git and GitHub are essential tools for modern software development. Learning these commands enables developers to:

- Manage code efficiently
- Collaborate with teams
- Maintain project history
- Build professional portfolios

Mastering Git workflows is a core skill for every software engineer.
