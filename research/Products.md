# Products.md — Goal 4

**What it is:** What the company actually sells, how it is priced, and where the gaps are. This is not a marketing brochure. This is the product catalog as it actually exists in the market, including what is missing.

**Depends on:** Company.md, Industry.md, Competition.md.

**Anti-pattern rule:** Examples show STRUCTURE, not content. Adapt the logic to your company's industry. Do not force PSU or rural examples onto a SaaS or consumer brand company.

**Agent Routing:**
- Agent A (Scope): Sections 1-2 (Catalog + Tiering)
- Agent B (Scope): Section 3 (Product Market Fit)
- Agent C (Scope): Section 4 (Gaps/Whitespace)
- Merge Agent: Verifies pricing sources, checks discontinued products included, validates lifecycle stage tags

---

## 1. Product Catalog Overview

List every product or service the company currently offers. Group by category. For each, state: what it is, who it serves, and the pricing model.

**Output table:**
| Product/Service | Category | Who It Serves | Pricing Model | Status | Lifecycle Stage |
|---|---|---|---|---|---|
| | | | | Active/Launched/Discontinued/Sunset/Pivoted | Emerging/Growing/Mature/Declining |

**Example (rural service company):**
| Product/Service | Category | Who It Serves | Pricing Model | Status | Lifecycle Stage |
|---|---|---|---|---|---|
| Aadhaar update | G2C service | Citizens | Commission based (5 to 50 rupees) | Active | Mature |
| LIC insurance | Financial service | Citizens | Commission based (15 to 50 percent of premium) | Active | Growing |
| Physics Wallah courses | EdTech referral | Citizens | Commission based (50 to 500 rupees per registration) | Active | Emerging |
| Passport Seva Kendra | G2C service | Citizens | Commission based | Active (launched 2025) | Emerging |
| AI training program | Skilling | VLEs and citizens | Free (government funded) | Active (launched 2025) | Emerging |

---

## 2. Product Tiering and Pricing Structure

How is the product portfolio organized? By price tier? By customer segment? By complexity? Show the structure.

**How to build it:**
1. Identify how the company organizes its products (by price, by customer, by complexity, by use case)
2. Show the tiers or categories
3. For each tier, note: what it includes, who it targets, and the price range
4. Flag any tiers that are missing or weak

**Example (manufacturing company) — JSL product tiers:**
| Tier | What It Includes | Who It Targets | Price Range |
|---|---|---|---|
| Raw materials | Steel coils, sheets at industrial scale | Large enterprises, OEMs | 1.6 lakh rupees per tonne |
| Semi finished | Processed steel, cut to size | Fabricators, service centers | 1.8 lakh rupees per tonne |
| Finished goods | Pressure cookers, utensils, railings | B2B and B2C buyers | Varies by product |
| Advisory and consulting | Specification help, lifecycle cost analysis | Architects, spec writers | Not currently offered |

---

## 3. Product Market Fit Signals

What evidence shows that products are actually being used and valued? Not what the company claims, what the data shows.

**How to build it:**
1. For each major product category, find evidence of adoption (usage numbers, growth, retention)
2. Flag products that are launched but show low adoption
3. Flag products that show strong adoption but are not being scaled
4. Note any products that have been discontinued and why

**Example (rural service company):**
| Product Category | Adoption Evidence | Growth Trend | Flag |
|---|---|---|---|
| G2C services | 373 lakh monthly transactions | Stable | No flag |
| Insurance brokerage | Only VLEs with RAP cert can sell | Growing slowly | Low adoption due to certification barrier |
| EdTech referrals | Added PW and Sarkari Pariksha in 2025 | Growing fast | No tracking system to measure actual signups |
| AI training | Announced for 10 lakh people in 2025 | Unknown | No usage data yet |

---

## 4. Product Gaps and Whitespace

What is missing from the product catalog? What do customers need that the company does not offer? What do competitors offer that the company does not?

**How to build it:**
1. List products that customers need but the company does not offer
2. List products that competitors offer but the company does not
3. Rate each gap as High, Medium, or Low priority
4. Note why the gap exists (structural, strategic, or accidental)

**Example (rural service company):**
| Missing Product | Who Needs It | Why It Is Missing | Gap Priority |
|---|---|---|---|
| Unified service dashboard | VLEs | No prioritization system exists | High |
| Certification tracker | VLEs | CSC Academy is disconnected from income ladder | High |
| Commission payment visibility | VLEs | Wallet system has no tracking | High |
| AI powered service recommendations | Citizens and VLEs | AI push is new, no product built yet | Medium |
| Peer support network | VLEs | Relies on WhatsApp groups, not formalized | Medium |

---

## Blind Spots and Assumptions (Products.md)

Flag: any product listed without evidence of current availability. Any pricing figure that is an estimate rather than reported. Any product that may have been discontinued since the source data was published.

## What Good Looks Like

- Product catalog is complete, not just the headline products
- Pricing structure is clear and specific
- Product market fit signals use real data, not claims
- Product gaps are specific, not generic "we need more products"
- Lifecycle stage is tagged for every product
- Discontinued/sunset products are noted with reason

## Human Evaluator Checkpoint

Before moving to the next file, ask yourself:

1. Does the product catalog include discontinued products? If a product was launched and shut down, note it with the reason.
2. Are the pricing figures sourced, or are they estimates? If estimates, label them clearly.
3. Do the product gaps reveal something the company does not officially acknowledge? If not, dig deeper.
4. Are the product market fit signals based on actual usage data, or just launch announcements?
5. Is the lifecycle stage tag applied consistently across all products?
