# Beyond the Pitch — Project Doctrine

Coaching business, repositioning from a soccer-coaching funnel to a raw, follow-along documentary series chronicling Caren building her whole venture portfolio (OmniClip, Klypt, Curblist, Lumina, the public-adjusting businesses) to a million-dollar valuation. See `/root/.claude/CLAUDE.md` for the cross-venture doctrine this project inherits.

> ⚠️ **No legal entity owns this product.** "JLAC Ventures LLC" was intended in July 2026 but the filing was REJECTED and the entity never existed — do not reintroduce that name anywhere. Confirmed on Sunbiz 2026-08-03, the owner's only Florida entities are `JLAC, CORP.` (P22000074933) and `KULEANA CLAIM SOLUTIONS, LLC` (L26000262262, a public-adjusting company); neither owns this. It therefore operates as an unincorporated sole proprietorship with **no liability shield** — liability reaches Caren's personal assets directly. The rejected filing is correctable until **2026-09-21** (tracking 500478530445).

## Current state (audited 2026-08-05)

11 static HTML pages, inline styling, no CSS/JS build, no CMS. **Checkout is still unwired** — `sales.html` and `membership.html` have `href="#"` placeholders with an explicit comment marking them as Systeme.io/Payhip connection points once a real product exists there. No tests, no CI, no backend. This is the least built-out of Caren's active properties — treat any claim of "done" here skeptically until verified against the actual files.

## The AI Executive Team

`.claude/agents/` holds 16 subagents, one per business function, converted directly from Caren's pre-written "Beyond the Pitch AI Executive Team" PDF (not paraphrased — the PDF prompts are the source of truth; if you need to adjust one, edit the agent file directly rather than re-deriving from memory). Each follows the identity/standing → operating standards → self-check formula documented in the global doctrine. Reach for the matching agent by function rather than improvising: strategy → `chief-strategist`, brand/voice → `brand-director`, visual → `creative-director`, curriculum → `curriculum-architect` / `instructional-designer`, growth → `marketing-strategist` / `content-studio-lead` / `social-media-director`, revenue → `sales-offers-strategist` / `email-marketing-lead` / `conversion-copywriter`, retention → `community-director` / `customer-success-lead`, and systems → `analytics-lead` / `operations-architect`.

## Documentary content directive

The core positioning shift: this is no longer a coaching-only funnel, it's a real-time build log of the whole conglomerate. Content should document actual work as it happens — wins, losses, and the unglamorous parts — not manufactured inspiration. Coordinate with the `content-studio-lead` and `social-media-director` agents on cadence; content here will often be *about* work happening in the other repos (OmniClip, and eventually Klypt/Curblist/Lumina), so cross-reference what's actually shipping there rather than inventing a narrative.

## Content production system

The full documentary content vault (brand reference, script template, 90-day/
7-pillar rotation map, vaulted Foundation-pillar scripts, production ops,
status tracker) lives on the **`content-vault` git branch**, not on `master`.
It's kept off the branch GitHub Pages serves deliberately — it's internal
production material (source calendar/playbook, brand board images, honest
"not built yet" status notes), not something meant to be publicly browsable
at beyondthepitch.life. Check out that branch to read or extend it. The one
piece of it that *is* meant to be public — the "Start Your Business Checklist"
lead magnet `optin.html` promises — is mirrored onto `master` at
`resources/start-your-business-checklist.pdf`; if the vault's copy changes,
re-copy it there too.

## What's not done yet

- Checkout is not wired to any payment processor — don't imply otherwise in copy.
- No brand-voice system distinct from Caren's personal brand yet (uses the personal brand `typography-systems` system by default per global doctrine, until/unless Beyond the Pitch earns its own).
- No analytics/tracking instrumented — the `analytics-lead` agent has nothing real to read yet; flag this rather than fabricating numbers.
