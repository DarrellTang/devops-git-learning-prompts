# Step 3: Writing Good Commit Messages

## What You'll Learn
Learn to write clear, professional commit messages that help your team understand infrastructure changes.

## Instructions
Copy the prompt below and paste it into your AI chat. This teaches commit message best practices for infrastructure work.

## Your Learning Prompt

```
You teach infrastructure professionals how to write effective Git commit messages for infrastructure work.
My student is a sysadmin/cloud engineer who understands traditional infrastructure but is completely new to development tools and version control.

IMPORTANT CONSTRAINTS:
- DO NOT mention automation scripts, Infrastructure as Code, or advanced DevOps tools
- Focus ONLY on traditional infrastructure tasks they definitely know
- Use familiar IT terminology, not development jargon
- Examples should be basic: config files, documentation, network rules, server settings

Your task is to provide MULTIPLE EXAMPLES of good vs bad commit messages for different infrastructure scenarios.

Provide 5 scenario comparisons showing bad vs good commit messages:

**Scenario 1: Server Configuration Changes**
- Bad example: "update config"
- Good example: "Fix SSH timeout in web server config to prevent connection drops"
- Explain why the good version is better

**Scenario 2: Network Configuration Changes**
- Bad example: "firewall stuff"
- Good example: "Add firewall rule to allow monitoring port 9090 for new tool"
- Explain why specificity matters

**Scenario 3: Documentation Updates**
- Bad example: "docs"
- Good example: "Update troubleshooting guide with disk space check procedure"
- Explain why context is important

**Scenario 4: System Monitoring Changes**
- Bad example: "fix script"
- Good example: "Fix log rotation script to handle empty log directories"
- Explain why the problem/solution is clear

**Scenario 5: Security Updates**
- Bad example: "security update"
- Good example: "Update SSL certificate paths in nginx after renewal"
- Explain why specific actions help team understanding

After the examples, provide a simple template:
```
[Action]: [What you changed] [Why/Context if needed]

Examples:
- Fix: SSH timeout in web server config
- Add: Monitoring check for disk space alerts
- Update: Network firewall rules for new application
```

End with: "Good commit messages are like good documentation - they help your future self and teammates understand infrastructure changes."

Keep it simple and relatable to their current daily work.
```

## What to Expect
You'll see 5 scenarios comparing bad vs good commit messages for infrastructure work, plus learn a simple template to write clear, professional commit messages that help your team understand changes.

---
[← Previous: Step 2](./step-2-add-commit-push.md) | [Next: Step 4 - Hands-On Practice →](./step-4-hands-on-practice.md)
