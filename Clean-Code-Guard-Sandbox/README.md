# Git & GitHub Automation Sandbox: Clean Code Guard

A demonstration project showcasing advanced Git workflows, client-side hook automation, continuous integration (CI) matrices, and enterprise-grade branch protection safety gates.

## ⚙️ Automated Architecture

### 1. Client-Side: Pre-Commit Hook
This repository features a local automated hook workflow. If a developer attempts to commit code that contains structural syntax errors or hardcoded credentials, the terminal execution halts instantly, preventing broken snapshots from entering the local history log.

### 2. Cloud-Side: GitHub Actions Validation
Every incoming Pull Request targeting the `main` branch triggers an isolated cloud runner. This runner executes a testing matrix validating the codebase stability across multiple environmental runtimes simultaneously.

### 3. Repository Governance: Branch Protections
The `main` branch is locked down to simulate an enterprise trunk-based development strategy:
* Direct pushes are explicitly forbidden.
* Changes require a formalized Pull Request.
* Merging is structurally blocked by GitHub unless the remote validation workflows pass completely green.

## ⚡ How to Run and Verify the Pipeline

To test your automation engine end-to-end, follow this real-world feature branch workflow to trigger the cloud validation matrices.

### Isolate the Project via Sparse-Checkout
To pull this specific tool out of your repository workspace without cluttering your system with your complete monorepo setup, open your terminal and run:

```bash
# Initialize an empty local directory
mkdir secure_git && cd secure_git
git init

# Link your multi-project workspace as the remote engine
git remote add origin https://github.com/sergio-a-juarez-1/Git

# Enable sparse-checkout and pull the target server directory
git sparse-checkout set Clean-Code-Guard-Sandbox .github
git pull origin main
```

### 1. Execute the Local Development Lifecycle
Open your terminal, shift out of your primary trunk, generate a dummy file execution path, and push the tracking changes up to your repository:

```bash
# A. Switch to a brand-new, isolated feature development branch
git checkout -b feature-test-pipeline

# B. Create a dummy Python script to give the lint engine code to analyze
echo 'print("Testing our automated guard rails!")' > test.py

# C. Stage, snapshot, and push your new feature tracking branch to GitHub
git add .
git commit -m "feat: introduce sandbox pipeline testing file"
git push origin feature-test-pipeline
```

---

### 2. View the Automation Live on GitHub

Once your feature branch changes hit GitHub, complete these validation steps to see the continuous integration (CI) architecture engage:

* **Open the Pull Request:** Navigate to your repository page in your web browser.

