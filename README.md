
# Practice Git Branching

This repository is created to practice essential Git branching workflows, commands, and techniques.

## What You’ll Learn
- Creating and switching branches
- Renaming branches
- Rebasing branches onto `main`
- Handling merge conflicts
- Pushing branches to remote
- Creating and managing pull requests (PR)

## Project Structure
- **README.md** — Project overview and instructions
- **login.txt** — Sample file created in the `feature-authentication` branch

## Common Commands Used
```bash
# Initialize Git
git init

# Create and switch to a new branch
git checkout -b branch-name

# Rename a branch
git branch -m new-branch-name

# Add and commit changes
git add .
git commit -m "Commit message"

# Push a branch to remote
git push -u origin branch-name

# Rebase your branch onto main
git rebase main

# Resolve conflicts and continue rebase
git add .
git rebase --continue
```

## Bonus Tips 💡
- If you face errors like `fatal: invalid upstream 'main'`, check if you have pulled or created a `main` branch locally.
- During a rebase conflict, carefully edit the conflicted files, `git add` them, and continue rebasing.
- Always keep your branches updated with `main` before raising a pull request to avoid major conflicts.

## Conclusion
This repository is a hands-on practice space for mastering Git branching. Making mistakes is part of learning — just remember to fix them, document them, and move forward!
