# Step 2: Creating and Using Branches

## What You'll Learn
Learn the Git commands for creating, switching between, and managing branches in your infrastructure projects.

## Instructions
Copy the prompt below and paste it into your AI chat. This provides hands-on branch management commands.

## Your Learning Prompt

```
You provide practical examples of Git branching workflows for infrastructure professionals.
My student is a sysadmin/cloud engineer who understands traditional infrastructure but is completely new to development tools and version control.

IMPORTANT CONSTRAINTS:
- DO NOT mention automation scripts, Infrastructure as Code, or advanced DevOps tools
- Focus ONLY on traditional infrastructure tasks they definitely know
- Use familiar IT terminology, not development jargon
- Examples should be basic: config files, documentation, network rules, monitoring setup

Your task is to provide MULTIPLE EXAMPLES of the complete branch-modify-commit-push workflow for different infrastructure scenarios.

Provide 4 detailed examples with exact Git commands:

**Example 1: Testing Server Configuration Changes**
- Scenario: Testing new Apache SSL configuration without affecting production
- Branch name: "ssl-config-update"
- Files: httpd.conf, ssl.conf
- Show complete workflow: create branch, edit files, commit, push branch

**Example 2: Network Security Policy Updates**
- Scenario: Updating firewall rules for new application requirements
- Branch name: "firewall-update-app"
- Files: firewall-rules.txt, security-policy.md
- Show complete workflow with multiple commits on the branch

**Example 3: Documentation Improvements**
- Scenario: Adding new troubleshooting procedures and runbooks
- Branch name: "update-troubleshooting-docs"
- Files: troubleshooting.md, server-maintenance.md
- Show how to work on documentation safely in isolation

**Example 4: Monitoring Configuration Testing**
- Scenario: Testing new monitoring thresholds and alert configurations
- Branch name: "monitoring-threshold-updates"
- Files: monitoring.conf, alert-rules.txt
- Show testing changes before merging to production

For each example:
- Show exact git commands: checkout -b, add, commit, push
- Explain why working on a branch is safer than direct changes
- Include git status checks to show branch state
- Connect to test environment concepts they already know

End with: "Each branch acts like a separate test environment for your changes. This isolation prevents breaking the main configuration while you experiment."

Keep it simple and relatable to their current daily work.
```

## What to Expect
You'll see 4 detailed examples showing complete branching workflows for different infrastructure scenarios - SSL configs, firewall rules, documentation, and monitoring. Each includes exact Git commands.

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
