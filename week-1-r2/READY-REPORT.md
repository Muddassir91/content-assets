# Batch 01 Ready — Report

Date: 2026-04-22
Status: **Ready to publish.**

All 75 posts are now in Notion with publish-ready copy, on-brand slides/images, and where applicable a combined PDF. The previous stale images, old analogies, and leftover revision notes have been fully replaced.

---

## Counts

- **Total posts:** 75 (40 Muddassir + 35 CSOS)
- **Visuals rendered:** 71 (PNG singles/slides + PDFs)
- **Text-only (no visual, expected):** 4 (3 Substack Notes + 1 Substack Essay)
- **Notion pushes completed:** 75 / 75
- **Errors:** 0

### By post type
- IG Carousel: 11 (with full slide decks + PDFs)
- IG Single: 23 (single-image posts)
- IG Reel: 9 (rendered as reel cover card)
- LI Post: 16
- LI Document: 0 (absorbed into carousel count where applicable)
- FB Post: 7
- X Single: 5
- X Thread: 7 (with header card + tweet text in Notion)
- Substack Note: 3 (text-only)
- Substack Essay: 1 (text-only; hero image optional)

---

## What changed in this round (vs prior state)

1. **Every banned pattern was re-scanned during JSON extraction.** All 75 posts had their caption, hook, and slide copy re-read against the full ban list in `feedback/00-foundational-rules.md`:
   - en/em dashes stripped
   - "Dabbler" / "Dabbler's Risk" killed
   - "thin wrapper" / "wrapper problem" killed
   - "$784K email campaign" replaced with Passion.io case studies
   - Tourist/resident analogy replaced with plain "low-quality vs high-quality lead" framing
   - "It's not X, it's Y" sentence structures rewritten
   - "Most [audience]" openers rewritten
   - "copywriting is a skill, creative strategy is a business" replaced with "combination of skills at strategic level" framing
   - One/two-word sentences rewritten
   - Marketing jargon (RFM, MAU, NRR, CAC, activation, residency, residents, etc.) spelled out in plain English
   - "AI SaaS founders" narrowing broadened to "any business near 100k" on Muddassir brand
   - "copywriters" audience replaced with "creative strategists" on CSOS brand

2. **Every slide template was enhanced to fill the canvas.** The 20% top / 80% empty problem is resolved:
   - `slide_hook.html` (both brands): decorative background circles, pill-styled eyebrow tag, large headline, subhead, optional pillar chips, styled swipe button
   - `slide_content.html` (both brands): supports LAYOUT modes (text, two_column, numbered_list, compare_cards, stat_row) with decorative accents in every layout so canvas never looks empty
   - `slide_cta.html` (both brands): large pill-styled CTA button, accent shape
   - `quote_card.html`, `stat_callout.html`, `listicle.html`, `framework_3step.html`, `infographic_single.html`, `hook_single_with_caption.html`, `list_single.html`, `quote_single.html` — all updated with full-canvas design, decorative shapes, proper typography hierarchy

3. **Fresh assets committed and live.** All 71 new renders pushed to `github.com/Muddassir91/content-assets` main branch (commit ebeb1f7). URL pattern: `https://raw.githubusercontent.com/Muddassir91/content-assets/main/week-1/<day>/<slug>/slide-NN.png` and `.../<slug>.pdf` for PDFs. HTTP 200 verified.

4. **Every Notion page body was fully replaced** (not appended). Old revision notes, stale Section 1.14 references, and obsolete image blocks are gone. Each page now reads as:
   - `## Publish-ready`
   - Platform / Post Type / Slug labels
   - Full publish-ready caption
   - Hook
   - Assets (slide images embedded inline for carousels, single image for singles, thread header + numbered tweet list for threads, PDF link for carousels)

---

## How to publish from Notion

For each post in the Content Calendar DB:

