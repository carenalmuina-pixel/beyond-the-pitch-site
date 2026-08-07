# Production Operations

Condensed from the source playbook (`../00-source/beyond-the-pitch-90-day-content-engine-playbook.docx`)
— the operational side of turning a vaulted script into a published post.
This doesn't repeat everything in the source doc; it's the working
reference for the parts you'll actually touch every week.

## Folder structure for produced assets

This is a local production structure (not part of this git repo — raw
media, exports, and drafts stay local per the site's `.gitignore` policy).
Set it up once:

```
BEYOND_THE_PITCH
  00_BRAND
    Logos / Color_Palette / Typography / Icons / Patterns / Photo_Style
    Canva_Master_Templates
  01_CONTENT
    2026_Q3_90_Day_Campaign
      Week_01 ... Week_13
        Day_01 / 01_Learn / 02_Do / 03_Connect
  02_RAW_MEDIA
    Founder_Photos / Workspace / Products / Screenshots / Stock_Licensed
  03_EXPORTS
    Instagram / TikTok / YouTube_Shorts / Facebook
  04_RESOURCES
    Lead_Magnets / Checklists / Templates / Courses
  05_ANALYTICS
    Weekly_Reports / Monthly_Reports / Top_Performers
  06_ARCHIVE
```

**Filename standard:** `YYYY-MM-DD_Day##_P#_Pillar_ShortTopic_V01.mp4`
(e.g. `2026-08-10_Day01_P1_Foundation_ProblemNotLogo_V01.mp4`). If you're not
working against calendar dates yet, use `D##_P#_Pillar_Topic_V01`.

## Three master visual templates (build once in Canva Free)

- **Template A — LEARN.** Ivory background, small BP submark, large
  Cormorant headline, one terracotta highlight word, 1–2 editorial photos,
  Lato caption line, thin moss divider. End frame: takeaway + tagline.
- **Template B — DO.** Sand or blush background, checklist card, moss
  heading, terracotta check marks/arrows, notebook/screen imagery, large
  action verb. End frame: "Save this and do it today."
- **Template C — CONNECT.** Founder image or path/horizon, warmer
  photography, larger negative space, one emotional line in restrained
  script accent, short body copy, subtle brush texture. End frame may use
  "Different field. Same drive."

Master canvas: 1080×1920 (9:16). Keep text out of the top/bottom UI zones.
Create 1080×1080 square derivatives only when a platform benefits from them.

## From vaulted script to finished photo-to-video

1. Pull the day file from `../02-scripts/foundation/` (or a filled-in
   scaffold once other pillars are vaulted). Fill every `[CAREN: ...]`
   bracket with what's actually true this week.
2. Collect 3–5 real visuals per post using the AI image prompts as a
   starting point, or real founder/workspace photography — real photos win
   over generated ones whenever you have them.
3. Duplicate the matching Learn/Do/Connect Canva master. Replace headline,
   on-screen text, and photos. Don't redesign the layout per post.
4. Export PNGs or an MP4 from Canva Free, in scene order if exporting
   frames individually.
5. Animate in CapCut: 9:16 project, 2–5s per frame, slow scale ~103→108%,
   gentle pan, cross-dissolve, restrained text motion — matches the motion
   spec already written into each vaulted script.
6. Voiceover: your own phone voice memo or CapCut recording for
   authenticity. If skipping voiceover, use on-screen text + captions +
   permitted ambient/trending audio.
7. Captions: always on, 2–3 lines max, high contrast, out of the bottom UI
   zone.
8. End card: 1.5–2.5s, BP submark, one CTA, optional tagline. Never stack
   multiple CTAs.
9. Export MP4, vertical, high resolution. Watch once with sound, once
   muted.

## Free-only tool stack

- Canva Free — https://www.canva.com/free/ (design + social video maker)
- CapCut — https://www.capcut.com/tools/video-editing-software (editing)
- Pexels — https://www.pexels.com/royalty-free-images/ (licensed stock, when
  real photography isn't available — log the source link)
- Meta Business Suite — Instagram/Facebook scheduling
- YouTube Studio — Shorts scheduling
- TikTok Studio — upload/schedule/analytics

Free tiers change. When a feature gets paywalled, fall back to the manual
Canva + CapCut keyframe workflow above rather than changing the whole
system.

## Weekly production rhythm

- **Monthly planning (2–3 hrs):** review the next 30 days from
  `../01-framework/pillar-rotation-map.md`, swap in any real launch/event
  content that should replace a generic day, confirm no regulated topic has
  drifted too specific, mark 30 days Approved for Production.
- **Weekly batch (21 posts):** work Week by Week, not post by post. Fill
  brackets, gather visuals, build in Canva, animate in CapCut, QA, schedule.
- **Publishing:** native platform tools only, no paid scheduler needed.
  Don't lock exact post times until analytics show when the audience is
  actually active — publish in rolling batches instead.

## Measurement: judge each post by its job

- AM (Learn) → discovery, search, follows.
- MIDDAY (Do) → saves, shares, "I did this too" replies.
- PM (Connect) → comments, trust, loyalty.

**Weekly rule:** identify three winners and one weak pattern. Don't redesign
the brand because one post underperforms — fix the hook, pacing, visual
relevance, CTA, or distribution first.

Beyond the Pitch has no analytics instrumented yet (per root `CLAUDE.md`) —
until that's wired up, "winner" and "weak" are judged from native platform
insights (views, saves, comments) directly, not from a dashboard this vault
doesn't have.

## Quality, accuracy, and trust rules (non-negotiable)

- Legal, tax, accounting, insurance, and regulatory content stays general
  and educational — tell viewers to verify for their own jurisdiction and
  situation with a licensed professional.
- Never promise guaranteed income, followers, virality, funding, tax
  savings, or business outcomes.
- Never fabricate testimonials, dashboards, customer results, AI-generated
  "customers," or — per this vault's documentary extension — fabricated
  founder wins. If a `[CAREN: ...]` bracket has nothing true to put in it,
  skip the post or swap topics.
- Use real founder photography heavily. When stock is needed, use a
  commercial-use-permitted source (Pexels) and keep the source link logged.
- Verify any statistic, law, platform feature, or price before publishing —
  these change.
- Keep the brand helpful, not superior: "here's a framework" beats shaming
  people for not knowing something.

## Launch checklist

- [ ] Brand system locked and referenced (`../00-brand/brand-system.md`).
- [ ] Three master vertical templates built in Canva Free.
- [ ] CapCut vertical project preset created.
- [ ] This vault's rotation map copied into the active campaign folder.
- [ ] Week 1 scripts (already vaulted — `../02-scripts/foundation/day-01.md`)
      reviewed and brackets filled with real specifics.
- [ ] Week 1 visuals gathered and licensed/owned.
- [ ] Week 1 videos designed, edited, and QA'd.
- [ ] Native platform accounts connected, scheduling tested.
- [ ] Weekly analytics review placed on the calendar.
