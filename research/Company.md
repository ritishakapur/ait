# Company.md — Goal 1

**What it is:** A one-page factual snapshot of the company. Not analysis. Ground truth. Everything downstream (Industry, Competition, Products, Customers, Stakeholders, Technology, Revenue) builds on this file — a hallucination here compounds into every file after it.

**template to follow, comply and adhere with this, how i want answers**

**Agent Routing:**
- Agent A (Scope): Section 1 (Company Overview + Hierarchy + Subsidiaries)
- Agent B (Scope): Section 2 (Claim vs Evidence + Comparison Table + Core Tensions + Contradictions)
- Agent C (Scope): Sections 3-4 (Core Assets + Key Numbers)
- Agent D (Scope): Sections 5-6 (Org Tree + What's New)
- Merge Agent: Reconciles subsidiary data, verifies all sources (minimum 2 per data point), checks MECE, tags informal roles with confidence levels

1. Company Overview
The Company at a Glance

Name: Company Name  
What it does: One sentence — e.g., "Runs a network of rural service centers that help citizens access government services"  
When it started: Year  
How big: Employees, revenue range, countries/regions covered
Hierarchy (who owns whom, who influences whom)
Describe the power structure — not just the org chart, but who influences whom. Think: parent company as influencer, subsidiary relationships, informal power centers.

Example from CSC:
CSC e-Governance India Ltd (CSC-SPV) → govt-backed rural digital services platform
│
├── CSC-SPV (the operating company, under MeitY)
│   ├── Sets policy, manages Digital Seva Portal
│   └── Reports to MeitY; governed by a board with govt + industry reps
│
├── SDA (State Dedicated Agency) → state-level policy + implementation
│   ├── State govt agency responsible for CSC rollout
│   └── Has almost no visibility into ground-level VLE capability
│
├── DM (District Manager) → the middleman layer
│   ├── Onboards + manages VLEs in their district
│   └── The structural bottleneck: 400+ VLEs, 80+ calls/day
│
├── VLE (Village Level Entrepreneur) → the delivery point
│   ├── Micro-franchise operators running CSC centres
│   └── Earn via commission on 814+ products
│
├── Super-VLEs → peer trainers (not an official role — emerged organically)
│   └── Filling the training/support gap the system doesn't provide
│
└── Service Providers (the content layer)
    ├── Government schemes (Aadhaar, PAN, Ayushman)
    └── Private partners (Jio, Physics Wallah, IRCTC, Maruti Courier)
Name, industries, business model (B2B / B2C / marketplace / franchise / SaaS / PSU / etc.), year founded, scale (employee count, revenue range, core vs non-core market coverage).
Subsidiaries and related companies, for each one:
- Name
- When it started (year)
- How it was created (built from scratch, bought, or merged with another company)
- How much money it has or loses
- Where to find proof (at least 3 sources)
If the company has no subsidiaries, write: "No subsidiaries. The company operates as a single entity.
Treat this like an investor doing diligence on the company as an umbrella: upstream and downstream services, not just the headline business.
2. What They Claim vs. What the Evidence Shows
What the company actually is (not what the website says)
2-3 sentences describing the business model in plain language. Example: "CSC is not a government website. It is a franchise system. Local entrepreneurs (called VLEs) pay to run service centers. They earn money when citizens use their centers for things like passport applications, bill payments, and certificates."


Purpose: Catch the gap between the company's story and the evidence. This is where you find the things the company says one thing but does another.

2.1 Comparison Table
4+ rows. Each row must show real tension, not just a fact, but a contradiction between what the company claims and what the data proves.
Format:
| What the company claims | What the evidence actually shows| [Claim] | [Evidence]

Rule for the agent: "If every row agrees, dig deeper. A table where claims and evidence match means you didn't look hard enough."

2.2 Core Tensions
This section shows where the company's actions contradict its stated priorities. Not lies — deeper stuff. Where the company is pulling in two directions at once.

Format:
**Tension 1: [Name]**
One-sentence description of the tension.
- Side A: What the company says it prioritizes
- Side B: What the company actually does
- Why it matters: What this tension creates (waste, confusion, lost opportunity)
- Evidence: [Specific example with source]

Rule for the agent: "Find 2-4 tensions. Each must be specific to THIS company. Not 'every company has this problem' — 'this company has this problem because of X specific action.'"

2.3 Contradiction Detection
This section catches places where the company (or its leaders) contradict themselves. Not to call them liars, because contradictions reveal where the company's thinking is confused, and that's genuinely interesting.

Format:
**Type: [Contradiction Type]**
- What they said: [Quote or reference]
- What they did/said later: [Quote or reference]
- What this reveals: [What tension this shows in their thinking]

Rule for the agent: "Find 1-3 contradictions. If you can't find any, the company's public messaging is unusually consistent , flag this as a note, not a failure."
—
Reference Examples
Comparison Table
Relevant Examples:
- Claim: "CSC is a government service portal" → Evidence: "It's a micro-franchise business — VLEs are entrepreneurs earning commission, not government employees"
- Claim: "814 services available" → Evidence: "Only a handful are actually used regularly — most sit unused because VLEs have no guidance on what to prioritize"

Core Tensions
Examples from CSC:
**Tension 1: Adding services vs helping VLEs focus**
CSC keeps adding new services but gives VLEs no system to decide which ones to prioritize.
- Side A: CSC says it wants VLEs to earn more (₹30,000/month target)
- Side B: CSC adds 814 services across 80+ categories with no prioritization system
- Why it matters: VLEs waste time on low-commission services instead of climbing the certification ladder
- Evidence: CSC pushes Jio recharges (1.6% margin), Physics Wallah courses, Maruti Courier, and insurance — all at once, with no guidance on which to focus on first

Examples from JSL:
**Tension 1: Positioning as a steel company vs building an ecosystem**
JSL says it's a stainless steel manufacturer but is actively building training, certification, and marketplace businesses.
- Side A: JSL's headline business is selling steel (₹40,182 cr revenue)
- Side B: JSL has invested in JSA (training), Saathi Pragati app (digital platform), Stainlessmart (retail), and partnerships with IITs/polytechnics
- Why it matters: The ecosystem plays (training, marketplace, data) could eventually rival material revenue, but nobody tracks them separately
- Evidence: JSA trained 700+ students across 21 institutions in FY26, but this is buried inside JSL's annual report, not reported as a separate business unit

Contradiction Detection
	The 4 Types:

Type
What it means	
Example
Says X early, says not-X later


Their thinking changed mid-conversation or between statements
"We're focusing on VLE income growth" (2023) → "We're adding 50 new private partners" (2025) — adding partners doesn't directly grow VLE income
Advocates X but does not-X


They say one thing, do another
CSC promotes "democratizing AI for Bharat" but AI training is only available to VLEs, not the 15 crore citizens who could benefit
Claims X is important but never mentions it again


They say something matters, then never talk about it
CSC CEO says "VLE retention is our biggest challenge" but none of the 2025-26 initiatives directly address why VLEs quit
Gives advice that contradicts their own path
Their recommendations don't match what they actually do
CSC tells VLEs to "diversify income streams" but the certification ladder only rewards focusing on one path at a time (Level 1 → Level 2 → Level 3)




3. Core Assets
What the company owns: customer base, infrastructure,I P, partnerships, licenses, data.

### Customer Relationships
What it is: [Plain-language explanation]
Example from CSC: [5.4 lakh VLEs who depend on the platform for their income — they can't easily switch to another platform]
Example from JSL: [Long-term contracts with auto companies like Honda and appliance makers who specify Jindal steel in their designs]
What to look for: [How many customers, how loyal, how hard is it to leave]
### Infrastructure
What it is: [Physical or digital assets that competitors can't easily build]
Example from CSC: [5 lakh service centers across 785 districts — a private company would need 10+ years to build this]
Example from JSL: [Manufacturing plants in Raigarh and Jharsuguda with combined capacity of 2.3 million tonnes per year]
What to look for: [Buildings, servers, devices, networks — things that cost money and time to create]
### Data and Intellectual Property
What it is: [Knowledge, research, or proprietary information that competitors don't have]
Example from CSC: [Transaction data from 373 lakh monthly transactions — nobody else has this view of rural digital activity]
Example from JSL: [70+ years of stainless steel research, material testing, and application engineering know-how]
What to look for: [Patents, research, proprietary databases, trade secrets]
### Partnerships
What it is: [Exclusive or strategic deals that give this company an advantage]
Example from CSC: [Partnerships with Jio, Physics Wallah, IRCTC, Maruti Courier — private brands using CSC for rural reach]
Example from JSL: [Partnerships with IITs, NITs, polytechnics, and HSBTE for curriculum development]
What to look for: [Government contracts, private partnerships, distribution deals, academic collaborations and more..]
Rule for the agent: "Not every company has all 5. If one doesn't apply, skip it. Don't force it. Better to have 3 strong assets than 5 weak ones."

4. Key Numbers That Define the Business
[Short intro: "These are the numbers that matter for THIS company. Not industry averages — actual numbers that show how big, fast, and healthy this business is. Pick the metrics that fit this company's type."]
### How Many People Use It?
What this tells you: Size of the user base, customer base, or network
Example from CSC: 5.4 lakh VLEs, 5,01,153 functional centers, 373 lakh monthly transactions
Example from JSL: 2.373 million tonnes of steel produced, serving customers across 50+ countries
What to look for: Users, customers
### How Much Money Does It Make?
What this tells you: Revenue, transaction volume, or earning potential
Example from CSC: Revenue from government funding + private partnerships — exact figure from annual report
Example from JSL: ₹40,182 cr in FY24 revenue, with ₹28,000 cr from raw materials alone
What to look for: Total revenue, revenue by segment, growth year-over-year
### How Fast Is It Growing?
What this tells you: Is this company expanding, shrinking, or staying flat?
Example from CSC: Added 50,000 new VLEs in 2025, expanded to 4 districts that previously had zero CSCs
Example from JSL: Stainless steel market growing at ~10% CAGR, JSL maintaining ~50% market share
What to look for: New partnerships, new products, new markets, employee growth
### How Efficient Is It?
What this tells you: Is this company wasting money or using it well?
Example from CSC: 373 lakh transactions / 5.4 lakh VLEs = ~69 transactions per VLE per month — is this high or low?
Example from JSL: ₹40,182 cr revenue from 2.373 million tonnes = ~₹1.69 lakh per tonne — how does this compare to competitors?
What to look for: Revenue per employee, cost per transaction, margin percentages
### What's the Market Position?
What this tells you: Is this company the leader, challenger, or niche player?
Example from CSC: Covers 785 districts, ~100% GP coverage in most states — near-monopoly in rural digital services
Example from JSL: 49% of stainless steel tonnage in India, 52% of stainless revenue — clear market leader
What to look for: Market share %, rank vs competitors, unique coverage areas
Rule for the agent: "Every number must have a source. If you can't find a source, write 'Estimated: number — based on logic' and flag it in Blind Spots. Don't make numbers up."

5. Organizational Tree
Visual hierarchy of how the company is structured. Must include informal/organic roles that emerged outside the official org chart (e.g., power users, informal trainers) — not just the formal chart.
[You will add the "parents as influencers" example here later. For now, include: formal hierarchy + informal power centers + anyone who influences decisions without being on the org chart.]

6. What's New in the Last 12–18 Months
Strategic pushes, new partnerships, new products, narrative shifts, policy changes. Flag anything older than 18 months elsewhere in the file as potentially outdated.

Blind Spots & Assumptions (Company.md)
List every claim in this file made on a single source, every number that's an estimate rather than a sourced figure, and anything that could have changed since the source's publish date.
What Good Looks Like
Every claim is backed by a number or a source (minimum 2 sources per data point).
The comparison table has real tension, not agreement dressed up as a table.
Key numbers are specific to this company, not industry-average filler.
The org tree includes informal roles.
You can state the business model in one sentence using only data from this file.
Human/Evaluator Checkpoint
Before moving to Industry.md, ask yourself:

1. Would a CEO challenge any claim here? If yes, go back and verify.
2. Is every number specific to THIS company, not a generic industry average?
3. Does the comparison table show real tension (not just agreement dressed up as a table)?
4. Are all informal roles tagged with confidence levels, not claimed as verified facts?
