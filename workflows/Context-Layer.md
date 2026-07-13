# Context-Layer.md — End-to-End Workflow

## Purpose
This is the full end-to-end workflow for producing a complete strategic analysis from scratch.

## Steps

### Phase 1: Setup (Day 0)
1. Create the project folder structure (rules/, workflows/, frameworks/, research/, templates/, sources/, tests/)
2. Populate `Global Organisation for Claude.md` with project context
3. Set up the GitHub repo (see `templates/Final-Deck.md` for reference)
4. Invite all collaborators

### Phase 2: Company Ground Truth (Day 1)
1. Agent A: Section 1 — Company Overview (name, what it does, hierarchy, subsidiaries)
2. Agent B: Section 2 — Claim vs Evidence (comparison table, core tensions, contradictions)
3. Agent C: Sections 3-4 — Core Assets + Key Numbers
4. Agent D: Sections 5-6 — Org Tree + What's New
5. Merge Agent: Verify all sources, check MECE, tag informal roles with confidence
6. Output: `research/Company.md`

### Phase 3: Industry Context (Day 2)
1. Agent A: Section 1 — Industry Definition & Boundaries
2. Agent B: Section 2.1 — Structure (value chain, market structure)
3. Agent C: Sections 2.1-4 — Trends, Benchmarks, Player Landscape
4. Merge Agent: Cross-check benchmarks, flag outdated sources
5. Output: `research/Industry.md`

### Phase 4: Stakeholders & Customers (Day 2-3)
1. Agent A: Capability Framework (Section 0)
2. Agent B: Map the Universe (Section 1)
3. Agent C: Build Groups, Per Layer, Cross Layer Tension (Sections 2-4)
4. Output: `research/Stakeholders.md`
5. Agent A: Customer Segments (Section 1)
6. Agent B: Customer Journey (Section 2)
7. Agent C: Needs/Pain Points + Retention (Sections 3-4)
8. Output: `research/Customers.md`

### Phase 5: Competition & Products (Day 3-4)
1. Agent A: Competitor Profiles (Section 1)
2. Agent B: Positioning Map (Section 2)
3. Agent C: Gap Analysis + Moats (Sections 3-4)
4. Output: `research/Competition.md`
5. Agent A: Product Catalog + Tiering (Sections 1-2)
6. Agent B: Product Market Fit (Section 3)
7. Agent C: Gaps/Whitespace (Section 4)
8. Output: `research/Products.md`

### Phase 6: Revenue (Day 4-5)
1. Multi-agent vertical scans (Revenue-Architecture.md)
2. Unit economics + income math problem (Revenue-Economics.md)
3. Sensitivity analysis
4. Output: `research/Revenue-Architecture.md`, `research/Revenue-Economics.md`

### Phase 7: Technology (Day 5)
1. Foundational stacks, interactions, fragmentation, gaps
2. Output: `research/Technology.md`

### Phase 8: Review & Finalize (Day 6)
1. Cross-file verification (all numbers consistent, all references valid)
2. Human checkpoint on each file
3. Blind spots review
4. Final deck preparation
5. Output: `templates/Final-Deck.md`

## Agent Routing
Each phase uses the agent routing defined in the respective research file. See each file's `**Agent Routing:**` block for details.
