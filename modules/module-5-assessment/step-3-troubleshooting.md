# Step 3: Common Issues and Troubleshooting

## What You'll Learn
Handle typical Git problems that infrastructure teams encounter and know how to get help when needed.

## Instructions
Copy the prompt below and paste it into your AI chat. This covers troubleshooting scenarios.

## Your Learning Prompt

```
You provide troubleshooting assessments for infrastructure professionals learning to resolve common Git issues.
My student is a sysadmin/cloud engineer who has mastered basic Git workflows but needs to understand how to handle common problems.

IMPORTANT CONSTRAINTS:
- DO NOT mention Infrastructure as Code, Terraform, or advanced DevOps tools
- Focus ONLY on traditional infrastructure scenarios they definitely know
- Use familiar IT terminology, not development jargon
- Examples should be basic: config files, documentation, network settings, team collaboration

Your task is to create LOW-STAKES troubleshooting scenarios that test their problem-solving abilities.

Create 5 troubleshooting scenarios with diagnostic questions:

**Scenario 1: Configuration File Merge Conflict**
- Situation: "Two team members edited firewall-rules.txt simultaneously. Git shows conflict markers when merging."
- Present symptoms and ask: "What caused this issue and how would you resolve it?"
- Provide multiple choice options with realistic wrong answers
- Connect to concurrent editing problems they've experienced

**Scenario 2: Accidentally Committed Sensitive Information**
- Situation: "You committed server passwords in a config file and pushed to GitHub."
- Present symptoms and ask: "What are your options to handle this security issue?"
- Include options about repository history and security considerations
- Connect to data security practices they already know

**Scenario 3: Push Rejected - Not Fast-Forward**
- Situation: "Your git push fails with 'rejected - non-fast-forward' error."
- Present symptoms and ask: "What does this error mean and how do you fix it?"
- Include options about remote changes and synchronization
- Connect to concurrent access issues they understand

**Scenario 4: Missing Work After Branch Switch**
- Situation: "You switched branches and your uncommitted config changes disappeared."
- Present symptoms and ask: "Where did your changes go and how can you recover them?"
- Include options about working directory vs staging vs commits
- Connect to file save/backup concepts they know

**Scenario 5: GitHub Authentication Failed**
- Situation: "Git push fails with authentication errors despite correct username/password."
- Present symptoms and ask: "What authentication issues could cause this?"
- Include options about tokens, SSH keys, and corporate firewalls
- Connect to network authentication issues they've troubleshot

For each scenario:
- Present ONE scenario at a time
- Wait for their diagnosis and solution choice
- Provide immediate feedback with correct answer and explanation
- Connect the Git issue to familiar infrastructure troubleshooting concepts
- Include prevention tips

IMPORTANT: Vary the correct answer positions across scenarios.

After all scenarios, provide troubleshooting readiness assessment:
- If 5/5 or 4/5: "Excellent troubleshooting skills! You can handle common Git issues independently."
- If 3/5: "Good foundation. Review the areas you missed for complete troubleshooting confidence."
- If 2/5 or below: "Focus on understanding Git's working directory, staging, and repository concepts before troubleshooting."

Keep it practical and connected to their infrastructure troubleshooting experience.
```

## What to Expect
You'll work through 5 troubleshooting scenarios testing your ability to diagnose and resolve common Git issues infrastructure teams encounter. Each scenario provides immediate feedback and connects to familiar troubleshooting concepts.

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