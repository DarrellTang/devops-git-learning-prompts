# Step 4: Team Collaboration Practice

## What You'll Learn
Practice the complete collaborative Git workflow, integrating branching, pull requests, and team coordination.

## Instructions
Copy the prompt below and paste it into your AI chat. This provides a comprehensive collaboration exercise.

## Your Learning Prompt

```
You provide distributed practice exercises that connect Git workflows to concepts from all previous modules.
My student is a sysadmin/cloud engineer who has learned version control concepts (Module 1), repositories (Module 2), basic Git workflow (Module 3), and branching/PRs (Module 4).

IMPORTANT CONSTRAINTS:
- DO NOT mention automation scripts, Infrastructure as Code, or advanced DevOps tools
- Focus ONLY on traditional infrastructure tasks they definitely know
- Use familiar IT terminology, not development jargon
- Examples should be basic: config files, documentation, network rules, team collaboration

Your task is to create DISTRIBUTED PRACTICE exercises that connect and reinforce concepts from all previous modules.

Create a comprehensive team collaboration scenario:

**Main Scenario:** "Your IT team needs to implement new backup procedures. Multiple team members will work on different aspects: server configurations, documentation, and monitoring setup."

**Part 1: Connect to Module 1 (Version Control Value)**
- Scenario: Multiple people editing backup procedures simultaneously
- Ask: "How does this demonstrate the collaboration problems version control solves?"
- Connect back to change management and team coordination challenges

**Part 2: Connect to Module 2 (Repository Concepts)**
- Have them identify what belongs in the shared repository
- Ask: "How does a central repository solve the shared drive problems from Module 2?"
- Connect to centralized storage concepts they already know

**Part 3: Connect to Module 3 (Basic Workflow)**
- Walk through add-commit-push workflow ON A BRANCH
- Ask: "How is staging and committing the same whether you're on main or a feature branch?"
- Reinforce that fundamental workflow doesn't change

**Part 4: Connect to Module 4 (Branching & PRs)**
- Show complete branch creation → PR → review → merge workflow
- Ask: "How does this formalize your existing change approval process?"
- Connect to change control boards and review processes

**Integration Questions:**
1. "Trace the complete path from your local edit to merged changes in main branch"
2. "How does this workflow improve on your previous team collaboration methods?"
3. "Which parts of this process mirror change management you already do?"

Throughout the exercise:
- Reference version control benefits from Module 1
- Use repository concepts from Module 2
- Apply staging and commit practices from Module 3
- Integrate branching and PR concepts from Module 4

End with: "You now understand the complete collaborative Git workflow for infrastructure teams. This foundation prepares you for real-world team collaboration and integration with existing infrastructure tools."

Keep it practical and connected to their infrastructure background.
```

## What to Expect
You'll complete a comprehensive team collaboration exercise that connects concepts from all previous modules through a realistic backup procedures scenario involving multiple team members.

## Complete Workflow Review
Now you should understand the full process:

1. **Create branch** for your feature/fix
2. **Switch to branch** to work in isolation
3. **Make changes** to files
4. **Add and commit** changes (same as Module 3)
5. **Push branch** to GitHub
6. **Create pull request** for review
7. **Address feedback** if needed
8. **Merge** when approved

## Team Collaboration Best Practices
- **Always create branches** for changes
- **Write clear PR descriptions** explaining your changes
- **Test thoroughly** before creating PR
- **Review others' PRs** promptly and constructively
- **Keep branches focused** on single features/fixes

## Self-Assessment Questions
After completing this module, you should be able to:
- Explain when and why to create a branch
- Navigate between branches safely
- Create professional pull requests
- Understand the review and merge process

## What's Next
You now have the core Git skills used in 80-90% of DevOps work:
- Version control concepts
- Repository management
- Basic Git workflow (add, commit, push)
- Branching and pull requests

Module 5 will help you integrate these skills and assess your readiness for real-world application.

---
[← Previous: Step 3](./step-3-pull-request-workflow.md) | [Next: Module 5 - Assessment and Integration →](../module-5-assessment/README.md)
