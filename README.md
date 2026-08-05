# week2-devops
This is my internship project related to git learning and version control system.

# Comprehensive Guide to Git, GitHub, and Version Control

This document provides definitions, workflows, architecture diagrams, and command references for essential Git concepts used in modern DevOps practices.

---

## 1. Overview of Core Concepts

| Topic | Definition | Real-World Use Case |
| :--- | :--- | :--- |
| **Git** | A local, distributed version control system (VCS) that tracks changes in source code over time. | Tracking code changes locally without needing an internet connection. |
| **GitHub** | A cloud-based platform that hosts Git repositories and provides collaboration tools. | Storing code remotely, running CI/CD pipelines, and conducting peer code reviews. |
| **Git Workflow** | A set of conventions or branching strategies followed by teams to manage code changes. | Standardizing how feature branches are merged into production code. |
| **Branching** | Creating an independent line of development isolated from the main codebase. | Developing a new feature without breaking the working production application. |
| **Merge** | Combining history and changes from one branch into another branch. | Integrating a completed feature branch back into the main branch. |
| **Rebase** | Re-applying commits from one branch on top of another base branch to maintain a linear history. | Keeping a feature branch up to date with `main` without extra "merge commits." |
| **Pull Request (PR)** | A request submitted on GitHub to propose and review changes before merging into a target branch. | Enabling peer code review and automated testing before code reaches production. |
| **README.md** | A Markdown documentation file explaining project installation, usage, and architectural details. | Onboarding new developers and documenting repository instructions. |
| **.gitignore** | A configuration file listing files and directories that Git should ignore and untrack. | Preventing credentials (`.env`), build outputs (`dist/`), or dependencies (`node_modules/`) from being pushed to GitHub. |

---

## 2. Git Architecture & Workflow
