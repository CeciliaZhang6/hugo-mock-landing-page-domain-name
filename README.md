# 🚀 Hugo Mock Landing Page (with Auto-Deployment)
This repository contains an automated deployment pipeline for a Hugo static website using GitHub Actions and GitHub Pages.
(CIS 3500 Spring 2025 HW2)

## Live Website Link
https://CeciliaZhang6.github.io/hugo-mock-landing-page-autodeployed/

## How Deployment Works
This repository is set up with GitHub Actions to automate the deployment of the Hugo website whenever changes are pushed to the main branch.

## Workflow Process
1. Trigger: The workflow is triggered on every push to the main branch.
2. Checkout Repository: GitHub Actions fetches the latest code from the repository.
3. Setup Hugo Environment: It installs Hugo and fetches any required themes.
4. Build the Site: The workflow compiles the website into static HTML.
5. Deploy to GitHub Pages: The generated files are published to the gh-pages branch.

## GitHub Actions Workflow
The workflow is defined in .github/workflows/gh-pages-deployment.yaml

## How to Modify & Deploy Updates
1. Make Edits
   Example: Modify any content in the content/ directory or adjust config.toml.

2. Push Changes

This will automatically trigger GitHub Actions to rebuild and deploy your site.