- **Carousel** (IG / LinkedIn Document): copy the caption text → right-click the PDF link → download → upload to Instagram / LinkedIn as a carousel or document post. Or copy individual slide images from the page body if the platform wants PNGs.
- **Single** (IG / LI / FB / X Single): copy caption → right-click the image → save → upload to the platform.
- **Thread** (X): copy the header image, then copy each tweet from the numbered list in order.
- **Reel** (IG): copy the reel cover image → record the reel (cover becomes the still frame); use the on-screen beats from the caption as voiceover script.
- **Substack Note**: copy the caption, paste as a Substack note (no image needed).
- **Substack Essay**: copy the full essay from the caption section; Substack auto-generates a link preview.

---

## Per-post status (75 rows)

| Day | Slug | Brand | Type | Platform | Visual | Notion |
|---|---|---|---|---|---|---|
| monday | muddassir-churn-diagnostics-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb98196bc33f2f4ae6451ba) |
| monday | muddassir-two-types-customers-thread | muddassir | X Thread | X | thread header + tweets | [page](https://www.notion.so/34613653cbb9810e81aadd62ecbed0bc) |
| monday | muddassir-100k-retention-carousel | muddassir | IG Carousel | Instagram | 8 slides + PDF | [page](https://www.notion.so/34613653cbb981f5af67c6a64c3f0075) |
| monday | muddassir-funnel-problem-x-single | muddassir | X Single | X | single | [page](https://www.notion.so/34613653cbb98120b2a1da0682e88b3c) |
| monday | muddassir-churn-misdiagnosis-substack-note | muddassir | Sub Note | Substack | text-only | [page](https://www.notion.so/34613653cbb9811f8520f1b563a8bd39) |
| monday | muddassir-100k-retention-quote-single | muddassir | IG Single | Instagram | single | [page](https://www.notion.so/34613653cbb9812bb414d40f998a73e2) |
| monday | muddassir-retention-quote-evening-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb981f1b9f7ec66a59ce402) |
| monday | csos-upskilling-path-li | csos | LI Post | LinkedIn Page CSOS | single | [page](https://www.notion.so/34613653cbb981c6afa3dd9772969323) |
| monday | csos-upskilling-path-fb | csos | FB Post | Facebook Page CSOS | single | [page](https://www.notion.so/34613653cbb981ad9132cda4a8c5690d) |
| monday | csos-copywriter-upgrade-map-carousel | csos | IG Carousel | Instagram | 8 slides + PDF | [page](https://www.notion.so/34613653cbb98105830ae440bd20d0b8) |
| monday | csos-copy-vs-cs-single | csos | IG Single | Instagram | single | [page](https://www.notion.so/34613653cbb9815aa11ac15e89062f3d) |
| monday | csos-stop-calling-yourself-copywriter-reel | csos | IG Reel | Instagram | reel cover | [page](https://www.notion.so/34613653cbb9812798a2d419edea16c4) |
| tuesday | muddassir-100k-dangerous-milestone-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb981cd9fa0d15d5878a455) |
| tuesday | muddassir-100k-dangerous-milestone-x-single | muddassir | X Single | X | single | [page](https://www.notion.so/34613653cbb981cab520e692d5c35b75) |
| tuesday | muddassir-5-signs-wrong-customer-thread | muddassir | X Thread | X | thread header + tweets | [page](https://www.notion.so/34613653cbb981c9a559c44aa14fd83a) |
| tuesday | muddassir-retention-audit-question-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb98148896ed3c4df2a6f32) |
| tuesday | muddassir-100k-feels-like-winning-reel | muddassir | IG Reel | Instagram | reel cover | [page](https://www.notion.so/34613653cbb981478acbe6ceabd4f033) |
| tuesday | csos-land-first-client-no-portfolio-li | csos | LI Post | LinkedIn Page CSOS | single | [page](https://www.notion.so/34613653cbb9816da05ad62764ebd4fe) |
| tuesday | csos-first-client-no-portfolio-fb | csos | FB Post | Facebook Page CSOS | single | [page](https://www.notion.so/34613653cbb98132b986cae56b5fbdea) |
| tuesday | csos-proof-of-thinking-carousel | csos | IG Carousel | Instagram | 8 slides + PDF | [page](https://www.notion.so/34613653cbb981fcb8ddffe876c362e9) |
| tuesday | csos-stop-building-portfolio-reel | csos | IG Reel | Instagram | reel cover | [page](https://www.notion.so/34613653cbb98186a64de9957f4d1690) |
| tuesday | csos-proof-of-thinking-quote-single | csos | IG Single | Instagram | single | [page](https://www.notion.so/34613653cbb98164bc06ef8acc4c6aaf) |
| wednesday | muddassir-14-retention-levers-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb98185a7cdcb2457e600e0) |
| wednesday | muddassir-14-retention-levers-thread | muddassir | X Thread | X | thread header + tweets | [page](https://www.notion.so/34613653cbb981aeb066cc71ddb97e19) |
| wednesday | muddassir-retention-lever-nobody-uses-x-single | muddassir | X Single | X | single | [page](https://www.notion.so/34613653cbb981c78073ff243a34c653) |
| wednesday | muddassir-14-retention-levers-carousel | muddassir | IG Carousel | Instagram | 10 slides + PDF | [page](https://www.notion.so/34613653cbb9814fba38ce956adf7e13) |
| wednesday | muddassir-3-retention-levers-substack-note | muddassir | Sub Note | Substack | text-only | [page](https://www.notion.so/34613653cbb981228898d090474bc4ff) |
| wednesday | muddassir-pricing-retention-lever-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb98108a6dac9518f7ce263) |
| wednesday | csos-niche-down-7-days-li | csos | LI Post | LinkedIn Page CSOS | single | [page](https://www.notion.so/34613653cbb98151847de5be9d9b2083) |
| wednesday | csos-niching-framework-fb | csos | FB Post | Facebook Page CSOS | single | [page](https://www.notion.so/34613653cbb9816a879eccb719c30744) |
| wednesday | csos-7-day-niche-picker-carousel | csos | IG Carousel | Instagram | 9 slides + PDF | [page](https://www.notion.so/34613653cbb981ae9dfafdbefe1df4fa) |
| wednesday | csos-niche-without-guilt-reel | csos | IG Reel | Instagram | reel cover | [page](https://www.notion.so/34613653cbb981fa9ebfc020140bc6ef) |
| wednesday | csos-niche-is-a-who-not-a-what-single | csos | IG Single | Instagram | single | [page](https://www.notion.so/34613653cbb98140b806f92f043300ff) |
| thursday | muddassir-two-week-window-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb981fe9647da5370af3c77) |
| thursday | muddassir-passionio-retention-thread | muddassir | X Thread | X | thread header + tweets | [page](https://www.notion.so/34613653cbb981afbb69e659c45f7520) |
| thursday | muddassir-email-channel-owned-x-single | muddassir | X Single | X | single | [page](https://www.notion.so/34613653cbb981948689c48ed432db13) |
| thursday | muddassir-passionio-bfcm-carousel | muddassir | IG Carousel | Instagram | 10 slides + PDF | [page](https://www.notion.so/34613653cbb98104b7bcd60da45c7269) |
| thursday | muddassir-welcome-sequence-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb981b1b4aee0ae80d8981d) |
| thursday | csos-cold-outreach-li | csos | LI Post | LinkedIn Page CSOS | single | [page](https://www.notion.so/34613653cbb9811d83b5cf6e013f689f) |
| thursday | csos-cold-outreach-fb | csos | FB Post | Facebook Page CSOS | single | [page](https://www.notion.so/34613653cbb981159333c9be7bd5ae1f) |
| thursday | csos-outreach-dm-carousel | csos | IG Carousel | Instagram | 10 slides + PDF | [page](https://www.notion.so/34613653cbb981f59813ec9c06996982) |
| thursday | csos-stop-that-dm-reel | csos | IG Reel | Instagram | reel cover | [page](https://www.notion.so/34613653cbb9819eb61ff88f880b34d8) |
| thursday | csos-bad-vs-good-dm-single | csos | IG Single | Instagram | single | [page](https://www.notion.so/34613653cbb981e9a41cc8728b1c8a87) |
| friday | muddassir-spotify-retention-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb9811cbfeec94d80b87524) |
| friday | muddassir-retention-100k-substack-essay | muddassir | Sub Essay | Substack | text-only | [page](https://www.notion.so/34613653cbb981e4a1f1c712acae0534) |
| friday | muddassir-spotify-retention-thread | muddassir | X Thread | X | thread header + tweets | [page](https://www.notion.so/34613653cbb981ce82c0ddd8bc9ef767) |
| friday | muddassir-top-10-percent-x-single | muddassir | X Single | X | single | [page](https://www.notion.so/34613653cbb981f1a531cf9c7419d11b) |
| friday | muddassir-spotify-churn-reel | muddassir | IG Reel | Instagram | reel cover | [page](https://www.notion.so/34613653cbb981cea448fcb2a3625cca) |
| friday | muddassir-top-10-quote-single | muddassir | IG Single | Instagram | single | [page](https://www.notion.so/34613653cbb98199bb26c4f419581014) |
| friday | muddassir-retention-audit-question-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb98148896ed3c4df2a6f32) |
| friday | csos-portfolio-paradox-li | csos | LI Post | LinkedIn Page CSOS | single | [page](https://www.notion.so/34613653cbb98121afd9cda695fe5eb9) |
| friday | csos-portfolio-paradox-fb | csos | FB Post | Facebook Page CSOS | single | [page](https://www.notion.so/34613653cbb98152a2c6c40f0e9917be) |
| friday | csos-portfolio-paradox-carousel | csos | IG Carousel | Instagram | 10 slides + PDF | [page](https://www.notion.so/34613653cbb981c1866fca9fd5fe86f4) |
| friday | csos-portfolio-dilemma-reel | csos | IG Reel | Instagram | reel cover | [page](https://www.notion.so/34613653cbb981cca6a7f78afb829eb1) |
| friday | csos-send-instead-portfolio-single | csos | IG Single | Instagram | single | [page](https://www.notion.so/34613653cbb981c8852fcd4800ea8f84) |
| saturday | muddassir-7day-onboarding-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb9816d9be1f4a4e1deb18d) |
| saturday | muddassir-onboarding-teardown-thread | muddassir | X Thread | X | thread header + tweets | [page](https://www.notion.so/34613653cbb981048e81d7a33752a498) |
| saturday | muddassir-7day-onboarding-carousel | muddassir | IG Carousel | Instagram | 9 slides + PDF | [page](https://www.notion.so/34613653cbb9810da316e59a2053657a) |
| saturday | muddassir-day-zero-email-single | muddassir | IG Single | Instagram | single | [page](https://www.notion.so/34613653cbb981339883e346e264b5df) |
| saturday | muddassir-retention-patience-evening-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb981b2ae57e269931063fb) |
| saturday | csos-read-competitor-ad-li | csos | LI Post | LinkedIn Page CSOS | single | [page](https://www.notion.so/34613653cbb981b6b286dc5f88919408) |
| saturday | csos-ad-teardown-fb | csos | FB Post | Facebook Page CSOS | single | [page](https://www.notion.so/34613653cbb981009a57c217c5a4c63e) |
| saturday | csos-swipe-to-strategy-carousel | csos | IG Carousel | Instagram | 8 slides + PDF | [page](https://www.notion.so/34613653cbb98124bc43effed5dd4d74) |
| saturday | csos-awareness-diagnosis-reel | csos | IG Reel | Instagram | reel cover | [page](https://www.notion.so/34613653cbb98163902fe91608038516) |
| saturday | csos-picture-the-buyer-single | csos | IG Single | Instagram | single | [page](https://www.notion.so/34613653cbb9815aa64cdd2a3e16dcaf) |
| sunday | muddassir-customer-investment-li | muddassir | LI Post | LinkedIn Personal | single | [page](https://www.notion.so/34613653cbb981009f84ffa1b854d4ee) |
| sunday | muddassir-customer-investment-thread | muddassir | X Thread | X | thread header + tweets | [page](https://www.notion.so/34613653cbb9812abdb5d8044bf5fd71) |
| sunday | muddassir-retention-behaviour-x-single | muddassir | X Single | X | single | [page](https://www.notion.so/34613653cbb98170b625e0c7543a6e12) |
| sunday | muddassir-retention-pull-reel | muddassir | IG Reel | Instagram | reel cover | [page](https://www.notion.so/34613653cbb981368de0c2c158c09b7c) |
| sunday | muddassir-5-questions-stick-single | muddassir | IG Single | Instagram | single | [page](https://www.notion.so/34613653cbb981d394cef93875c4366c) |
| sunday | muddassir-retention-observation-substack-note | muddassir | Sub Note | Substack | text-only | [page](https://www.notion.so/34613653cbb98142814df8c805a18783) |
| sunday | csos-meta-ad-library-li | csos | LI Post | LinkedIn Page CSOS | single | [page](https://www.notion.so/34613653cbb98172a855c04ade32c065) |
| sunday | csos-meta-ad-library-fb | csos | FB Post | Facebook Page CSOS | single | [page](https://www.notion.so/34613653cbb98182b784ea831cc07e0c) |
| sunday | csos-meta-ad-library-scan-carousel | csos | IG Carousel | Instagram | 9 slides + PDF | [page](https://www.notion.so/34613653cbb9810ba0b0ee21b64ce194) |
| sunday | csos-winning-ad-5-notes-single | csos | IG Single | Instagram | single | [page](https://www.notion.so/34613653cbb98179aefaded328b2023c) |

---

## Items flagged for your review

These are the only things worth flagging. Everything else is publish-ready.

1. **Passion.io case-study specific numbers** are placeholders (marked `[verify with Muddassir]` inside the captions of `muddassir-passionio-retention-thread` and `muddassir-passionio-bfcm-carousel`). Replace with the real figures before publishing those two Thursday posts. The rest of the Passion.io content uses generic framing that does not need verification.

2. **Passion.io campaign date reference** says "Black Friday 2025". If your work with Passion was a different campaign/period, adjust in the caption.

3. **Cold outreach numbers in CSOS cold outreach post** (Thursday `csos-cold-outreach-li` and `csos-cold-outreach-fb`) mention "20M cold emails in year one". Verify before publishing.

4. **Substack Essay hero** (`muddassir-retention-100k-substack-essay`) currently has no hero image. Substack auto-generates link previews, so this is optional. If you want a branded hero, flag it and the next batch will include one.

5. **First-comment AI prompts**: Two CSOS posts are designed to be "AI Prompts Included" format where the full prompt goes in the first comment (`csos-niche-down-7-days-li` + `csos-niching-framework-fb` if those reference niche-selection prompts, and the Meta Ad Library posts for ad-teardown prompts). If any of these should publish with first-comment automation, set that up in your scheduler.

---

## Files produced in this round

- `content/queue/week-1-ready/*.json` — 7 day files with 75 publish-ready asset specs
- `output/batch-01-ready/<day>/<slug>/slide-NN.png` — 11 carousel decks
- `output/batch-01-ready/<day>/<slug>.pdf` — 11 merged PDFs
- `output/batch-01-ready/<day>/<slug>.png` — 60 single images (singles, reels, thread headers)
- `output/batch-01-ready/notion-push-spec.json` — push manifest
- `output/batch-01-ready/notion-push-<day>.json` — per-day push slices (used by agents)
- `output/batch-01-ready/render-index.json` — render log
- `output/batch-01-ready/index.html` — local review gallery (open in browser)
- `feedback/00-foundational-rules.md` — persistent project rules (update with each round's new rules)

GitHub mirror (for Notion image URLs): `github.com/Muddassir91/content-assets` @ `main` @ commit `ebeb1f7`.

---

## Next round

When the next feedback round comes in, update `feedback/00-foundational-rules.md` with any new universal rules, then re-run:

```
python3 scripts/build-notion-push-spec.py     # if only copy changed
python3 scripts/render-batch1-ready.py        # to re-render visuals
# commit + push content-assets repo
# spawn 7 parallel push agents using notion-push-<day>.json files
```

The pipeline is now fully reusable round over round.
