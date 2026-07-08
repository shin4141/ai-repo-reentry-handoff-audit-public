# Accident Menu

These are not blame labels. They are common failure patterns in AI-assisted repo operations.

## 1. Pushed-is-Done Accident

The repo is treated as complete because commits reached the remote.

Takeaway: remote state is necessary but not sufficient; completion needs a re-entry surface check.

## 2. README Mirage Accident

The README looks complete internally but does not answer the first-time reader's boundary questions.

Takeaway: the README should show what this is, what this is not, and what can happen next.

## 3. Handoff Orphan Accident

The handoff exists, but no obvious repo entry point routes future sessions to it.

Takeaway: a handoff needs a visible path from the repo's restart surfaces.

## 4. Green Badge Accident

A passing badge or manifest is mistaken for user-facing readiness.

Takeaway: green checks should be interpreted against the current gate ledger.

## 5. Context Tomb Accident

Critical decisions are buried in chat, local memory, or old notes rather than living in the repo.

Takeaway: decisions needed for restart should be promoted into durable repo surfaces.

## 6. False Completion Accident

Work is declared done before the actual completion condition has been verified.

Takeaway: define the completion line before declaring done.

## 7. Agent Drift Accident

A future AI continues from stale or adjacent instructions and misses the active boundary.

Takeaway: current gate, allowed actions, and blocked actions should be explicit.

## 8. Public Surface Mismatch Accident

Public-facing text implies a different state than the current handoff or gate ledger.

Takeaway: first-screen public signals should be audited against the current gate.

## 9. No Return-to-Human Accident

The repo tells an AI what to do but does not say when to stop and return to the operator.

Takeaway: every audit result should include a do-not-continue boundary.

## 10. Restart Surface Gap Accident

The repo has useful audit assets, but a future session cannot easily discover them.

Takeaway: after each audit, update the surfaces a future session is likely to read first.
