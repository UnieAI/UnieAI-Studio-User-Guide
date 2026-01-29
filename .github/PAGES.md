# GitHub Pages Configuration

# This file is used to configure the deployment of this repository to GitHub Pages
# The build and deployment is managed by GitHub Actions from .github/workflows/deploy.yml

# Repository Settings:
# 1. Go to repository Settings > Pages
# 2. Set Source to "GitHub Actions"
# 3. The deployment will happen automatically when code is pushed to main branch

# Documentation Structure:
# - Markdown files in root directory are converted to HTML
# - Images in /images folder are copied to site
# - Navigation is configured in mkdocs.yml

# Build Process:
# 1. GitHub Action triggers on push to main branch
# 2. MkDocs Material theme builds static HTML
# 3. Deploys to https://unieai.github.io/UnieAI-Studio-User-Guide/