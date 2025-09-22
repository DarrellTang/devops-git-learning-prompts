# Step 3: Pull Request Workflow

## What You'll Learn
Master the pull request process for collaborative infrastructure changes and code review.

## Instructions
Copy the prompt below and paste it into your AI chat. This teaches the complete pull request workflow.

## Your Learning Prompt

```
You provide practical examples of the pull request workflow for infrastructure professionals.
My student is a sysadmin/cloud engineer who understands traditional infrastructure but is completely new to development tools and version control.

IMPORTANT CONSTRAINTS:
- DO NOT mention automation scripts, Infrastructure as Code, or advanced DevOps tools
- Focus ONLY on traditional infrastructure concepts they definitely know
- Use familiar IT terminology, not development jargon
- Examples should be basic: config files, documentation, network rules, change control processes

Your task is to provide MULTIPLE EXAMPLES of the complete pull request workflow for different infrastructure scenarios.

Provide 3 detailed examples with step-by-step GitHub interface instructions:

**Example 1: Server Configuration Change Request**
- Scenario: Requesting approval for SSL certificate update in web server config
- Branch: "ssl-cert-renewal"
- Show: Creating PR, writing description, requesting reviewers
- Connect to: Change control board approval process they know

**Example 2: Network Security Policy Review**
- Scenario: Proposing new firewall rules for application deployment
- Branch: "firewall-rules-app-deployment"
- Show: PR description with justification, review comments, addressing feedback
- Connect to: Security change approval process they know

**Example 3: Documentation Update Review**
- Scenario: Adding new incident response procedures to team documentation
- Branch: "incident-response-procedures"
- Show: Collaborative review, suggestions, final approval and merge
- Connect to: Document review and publication process they know

For each example:
- Show exact GitHub interface steps for creating PR
- Explain PR description template for infrastructure changes
- Show review process with comments and approvals
- Connect to change management processes they already use
- Include merge process and branch cleanup

Throughout examples:
- Compare PR to change request tickets
- Compare reviewers to change approval board
- Compare merge to change implementation
- Explain why this is better than email-based reviews

End with: "Pull requests formalize the change review process you already know, but with complete change tracking and collaboration tools."

Keep it simple and relatable to their current daily work.
```

## What to Expect
You'll see 3 detailed examples of the pull request workflow for infrastructure scenarios - server configs, security policies, and documentation. Each connects to change management processes you already know.

## Pull Request = Change Request
The pull request process mirrors formal change management:
1. **Submit change request** (create PR)
2. **Provide documentation** (PR description)
3. **Peer review** (code review)
4. **Approval process** (PR approval)
5. **Implementation** (merge)
6. **Documentation** (merge commit)

## What to Include in PR Description
- **What changed:** Brief summary of modifications
- **Why changed:** Reason for the change
- **Testing done:** How you verified it works
- **Impact:** What systems/processes are affected

## Example PR Description
```
## Summary
Update firewall rules to allow new monitoring service

## Changes
- Added port 9090 for Prometheus metrics
- Updated security group sg-12345

## Testing
- Verified connectivity from monitoring server
- Confirmed no impact on existing services

## Impact
- Enables new monitoring capabilities
- No downtime required
```

## Practice Exercise
1. Create a branch with a simple change
2. Push the branch to GitHub
3. Create a pull request through GitHub interface
4. Write a professional description
5. Review your own PR to see how it looks

---
[← Previous: Step 2](./step-2-creating-branches.md) | [Next: Step 4 - Team Collaboration →](./step-4-team-collaboration.md)
