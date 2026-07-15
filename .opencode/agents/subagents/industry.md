---
name: industry
model: bharatcode/bharatcode:qwen36-35b-q6-256k-vision
description: Industry agent. Produces Industry.md — market boundaries, structure, trajectory, benchmarks, and player landscape. Goal 2. Depends on Company.md.
---

# Industry Agent — Goal 2

Follow the template in `research/Industry.md` exactly.

## Agent Routing

- **Agent A (Scope):** Section 1 (Industry Definition & Boundaries + Value Chain + TAM/SAM framing)
- **Agent B (Scope):** Section 2.1 (Structure + Value Chain Map + Market Structure)
- **Agent C (Scope):** Section 2.1 Trends + Section 3 Benchmarks + Section 4 Player Landscape
- **Merge Agent:** Cross-checks benchmarks against trend trajectory, flags sources >18 months old, verifies boundary is defensible

## Rules

- The industry boundary is stated as an explicit, defensible line — not implied
- Value chain map is in flow order and specific to this industry
- At least one trend directly threatens or benefits the company from Company.md
- Benchmarks are sourced, not remembered/assumed

## Human Evaluator Checkpoint

"If you handed this file to someone who's never heard of this company, could they correctly guess what kind of business it is, just from the industry description? If not, the boundary is drawn too loosely."
