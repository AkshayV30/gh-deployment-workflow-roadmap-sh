# GitHub Actions Deployment Workflow

This repository is a solution for the roadmap.sh project:

🔗 https://roadmap.sh/projects/github-actions-deployment-workflow

---

## Overview

The purpose of this project is to understand and implement **Continuous Integration (CI)** and **Continuous Deployment (CD)** using **GitHub Actions**.

A simple static website is automatically deployed to **GitHub Pages** whenever changes are made to the `index.html` file. The deployment workflow only runs when relevant changes are detected.

---

## Project Requirements

- Create a GitHub repository for the project
- Add a simple `index.html` file
- Configure GitHub Pages for the repository
- Create a GitHub Actions workflow to deploy the site
- Ensure the workflow runs **only when `index.html` changes**
- Deploy the site automatically on pushes to the `master` branch

---

## How the Workflow Works

1. A commit is pushed to the `master` branch
2. GitHub Actions checks whether `index.html` was modified
3. If the condition is met, the deployment workflow runs
4. The static site is deployed to GitHub Pages
5. The updated website becomes publicly accessible

This workflow demonstrates conditional deployment, a core CI/CD concept.

---

## Repository Structure

```

.
├── index.html
├── README.md
└── .github
└── workflows
└── deploy.yml

```

---

## Files Explanation

- **index.html**  
  Contains the static content of the website

- **README.md**  
  Documentation describing the project and implementation

- **.github/workflows/deploy.yml**  
  GitHub Actions workflow that handles automated deployment

---

## Deployment Conditions

- Trigger: Push to the `master` branch
- Condition: `index.html` must be modified
- Deployment Target: GitHub Pages

---

## Live Deployment

The deployed website is available at:

```
https://akshayv30.github.io/gh-deployment-workflow-roadmap-sh/

```

---

## Expected Output

When the workflow runs successfully, the website displays:

```

Hello, GitHub Actions!

```

---

## Learning Outcomes

By completing this project, you will:

- Understand how CI/CD works in practice
- Learn how to write GitHub Actions workflows
- Deploy a static website using GitHub Pages
- Implement conditional workflow execution
```

