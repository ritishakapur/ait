# Customers.md — Goal 5

**What it is:** Who buys from this company, why they buy, and what happens after. This is the customer layer. Stakeholders.md references this file for customer segments rather than rebuilding them.

**Depends on:** Company.md, Products.md.

**Anti-pattern rule:** Examples show STRUCTURE, not content. Adapt the logic to your company's industry. Do not force PSU or rural examples onto a SaaS or consumer brand company.

---

## 1. Customer Segments Overview

List every customer segment the company serves. For each, state: who they are, what they buy, how much they pay, and how many there are.

**Output table:**
| Customer Segment | What They Buy | Avg Spend | Segment Size | Growth Trend |
|---|---|---|---|---|
| | | | | |

**Example (rural service company):**
| Customer Segment | What They Buy | Avg Spend | Segment Size | Growth Trend |
|---|---|---|---|---|
| Rural citizens | Aadhaar, PAN, bill payment | 5 to 50 rupees per txn | 50 crore rural population | Stable |
| Urban citizens | Same services, less frequently | 5 to 50 rupees per txn | 14 crore urban population | Growing slowly |
| Government agencies | Service delivery through CSCs | N/A (government pays CSC) | N/A | Growing |
| Private partners | Distribution through CSC network | Partnership fees | ~50 partners | Growing fast |

**Example (manufacturing company) — JSL customers:**
| Customer Segment | What They Buy | Avg Spend | Segment Size | Growth Trend |
|---|---|---|---|---|
| Large enterprises and OEMs | Raw steel coils and sheets | 1.6 lakh rupees per tonne | ~500 large buyers | Stable |
| Fabrication shops | Semi finished and finished goods | Varies by product | ~480,000 shops | Growing |
| End consumers (B2C) | Pressure cookers, utensils | 500 to 5000 rupees per product | Mass market | Growing |
| Architects and spec writers | Specification consulting (not yet offered) | N/A | ~50,000 professionals | Not yet served |

---

## 2. Customer Journey

How does a customer go from first contact to purchase to repeat use? Map the steps.

**How to build it:**
1. List each step in the customer journey
2. For each step, note: what happens, how long it takes, where friction occurs
3. Flag steps with high friction

**Example (rural service company):**
| Step | What Happens | Time | Friction |
|---|---|---|---|
| Citizen arrives at CSC | Walks in with physical documents | N/A | Needs to carry physical docs |
| VLE logs into portal | Struggles with login, may need to switch portals | 5 to 10 minutes | 17 plus logins |
| Service is processed | VLE fills form, runs biometric scan | 5 to 15 minutes | Biometric scanner fails often |
| Citizen receives receipt | Digital or physical receipt | N/A | Sometimes no receipt is given |

---

## 3. Customer Needs and Pain Points

What do customers actually need? What frustrates them? What do they complain about?

**How to build it:**
1. For each customer segment, list: what they need, what frustrates them, what they complain about
2. Use the capability framework from Stakeholders.md to categorize needs
3. Flag needs that are not currently served

**Example (rural service company):**
| Customer Segment | What They Need | What Frustrates Them | What They Complain About | Gap |
|---|---|---|---|---|
| Rural citizens | Fast, error free service | Biometric scanner fails, long waits | "Takes too long, VLE does not know what they are doing" | No quality assurance layer |
| Urban citizens | Same as rural, but less tolerant | Same friction, less patience | "Why is this so slow in a city?" | Same gap |
| Government agencies | Reliable service delivery | VLE capability varies wildly | "5 lakh centers but not all can deliver" | No readiness check before launching services |
| Private partners | Rural distribution reach | VLEs are not trained on their products | "VLEs do not know how to sell my product" | No AI localization or training layer |

---

## 4. Customer Retention and Churn Signals

What evidence shows that customers stay or leave? What signals indicate churn risk?

**How to build it:**
1. For each customer segment, find evidence of retention or churn
2. Note any signals of churn risk (declining usage, complaints, competitor migration)
3. Flag segments with unknown retention data

**Example (rural service company):**
| Customer Segment | Retention Evidence | Churn Risk Signal | Data Quality |
|---|---|---|---|
| Rural citizens | High demand for G2C services | None observed | Good |
| VLEs (as customers of CSC) | 5.4 lakh VLEs active | Zero churn data available, inference is high churn among low earners | Poor, no tracking |
| Private partners | 50 partners in 2025, growing | None observed | Good |

**Example (manufacturing company) — JSL customers:**
| Customer Segment | Retention Evidence | Churn Risk Signal | Data Quality |
|---|---|---|---|
| Large enterprises | Long term contracts, repeat orders | None observed | Good |
| Fabrication shops | Growing through JSA training | Price sensitivity, may switch to cheaper steel | Medium |
| End consumers (B2C) | Jindal Lifestyle brand loyalty | Competitor products at lower price | Medium |

---

## Blind Spots and Assumptions (Customers.md)

Flag: any customer segment built from company claims with no independent verification. Any retention or churn figure that is an estimate. Any segment that may have changed since the source data was published.

## What Good Looks Like

- Customer segments are distinct, not lumped together
- Customer journey shows real friction points, not idealized steps
- Customer needs use the capability framework
- Retention and churn signals use real data, not assumptions

## Human Evaluator Checkpoint

Before passing to Stakeholders.md (which references this file), ask yourself:

1. Are the customer segments distinct? If two segments could be merged, merge them. If a segment is missing, add it.
2. Does the customer journey show real friction, or did you write the idealized version from the company brochure?
3. Are the retention and churn signals based on actual data, or are they assumptions? If assumptions, flag them clearly.
4. Do the customer needs align with the stakeholder layers in Stakeholders.md? If not, reconcile them.
