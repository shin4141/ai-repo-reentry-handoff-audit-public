# Re-entry Maturity Rank

This rank is a re-entry maturity signal for AI-assisted repo operations.

It is not a safety guarantee, legal review, medical review, security audit, code correctness review, or implementation approval.

## Rank Scale

- S - Next AI can restart immediately from repo surface
- A - Restartable with minor clarification
- B - Works if the original operator remembers context
- C - Likely to cause handoff / re-entry friction
- D - Human reconstruction required
- BLOCK - Do not continue from current state

## Default Result Fields

- Rank
- Detected accident patterns
- What worked
- Missing closure
- One delta to reach the next rank
- Do Not Continue Boundary
