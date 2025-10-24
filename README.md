# DevOps Git Project
## Documentation Updated: Added workflow explanation

## Project Overview
This project demonstrates a version-controlled DevOps workflow using Git and GitHub.  
It includes branching, pull requests, tagging, and proper documentation.

---

## Branching Strategy
- **main**: Production-ready stable branch  
- **dev**: Development branch for integrating features  
- **feature/***: Feature branches for specific functionality (e.g., `feature/login-module`)

---

## Features Implemented
- Login module (`src/login.py`)  
- Project setup (`src/app.py`)  
- Proper `.gitignore` and project structure  
- Documentation in Markdown

---

## Git Workflow Summary
1. Initialize Git repository locally and push to GitHub  
2. Create `main`, `dev`, and `feature` branches  
3. Develop features in feature branches  
4. Merge feature → dev using Pull Requests  
5. Merge dev → main after testing using Pull Requests  
6. Tag stable releases (e.g., `v1.0`)  

---

## Getting Started
```bash
# Clone the repository
git clone https://github.com/venkateshkallu/devops-git-project.git

# Switch to dev branch
git checkout dev
