# Git Warp 9: Master Git, GitHub & Team Workflows

Welcome to the official repository for the **Git Warp 9** training course! This repository contains code snippets, project folders, and reference materials corresponding to the 16-section hands-on curriculum designed to take you from a Git beginner to a confident team collaborator.

---

## 📊 Course Overview
* **Total Scope:** 16 Sections • 47 Lectures • 1h 55m total runtime
* **Core Goal:** Master local version control, GitHub collaboration, branching strategies, and conflict resolution.
* **Format:** Theory explanations followed by interactive, hands-on terminal challenges.

---

## 📂 Repository Structure

```text
├── 01-getting-started/     # Environment setup, code editors, and GitHub configuration
├── 02-git-fundamentals/    # Repo initialization, commits, GUI vs CLI usage, remotes
├── 03-branching-merging/   # Creating branches, Merging vs Rebasing, and commit squashing
├── 04-collaboration/       # Cloning, pulling, forking, and executing Pull Requests (PRs)
├── 05-conflict-resolution/ # Solving local and PR-level merge conflicts
├── 06-advanced-workflows/  # Branching strategies, rollbacks, detached HEAD fixes, and gitignore
├── challenges/             # Complete setups and solutions for Challenges 1, 2, and 3
└── reference/              # Handy cheatsheets and time-saving shortcuts
```

---

## 🛠️ Getting Started

### Prerequisites
* Your preferred text editor (e.g., VS Code)
* Git installed on your local machine
* A GitHub account
* (Optional) GitHub Desktop installed

### Installation & Usage
```bash
# 1. Clone this course repository
git clone https://github.com

# 2. Navigate into the folder
cd git-warp-9

# 3. Explore the corresponding section folder for your current lecture
cd 02-git-fundamentals
```

---

## 📘 Detailed Syllabus Breakdown

### 🎯 Foundations & Local Setup
* **Intro & Environment:** Text editor configuration, folder structures, and GitHub Desktop integration.
* **Your First Commits:** Initializing a repo, running your first `git commit`, and mapping out the differences between Git (CLI/Local) and GitHub (Cloud).
* **Remotes & Pushing:** Linking local repos to GitHub via CLI remotes and pushing code upstream.
* **⚡ Challenge 1:** Put your foundational committing and pushing skills to the test.

### 🌿 Branching, Merging & Commits
* **Branches 101:** Isolating your feature development from the main codebase.
* **Merge vs Rebase:** In-depth breakdown of histories—understanding when to merge and when to rebase.
* **Commit Cleanup:** Strategies to reduce and tidy up unnecessary intermediate commits.
* **⚡ Challenge 2:** Branch management and local tree structuring challenge.

### 👥 Collaboration & Pull Requests
* **Remote Ecosystems:** Mastering `git clone`, `git pull`, and repository forking for open-source or team projects.
* **Pull Requests (PRs):** Creating clean PRs, reviewing code changes, and safely merging them.
* **Conflict Mastery:** Step-by-step techniques to handle and fix merge conflicts both locally and directly within GitHub PRs.
* **⚡ Challenge 3:** Complete simulation of a multi-developer workflow and conflict resolution.

### 🚀 Advanced Team Strategies & Recovery
* **Branching Strategies:** Real-world workflows (Feature Branching, Gitflow, etc.) tailored for team scale.
* **Undoing Mistakes:** Rolling back bad commits, fixing a "Detached HEAD" state safely, and using `git blame` to track down bugs.
* **Efficiency Tactics:** Utilizing `.gitignore` files effectively and implementing daily time-saving command line hacks.
