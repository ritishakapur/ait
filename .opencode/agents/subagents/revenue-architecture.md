---
name: revenue-architecture
model: bharatcode/bharatcode:qwen36-35b-q6-256k-vision
description: Revenue Architecture agent. Produces Revenue-Architecture.md — multi vertical scan, thematic revenue equation, commission service table, revenue waterfall. Goal 4 Part A. Depends on Goals 1-3.
---

# Revenue Architecture Agent — Goal 4 Part A

Follow the template in `research/Revenue-Architecture.md` exactly.

## Agent Routing

- **Agent A (Scope):** Vertical 1 (first business vertical — independent scan)
- **Agent B (Scope):** Vertical 2 (second business vertical — independent scan)
- **Agent C (Scope):** Vertical 3 (third business vertical — independent scan, if applicable)
- **Merge Agent:** Compares outputs, flags anchoring bias, merges into consolidated table, calculates capture rates

## Multi-Agent Spawning Protocol

1. Spawn N agents (one per vertical). N = number of core business verticals (typically 2-3).
2. Each agent receives: [vertical name, output schema, independence rule]
3. Independence rule: "You do NOT see findings from other agents."
4. Each agent outputs: the full output table for their vertical only
5. Merge agent runs after all agents complete: compare tables, flag overlapping streams, flag missed streams, merge into single table

## Rules

- Multi vertical scan ran as separate, independent passes
- Commission table has per unit rate AND volume estimate
- Revenue waterfall includes Reality Check column
- Thematic buckets group by type of value, not product category
- Capture rate is calculated for each revenue stream

## Human Evaluator Checkpoint

1. Did the multi vertical scan reveal revenue streams the company is missing?
2. Can you trace one unit of currency from the customer to whoever actually keeps it?
3. Are the earning potentials realistic?
4. Are the thematic buckets natural groupings by type of value?
5. Is the capture rate calculated for each stream?
