# Beyond the Pitch — Content Vault

The production system behind Beyond the Pitch's daily content. Not a page on the
website — this is the internal library the content is *made from*: scripts,
storyboards, image prompts, and the operating rules that keep 90 days of output
looking like one brand instead of 270 disconnected posts.

## What this is, in one paragraph

A 90-day, 7-pillar, 3-post-a-day content engine (Learn → Do → Connect), rewritten
into **documentary voice** — real build-log footage of Caren building JLAC
Ventures' portfolio (OmniClip, Klypt, Curblist, Lumina, the public-adjusting
businesses) toward a million-dollar valuation, not generic motivational tips.
The teaching content (the actual business lesson each post carries) is evergreen
and fully written. The documentary *specifics* — which venture, what happened
that week, what the win or the loss actually was — are Caren's to fill in, because
nobody else can write truthfully about what shipped this week. See
[`01-framework/documentary-template.md`](01-framework/documentary-template.md)
for exactly how that split works and why.

## Where this came from

- `00-source/` holds the two files this vault was built from: the original
  90-day/270-script xlsx calendar and the content engine playbook docx. Treat
  them as the source of truth for anything this vault doesn't cover — if a
  script here seems to drift from them, the source files win until someone
  deliberately updates both.
- The brand system is the one already live on the site (`../assets/`, and the
  CSS variables in `../index.html`) — sage/moss/terracotta, Cormorant Garamond +
  Lato + script accent. `00-brand/brand-system.md` is the condensed reference;
  `00-brand/reference/` holds the fuller brand board images for mood/imagery
  calibration.

## How the vault is organized

```
content-vault/
  00-brand/            brand system reference + mood board images
  00-source/           the original xlsx + docx this vault extends
  01-framework/        the documentary script template, and the full 90-day/
                        7-pillar topic map with build status per pillar
  02-scripts/          the actual scripts, one folder per pillar
    foundation/         ✅ fully vaulted — 13 days, 39 scripts
    brand/               🔲 scaffolded — topics only, not yet vaulted
    marketing/           🔲 scaffolded
    sales/                🔲 scaffolded
    systems/              🔲 scaffolded
    money/                🔲 scaffolded
    leadership-founder/   🔲 scaffolded
  03-production/        folder structure, filenames, tools, weekly rhythm,
                        measurement rules, quality/trust rules
  04-status/            what's actually built vs. what's a placeholder —
                        read this before telling anyone something is "done"
```

## Current build status

**Foundation pillar is fully vaulted** (13 days / 39 scripts) as the working
proof of concept — every script has a full documentary script, on-screen text,
scene-by-scene storyboard, AI image prompts, a photo-to-video motion prompt,
a caption, B-roll suggestions, and platform-specific variations (IG/FB Reel,
TikTok, YouTube Shorts, Pinterest Idea Pin, blog expansion angle).

**The other six pillars (Brand, Marketing, Sales, Systems, Money, Leadership &
Founder — 51 days / 153 scripts) are scaffolded only**: topic, hook seed, and
offer/folder tag, ready to run through the same template. Full detail in
[`04-status/vault-status.md`](04-status/vault-status.md) — don't assume
anything past Foundation is production-ready without checking that file.

## How to use this to actually produce a post

1. Open the day file in `02-scripts/foundation/` for whatever's next in the
   rotation (see `01-framework/pillar-rotation-map.md` for the full sequence).
2. Fill in every `[CAREN: ...]` bracket with what's actually true this week —
   the real venture, the real screen, the real number. If nothing real fits a
   slot this week, skip that post or swap in a scaffolded topic rather than
   inventing a placeholder win.
3. Follow `03-production/production-ops.md` for the Canva/CapCut workflow,
   filename convention, and folder structure to actually build the video.
4. Publish, then follow the weekly measurement rule in the same doc — three
   winners and one weak pattern, don't redesign the brand off one flop.

## Who to loop in

`content-studio-lead` and `social-media-director` own cadence and platform
adaptation. `brand-director` owns anything that touches voice or visual
consistency. If a script needs real specifics about what shipped in OmniClip,
Klypt, Curblist, or Lumina, that has to come from Caren or those repos directly
— this vault doesn't invent that content, per the project doctrine in the root
`CLAUDE.md`.
