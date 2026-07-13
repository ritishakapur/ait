# Revenue-Architecture.md — Goal 4 (Part A)

**What it is:** How money flows through the company's ecosystem. The full map of revenue avenues, who earns what, and what is currently captured. This is Part A of Goal 4. Part B (Revenue-Economics.md) covers the math, the problems, and the sizing.

**Depends on:** all of Goals 1 through 3 (Company, Industry, Stakeholders).

**Anti-pattern rule:** Examples show STRUCTURE, not content. Adapt the logic to your company's industry. Do not force PSU or rural examples onto a SaaS or consumer brand company.

**Agent Routing:**
- Agent A (Scope): Vertical 1 (first business vertical — independent scan)
- Agent B (Scope): Vertical 2 (second business vertical — independent scan)
- Agent C (Scope): Vertical 3 (third business vertical — independent scan, if applicable)
- Merge Agent: Compares outputs, flags anchoring bias, merges into consolidated table, calculates capture rates

---

## 1. Multi Vertical Scan

Run separate research passes on 2 to 3 core business verticals. Each pass works in isolation. The agent doing Vertical A does not see what the agent doing Vertical B finds. This prevents anchoring bias. Then compare findings to spot missed revenue avenues.

**Multi-Agent Spawning Protocol:**
1. Spawn N agents (one per vertical). N = number of core business verticals (typically 2-3).
2. Each agent receives: [vertical name, output schema, independence rule]
3. Independence rule: "You do NOT see findings from other agents. If you suspect anchoring, note it but proceed independently."
4. Each agent outputs: the full output table for their vertical only
5. Merge agent runs after all agents complete:
   a. Compare tables across verticals for overlapping revenue streams
   b. Flag streams that appear in multiple verticals (anchoring check)
   c. Flag streams missed by all agents (blind spot check)
   d. Merge into single consolidated table

**Output table:**
| Vertical | Revenue Stream | Who Pays | Per Unit Rate | Volume Reality | Company Captures It? | Capture Rate % | Agent Confidence |
|---|---|---|---|---|---|---|---|
| | | | | | Yes/No/Partial | | High/Med/Low |

**Example (rural service company) — CSC verticals:**
Vertical A: G2C services (Aadhaar, PAN, voter ID)
Vertical B: Financial services (AEPS, BBPS, insurance)
Vertical C: EdTech and skilling (Physics Wallah, CSC Academy)

**Example (manufacturing company) — JSL verticals:**
Vertical A: Material revenue (raw steel, semi finished, finished goods)
Vertical B: Human capital revenue (training, certification, placement)
Vertical C: Intellectual capital revenue (advisory, data products, API)

---

## 2. Thematic Revenue Equation

Group all revenue streams by TYPE of value, not by product category. "Material revenue" is a type. "Training revenue" is a type. "Data revenue" is a type. Not "product A, product B, product C."

**Format:**
```
BUCKET NAME
One sentence description of what this bucket represents
  Sub category — what it is (pricing model)
    Sub sub category — specific product or service
  Sub category — what it is (pricing model)
    Sub sub category — specific product or service
```

**Example (manufacturing company) — JSL Revenue Equation:**

1. MATERIAL REVENUE
Selling steel at every level of completion
1.1 Raw Materials — coils and sheets at industrial scale (rupees per tonne)
  1.1.1 Direct sales to large enterprises and OEMs
  1.1.2 Sales through service centers
1.2 Semi Finished Goods — processed steel, ready to use components (rupees per tonne processed)
  1.2.1 Cut to size from service centers
  1.2.2 Fabricated components like brackets and fittings
1.3 Finished Goods — end products customers buy and use (rupees per unit)
  1.3.1 B2B finished products (tools, architectural railings)
  1.3.2 B2C finished products (pressure cookers, utensils)

2. HUMAN CAPITAL REVENUE
Training plus Certification plus Placement
2.1 Training Programs — teaching skills (rupees per learner times number of learners)
  2.1.1 Digital self serve (online courses)
  2.1.2 In person workshops (ITI and polytechnic colleges)
