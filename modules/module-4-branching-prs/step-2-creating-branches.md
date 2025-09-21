# Step 2: Creating and Using Branches

## What You'll Learn
Learn the Git commands for creating, switching between, and managing branches in your infrastructure projects.

## Instructions
Copy the prompt below and paste it into your AI chat. This provides hands-on branch management commands.

## Your Learning Prompt

```
Generate 4 scenarios showing the complete branch-modify-commit-push workflow: (1) testing a new monitoring configuration, (2) updating security policies, (3) trying a new automation approach, (4) documenting a new procedure. For each scenario, show every Git command from branch creation through pushing the branch, explaining why each step matters for infrastructure teams.
```

## What to Expect
You'll see complete workflows for different infrastructure scenarios, with all the Git commands you need to create and work with branches.

## Essential Branch Commands
- `git branch` - List all branches
- `git branch feature-name` - Create new branch
- `git checkout feature-name` - Switch to branch
- `git checkout -b feature-name` - Create and switch in one command
- `git push origin feature-name` - Push branch to GitHub

## Branch Naming Conventions
For infrastructure work, use descriptive names:
- `update-firewall-rules`
- `add-monitoring-config`
- `fix-backup-script`
- `document-deployment-process`

## Practice Exercise
1. Create a branch for adding a simple config file
2. Switch to that branch
3. Add/modify a file
4. Commit your changes
5. Push the branch to GitHub
6. Check GitHub to see your new branch

## Common Questions
- "What happens to my changes when I switch branches?" - Uncommitted changes may conflict
- "Can I switch back to main?" - Yes, use `git checkout main`
- "How do I see which branch I'm on?" - `git branch` shows current branch with *

---
[← Previous: Step 1](./step-1-understanding-branching.md) | [Next: Step 3 - Pull Request Workflow →](./step-3-pull-request-workflow.md)
