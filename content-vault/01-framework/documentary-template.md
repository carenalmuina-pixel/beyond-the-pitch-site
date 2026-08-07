# Documentary Script Template

How every script in this vault turns a business lesson into a documentary
post — real build-log footage of the JLAC Ventures portfolio, not a generic
tip account. Read this before writing or filling in a script.

## Why scripts have brackets in them

The source playbook (`../00-source/`) was written as straight educational
content — "here's a business concept, here's how to apply it." Beyond the
Pitch's actual doctrine (root `CLAUDE.md`) is different: this is a real-time
build log. Content should document actual work as it happens — wins, losses,
and the unglamorous parts — not manufactured inspiration.

That creates one hard constraint: **nobody outside the actual build can write
the documentary specifics truthfully.** I don't know what shipped in OmniClip
this week, what broke in Klypt, or what the real number was in the
public-adjusting business — and inventing a plausible-sounding one would be
exactly the "fabricated results" the source playbook itself warns against
(see its Quality, Accuracy & Trust rules, carried into
`../03-production/production-ops.md`).

So every script in this vault is split into two kinds of content:

- **The lesson** — the underlying business teaching for that pillar/day. This
  is evergreen, fully written, and doesn't change week to week.
- **The documentary specifics** — which venture, what actually happened, what
  the real screen/number/moment was. These are marked `[CAREN: ...]` and are
  never filled with invented detail. If nothing true fits a slot, skip the
  post that day or swap in a different scaffolded topic — don't fabricate to
  fill the calendar.

Where it helps to show *how* to fill a bracket, a script includes an
*example fill* in italics, always labeled `EXAMPLE FILL — swap for your real
week`. Example fills are never publishable as written; they exist only to
demonstrate the pattern.

## The five-beat structure

Every script — AM, MIDDAY, or PM — follows the same underlying beats. What
changes between the three daily slots is which beat gets the weight (see
below), not the presence of the beats.

1. **Hook (0–3s)** — A specific, real moment from the build. Interrupts the
   scroll because it's concrete, not because it's dramatic. `[CAREN: ...]`.
2. **Struggle (3–10s)** — The real friction that moment created, named
   plainly. What made it hard, confusing, or expensive. Usually also
   `[CAREN: ...]`, though for topics with an obvious universal friction the
   script may pre-fill this with the general version.
3. **Shift (10–24s)** — The lesson. This is the evergreen teaching content
   inherited from the source playbook, reframed as "here's what I'm learning
   by actually doing it" rather than "here's a tip." Fully written, no
   brackets.
4. **Proof (24–32s)** — A concrete, visual takeaway: a screenshot, a
   document, a number, a decision made on camera. `[CAREN: ...]` — this is
   what keeps the post honest instead of aspirational.
5. **CTA (32–40s)** — Follow the build, save the framework, or go use the
   resource. Brand-standard, not fabricated, reusable across scripts.

This keeps the on-brand teaching content (photo-to-video anatomy, pacing,
visual direction) that the source playbook already validated, while replacing
"Save this for your next CEO day" hype-adjacent framing with documentary
framing.

## How AM / MIDDAY / PM differ

Same topic, same day, three different jobs — this is unchanged from the
source playbook's 3-post architecture:

- **AM — LEARN.** Weight on Struggle → Shift. Goal: discovery, authority,
  follows. The viewer should learn one real thing.
- **MIDDAY — DO.** Weight on Shift → Proof, phrased as an assignment the
  viewer can copy. Goal: saves, shares, and "I did this too" replies.
- **PM — CONNECT.** Weight on Hook → Proof, minimal Shift. Slower pacing,
  founder-forward, honest about the hard part. Goal: trust, comments, loyalty.

## Per-script deliverable checklist

Every vaulted script (see `../02-scripts/foundation/` for the worked
examples) includes:

- Full script (documentary voiceover, 25–40 sec)
- On-screen text (2–3 lines max, high contrast, out of the bottom UI zone)
- Scene-by-scene storyboard (4–5 scenes mapped to the beats above)
- AI image prompts, one per scene, in brand palette/mood
- Photo-to-video motion prompt (9:16 master, matches the source playbook's
  motion spec: slow push-in 103–108%, gentle pan, 0.3–0.5s cross-dissolve)
- B-roll suggestions
- Caption (feed copy + hashtags)
- Platform-specific variations: IG/FB Reel, TikTok, YouTube Shorts, Pinterest
  Idea Pin, blog-expansion angle

## Guardrails (inherited from the source playbook + root CLAUDE.md)

- Never promise guaranteed income, followers, virality, funding, tax savings,
  or business outcomes.
- Never fabricate testimonials, dashboards, customer results, or AI-generated
  "customers." The same now extends to founder results — no fabricated wins.
- Legal, tax, accounting, insurance, and regulatory content stays general and
  educational; tell viewers to verify for their own jurisdiction/situation.
- If a script claims something happened in OmniClip, Klypt, Curblist, Lumina,
  or the public-adjusting businesses, it must cross-reference what's actually
  shipping there — don't invent a narrative for another venture.
- No analytics are instrumented yet on this site (per root `CLAUDE.md`) — this
  vault doesn't reference real numbers ("10K followers," "3x conversion") for
  Beyond the Pitch itself until there's real data to cite.
