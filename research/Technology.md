# Technology.md — Goal 7

**What it is:** The invisible systems that make the company work. Not the tech stack in the marketing sense, but the layers of infrastructure that nobody talks about but everything depends on. This is the operating stack.

**Depends on:** Company.md, Products.md, Stakeholders.md.

**Anti-pattern rule:** Examples show STRUCTURE, not content. Adapt the logic to your company's industry. Do not force PSU or rural examples onto a SaaS or consumer brand company.

**Agent Routing:**
- Agent A (Scope): Section 1 (Foundational Stacks)
- Agent B (Scope): Section 2 (Stack Interactions)
- Agent C (Scope): Sections 3-4 (Fragmentation Count + Technology Gaps)
- Merge Agent: Validates component counts, checks stack connections, verifies fragmentation reveals actual complexity

---

## 1. Foundational Stacks

Identify 3 to 5 foundational stacks per company. Name each stack clearly. For each stack, define: what it is, how it applies to this company, what is broken, how many components make it up.

**Output table:**
| Stack Name | What It Is | How It Applies to This Company | What Is Broken | Component Count |
|---|---|---|---|---|
| | | | | |

**Example (rural service company):**
| Stack Name | What It Is | How It Applies to This Company | What Is Broken | Component Count |
|---|---|---|---|---|
| Portal Layer | The login and dashboard where users access services | 17 plus separate portals, each service redirects to a different government site | Fragmented, no unified login | 17+ portals |
| Certification Layer | The credentialing system that gates services | 4 level architecture, but invisible to new VLEs | Nobody explains the ladder | 4 levels, no display |
| Management Layer | The governance and support structure | DMs overwhelmed with 80 plus calls per day, SDAs are policy only | DMs are the bottleneck | DM portal, WhatsApp, phone |
| Transaction Layer | What actually gets processed | 373 lakh transactions per month, about 74 per VLE per month | Very low per VLE, no optimization | DSP, non DSP services |

---

## 2. Stack Interactions

How do stacks connect? Which enables which? Which breaks which? Where information flows and where it does not?

**How to build it:**
1. For each pair of stacks, state: enables, breaks, or neutral
2. Note where information flows between stacks
3. Note where information is blocked between stacks

**Example (rural service company):**
| Stack A | Stack B | Relationship | Information Flow | Information Blocked |
|---|---|---|---|---|
| Certification Layer | Transaction Layer | Enables | Cert status determines which services VLE can access | Cert status not visible on portal |
| Management Layer | Portal Layer | Breaks | DMs blast WhatsApp messages about new services | DMs do not know which VLEs are certified |
| Portal Layer | Transaction Layer | Enables | Portal is where transactions happen | 17 logins cause transaction drop off |

---

## 3. Fragmentation Count

How many separate tools, portals, or logins make up each stack? This number reveals complexity.

**How to build it:**
1. Count the number of separate components per stack
2. Note the average time spent switching between them
3. Flag any stack with more than 5 components as high complexity

**Example (rural service company):**
| Stack | Component Count | Avg Time Spent Switching | Complexity |
|---|---|---|---|
| Portal Layer | 17+ | 2 hours per day | High |
| Certification Layer | 4 | N/A | Medium |
| Management Layer | 3 (portal, WhatsApp, phone) | 80 calls per day | High |
| Transaction Layer | 2 (DSP, non DSP) | N/A | Low |

---

## 4. Technology Gaps

What technology is missing that would unlock value? What technical debt is holding the company back?

**How to build it:**
1. List technology that is missing but needed
2. List technical debt that is holding the company back
3. Rate each as High, Medium, or Low priority
4. Note the impact of fixing each gap

**Example (rural service company):**
| Missing Technology | Impact of Fixing | Priority |
|---|---|---|
| Unified login portal | Reduces 2 hours daily switching time to minutes | High |
| Certification visibility on portal | VLEs can see which services they can deliver | High |
| DM dashboard with VLE certification data | DMs can target training instead of blasting everyone | Medium |
| Commission payment tracker | VLEs can see why payments are stuck | High |

---

## Blind Spots and Assumptions (Technology.md)

Flag: any stack described from marketing material alone with no independent verification. Any component count that is an estimate. Any technology gap that is assumed rather than observed.

## What Good Looks Like

- 3 to 5 stacks identified, not 2 and not 10
- Each stack has a clear name and one sentence definition
- The "what is broken" column is specific, not generic
- The fragmentation count reveals actual complexity
- Stack interactions are shown clearly

## Human Evaluator Checkpoint

Before moving to the next file, ask yourself:

1. Can a new person joining this company understand how everything connects by reading just this file? If they still need to ask how X talks to Y, clarify the stack connections.
2. Are the fragmentation counts real numbers, or estimates? If estimates, label them clearly.
3. Do the stack interactions reveal something the company does not officially acknowledge? If not, dig deeper.
4. Are the technology gaps specific and actionable, or generic "we need better tech"?