2.2 Certification — credentialing (rupees per credential times number certified)
  2.2.1 Individual credential (skill assessment)
  2.2.2 Facility certification (ISO Shop Mark)
2.3 Placement and Talent Discovery — connecting talent to opportunity (rupees per placement)
  2.3.1 Job creation and matching
  2.3.2 Entrepreneur pipeline (franchise in a box)

---

## 3. Commission Service Table

| Service or Product Category | Examples | Per Unit Rate | Volume Reality | Monthly Earning Potential | Pricing Type | Revenue Type | Market Benchmark |
|---|---|---|---|---|---|---|---|
| | | | | | Product/Service | One time/Recurring/Per use | Source or comparable |

Pricing type equals product based or service based. Revenue type equals one time or recurring or per use or per project.

**Example (rural service company) — CSC commission table:**
| Service or Product Category | Examples | Per Unit Rate | Volume Reality | Monthly Earning Potential | Pricing Type | Revenue Type | Market Benchmark |
|---|---|---|---|---|---|---|---|
| G2C services | Aadhaar update, PAN, bill payment | 5 to 50 rupees per txn | 2 to 3 per day per VLE | 1500 to 4000 per month | Service | Per use | CSC annual report |
| Insurance | LIC, motor, health | 15 to 50 percent of premium | Low volume, needs cert | 5000 to 15000 per month if certified | Service | Per use | IRDAI benchmark |
| EdTech referrals | PW courses, Sarkari Pariksha | 50 to 500 per registration | Growing | 2000 to 8000 per month | Service | Per use | EdTech industry avg |

---

## 4. Revenue Waterfall

All income streams ranked by earning potential, with a Reality Check column for what actually limits earnings (certification barriers, volume constraints, complexity, trust requirements).

| Rank | Revenue Stream | Earning Potential | Reality Check | Thematic Bucket |
|---|---|---|---|---|
| | | | | |

**Example (rural service company) — CSC revenue waterfall:**
| Rank | Revenue Stream | Earning Potential | Reality Check | Thematic Bucket |
|---|---|---|---|---|
| 1 | Insurance brokerage | 5000 to 15000 per VLE per month | Requires RAP cert plus sales skills plus trust | Financial |
| 2 | EdTech referrals | 2000 to 8000 per VLE per month | VLEs do not know which course to prioritize | Human Capital |
| 3 | G2C commission | 1500 to 4000 per VLE per month | Low per unit rate, volume constrained | G2C Services |
| 4 | Banking (AEPS and BBPS) | 500 to 2000 per VLE per month | Requires IIBF exam (98 rupees), most VLEs skip it | Financial |

---

## Blind Spots and Assumptions (Revenue-Architecture.md)

Flag: any revenue stream discovered in the multi vertical scan that lacks a source. Any earning potential estimate without a per unit rate and volume estimate. Any thematic bucket that feels forced rather than natural.

## What Good Looks Like

- Multi vertical scan ran as separate, independent passes
- Commission table has per unit rate AND volume estimate
- Revenue waterfall includes Reality Check column
- Thematic buckets group by type of value, not product category
- Capture rate is calculated for each revenue stream (what % stays with company vs leaks to intermediaries)

## Human Evaluator Checkpoint

Before passing to Revenue-Economics.md, ask yourself:

1. Did the multi vertical scan reveal revenue streams the company is missing? If every vertical shows "Yes" for every stream, you did not scan deeply enough.
2. Can you trace one unit of currency from the customer to whoever actually keeps it? If not, you are missing a step in the flow.
3. Are the earning potentials realistic? If the numbers do not add up to a plausible earning, a revenue stream is missing or volume is overestimated.
4. Are the thematic buckets natural groupings by type of value, or did you force products into buckets?
5. Is the capture rate calculated for each stream? If not, add it.
