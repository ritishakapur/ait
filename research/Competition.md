# Competition.md — Goal 3

**What it is:** Who else operates in this space, what they actually do versus the company, and where the real gaps are. This is where the industry level tiering from Industry.md becomes named, profiled players.

**Depends on:** Company.md, Industry.md.

**Anti-pattern rule:** Examples show STRUCTURE, not content. Adapt the logic to your company's industry. Do not force PSU or rural examples onto a SaaS or consumer brand company.

**Agent Routing:**
- Agent A (Scope): Section 1 (Competitor Profiles)
- Agent B (Scope): Section 2 (Positioning Map)
- Agent C (Scope): Sections 3-4 (Gap Analysis + Moats/Vulnerabilities)
- Merge Agent: Validates moat replication test, checks gap sizes aren't all High/Low, runs competitive response simulation

---

## 1. Competitive Set + Profiles

### Part A: Inclusion Criteria

State why each competitor belongs here before naming them.

| Category | Definition | Why included |
|---|---|---|
| Direct competitors | Same product, same customer | |
| Indirect competitors | Different product, same need | |
| Adjacent players | Could enter this space easily | |
| Substitutes | Customer solves the problem another way entirely | |

**Example (rural service company):**
| Category | Definition | Why included |
|---|---|---|
| Direct competitors | Common Help Centers, state digital service portals | Same product, same customer |
| Indirect competitors | Private help desks, cyber cafes offering Aadhaar and PAN services | Different product, same need |
| Adjacent players | State e-governance missions like Karnataka e-District | Could enter rural last mile easily |
| Substitutes | Online government portals like UMANG app | Customer solves the problem another way |

### Part B: Competitor Profiles

For the top 5 to 10 players (pull from Industry.md Leaders and Challengers tiers), one entry each.

| Field | Detail |
|---|---|
| Name | Full legal name |
| What they do / USP | One sentence describing their core offering and what makes them different |
| Est. market share | Percentage of market or "Unknown, estimated at X based on Y" |
| Pricing model | How they make money (subscription, commission, one time fee, freemium) |
| Funding / ownership status | Bootstrapped, VC funded, government owned, public company |
| Recent moves (last 12 months) | New products, partnerships, leadership changes, funding rounds |
| Where they beat the company | Specific areas of competitive advantage (must cite evidence, not confidence) |
| Where the company beats them | Specific areas where the company has an edge (must cite evidence, not confidence) |

**Example (rural service company):**
| Field | Detail |
|---|---|
| Name | Common Help Centers |
| What they do / USP | State run digital service centers focused on rural citizen services |
| Est. market share | 5 to 8 percent, fragmented across states |
| Pricing model | Commission based, similar to CSC VLE model |
| Funding / ownership status | State government funded |
| Recent moves | Expanded to 5 new states, added insurance brokerage |
| Where they beat the company | Stronger state level relationships in Tamil Nadu and Kerala |
| Where the company beats them | CSC has 10x the scale, 5 lakh VLEs versus CHC's 50,000 |

---

## 2. Positioning Map

Find axes that actually differentiate players in this space. Do not use generic axes like "price versus quality" unless that is truly the sharpest cut for this industry. Ask: what dimension do customers care about most? What dimension do competitors vary on?

**How to build it:**
1. Propose 4 to 6 candidate axes that differentiate players
2. Select the 2 most independent and most explanatory
3. Plot every named competitor plus the company itself on the grid
4. Explain why you chose the axes and why you rejected the others

**Example (rural service company):**
Candidate axes:
- Government backed versus private — too obvious, everyone clusters on one side
- Scale versus specialization — CSC is broad with 814 services, CHCs are narrow and state specific
- Digital native versus phone first — some have apps, others rely on calls and WhatsApp
- Commission only versus subscription — how operators earn

Selected axes: Scale versus Specialization (most explanatory for rural digital services)
Rejected axes: Government versus private (too binary), Digital versus phone (not enough variance)

