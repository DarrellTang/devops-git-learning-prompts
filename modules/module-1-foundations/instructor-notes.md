# Instructor Notes: Module 1

**This directory contains instructor documentation. Learners should focus on the step-by-step files.**

## Pedagogical Framework

### Module 1 Teaching Strategies

| Step | Strategy Used | Purpose | Duration |
|------|---------------|---------|----------|
| Step 1 | Multiple Explanations + Student Assessment | Foundation concepts via analogies + Socratic dialogue | 20 min |
| Step 2 | Multiple Explanations + Student Assessment | Critical distinction clarification + interactive reflection | 15 min |
| Step 3 | Multiple Examples + Student Assessment | Concrete applications + use case identification | 25 min |
| Step 4 | Low-Stakes Testing + Student Assessment | Sequential quiz + personalized guidance | 15 min |

**Note:** All steps now combine multiple strategies through interactive AI-facilitated dialogue rather than passive content consumption.

## Learning Objectives
- Understand version control fundamentals using infrastructure analogies
- Distinguish clearly between Git (tool) and GitHub (service)
- Recognize infrastructure applications for version control
- Demonstrate readiness for hands-on practice

## Common Issues and Solutions

### Issue: "This is just backup with extra steps"
**Solution:** Emphasize collaboration and change tracking vs. point-in-time copies

### Issue: "Our config management tool already does this"
**Solution:** Show complementary relationship, not replacement

### Issue: Confusion between Git and GitHub
**Solution:** Reinforce local tool vs. cloud service analogy repeatedly

## Assessment Criteria
Students should achieve 80% on Step 4 assessment before proceeding to Module 2.

## Quality Review Notes
- All prompts should generate infrastructure-focused content
- Avoid development jargon and examples
- Connect to existing change management processes
- Provide multiple analogies for different learning styles

## Implementation Notes
- Learners copy prompts into any AI chat interface
- No specific AI tool required
- Self-paced progression through steps
- Can repeat steps if concepts unclear

## Prompt Engineering Design Decisions

### Cross-LLM Consistency
- All prompts include explicit constraints to prevent mention of advanced DevOps tools
- Structured conversation flows with defined endpoints prevent infinite questioning loops
- Brief response requirements (1-3 sentences) work consistently across Claude, ChatGPT, etc.
- Sequential questioning prevents overwhelming learners with multiple questions at once

### Interactive Learning Design
- **Socratic Dialogue Pattern**: AI asks questions, provides insights, guides reflection
- **Structured Conversations**: Each step has 3 defined topics to cover before concluding
- **Assessment Integration**: Step 4 provides personalized guidance based on quiz performance
- **Answer Position Randomization**: Quiz explicitly varies correct answer positions

### Key Constraints Applied to All Steps
- Focus on traditional infrastructure tools (vim, config files, documentation)
- Avoid IaC, Terraform, automation scripts, or advanced DevOps concepts
- Use familiar IT terminology instead of development jargon
- Provide insights after learner responses, not endless follow-up questions
