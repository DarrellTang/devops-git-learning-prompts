# DevOps Git Learning Prompts

## Project Overview

This repository contains AI-powered learning prompts designed to teach Git/GitHub to infrastructure professionals (sysadmins, network engineers, systems engineers, cloud engineers) who are transitioning to DevOps roles.

## Target Audience

**Primary Learners:**
- Infrastructure professionals with strong technical backgrounds
- Minimal development experience
- Currently work with servers, networks, cloud infrastructure
- Need Git/GitHub skills for DevOps workflows
- Understand change management, configuration management, backup strategies

**Key Characteristic:** They think in infrastructure terms, not development terms.

## Pedagogical Foundation

Based on "Using AI to Implement Effective Teaching Strategies in Classrooms: Five Strategies" by Mollick & Mollick (2023):

1. **Multiple Examples** - Infrastructure scenarios across different contexts
2. **Multiple Explanations** - Analogies to familiar infrastructure concepts  
3. **Low-Stakes Testing** - Diagnostic quizzes with realistic distractors
4. **Student Learning Assessment** - Tools to identify learning gaps
5. **Distributed Practice** - Connecting new and previous concepts

## Repository Structure

```
modules/
├── module-1-foundations/           # Version control concepts (1 hour)
├── module-2-repository-basics/     # Repository creation & management (50 min)
├── module-3-basic-workflow/        # Add, commit, push workflow (70 min)
├── module-4-branching-prs/         # Collaboration workflows (75 min)
└── module-5-assessment/            # Integration & troubleshooting (65 min)
```

Each module contains:
- `README.md` - Learning path overview
- `step-X-[topic].md` - Individual learning steps
- `instructor-notes.md` - Pedagogical documentation (Module 1 only)

## Learning Experience Design

**Learner Workflow:**
1. Navigate to module README for overview
2. Follow step-by-step progression
3. Copy prompts into AI chat interfaces (ChatGPT, Claude, etc.)
4. Receive tailored explanations using infrastructure analogies
5. Complete hands-on exercises with Git commands
6. Self-assess understanding before proceeding

**Key Design Principles:**
- No academic jargon in learner-facing content
- Copy-paste prompts optimized for AI chat
- Infrastructure contexts in all examples
- Progressive complexity building
- Practical application throughout

## Content Strategy

**Analogies Used:**
- Version control → Change control processes
- Repositories → Centralized configuration stores
- Branches → Test environments  
- Staging → Change approval workflow
- Commits → Documented deployments
- Pull requests → Change review process

**Examples Focus:**
- Server configuration management
- Infrastructure-as-code workflows
- Documentation maintenance
- Automation script sharing
- Firewall rule updates
- Monitoring configuration

## Implementation Notes

**AI Tools:** Prompts work with ChatGPT, Claude, or similar LLMs
**Quality Control:** All AI-generated content requires instructor review
**Technical Accuracy:** Infrastructure contexts reduce hallucination risk
**Scalability:** Self-paced learning with AI assistance

## Success Metrics

**Learning Outcomes:**
- Understand version control value for infrastructure work
- Execute basic Git workflow (add, commit, push)
- Use branching for safe infrastructure changes
- Collaborate via pull requests
- Integrate Git with existing infrastructure tools

**Coverage:** 80-90% of DevOps Git usage patterns

## Current Status

**Complete:** All 5 modules with 20 learning steps
**Ready for:** Testing with target audience
**Next Steps:** Learner feedback integration, prompt refinement

## Business Model Potential

**Productization Path:**
1. AI-generated theoretical content (this repository)
2. Practical hands-on exercises (GitHub PR reviews)
3. Expert feedback on real infrastructure implementations
4. Scalable DevOps education for infrastructure professionals

The repository serves as the foundation for a complete learning product targeting the underserved market of infrastructure professionals transitioning to DevOps roles.
