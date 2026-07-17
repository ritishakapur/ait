# Stakeholders.md — Goal 6

**What it is:** Every person or group the company interacts with, mapped by their role in the system, not by org chart. This includes customers (already detailed in Customers.md, which this file should reference rather than rebuild) plus everyone else: employees, informal power users, regulators, suppliers, partners, capital providers. This is the human dynamics layer that reveals what actually drives or breaks the business.

**Depends on:** Company.md.

**Note:** This file holds the master definition of the capability framework referenced by Products.md, Competition.md, and Customers.md. Define it once here. The other files should link back rather than redefine it.

**Agent Routing:**
- Agent A (Scope): Section 0 (Capability Framework)
- Agent B (Scope): Section 1 (Map Universe Pass 1)
- Agent C (Scope): Sections 2-4 (Groups, Per Layer, Cross Layer Tension)
- Merge Agent: Runs MECE check, tests 2x2 grid, verifies no stakeholder counted twice, validates cross-references

---

## The Capability Framework

This framework sorts what people need by how complex the task is. Think of it like sorting tasks from easy to hard: basic info gathering, doing tasks, making judgments, coordinating groups, and dealing with people and relationships.

| Tier | What It Means | Verbs | What It Looks Like | Examples |
|---|---|---|---|---|
| Simple | Basic info work | retrieve, classify, compare, summarize, draft | Pulling data, sorting items, comparing two options, generating a first draft | Search results, comparison tables, executive summaries |
| Functional | Doing tasks | create, schedule, call, transact, track | Building something from scratch, setting timed actions, processing payments, monitoring activity | Form generation, appointment booking, payments, dashboards |
| Judgment | Making decisions | monitor, evaluate, test, optimize, flag | Watching systems in real time, assessing quality, running tests, finding problems | Quality monitoring, performance scoring, A/B testing, anomaly detection |
| Coordination | Managing groups | remind, warn, route, escalate, sync | Keeping people on track, alerting to risk, directing work to the right person, syncing across teams | Deadline reminders, risk alerts, task routing, cross team status updates |
| Higher order | Dealing with people | negotiate, reassure, reward, inspire, mentor | Resolving conflict, building trust, designing incentives, motivating action, guiding growth | Stakeholder negotiation, trust campaigns, incentive design, mentorship |

---

## 1. Map the Universe (Pass 1)

This section is about finding every stakeholder in the system. Do not skip anyone important. Do not count anyone twice.

### Step 1: The Flow from Start to Finish

Trace the value from start to finish. For each node, state what it does to the value: extracts, moves, transforms, consumes, or recycles. If a node does none of those five things, it is not in the chain.

**How to build it:**
1. Start at the deepest upstream input (raw materials, funding, raw data, whatever the business needs first)
2. Move through every stage until you reach the end user and what happens after (disposal, recycling, renewal)
3. For each stage, write: the node name, what it does to the value, and who typically occupies it (types of players, not names yet)

**Example (rural service company):**
Government funding → CSC SPV → SDA → DM → VLE → Citizen → Service completion
Each node transforms value: funding becomes policy becomes onboarding becomes delivery becomes service.

**Example (manufacturing company):**
Raw steel coil → Manufacturer → Processing center → Distributor → Fabricator → End product (railing, kitchen, bridge component) → Scrap/Recycling

### Step 2: People Who Affect the Business Without Touching It

These are people who do not touch the product but affect whether the business can operate. Think: regulators who approve services, capital providers who fund growth, talent pipelines who supply workers, public perception that shapes demand.

**How to build it:**
1. List every group that does not touch the product but affects the business
2. For each group, state what power they hold (approval, funding, talent, perception)
3. Adapt this list to the company's actual sector

**Example (rural service company):**
MeitY (regulator), NSDC (talent pipeline and funder), state governments (capital providers for SDA operations), citizens (public perception)

**Example (manufacturing company):**
IITs (talent pipeline), NBFCs (capital providers), architects and spec writers (influence demand), industry bodies like the Indian Institute of Welding (industry structure)

### Step 3: Check That Everyone Is Counted Once

MECE means Mutually Exclusive, Collectively Exhaustive. "Mutually exclusive" means no stakeholder appears in two roles who should be separate. "Collectively exhaustive" means you have not missed anyone important. Check both.

**How to build it:**
1. Review your list. Is any stakeholder playing two roles who should be split into two entries? Fix it.
2. Review your list again. Is any important stakeholder missing? Add it.
3. Verify against the real flow of the business, not your assumptions.

### Step 4: Output the Full Map

Write the final map. Chain left to right. Orbit stakeholders labeled separately. Nothing enriched yet.

**Output format:**
```
Vertical Chain (left to right):
Node 1 → Node 2 → Node 3 → Node 4 → Node 5

Horizontal Orbit (separate):
Orbit Stakeholder 1: [role/power]
Orbit Stakeholder 2: [role/power]
Orbit Stakeholder 3: [role/power]
```

---

## 2. Build the Groups That Matter (Pass 2)

This section is about building detailed profiles for the stakeholders who have the biggest impact on the business. Typically 3 to 7 layers, including the relevant customer segments already built in Customers.md.

### Step 1: Find What Drives Different Behavior

Do not segment by outcome ("good users vs bad users") or demographics ("rich vs poor"). Segment by driver, which is the underlying force that produces the outcome.

**How to build it:**
1. Propose 4 to 6 candidate driver axes for this stakeholder group
2. For each axis, write the two extreme poles as one line of behavior
3. Select the 2 most independent and most explanatory axes
4. Explain why you rejected the others

