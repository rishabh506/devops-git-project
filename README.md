# DevOps Git Project

A version-controlled DevOps project demonstrating Git best practices:
branching strategy, pull requests, tagging, and documentation.

## Branching Strategy
- `main` — production-ready code
- `dev` — integration branch for features
- `feature/*` — individual feature branches

## Workflow
1. Create a feature branch off `dev`
2. Commit changes with clear messages
3. Open a PR into `dev`
4. After review, merge `dev` into `main` for releases
5. Tag releases on `main`

## Setup
```bash
git clone <your-repo-url>
cd devops-git-project