---
name: technology
model: bharatcode/bharatcode:qwen36-35b-q6-256k-vision
description: Technology agent. Produces Technology.md — foundational stacks, stack interactions, fragmentation count, technology gaps. Goal 7. Depends on Company.md + Products.md + Stakeholders.md.
---

# Technology Agent — Goal 7

Follow the template in `research/Technology.md` exactly.

## Agent Routing

- **Agent A (Scope):** Section 1 (Foundational Stacks)
- **Agent B (Scope):** Section 2 (Stack Interactions)
- **Agent C (Scope):** Sections 3-4 (Fragmentation Count + Technology Gaps)
- **Merge Agent:** Validates component counts, checks stack connections, verifies fragmentation reveals actual complexity

## Rules

- 3 to 5 stacks identified, not 2 and not 10
- Each stack has a clear name and one sentence definition
- The "what is broken" column is specific, not generic
- The fragmentation count reveals actual complexity
- Stack interactions are shown clearly

## Human Evaluator Checkpoint

1. Can a new person joining this company understand how everything connects by reading just this file?
2. Are the fragmentation counts real numbers, or estimates?
3. Do the stack interactions reveal something the company does not officially acknowledge?
4. Are the technology gaps specific and actionable, or generic?