Grid:
| | Specialized (narrow focus) | Broad (wide service range) |
|---|---|---|
| High scale | CHC Tamil Nadu | CSC SPV national |
| Low scale | District level centers | Private cyber cafes |

---

## 3. Gap Analysis

This section owns the gap analysis. Where competitors beat the company, where the company beats competitors, and what the company is missing entirely.

| Revenue or Capability Avenue | Competitors Doing It? | Company Doing It? | Gap Size | Why the Gap Exists |
|---|---|---|---|---|
| | Yes/No | Yes/No/Partial | High/Med/Low | |

Gap size must be rated honestly. If every row is "High," the scan was not deep enough. If every row is "Low," it was not skeptical enough.

**Example (rural service company):**
| Revenue or Capability Avenue | Competitors Doing It? | CSC Doing It? | Gap Size | Why the Gap Exists |
|---|---|---|---|---|
| Insurance brokerage | Yes | Partial | High | Only VLEs with RAP cert can sell |
| EdTech referral commissions | Yes | Partial | Med | CSC added PW but no tracking system |
| Advisory and consulting | Yes | No | High | Complete whitespace |
| Data products and market intelligence | Yes | No | High | CSC has transaction data but does not monetize it |

---

## 4. Moats and Vulnerabilities

For the company and for each major competitor: what actually protects their position versus what is assumed to be a moat but is not. Test each claimed moat against the question: could a well funded new entrant replicate this in 18 months? If yes, it is not a moat. It is a temporary advantage.

| Moat | Is It Real? | Why |
|---|---|---|
| | | |

| Vulnerability | Could Entrant Replicate? | Why |
|---|---|---|
| | | |

**Example (rural service company):**
| Moat | Is It Real? | Why |
|---|---|---|
| Scale (5 lakh VLEs) | Yes | Would take 10 plus years and billions to replicate |
| Government backing | Yes | Regulatory barriers prevent new entrants at same scale |
| Brand recognition | Partial | Known in rural India but not differentiated from CHCs |

| Vulnerability | Could Entrant Replicate? | Why |
|---|---|---|
| Portal fragmentation (17 plus logins) | Yes | Any competitor could build a unified portal |
| No service prioritization | Yes | Easy to add a recommendation engine |
| Invisible certification ladder | Yes | Any competitor could display income tiers upfront |

---

## 5. Competitive Response Simulation

If the company launches [X], predict how each major competitor would respond.

| Competitor | Likely Response | Confidence | Evidence |
|---|---|---|---|
| | | H/M/L | |

Response types: price cut, feature match, partnership, legal/regulatory action, acquisition, public relations campaign.
Rule for the agent: "For each competitor, state what they would likely do, rate your confidence, and cite the evidence (past behavior, stated strategy, resource capacity) that supports your prediction."

---

## Blind Spots and Assumptions (Competition.md)

Flag: any competitor profile built from marketing material alone with no independent verification. Any market share figure that is an estimate rather than reported. Any competitor that may have exited or pivoted since the source data was published.

## What Good Looks Like

- Inclusion criteria are explicit, no player appears without a stated reason
- At least one gap in the Gap Analysis genuinely surprises you
- The positioning map axes are specific to this industry, not a generic template
- Moats are tested, not asserted
- Competitive response simulation shows plausible reactions, not guesses

## Human Evaluator Checkpoint

Before moving to the next file, ask yourself:

1. Would a competitor's own team recognize their profile as accurate, or would they say that is not really what we do? If the profile reads like it came only from their homepage, verify against a second source.
2. Are the gap sizes rated honestly? If every row is High, dig deeper. If every row is Low, be more skeptical.
3. Did you test each claimed moat against the 18 month replication question? If not, redo it.
4. Are the positioning map axes specific to this industry, or did you use generic axes like price versus quality?
5. Does the competitive response simulation show what competitors would actually do, or just what you hope they would do?
