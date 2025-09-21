# Step 2: Add, Commit, Push Workflow

## What You'll Learn
Master the core Git workflow that you'll use daily: add changes to staging, commit them to your local repository, then push to GitHub.

## Instructions
Copy the prompt below and paste it into your AI chat. This shows the complete workflow with practical examples.

## Your Learning Prompt

```
Generate 4 different scenarios showing the complete add-commit-push workflow: (1) a cloud engineer updating Terraform files, (2) a sysadmin modifying configuration files, (3) a network engineer updating firewall rules, (4) a systems engineer adding documentation. For each scenario, show the exact Git commands, explain what each command does, and why this workflow is better than their current file management approach.
```

## What to Expect
You'll see four realistic infrastructure scenarios with the exact Git commands for each step. Pay attention to how the workflow stays the same regardless of what type of files you're working with.

## The Three-Step Workflow
Every change you make follows this pattern:

1. **Add** (`git add`) - Stage your changes for commit
2. **Commit** (`git commit`) - Save changes to your local repository
3. **Push** (`git push`) - Send changes to GitHub

## Key Commands You'll Learn
- `git add filename` - Stage a specific file
- `git add .` - Stage all modified files
- `git commit -m "message"` - Commit with a message
- `git push` - Send to GitHub
- `git status` - Check current state

## Why This Workflow Matters
Each step serves a purpose:
- **Add** lets you review what you're about to commit
- **Commit** creates a save point with a description
- **Push** shares your work and backs it up

## Practice Exercise
After learning the commands, try this on your test repository:
1. Edit the README file
2. Add it to staging
3. Commit with a message
4. Push to GitHub
5. Check GitHub to confirm the change appeared

---
[← Previous: Step 1](./step-1-understanding-staging.md) | [Next: Step 3 - Commit Messages →](./step-3-commit-messages.md)