**Example (VLEs in rural services):**
Axis 1: "Quick cash seeker" vs "Long term builder" — some want immediate commission, others invest in certifications for future income
Axis 2: "Tech comfortable" vs "Tech resistant" — some embrace digital tools, others prefer phone and WhatsApp
Rejected axis: "Rural vs urban" — does not explain behavioral variance, only geographic location

### Step 2: Describe the Two Extremes

Rewrite both poles as vivid, specific behaviors you could observe. Not "high income" because that is abstract. Instead: "checks wallet balance before every transaction" vs "buys a second device to handle more services."

### Step 3: Build the Grid

If you chose 2 axes with 2 poles each, you get a 2 by 2 grid with 4 cells. Label every cell. If a cell is empty or implausible, merge it with another cell and explain why.

**Example (VLEs):**
| | Quick cash seeker | Long term builder |
|---|---|---|
| Tech comfortable | "Digital hustler" — uses app to maximize daily transactions | "Certification climber" — invests in Level 2 and Level 3 certs for higher commission |
| Tech resistant | "Phone only operator" — relies on calls and WhatsApp, avoids portals | "Gradual adopter" — slowly picks up tools when DM trains them |

### Step 4: Enrich Each Group

For each surviving group, give:
- A memorable name (not clinical like "Segment A")
- A one line essence
- Defining behavior (observable)
- Underlying driver (their "why")
- What they can do to help or hurt the business
- What they need from the business
- The lever that shifts them

**Example (Certification climber):**
- Essence: Invests in credentials to unlock higher commission tiers
- Defining behavior: Spends weekends studying for IIBF and UIDAI exams
- Underlying driver: Long term income growth, not quick cash
- What they can do: Stay and grow, or leave if they cannot see a path forward
- What they need: Clear certification ladder, exam reminders, income projections per level
- Lever that shifts them: Show them the 3000 to 15000 income jump after Level 2 cert

### Step 5: Test Against Real People

Test your groups against 5 real or plausible people. If someone does not fit cleanly, either create a new group, blend two groups, or redraw your axes.

---

## 3. Per Layer Detail

For each stakeholder layer, build the following.

### Who They Are

Give them a name, age, location, education, income or economics, tools they use daily, and motivation. Motivation is the key. Are they driven by money, status, mission, fear, convenience, or growth? Not a job title. A person.

**Example:**
Ramesh, 34, Bihar
Education: 12th pass, self taught on CSC portal
Income: 4000 to 6000 per month from G2C services
Tools: Basic Android phone, Firefox browser, Mantra fingerprint scanner
Motivation: Money — wants to earn 15000 per month but does not know which certifications to get

### What They Actually Do Day to Day

Not their job description. What they actually spend their time on. What they complain about. What frustrates them.

**Example:**
Spends 2 hours a day switching between 5 different portals trying to process one citizen's application. Complains that the biometric scanner fails 3 times out of 5.

### What Is Implied But Not Said

Behaviors, workarounds, self organized solutions that reveal unmet needs. Things not in any official document.

**Example:**
VLEs form WhatsApp groups to share which services are paying well this week. The company does not know this exists.

### Needs Table

Use the capability framework from Section 0. For each need, mark an X if there is no current product or system serving it. Aim for at least 2 gaps per layer.

| What They Need | Capability Type | Current Products or Systems That Serve It | Gap |
|---|---|---|---|
| Know which services to prioritize | Simple (retrieve, classify) | 814 services on portal, no map | X |
| Track certification progress | Functional (track, schedule) | CSC Academy (disconnected) | X |
| Get paid reliably | Functional (transact) | CSC wallet system | X Payments stuck, no visibility |
| Learn how to use new services | Functional (create, schedule) | DM WhatsApp blasts | X No targeting |

### Tension with Other Layers

What Layer A needs vs. what Layer B delivers. Where the system breaks between stakeholders.

**Example:**
VLEs need clear service prioritization (Simple capability). DMs blast WhatsApp messages to everyone about every new service (no filtering). The system breaks because VLEs cannot act on information they cannot use.

---

## 4. Cross Layer Tension Map

This table shows where two stakeholder layers actively conflict. Not just "they have different needs." Where Layer A's need directly breaks Layer B's ability to deliver.

| Layer A | Layer B | The Tension | What Breaks |
|---|---|---|---|
| VLEs | SDAs | VLEs need certification visibility; SDAs assume 5 lakh centers equal 5 lakh capable delivery points | SDAs launch services VLEs cannot deliver |
| DMs | VLEs | DMs measured on transaction volume; VLEs need income growth | DM pushes any service that moves numbers, not what earns VLEs money |

---

## Blind Spots and Assumptions (Stakeholders.md)

Flag: any stakeholder layer built only from official documentation with no independent verification of what is implied but not said. Any layer where the persona feels generic rather than evidence based.

## What Good Looks Like

- Each layer has a named persona, not a job title
- The needs table uses the capability framework consistently
- At least 2 gaps per layer marked with X
- What is implied but not said reveals something the company does not officially acknowledge
- Cross layer tension is visible, not just described
- The map includes informal or organic roles, not just official structure

## Human Evaluator Checkpoint

Before moving to the next file, ask yourself:

1. Would each stakeholder layer say "yes, that is me" if you showed them this map? If any layer would say "no, that is not what we are like," something is missing. Go back.
2. Are the needs tables using the capability framework consistently, or did you mix up Simple and Functional needs?
3. Does the "implied but not said" section reveal something the company does not officially acknowledge, or did you just restate what is already in their documents?
4. Are the cross layer tensions real conflicts, or just different needs? A real tension means Layer A's need directly breaks Layer B's ability to deliver.
