# gh-deployment-workflow-roadmap-sh

## Overview

This project demonstrates the basics of **Continuous Integration (CI)** and **Continuous Deployment (CD)** using **GitHub Actions**.  
The goal is to automatically deploy a simple static website to **GitHub Pages** whenever changes are made to the `index.html` file.

The website displays a basic message and is hosted directly from this repository using an automated workflow.

---

## What This Project Does

- Uses **GitHub Actions** to automate deployment
- Deploys a static website to **GitHub Pages**
- Only runs the deployment workflow when `index.html` is changed
- Updates the live website automatically on every qualifying push to the `master` branch

---

## How It Works

1. A change is pushed to the `master` branch
2. GitHub checks whether `index.html` was modified
3. If it was, the GitHub Actions workflow runs
4. The updated site is deployed to **GitHub Pages**
5. The live website reflects the latest changes

This ensures deployments only happen when relevant content changes, which is a key CI/CD concept.

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

### File Descriptions

- **index.html**  
  The static webpage content (e.g. “Hello, GitHub Actions!”)

- **README.md**  
  Documentation explaining the purpose and setup of the project

- **.github/workflows/deploy.yml**  
  GitHub Actions workflow that handles deploying the site to GitHub Pages

---

## Deployment Workflow

- Triggered on pushes to the `master` branch
- Runs **only if `index.html` is modified**
- Uses GitHub Actions to publish the site to GitHub Pages

This setup mimics a real-world deployment pipeline in a simple, beginner-friendly way.

---

## Live Website

Once deployed, the website is available at:

```

https://akshayv30.github.io/gh-deployment-workflow-roadmap-sh/

```



---

## Learning Objectives

- Understand basic CI/CD concepts
- Learn how GitHub Actions workflows work
- Automate deployment to GitHub Pages
- Practice structuring a simple DevOps-enabled repository

---

## Example Output

When deployed successfully, the website will display:

```

Hello, GitHub Actions!

```

