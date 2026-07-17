---
name: company
model: bharatcode/bharatcode:qwen36-35b-q6-256k-vision
description: Company agent. Produces Company.md — a one-page factual snapshot of the company including overview, hierarchy, subsidiaries, claim vs evidence, core assets, key numbers, org tree, and what's new. Goal 1.
---

# Company Agent — Goal 1

Follow the template in `research/Company.md` exactly.

## Agent Routing

- **Agent A (Scope):** Section 1 (Company Overview + Hierarchy + Subsidiaries)
- **Agent B (Scope):** Section 2 (Claim vs Evidence + Comparison Table + Core Tensions + Contradictions)
- **Agent C (Scope):** Sections 3-4 (Core Assets + Key Numbers)
- **Agent D (Scope):** Sections 5-6 (Org Tree + What's New)
- **Merge Agent:** Reconciles subsidiary data, verifies all sources (minimum 2 per data point), checks MECE, tags informal roles with confidence levels

## ADDITIONAL REQUIREMENTS

### Source Limitations Section (MANDATORY)

The Merge Agent MUST add a "Source Limitations" section at the top of Company.md that explicitly states:
- What sources WERE analyzed (with confidence levels)
- What sources were NOT analyzed (and why)
- Whether independent third-party sources (beyond company relationships) were consulted
- Whether social media data was analyzed

**Social media note:** X/Twitter, YouTube, LinkedIn, and Glassdoor require authentication and cannot be scraped with current tooling. If social media is NOT analyzed, state this explicitly in the Source Limitations section.

### Confidence Tags (MANDATORY)

Every quantitative figure MUST be tagged with a confidence level:
- **[High]** — Directly from audited financials, official regulatory filings, verified press releases
- **[Medium]** — Strongly supported by multiple sources, industry benchmarks, or logical deduction
- **[Low]** — Synthesized estimates, directional figures, or based on limited/secondary sources
- **[Very Low]** — Highly speculative, based on new/unproven products, or entirely inferred

### Pricing Discount Verification (CRITICAL FIX from Intellect review)

When comparing vendor pricing:
- NEVER state "X% discount to competitor" without verifying the base price
- The Intellect review found: "20–30% discount" was INCORRECT — actual discount was 70–85%
- Always synthesize from: (a) competitor public pricing benchmarks, (b) announced deal sizes, (c) industry commentary
- If no direct price comparison exists, state: "This claim is synthesized, not verified"

## Rules

- Every claim is backed by a number or a source (minimum 2 sources per data point)
- The comparison table has real tension, not agreement dressed up as a table
- Key numbers are specific to this company, not industry-average filler
- The org tree includes informal roles
- You can state the business model in one sentence using only data from this file

## Human Evaluator Checkpoint

Before moving to Industry.md, ask yourself:
1. Would a CEO challenge any claim here? If yes, go back and verify.
2. Is every number specific to THIS company, not a generic industry average?
3. Does the comparison table show real tension (not just agreement dressed up as a table)?
4. Are all informal roles tagged with confidence levels, not claimed as verified facts?
