# CHATGPT_WORK_STARTFRAMES_2026-08-18_2026-08-19_EXPORT

Created: 2026-08-20T03:58:00+02:00
Source: ChatGPT Work / `michael-banger/organic-briefs`
Requested Hermes target: `/opt/data/profiles/organic-ai-operator/workspace/hermes-organic-ai-operator/ops/start-frames/2026-08-18-19-chatgpt-ready/`

## Verdict

- READY videos: **0**
- BLOCKED videos: **3**
- Verified generated start frames exported: **9**
- 2026-08-19 new generated start frames: **0**

The 2026-08-18 KLING run originally marked CARBLAZZ POST 1-3 complete and verified 9/9 PNGs. The current source of truth, revised on 2026-08-20, explicitly invalidates that batch. `output/2026-08-18/CARBLAZZ/_NON-EXPLOITABLE.md` states that it must not be mounted or sent to video generation.

Therefore this export preserves the **actual generated assets** for forensic/handoff purposes but marks every video `BLOCKED`. Hermes must **not** launch Kling/Higgsfield from these frames. The corrected replacement brief is `DAILY-BRIEF-2026-08-21-CARBLAZZ.md` and is intentionally not mixed into this historical export.

## Source provenance

- Generation/output commit: `6be3682083254c34c4c3dffecb234fb395d554a0`
- 2026-08-18 run summary: `output/2026-08-18/KLING-RUN-SUMMARY.md`
- 2026-08-19 run summary: `output/2026-08-19/KLING-RUN-SUMMARY.md`
- Current manifest: `MANIFEST.md`
- Current product truth: `product-breakdowns/CARBLAZZ.md`
- Explicit invalidation marker: `output/2026-08-18/CARBLAZZ/_NON-EXPLOITABLE.md`

## 2026-08-18 / carblazz

### VIDEO-01 — BLOCKED
- Source post: CARBLAZZ POST 1
- Product slug used: `horloge-bois-f1`
- Hook: `Every F1 fan I know has the same empty wall`
- Caption: `Race weekend starts on the wall. 🕒 Link in bio`
- ManyChat keyword: `CLOCK`
- Frames: 3
- Blockers: `FAIL_PRODUCT_IDENTITY`, `FAIL_MARKET`
- Reason: the 18/08 prompt treated the product as wood-toned / wood grain. Verified product truth says **no wood**: red/white/black F1 livery, top-down F1 car, flat matte face, no glass. The historical US/English market is also invalid; current truth is FR/French.

### VIDEO-02 — BLOCKED
- Source post: CARBLAZZ POST 2
- Product slug used: `horloge-metal-noir`
- Hook: `Nobody notices the wall until it's this one`
- Caption: `Brushed metal, brake-disc face, zero noise. 🕒 Link in bio`
- ManyChat keyword: `CLOCK`
- Frames: 3
- Blockers: `FAIL_PRODUCT_IDENTITY`, `FAIL_MARKET`
- Reason: the 18/08 prompt described a brushed black metal face / machining texture. Verified product truth is a glossy black 5-spoke wheel with yellow caliper, brake disc, tyre-sidewall bezel with gold emblems, reflective glass and white hands.

### VIDEO-03 — BLOCKED
- Source post: CARBLAZZ POST 3
- Product slug used: `horloge-metal-noir` + `horloge-packaging`
- Hook: `Send this to whoever still buys him socks`
- Caption: `One box. Solved. 🕒 Link in bio`
- ManyChat keyword: none
- Frames: 3
- Blockers: `FAIL_PACKAGING_MECHANICS`, `FAIL_WRONG_VARIANT`, `FAIL_STATE_CONTINUITY`, `FAIL_MARKET`
- Reason: scene 2 used a lifted lid even though the real packaging is a flat sleeve + side-sliding drawer; the clock visible in scene 2 was the wrong variant; the sequence skipped the required held/installation state before the mounted hero.

## 2026-08-19

No new start frame was generated. The run only deduplicated the already completed 18/08 CARBLAZZ batch and reported missing briefs for Onsimplifie/Myteaovo and no new Carblazz brief.

## Exported binary assets

Only the canonical `IMG-SCENE*.png` files from the validated 18/08 output commit are exported. Legacy duplicate filenames `start-frame-scene*.png` are deliberately omitted to avoid ambiguity.

| Video | Export file | Source blob SHA | Source bytes |
|---|---|---|---:|
| VIDEO-01 | `2026-08-18/carblazz/VIDEO-01/startframes/SCENE-01.png` | `9807d0f04fddf4d136d60a865c15716d41473336` | 467270 |
| VIDEO-01 | `2026-08-18/carblazz/VIDEO-01/startframes/SCENE-02.png` | `6b3c5337179fa643364fb77d7601ce717023b139` | 473150 |
| VIDEO-01 | `2026-08-18/carblazz/VIDEO-01/startframes/SCENE-03.png` | `6f9a0625bd4ff356d23f5d8016ee09241924d1ff` | 707878 |
| VIDEO-02 | `2026-08-18/carblazz/VIDEO-02/startframes/SCENE-01.png` | `f386278a17c415d3e73752a4fe60207b00211860` | 385934 |
| VIDEO-02 | `2026-08-18/carblazz/VIDEO-02/startframes/SCENE-02.png` | `5e36179a6d3667ffcb0fa7129fcee3dfe47304e7` | 402162 |
| VIDEO-02 | `2026-08-18/carblazz/VIDEO-02/startframes/SCENE-03.png` | `7a0c4d53ec40065beebd015a2a0141b5dfaf42c1` | 577783 |
| VIDEO-03 | `2026-08-18/carblazz/VIDEO-03/startframes/SCENE-01.png` | `37ef8bf882a7cd096a2e91a0756b44c2d1b58908` | 442538 |
| VIDEO-03 | `2026-08-18/carblazz/VIDEO-03/startframes/SCENE-02.png` | `61235d58d05f0b27a5be6c5bc49640eef5834fe7` | 449822 |
| VIDEO-03 | `2026-08-18/carblazz/VIDEO-03/startframes/SCENE-03.png` | `f1addb93306bb14aa4502be6e9a685801caa473b` | 609906 |

All nine canonical PNGs were previously fetched back from GitHub and validated as non-empty PNG binary content, dimensions 941×1672, with SHA-256 equality confirmed by the run report.

## Organic AI constraints for Hermes

- Vertical 9:16; realistic iPhone / social-native Instagram look.
- Product must stay stable, recognizable and geometrically identical; no morphing.
- No malformed/unintended text; no watermark.
- No prohibited brand elements.
- No dominant full face unless a brief explicitly authorizes it.
- Hooks: no emoji unless Apple-native rendering has been explicitly validated.
- Avoid full-width white overlays and duplicated/stacked hooks.
- Carblazz: real clock diameter 35–40 cm; one colorway per video.
- Only the thin seconds hand may move when appropriate; hour/minute hands, wheel, brake disc, caliper and dial remain static.

## Hermes action

`BLOCKED` means **do not generate video from these start frames**. Keep them for traceability/QC only. Use the corrected brief and verified references for any regeneration; never infer a correction from these defective images.