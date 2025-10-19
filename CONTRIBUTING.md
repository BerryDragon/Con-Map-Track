# Contributing Guidelines

This file explains how I'm managing branches and pull requests for the Convention Map Tracker project. 
My goal is to keep everything organized and make sure the main branch always has working code, I guess we can call them versions or beta versions.

## Branch Policy

I'm using a simple branching structure:

- **main** - Stable, production ready code only. Nothing gets merged here unless it's tested and working. I will test and run the code as the admin.
- **dev** - The main working branch where most development happens.
- **feature** - Used for building new features.
- **fix** - Used for fixing bugs.

**Rules:**
- Always branch off `dev`, not `main` until request is pulled by admin. 
- Use short branch names
- Make small, focused commits instead of huge changes all at once
- Before merging to `main`, make sure the sprint's user stories are complete, ask the admin to pulll

## Pull Request

Every pull request should:
- Be made from a feature branch into `dev` (and later `dev` into `main` when 100% ready)
- Have a clear title that explains what changed
- Include a short description of what was done (example: "Added hotel cost estimation to detail panel") as well as adding comment to code
- Reference the user story ID when possible (like "Implements CMT-6")

**Before submitting a PR:**
1. Test the feature to make sure it works as you wanted
2. Make sure no sensitive files (like `.env`) are being committed
3. Confirm the README is still accurate and make sure a baby could figure it out.

Once merged into `dev`, delete the old branch to keep things clean.

## Commit Message Style

I'm trying to follow this format:
```
[type]: short description

Examples:
feat: add travel cost calculator to run on this button click
fix: correct distance calculation bug for gas milage
docs: update sprint plan in README
```

**Types:**
- `feat` = new feature
- `fix` = bug fix
- `docs` = documentation update
- `refactor` = code cleanup

## General Guidelines

- Use clear variable names
- Keep functions focused on one task
- Comment anything that's not obvious
- Test locally before pushing to GitHub and ask for review

PS: I say that putting ** and ``` and ## Helps with visualizations in readme files
