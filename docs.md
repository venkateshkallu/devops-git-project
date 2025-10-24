# DevOps Git Workflow Documentation

## 1. Repository Initialization
- Created project folder locally
- Initialized Git: `git init`
- Pushed initial commit to GitHub

## 2. Branching Strategy
- **main**: Stable production-ready branch
- **dev**: Development branch for testing features
- **feature/***: Temporary branches for specific tasks
  - Example: `feature/login-module`

## 3. Feature Development
- Created `feature/login-module` branch from `dev`
- Added `src/login.py` for login feature
- Committed changes with meaningful messages:
  - `Added login feature`
  - `Updated README in dev branch`

## 4. Pull Requests
- Merged `feature/login-module` → `dev` using GitHub PR
- Reviewed changes and merged without conflicts
- Deleted feature branch after merge

## 5. Merge to Main
- Merged `dev` → `main` after testing
- Pull request titled: `Merge development branch into main (v1.0 stable release)`

## 6. Tagging Releases
- Tagged stable release in Git:
```bash
git tag -a v1.0 -m "First stable release with login module"
git push origin v1.0
