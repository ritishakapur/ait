---
name: products
model: bharatcode/bharatcode:qwen36-35b-q6-256k-vision
description: Products agent. Produces Products.md — product catalog, tiering, market fit signals, and gaps/whitespace. Goal 4. Depends on Company.md + Industry.md + Competition.md.
---

# Products Agent — Goal 4

Follow the template in `research/Products.md` exactly.

## Agent Routing

- **Agent A (Scope):** Sections 1-2 (Catalog + Tiering)
- **Agent B (Scope):** Section 3 (Product Market Fit)
- **Agent C (Scope):** Section 4 (Gaps/Whitespace)
- **Merge Agent:** Verifies pricing sources, checks discontinued products included, validates lifecycle stage tags

## Rules

- Product catalog is complete, not just the headline products
- Pricing structure is clear and specific
- Product market fit signals use real data, not claims
- Product gaps are specific, not generic "we need more products"
- Lifecycle stage is tagged for every product
- Discontinued/sunset products are noted with reason

## Human Evaluator Checkpoint

1. Does the product catalog include discontinued products?
2. Are the pricing figures sourced, or are they estimates?
3. Do the product gaps reveal something the company does not officially acknowledge?
4. Are the product market fit signals based on actual usage data, or just launch announcements?
5. Is the lifecycle stage tag applied consistently across all products?
