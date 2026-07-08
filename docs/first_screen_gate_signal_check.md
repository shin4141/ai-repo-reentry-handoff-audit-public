# First-Screen Gate Signal Check

Public-facing audit closure must compare the first visible public surface against the current gate ledger.

First-screen visible elements are gate signals.

Public-entry PASS cannot rely only on repo state, manifest state, README body text, or adjacent caveats.

## When To Use

Use this checklist for public-facing repos, public shelves, launch surfaces, GitHub repo surfaces, README first screens, or external-reader boundaries.

Use it before declaring:

- public-entry PASS
- public-placement PASS
- public-surface PASS
- rendered-surface completion
- external-reader boundary visible

## Inputs

- current gate ledger
- README first screen
- repo status / status badges
- GitHub About description, if evidence exists
- GitHub Topics, if evidence exists
- issue templates or community surface, if relevant
- license / status wording
- publication, manifest, handoff, or audit records
- screenshot or rendered surface evidence, if available

## Check Items

Compare these first-screen or first-contact signals against the current gate ledger:

- README/status badges
- title/subtitle
- video/thumbnail if present
- GitHub About description
- GitHub Topics
- issue/community surface
- license/status wording
- `GO` / `ready` / `public` / `launch` wording
- implementation / automation / API wording
- posting / outreach / pricing wording

For each signal, ask:

- Does it imply a stronger gate than the ledger allows?
- Does a visible `GO`, `ready`, `public`, `launch`, or similar word require a limiting qualifier?
- Does nearby HOLD/BLOCK text actually neutralize the stronger first-screen signal?
- Would a first-time external reader understand what is allowed and what remains held or blocked?
- Is the evidence live-rendered, screenshot-provided, or source-ledger-only?

## Evidence Labels

Use exactly one or more of these labels:

- `live-rendered`
- `screenshot-provided`
- `source-ledger-only`

If evidence is `source-ledger-only`, do not claim live rendered PASS.

## PASS / DELAY / BLOCK Interpretation

PASS:

- first-screen signals match the current gate ledger
- held and blocked surfaces are visible enough for a first-time reader
- strong words are bounded by clear qualifiers
- evidence label is recorded

DELAY:

- first-screen signals are mostly correct, but one or more strong words depend on body text, adjacent caveats, or internal notes to be understood safely
- live rendered evidence is unavailable and the audit can only claim source-level PASS
- GitHub About / Topics / badges / title / video surface are unknown or partially checked

BLOCK:

- first-screen signals imply active promotion, launch, implementation, API, automation, pricing, posting, or release when the gate does not allow it
- visible `GO`, `ready`, `public`, or `launch` wording contradicts HOLD/BLOCK state
- public surface hides or contradicts the current gate ledger

## Do Not Continue Boundary

Do not use this checklist to authorize implementation, outreach, pricing/sell-test, public posting, release/tag, API use, scraping, automation, or safety claims.
