# Industry.md — Goal 2

**What it is:** The market the company sits inside — its boundaries, structure, trajectory, and the standard numbers that define "normal" for this kind of business. Where Company.md is about one company, this file is about the space it operates in, so Competition.md (Goal 3) has a landscape to place people on and Revenue.md (Goal 8) has benchmarks to sanity-check against.

**Depends on:** Company.md (needs to know the company's business model and market to know which industry boundaries to draw).

**Agent Routing:**
- Agent A (Scope): Section 1 (Industry Definition & Boundaries + Value Chain + TAM/SAM framing)
- Agent B (Scope): Section 2.1 (Structure + Value Chain Map + Market Structure)
- Agent C (Scope): Section 2.1 Trends + Section 3 Benchmarks + Section 4 Player Landscape
- Merge Agent: Cross-checks benchmarks against trend trajectory, flags sources >18 months old, verifies boundary is defensible

1. Industry Definition & Boundaries
What counts as "in" this industry vs. adjacent-but-different. State the boundary explicitly — most industry mis-analysis comes from drawing the box wrong.
Where the company sits on the value chain (raw input → distribution → end use → disposal/renewal), stated as one sentence.
TAM / SAM framing at a high level (full sizing happens later in Revenue.md — this is just the boundary, not the number).
Example (PSU/Govt): CSC operates in the "rural digital services" industry — not "government IT" (too narrow) and not "all of digital India" (too broad). Boundary: includes last-mile service delivery via physical centers; excludes pure software platforms that don't have physical presence.
2. Industry Landscape
"Examples show STRUCTURE, not content. Adapt the logic to your company's industry. Don't force PSU/rural examples onto a SaaS or consumer brand company."

2.1  Structure
Value chain map: list every stage from deepest upstream input to end-of-life, in flow order. For each stage, note who typically occupies it (types of players, not names yet — names come in Competition.md).
Market structure: fragmented / consolidated / oligopoly / Monopolistic / regulated. State the evidence, not just the label
Evidence options: top-4 concentration %, HHI index, number of players by revenue share, regulatory barriers to entry, reported market share from annual reports or industry bodies.
Example (PSU/Govt): CSC operates in a regulated oligopoly — one dominant player (CSC-SPV) with state-level fragmentation (SDAs). Top-4 concentration is ~85% of rural digital service delivery, with regulatory barriers (government approval) preventing new entrants at the same scale.

Example (B2B Industrial): JSL operates in a consolidated market — top-3 stainless steel manufacturers hold ~75% of India's market. High capital requirements (₹10,000+ cr per plant) and 3-5 year build timelines create high barriers to entry.
2.1  Trends & Trajectory
A trend is a SHIFT in how the industry operates, not just a fact. "The industry is growing" is a fact. "The industry is shifting from one-time purchases to subscriptions" is a trend.

Look for trends in these categories:
- Business model shifts (e.g., product → service, transactional → recurring)
- Technology adoption (e.g., manual → automated, on-prem → cloud)
- Regulatory/policy changes (e.g., new compliance rules, subsidy shifts)
- Customer behavior changes (e.g., self-service → assisted, price-sensitive → value-driven)
- Competitive dynamics (e.g., fragmentation → consolidation, price wars → differentiation)

Example rows:
| Shift from one-time sales to subscription/recurring revenue | Growing | SaaS players moving to annual contracts | 12-24 months | High |
| Regulatory push for data localization | Growing | New data protection laws forcing local storage | 6-12 months | High |
| Customer preference for self-service over assisted delivery | Shifting | Mobile apps replacing call centers | 12-36 months | Medium |

3. Industry Trends & Trajectory
Needs more nuance
Trend
Direction
Evidence/Source
Time Horizon
Confidence (H/M/L)


Growing/Shrinking/Shifting







Include: growth rate (CAGR with source), disruption vectors (new tech, new entrants, substitute products), and what's changed in the last 12–18 months specifically.
3. Industry Benchmarks
The "what normal looks like" numbers — so later files (especially Revenue.md) have something to compare the company against instead of judging it in a vacuum.
Metric
Industry Typical Range
Source
Notes
Typical margin






Typical CAC / unit cost






Typical growth rate






Typical valuation multiple (if applicable)







Pick the metrics that match the company's business type. Don't force PSU benchmarks onto a SaaS company.
- SaaS: CAC (Customer Acquisition Cost), churn rate, ARR(Annual Recurring Revenue), gross margin
- PSU/Govt: coverage %, transaction volume, cost per endpoint
- Consumer brand: SKU(Stock Keeping Unit) margin, retail sell-through rate, distribution cost
- Marketplace: take rate, GMV(Gross Merchandise Value) growth, buyer-seller ratio
Example row (structure only): | [Metric name] | [Typical range] | [Source] | [Context/notes] |

4. Industry Player Landscape (high-level only)
A tiering pass, not full profiles (full profiles are Competition.md's job):
Tier
Who's in it
Rough count
What defines this tier
Leaders






Challengers






Niche/specialist






Emerging/new entrants







Example:
| Leaders | CSC-SPV (near-monopoly in rural digital services) | 1 | Dominant player, government-backed |
| Challengers | Common Help Centers (state-level, fragmented) | ~15-20 | State-specific, smaller scale |
| Niche/specialist | District-level digital centers | ~100+ | Single-district coverage, local focus |
| Emerging/new entrants | Private rural service startups | ~10-15 | New, unproven at scale |

Blind Spots & Assumptions (Industry.md)
Flag: any boundary-drawing decision that's a judgment call rather than a hard fact; any benchmark pulled from a report that's >18 months old; any trend stated with only one source.
What Good Looks Like
The industry boundary is stated as an explicit, defensible line — not implied.
Value chain map is in flow order and specific to this industry, not a generic template.
At least one trend directly threatens or benefits the company from Company.md, named explicitly.
Benchmarks are sourced, not remembered/assumed.
Human/Evaluator Checkpoint
"If you handed this file to someone who's never heard of this company, could they correctly guess what kind of business it is, just from the industry description? If not, the boundary is drawn too loosely."
Good boundary example: "Rural digital services via physical centers" — you can guess CSC from this.
Bad boundary example: "Technology and government services" — that could be anything.
