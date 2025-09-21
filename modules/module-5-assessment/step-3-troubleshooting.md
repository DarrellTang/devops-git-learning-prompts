# Step 3: Common Issues and Troubleshooting

## What You'll Learn
Handle typical Git problems that infrastructure teams encounter and know how to get help when needed.

## Instructions
Copy the prompt below and paste it into your AI chat. This covers troubleshooting scenarios.

## Your Learning Prompt

```
Create troubleshooting guidance for common Git issues infrastructure professionals encounter: (1) merge conflicts in configuration files, (2) accidentally committing sensitive information, (3) push rejected errors, (4) lost work after switching branches, (5) authentication problems with GitHub. For each issue, provide the symptoms, cause, and step-by-step resolution, using infrastructure analogies where helpful.
```

## What to Expect
You'll get practical troubleshooting guidance for the most common issues, with clear steps to resolve each problem.

## Essential Troubleshooting Commands
- `git status` - Check current state
- `git log --oneline` - See recent commits
- `git branch -a` - See all branches
- `git remote -v` - Check GitHub connection
- `git diff` - See what changed

## When to Ask for Help
- **Before force-pushing** (`git push --force`) - Very dangerous
- **Before deleting branches** with uncommitted work
- **When dealing with merge conflicts** in critical files
- **Authentication issues** that persist after basic troubleshooting

## Prevention Strategies
- Commit work frequently
- Use descriptive branch names
- Check `git status` before switching branches
- Test in branches before merging
- Keep sensitive data in separate files (not in Git)

## Getting Help
- Use your AI assistant for specific error messages
- GitHub documentation for interface issues
- Team members who are Git-experienced
- Online Git tutorials for complex scenarios

## Recovery Mindset
Remember: Git is designed for safety
- Most "lost" work can be recovered
- Commits are nearly impossible to truly lose
- When in doubt, ask for help before taking drastic action

---
[← Previous: Step 2](./step-2-infrastructure-integration.md) | [Next: Step 4 - Next Steps →](./step-4-next-steps.md)