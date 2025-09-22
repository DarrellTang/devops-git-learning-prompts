# Step 3: Writing Good Commit Messages

## What You'll Learn
Learn to write clear, professional commit messages that help your team understand infrastructure changes.

## Instructions
Copy the prompt below and paste it into your AI chat. This teaches commit message best practices for infrastructure work.

## Your Learning Prompt

```
Teach an infrastructure professional how to write effective Git commit messages for 
infrastructure work. 

Show examples of good vs bad commit messages for scenarios like: updating server configurations, 
modifying firewall rules, changing automation scripts, and updating documentation. 

Explain why clear commit messages matter for infrastructure teams and provide a simple template 
they can follow.
```

## What to Expect
You'll learn the difference between helpful and unhelpful commit messages, with examples specific to infrastructure work. You'll get a simple template to follow.

## Why Commit Messages Matter
Good commit messages help you and your team:
- Understand what changed and why
- Debug issues faster
- Review changes more effectively
- Track infrastructure evolution over time

## Common Infrastructure Examples

**Bad:**
- "fix"
- "update config"
- "changes"

**Good:**
- "Fix SSH timeout in web server config"
- "Update firewall rules to allow new monitoring port 9090"
- "Add error handling to backup script for disk space check"

## Simple Template to Follow
```
Action: Brief description

Optional: More details if needed
```

Examples:
- "Add: New backup retention policy for database servers"
- "Fix: Memory leak in log rotation script"
- "Update: SSL certificate paths in nginx config"

## Practice Exercise
Think about your last infrastructure change and write a commit message for it using the template. Consider:
- What action did you take?
- What specific component did you change?
- Why was the change needed?

---
[← Previous: Step 2](./step-2-add-commit-push.md) | [Next: Step 4 - Hands-On Practice →](./step-4-hands-on-practice.md)
