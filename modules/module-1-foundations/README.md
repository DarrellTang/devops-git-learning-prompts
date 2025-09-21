# Module 1: Foundation Concepts

## Learning Objectives
By the end of this module, learners will:
- Understand what version control is and why it's essential for infrastructure work
- Distinguish between Git and GitHub
- Recognize scenarios where version control solves real infrastructure problems
- Connect version control concepts to familiar infrastructure practices

## Prompts

### 1.1 Multiple Explanations - Version Control Fundamentals (Strategy 2)

```
You generate clear explanations for infrastructure professionals learning version control. My student is a sysadmin/cloud engineer who understands infrastructure but is new to version control. Explain what version control is and why it matters for infrastructure work. Provide a clear, multi-paragraph explanation using specific examples from infrastructure contexts, then give me 5 analogies that relate to change management, backup strategies, or configuration management that help explain version control concepts.
```

**Implementation Notes:**
- Focus on infrastructure contexts the learner already understands
- Emphasize problem-solving aspects rather than development features
- Connect to existing change control processes

### 1.2 Multiple Explanations - Git vs GitHub (Strategy 2)

```
Explain the difference between Git and GitHub to an infrastructure professional who might confuse them. Use analogies they understand: compare Git to a tool they use locally (like a text editor or configuration manager) and GitHub to a centralized service they use (like a file server or cloud storage). Provide multiple explanations from different angles to ensure they understand this critical distinction.
```

**Implementation Notes:**
- This distinction is crucial and often confusing for beginners
- Use familiar local vs. cloud service analogies
- Emphasize that Git works without GitHub

### 1.3 Multiple Examples - Infrastructure Version Control Scenarios (Strategy 1)

```
Generate 4 different scenarios where infrastructure professionals would benefit from version control: (1) managing server configuration files, (2) tracking infrastructure-as-code changes, (3) maintaining documentation, (4) sharing automation scripts. For each scenario, show the specific problems version control solves and what their workflow looks like without and with version control.
```

**Implementation Notes:**
- Each scenario should be realistic and relatable
- Show clear before/after comparisons
- Emphasize pain points they likely experience now

### 1.4 Low-Stakes Assessment - Foundational Understanding (Strategy 3)

```
Create a diagnostic quiz with 4 multiple-choice questions testing whether an infrastructure professional understands basic version control concepts. Focus on: (1) what problems version control solves, (2) the difference between Git and GitHub, (3) when version control is useful vs. overkill, (4) how version control relates to backup strategies. Include plausible wrong answers that reflect common misconceptions from people used to manual file management.
```

**Implementation Notes:**
- Questions should test understanding, not memorization
- Wrong answers should be believable and address common confusion
- Focus on conceptual understanding before technical details

## Expected Learning Outcomes

After completing this module, learners should be able to:
- Explain version control in their own words using infrastructure analogies
- Correctly distinguish between Git (the tool) and GitHub (the service)
- Identify situations where version control would improve their current workflows
- Recognize version control as an evolution of change management practices they already know

## Common Misconceptions to Address

1. **"Version control is just for developers"** - Emphasize infrastructure applications
2. **"Git and GitHub are the same thing"** - Reinforce the local vs. cloud distinction
3. **"This is just fancy backup"** - Explain collaboration and change tracking benefits
4. **"Too complex for simple config files"** - Show how it scales from simple to complex

## Next Module Connection

Module 2 will build on these concepts by showing how to actually create and work with repositories, connecting the theoretical understanding to practical implementation.
