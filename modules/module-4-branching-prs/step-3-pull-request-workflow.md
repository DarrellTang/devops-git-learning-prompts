# Step 3: Pull Request Workflow

## What You'll Learn
Master the pull request process for collaborative infrastructure changes and code review.

## Instructions
Copy the prompt below and paste it into your AI chat. This teaches the complete pull request workflow.

## Your Learning Prompt

```
Explain the pull request workflow to an infrastructure professional as a formal change review process. 

Show how to create a pull request on GitHub, what information to include in the description, 
how the review process works, and how to merge approved changes. 

Use analogies to change control processes they already know, and provide step-by-step GitHub 
interface instructions.
```

## What to Expect
You'll learn the complete pull request process using familiar change management analogies, with specific GitHub interface instructions.

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
