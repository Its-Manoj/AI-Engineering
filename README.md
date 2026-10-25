=============================================================================================
|                             "# AI-Engineering-Practice"                                   |
=============================================================================================


# Contributing

This repository is managed as an open-source project. To ensure a smooth development workflow for
all contributors, please follow the guidelines below.

## 1. Create Your Own Branch

Before making any changes, create a new branch based on `main`. This keeps your work isolated and
prevents accidental conflicts with other contributors' changes.

**Naming Convention:**
Use descriptive names for your branches, such as:
- `feature/add-new-plugin`
- `fix/button-alignment-issue`
- `docs/update-installation-guide`

**Command:**
```bash
git checkout -b <branch-name>
```

## 2. Sync with `main` Before Pushing

To avoid merge conflicts when you're ready to share your changes, always update your local branch
with the latest changes from `main`. This ensures you're working with the most recent version of
the codebase.

**Commands:**
```bash
git checkout main
git pull origin main
git checkout <your-branch-name>
```

## 3. Commit and Push Your Changes

Once you've completed your work, commit your changes to your feature branch. Write clear and
concise commit messages that explain what you changed and why.

**Commands:**
```bash
git add .
git commit -m "<descriptive-commit-message>"
git push origin <your-branch-name>
```

## 4. Create a Pull Request (PR)

After pushing your branch, create a Pull Request targeting the `main` branch. Your PR should
include:
- A clear title describing the changes
- A detailed description of what was implemented
- Any relevant context, screenshots, or test results
- A checklist of completed tasks (if applicable)

## 5. Wait for Review and Approval

After submitting your PR, it will be reviewed by project maintainers. Be prepared to:
- Address any feedback or requested changes
- Provide additional information or clarification
- Make necessary updates to your branch

Your changes will only be merged into `main` after receiving approval.

## Summary

**Your Workflow:**
```
main → Your Feature Branch → Code & Test → Push → Pull Request → Review & Merge
```

**Important Reminders:**
- Direct pushes to the `main` branch are not allowed
- Contributors without write access should fork the repository and submit a PR
- Keep your changes focused, tested, and clearly documented

Thank you for contributing to the project!
