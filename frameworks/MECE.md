# MECE.md — How to Think Mutually Exclusive, Collectively Exhaustive

## What Is MECE?
MECE is a way of organizing information so that:
- **Mutually Exclusive** — No overlap between categories (each item belongs to exactly one category)
- **Collectively Exhaustive** — Nothing important is missing (all items are accounted for)

## Why It Matters
Without MECE, your analysis will have:
- Gaps (things you missed)
- Overlaps (things you counted twice)
- Confusion (where does X belong?)

## How to Apply MECE

### Step 1: Choose a Dimension
Pick ONE way to slice the problem:
- By customer segment (B2B, B2C, B2G)
- By geography (North, South, East, West)
- By product category (A, B, C)
- By value chain stage (upstream, midstream, downstream)
- By capability level (Simple, Functional, Judgment, Coordination, Higher order)

### Step 2: Check for Overlap
Ask: "Can something belong to more than one category?"
- If yes → adjust your categories
- If no → move on

### Step 3: Check for Gaps
Ask: "Is there anything that doesn't fit into any category?"
- If yes → add a category or adjust definitions
- If no → you're MECE

### Step 4: Apply Consistently
Use the same MECE structure across related analyses so things connect.

## Examples

### Good MECE (Customer Segments)
| Segment | Description |
|---|---|
| Rural citizens | Individuals in rural areas using CSC services |
| Urban citizens | Individuals in urban areas using CSC services |
| Government agencies | Government bodies using CSC for service delivery |
| Private partners | Companies using CSC for distribution |

Each customer belongs to exactly one category. All customers are covered. MECE.

### Bad MECE (Customer Segments)
| Segment | Description |
|---|---|
| Rural citizens | People in villages |
| Poor citizens | People with low income |
| First-time users | People using CSC for the first time |

Overlap: A rural citizen can also be poor. A rural citizen can also be a first-time user. Not MECE.

## When MECE Doesn't Work
MECE is a tool, not a religion. Sometimes categories naturally overlap (e.g., "high-value" and "frequent" customers). In those cases:
- Acknowledge the overlap explicitly
- Use a different structure (e.g., a 2x2 grid instead of mutually exclusive categories)
- Don't force MECE where it doesn't fit

## What Good Looks Like
- Every item in your analysis fits into exactly one category
- Every important item is in a category
- Anyone reading your analysis can understand why each item is where it is
