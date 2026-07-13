# Revenue-Economics.md — Goal 4 (Part B)

**What it is:** The honest math section. Unit economics, the structural income problem, revenue levers, and market sizing. This is Part B of Goal 4. Part A (Revenue-Architecture.md) covered the map of revenue avenues. This part covers the numbers, the problems, and the sizing.

**Depends on:** Revenue-Architecture.md, all of Goals 1 through 3.

**Anti-pattern rule:** Examples show STRUCTURE, not content. Adapt the logic to your company's industry. Do not force PSU or rural examples onto a SaaS or consumer brand company.

**Agent Routing:**
- Agent A (Scope): Sections 1-2 (Unit Economics + Income Math Problem)
- Agent B (Scope): Section 3 (Revenue Levers)
- Agent C (Scope): Section 4 (Market Sizing)
- Merge Agent: Validates all math, checks per-segment separation, runs hallucination check, adds sensitivity analysis

---

## 1. Unit Economics (the honest math)

Rule for the agent: "If the company serves multiple distinct customer segments, create ONE table per segment. Label each table with the segment name. Never aggregate across segments."

Validation formula: Gross earning = per transaction earning × daily volume × 30. Net earning = gross earning − fixed costs. Gap = potential or survival threshold − actual net earning. If any calculation doesn't balance, flag in Blind Spots.

| Component | Value | Source or Assumption |
|---|---|---|
| Per transaction earning | | |
| Daily or monthly volume | | |
| Gross earning | Calculation: per unit times volume | |
| Fixed costs | | |
| Net earning | Calculation: gross minus fixed costs | |
| Gap: earned versus potential | | |
| Gap: earned versus needed to sustain or grow | | |

Separate product pricing from service pricing. Never mix revenue types in one line without explaining the logic. Every number: named source, comparable company benchmark, bottom up calculation, or explicitly labeled assumption. If using a range, explain why the low and high ends exist.

**Example (rural service company) — VLE unit economics:**
| Component | Value | Source or Assumption |
|---|---|---|
| Per transaction earning | 25 rupees avg | CSC annual report (5 to 50 range, weighted avg) |
| Daily volume | 2.5 txns per day | CSC transaction data divided by VLE count |
| Gross earning | 1875 per month | Calculation: 25 times 2.5 times 30 |
| Fixed costs | 500 per month | Internet, device maintenance, center rent (est.) |
| Net earning | 1375 per month | Calculation: 1875 minus 500 |
| Gap: earned versus potential | 13625 per month | Potential at Level 3: 15000 minus Actual: 1375 |
| Gap: earned versus needed to sustain | 3625 per month | Survival threshold: 5000 minus Actual: 1375 |

---

## 2. The Income Math Problem

A specific structural issue, not a vague complaint. Not "people do not earn enough." Something like "high commission services require certifications invisible to the people who need them."

**Format:**
```
The [X] Problem: one sentence description
Why it exists: [root causes]
What it means: [consequences]
```

**Example (rural service company) — The Invisible Ladder Problem:**
One sentence: High commission services require certifications that are invisible to the VLEs who need them.
Why it exists:
- CSC portal shows 814 services but does not show which ones pay more
- The 4 level certification ladder exists but is not displayed on the product catalog
- Nobody proactively tells new VLEs: get this 98 rupee cert to 5x your income
What it means:
- VLEs stay at Level 1 earning 3000 per month when Level 3 pays 15000
- YouTube educators fill this gap organically, 46 tutorials on certification
- CSC loses commission revenue because VLEs cannot access high paying services

---

## 3. Revenue Levers

| Revenue Lever | What It Is | Company Is Pushing It? | Money Actually Flows Here? | Gap |
|---|---|---|---|---|
| | | Yes/No | Yes/No | |

Ranked by impact. What actually moves the most money, distinct from what the company talks about pushing.

