# Git Workflow Rules

## Branch Strategy
- **main**: Production-ready code only. No direct commits allowed.
- **develop**: Integration branch for features.
- **feature/***: Create a new branch for every task/fix.

## Development Process
1. Create a feature branch from `main` or `develop`.
2. Commit changes with clear messages.
3. Push the branch to GitHub.
4. Create a Pull Request (PR) to `main`.
5. Wait for user review/approval before merging.

## Recovery
- If a mistake occurs, revert the PR or checkout a previous stable branch.
