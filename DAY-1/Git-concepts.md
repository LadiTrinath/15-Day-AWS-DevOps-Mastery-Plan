# 📚 Git Concepts Guide - MindCircuit DevOps

Welcome to the **Git (SCM)** learning guide, crafted based on the MindCircuit DevOps curriculum. This guide will help you understand Git from the ground up, solve real-world collaboration issues, and ace interviews. 🚀

---

## 🧠 What is Git?
Git is a distributed version control system that helps developers track changes in their codebase. It enables collaboration, rollback, and powerful branching workflows.

> Real-World Problem Solved: Avoids confusion when multiple developers work on the same code by providing proper change tracking and collaboration features.

---

## 🔧 Installing Git and Basic Commands Overview
- Download and install Git from [git-scm.com](https://git-scm.com)
- `git --version`, `git init`, `git status`, `git add`, `git commit`, `git log`

---

## 🔍 Diff Between Git and GitHub
- Git: A tool for version control (local)
- GitHub: Cloud-based Git repository hosting service for collaboration

## 🔄 Diff Between Git and SVN
- Git is distributed; SVN is centralized
- Git offers offline commits; SVN does not

---

## 🔐 How to Create GitHub Account and Use GitHub
- Sign up at [GitHub](https://github.com)
- Create a repo → Clone it → Push code using Git

## 🗂️ Git Stages
1. Working Directory (Untracked/Modified files)
2. Staging Area (`git add`)
3. Committed (`git commit`)

---

## 🌲 Git Branches & Strategy
- `git branch`, `git checkout`, `git merge`, `git rebase`
- Strategies: Feature branches, GitFlow, Trunk-based development

> Real-World Problem Solved: Enables parallel development of features without breaking the main application.

---

## 🧪 Git Merge vs Git Rebase
- Merge: Combines branches keeping all history
- Rebase: Moves your changes on top of the target branch

---

## 🧾 Basic Linux Commands for Git Practice
- `ls`, `cd`, `mkdir`, `touch`, `rm`, `cat`, `nano`, `vim`

---

## 🛠️ Git Repository Setup
- `git init`, `git remote add origin`, `git push -u origin main`

## 📤 Git Push, Pull and Fetch
- `git push`: Upload changes to remote
- `git pull`: Fetch + merge changes from remote
- `git fetch`: Only fetch changes (no merge)

---

## 💾 Git Stash
Temporarily saves your changes: `git stash`, `git stash apply`, `git stash pop`

## ⚔️ Git Conflicts
- Happens during merge/rebase
- Resolved by manually editing files then committing

---

## 🔖 Git Tags
Used to mark release points: `git tag v1.0`, `git tag`, `git push origin v1.0`

## ⏪ Git Revert
Undo a commit without modifying history: `git revert <commit-id>`

## 🍒 Git Cherry Pick
Apply specific commit(s) from one branch to another: `git cherry-pick <commit-id>`

---

## 🔄 Pull Request (PR)
Request to merge code into a main branch from a feature branch. Common in GitHub workflows.

## 🌐 Git Webhooks
Trigger actions (e.g., CI/CD) when a push/PR happens.

## 🔐 Protecting GitHub Branches
- Enable protection on `main` or `dev` branches
- Require PR approvals, prevent force pushes

---

## 🧩 Real-World Problems Solved by Git
- **Collaboration**: Manage multiple developers working on the same codebase
- **Tracking**: Every change is documented
- **Rollback**: Restore any previous working state
- **Branching**: Isolate features, fixes, or experiments

---

## 💬 Top Git Interview Questions
| Question | Answer |
|----------|--------|
| What is Git? | A distributed version control system for tracking changes in source code. |
| What is the difference between Git and GitHub? | Git is a local tool; GitHub is a remote hosting service. |
| How do you resolve a Git conflict? | Manually fix files, add, and commit the resolution. |
| What is the use of `git stash`? | Temporarily stores uncommitted changes. |
| What’s the difference between `git pull` and `git fetch`? | `pull` = fetch + merge; `fetch` = only fetch. |
| When to use `rebase` vs `merge`? | Use rebase for cleaner history, merge for preserving full context. |

---

## 🔗 Connect & Practice
- Practice on GitHub by pushing code from your terminal.
- Create sample projects and open pull requests.
- Use Git + Jenkins to create CI pipelines.

> 💡 Tip: Create a `Git Cheatsheet.md` and keep it pinned to your repo for interview revision!

---

Made with ❤️ by MindCircuit ✨
