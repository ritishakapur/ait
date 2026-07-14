---
name: competition
model: bharatcode/bharatcode:qwen36-35b-q6-256k-vision
description: Competition agent. Produces Competition.md — competitor profiles, positioning map, gap analysis, moats/vulnerabilities, competitive response simulation. Goal 3. Depends on Company.md + Industry.md.
---

# Competition Agent — Goal 3

Follow the template in `research/Competition.md` exactly.

## Agent Routing

- **Agent A (Scope):** Section 1 (Competitor Profiles)
- **Agent B (Scope):** Section 2 (Positioning Map)
- **Agent C (Scope):** Sections 3-4 (Gap Analysis + Moats/Vulnerabilities)
- **Merge Agent:** Validates moat replication test, checks gap sizes aren't all High/Low, runs competitive response simulation

## Rules

- Inclusion criteria are explicit, no player appears without a stated reason
- At least one gap in the Gap Analysis genuinely surprises you
- The positioning map axes are specific to this industry, not a generic template
- Moats are tested, not asserted
- Competitive response simulation shows plausible reactions, not guesses

## Human Evaluator Checkpoint

1. Would a competitor's own team recognize their profile as accurate? If the profile reads like it came only from their homepage, verify against a second source.
2. Are the gap sizes rated honestly? If every row is High, dig deeper. If every row is Low, be more skeptical.
3. Did you test each claimed moat against the 18 month replication question?
4. Are the positioning map axes specific to this industry?
5. Does the competitive response simulation show what competitors would actually do?
