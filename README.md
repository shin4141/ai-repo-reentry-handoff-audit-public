# AI Repo Re-entry / Handoff Audit

Have you ever let an AI agent build something, then opened the next chat and realized the repo could not explain what was actually done, what was still blocked, or what the next AI should not touch?

This manual audit checks whether your AI-assisted repo can be safely restarted by the next AI, without relying on your memory.

Find your AI repo's Re-entry Maturity Rank.

![Manual MVP](https://img.shields.io/badge/Manual_MVP-HUMAN_REVIEW-lightgrey)
![Human Review](https://img.shields.io/badge/Human_Review-YES-lightgrey)
![Automation](https://img.shields.io/badge/Automation-NO-lightgrey)
![API / Scraping](https://img.shields.io/badge/API_%2F_Scraping-BLOCKED-red)
![Safety Guarantee](https://img.shields.io/badge/Safety_Guarantee-NO-lightgrey)
![License / Re-use](https://img.shields.io/badge/License_%2F_Re--use-HOLD-yellow)

A manual repo re-entry / handoff audit for agentic codebases, handoff files, and public surfaces.

It checks whether a future AI or operator can restart from the repo surface without reconstructing hidden chat context, stale handoffs, or unclear public/private boundaries.

## 1-Minute Self-Check

If a new AI opened your repo right now, could it answer these?

1. What is already done?
2. What is still HOLD or BLOCK?
3. Who owns the next action?
4. What must not be touched?
5. Where is the restartable handoff?

If any answer is unclear, your repo may have a re-entry gap.

## Example Result

```text
Rank: B
Detected patterns: README Mirage, Handoff Orphan
One delta: Add a visible Current Gate + Next Owner + Do Not Continue Boundary block.
```

## What You Get

- Re-entry Maturity Rank
- Detected Accident Patterns
- What Worked
- Missing Closure
- One Delta
- Do Not Continue Boundary

## Diagnose The Gap

- [Accident Menu](docs/accident_menu.md)
- [Re-entry Maturity Rank](docs/re_entry_maturity_rank.md)
- [Minimum Input Pack](docs/minimum_input_pack.md)
- [Sample Output](docs/sample_output.md)
- [First-Screen Gate Signal Check](docs/first_screen_gate_signal_check.md)
- [Public Visibility Gate](docs/public_visibility_gate.md)

## What This Is

- manual repo re-entry / handoff audit
- restartability diagnosis
- public-surface gate check
- non-blaming accident-pattern review

## What This Is Not

- not a security audit
- not legal advice
- not a code correctness review
- not automation
- not scraping/API
- not implementation approval
- not a guarantee of safety

## Current Gate

```text
Manual MVP public repo: PUBLIC CANDIDATE
GitHub public repo creation: DONE
Rendered GitHub surface check: REQUIRED BEFORE ANNOUNCEMENT
Announcement / posting: HOLD
Star-seeking: HOLD
Pricing / sell-test: HOLD
Release / tag: HOLD
Implementation: HOLD
License / reuse selection: HOLD
API / scraping / automation: BLOCK
```

This repository is public, but it has not been announced.

Before announcement, the rendered GitHub surface still needs to be checked.

This is not a license grant.

## Do Not Continue Boundary

Do not announce, price, sell-test, release/tag, implement, use API/scraping/automation, select a license, or treat this repository as a safety guarantee.
