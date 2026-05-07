---
name: contract-analysis
description: |
  Analyzes contracts for key terms, risks, and obligations.
  Use when user asks to "review this contract", "find the liability clause",
  "summarize the key terms", or "compare these two agreements".
license: MIT
metadata:
  author: Contoso Legal Tech
  version: "1.0"
---

# Contract Analysis

## What This Skill Does

Guides Cowork through systematic contract review, identifying:
- Key commercial terms (pricing, payment, renewal)
- Risk clauses (indemnification, limitation of liability, IP)
- Obligations and deadlines
- Non-standard or unusual provisions

## Workflow

1. Read the uploaded contract document
2. Extract and categorize all clauses
3. Flag risk areas with severity ratings
4. Generate a structured summary with recommendations

## Output Format

Present findings in a structured table:

| Clause | Category | Risk Level | Summary |
|--------|----------|------------|---------|
| Section 4.2-Indemnification | Risk | High | Unlimited indemnification for IP claims |
| Section 7.1-Term | Commercial | Low | 12-month auto-renewal with 30-day notice |
## Additional Resources

- **`references/clause-taxonomy.md`**-Full taxonomy of contract clause types
- **`references/risk-scoring.md`**-Risk scoring methodology and thresholds
- **`scripts/extract-clauses.py`**-Automated clause extraction utility