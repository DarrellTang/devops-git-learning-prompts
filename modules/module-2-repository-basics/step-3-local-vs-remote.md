# Step 3: Local vs Remote Repositories

## What You'll Learn
Understand the critical relationship between repositories on your computer (local) and repositories on GitHub (remote).

## Instructions
Copy the prompt below and paste it into your AI chat. This explains how local and remote repositories work together.

## Your Learning Prompt

```
You generate diagnostic assessments for infrastructure professionals learning about local vs remote repositories.
My student is a sysadmin/cloud engineer who understands traditional infrastructure but is completely new to development tools and version control.

IMPORTANT CONSTRAINTS:
- DO NOT mention Terraform, Infrastructure as Code, automation scripts, or any DevOps tools
- Focus ONLY on traditional infrastructure concepts they definitely know
- Use familiar IT terminology, not development jargon
- Examples should be basic: local files vs shared drives, file synchronization, backups

Create a diagnostic quiz with 4 multiple-choice questions testing whether they understand the critical relationship between local Git repositories and GitHub repositories.

Focus on scenarios like:
- When changes exist only locally vs. on GitHub
- What happens when you create a repository in each location
- How the two repositories stay synchronized
- Common misconceptions from direct server file editing

For each question:
- Present a realistic infrastructure scenario (editing config files, updating documentation, etc.)
- Include plausible wrong answers based on common misconceptions from people used to:
  * Direct file editing on servers
  * Automatic cloud sync services like Dropbox
  * Shared network drives
- Make the correct answer clearly show the separate nature of local vs remote

IMPORTANT: Present ONE question at a time, wait for their answer, then move to the next question.

After each question:
- Provide brief feedback (correct/incorrect and why)
- Connect their answer to file sync concepts they already know

IMPORTANT: Vary the correct answer position - don't put all correct answers in the same position (A, B, C, or D).

Keep track of their score as you go. After all 4 questions, provide their final score and feedback.

PROVIDE GUIDANCE BASED ON SCORE:
- If 4/4 or 3/4: "Excellent! You understand the local/remote distinction. You're ready for Step 4."
- If 2/4: "Good foundation, but review the synchronization concepts. Remember: local and remote start as separate copies."
- If 1/4 or 0/4: "This is a critical concept. Review how local files and shared drives work separately until you sync them."

Keep it simple and relatable to their current daily work.
```

## What to Expect
You'll take a 4-question quiz testing your understanding of the critical local vs remote repository relationship. The AI will provide immediate feedback after each question and guidance based on your overall performance.

---
[← Previous: Step 2](./step-2-creating-github-repository.md) | [Next: Step 4 - Environment Setup →](./step-4-environment-setup.md)