**Example (rural service company) — CSC revenue levers:**
| Revenue Lever | What It Is | Company Is Pushing It? | Money Actually Flows Here? | Gap |
|---|---|---|---|---|
| Insurance brokerage | High commission sales (15 to 50 percent of premium) | Partial, pushes via DMs | Yes, only real money earner for VLEs | DMs do not know which VLEs are certified |
| EdTech referrals | Course sign up commissions (50 to 500 rupees) | Yes, added PW and Sarkari Pariksha | Partial, growing but untracked | No system to match VLEs to courses |
| G2C services | Government service commissions (5 to 50 rupees) | Yes, core business | No, low per unit, volume constrained | Structural limit, not a lever |

---

## 4. Market Sizing (iterative)

Follow this order. Do not skip ahead.

**Step 1: Restate inputs**
Give a concise structured summary of: the category, what is being estimated, what is known, what is uncertain, what needs to be answered next.

**Step 2: Big questions**
List the 3 to 7 biggest questions that determine market size or pricing.

**Step 3: Smaller questions**
Break each big question into smaller, answerable questions.

**Step 4: Buyer tables**
Build tables for each buyer segment. Pull segments from Customers.md.

| Buyer Segment | What They Need | Segment Size | What They Might Pay | Pricing Type | Market Benchmark |
|---|---|---|---|---|---|
| | | | | | |

**Step 5: Iterate**
Validate against public sources. Cross check against comparables. Adjust ranges as evidence comes in. Show both serviceable market size (total addressable pool) and capturable revenue pool. These are different numbers and should not be conflated.

**Example (manufacturing company) — JSL buyer table:**
| Buyer Segment | What They Need | Segment Size | What They Might Pay | Pricing Type | Market Benchmark |
|---|---|---|---|---|---|
| ITI welders (supply side) | SS welding certification | 82715 per year | 2000 to 5000 per cert | Per use | NSDC training benchmark |
| Polytechnic students (demand side) | SS specification awareness | 211500 per year | 0 (sponsored by JSL) | One time | AICTE partnership model |
| Fabrication shops (B2B buyers) | Premium SS material plus advisory | 480000 shops | 1.6 lakh per tonne plus 5000 per project advisory | Product plus Service | Steel industry avg |

---

## 5. Sensitivity Analysis

For each major revenue stream, show three scenarios:

| Revenue Stream | Base Case | Best Case | Worst Case | What Moves the Needle |
|---|---|---|---|---|
| | | | | |

What Moves the Needle: [the single variable that, if changed by 20%, shifts the outcome most. E.g., "Certification completion rate" or "Daily transaction volume per VLE"]

Rule for the agent: "For each scenario, state the key assumption that drives it. What Moves the Needle must be specific and actionable — not 'more marketing' but 'increase VLE certification completion rate from 15% to 30%'."

---

## Blind Spots and Assumptions (Revenue-Economics.md)

Flag: any revenue figure that is a company claim rather than independently verified. Any unit economics number without a labeled source. Any projection that has not been checked against actual reported revenue (hallucination check: if projections consistently miss actuals by more than 20 percent, flag the underlying data as unreliable).

## What Good Looks Like

- Every earning figure has both a per unit rate and a volume estimate
- The unit economics section shows the actual calculation, not just a stated conclusion
- The income math problem is specific and structural
- You can trace currency from customer to final recipient
- Market sizing shows both TAM/SAM and capturable pool separately
- Sensitivity analysis shows best/base/worst case with clear drivers
- Math validation passes: (per unit × volume) - fixed costs = net earning

## Human Evaluator Checkpoint

Before considering Goal 4 complete, ask yourself:

1. Run the math yourself. If the numbers do not add up to a plausible earning for the typical person or entity in this system, a revenue stream is missing or volume is overestimated. Fix it.
2. Can you trace one unit of currency from the customer to whoever actually keeps it? If not, you are missing a step in the flow.
3. Did you separate product pricing from service pricing? If they are mixed in one line without explanation, redo it.
4. Does every number have a source, a benchmark, or an explicit assumption label? If any number appears without a source, flag it in Blind Spots.
5. Does the sensitivity analysis reveal what actually moves the needle, or is it generic?
6. If the company has multiple customer segments, are unit economics shown per segment, not aggregated?
