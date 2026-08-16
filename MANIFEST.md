# Manifest — what each reference file is, exactly

Read this before fetching any file. Filenames already encode the type via prefix:
`pr` = product, `av` = avatar, `lieu` = location, `prop` = prop (in-scene, not sold).
This file spells out what each one shows and which product it belongs to, so nothing is
guessed from the filename alone.

## refs/onsimplifie/ (brand: Onsimplifie, product: portable dog wash)

| File | Type | What it is |
|---|---|---|
| `ons-pr-douchechien-gray.png` | Product | Portable dog wash/bath stand, gray mesh variant. 7-view sheet: folding metal legs, 6 oval leg holes, hole trim matches fabric color. |
| `ons-pr-douchechien-blue.png` | Product | Same product, blue variant. |
| `ons-pr-douchechien-pink.png` | Product | Same product, pink variant. |
| `ons-prop-chien-golden.png` | Prop (not sold) | Golden retriever, wet + dry, 4 angles — recurring "hero" dog for this brand. |
| `ons-prop-chien-petit.png` | Prop (not sold) | Small curly-haired dog — secondary dog for variety. |
| `ons-lieu-sdb.png` | Location | Realistic French bathroom (tile, bathtub) — not a US-style loft. |
| `ons-av-clara.png` | Avatar | Woman 25-35, French, casual outfit — only if a human is needed in frame. |

Never mix product colors in the same video. One product = one video.

## refs/myteaovo/ (brand: Myteaovo, product: decorative plant pots)

| File | Type | What it is |
|---|---|---|
| `myt-pr-pot-style1.png` | Product | Pot style 1 (airplant/fern style). |
| `myt-pr-pot-style2.png` | Product | Pot style 2 (purple succulent style). |
| `myt-pr-pot-style3.png` | Product | Pot style 3 (aloe style). |
| `myt-prop-plante.png` | Prop (not sold) | Plant used in scenes with the pot. |
| `myt-lieu-salon.png` | Location | Bright French living room. |
| `myt-av-julie.png` | Avatar (split-test A) | New avatar, validated 2026-08-06. |
| `CLEMENCE-POTERIE-VF.png` | Avatar (split-test B) | Older locked avatar "Clemence", used in content already posted since June. Both avatars are valid — alternate one per video, never both in the same video, let view performance decide which wins. |

## refs/troputile/ (brand: Troputile, product: drink bag)

| File | Type | What it is |
|---|---|---|
| `tro-pr-sacboisson-sipsway-coralblue.png` | Product | Sipsway drink bag, coral/blue colorway. |
| `tro-pr-sacboisson-sipsway-coralpink.png` | Product | Sipsway drink bag, coral/pink colorway. |
| `tro-pr-sacboisson-sipsway-midnightcharcoal.png` | Product | Sipsway drink bag, charcoal colorway. |
| `tro-pr-sacboisson-aliexpress.png` | Product | Separate, distinct model (AliExpress source) — never mix with the Sipsway variants in one video. |
| `tro-av-groupe.png` | Avatar | Group of 2-3 friends. |
| `tro-lieu-*.png` (13 files) | Location | Lifestyle plates: beach, festival (Solidays), Cannes, Saint-Tropez, La Guerite beach club, Riviera beach club, Trocadero (day/night), Eiffel Tower (night), Parisian apartment (day/evening, with friends). Day/night or day-suffixed variants are separate plates, pick the one matching the scene's time of day. |

Product for a drink bag scene = **one** of the 4 product files above, never more than one per video.

## refs/spiraledazur/ (brand: Spiraledazur, product: crochet handbags)

These predate the naming convention above and were **not renamed** — filenames are the
original ones, matched by their self-descriptive names. If in doubt about which one to use,
check `higgsfield-elements-registry.md` in the vault (not in this repo) for the authoritative
product-to-element mapping, or ask Yann.

| File | Likely content (self-descriptive, unverified 1:1 mapping) |
|---|---|
| `SAC-COWGIRL-REF1.png` / `SAC-COWGIRL-REF2.png` | Cowgirl bag product references. |
| `FOUR-TOUT-BAG.png` | Four Tout Bag product. |
| `MEUF-HANDBAG-V2.png` | Younger woman avatar. |
| `GRANDMA-HANDBAG-V2.png` | Older woman / mentor avatar. |
| `MONOPRIX-RAYON.png` | French retail store location (Monoprix aisle). |
| `HANBAG-REF-3.png`, `NEW-HANDBAG-ALL-COLORS.png`, `HANDBAG-AVATARS-REF.png` | Additional product/avatar reference sheets, content not re-verified here. |
| `CROCHET BIRKIN STYLE.png`, `LEMON BLOSSOM.png`, `SHELL BLOOM.png`, `SUNSET RIVIERA.png` | Named product/color variant sheets. |

## refs/carblazz/ (brand: Carblazz, product: car-themed decorative WALL CLOCKS)

Added 2026-08-16. Niche = **home decor for car enthusiasts**, not in-car accessories.
Filenames match the Higgsfield element slugs exactly (`horloge-compteur`, `horloge-bois-f1`,
`horloge-packaging`) — never rename, never paraphrase these slugs.

All five colorways are complete 7-view sheets, same layout every time: large front, 3/4 left,
pure side profile (shows the shallow depth + wall mount), small-scale front, angled wall shot,
macro on the dial center, macro on one numeral sector. Matte grey-beige wall on every plate.

| File | Type | What it is |
|---|---|---|
| `horloge-carbone.png` | Product | **Hero variant.** Wall clock built as a carbon-fibre alloy wheel seen face-on: glossy woven-carbon spokes, a real brake disc and a **yellow brake caliper** visible behind the spokes, slim gold hour/minute/second hands, white numerals 1-12 around the rim, black bezel. The most visually striking of the five — best choice for a scroll-stopping opening shot. No third-party wordmark. |
| `horloge-metal-noir.png` | Product | Brake-disc/metal colorway, black. |
| `horloge-metal-rouge.png` | Product | Brake-disc/metal colorway, red. |
| `horloge-compteur.png` | Product | Wall clock built as a vintage car speedometer: black dial, white markers + white numerals 10-120 km/h, orange dot accents at 12/3/6/9, an automotive wordmark under the 12, a white odometer window reading `170884` and a second window reading `1984`, thin white sweep second hand, slim black bezel. |
| `horloge-bois-f1.png` | Product | Wood / F1-themed colorway. |
| `horloge-packaging.png` | Packaging | Retail box — unboxing/delivery scenes only, never the hero product. |

One colorway per video. Never mix two clocks in the same video.

Do **not** use the files under `ELEMENTS HIGGSFIELD/` on Yann's Mac: they are screenshots of the
Higgsfield "New Element" dialog, full app UI around a 300 px thumbnail. Only the plates above are
references.

Trademark note: the compteur dial carries a third-party automotive wordmark. Keep it as-is when
reproducing the real product, but never build a hook, caption, or brand claim around that mark.

## refs/whiskeysmok/

Empty. No product chosen — do not generate, do not invent a reference.

## Nightly brief drop (Hermes -> here)

`DAILY-BRIEF-[date]-[BRAND].md` files land at the repo root (or a `briefs/` folder once
Hermes starts pushing them) — one per brand per night, per
`wiki/ecom-organic/daily-content-pipeline-v1.md`. Not set up yet as of 2026-08-06 — Hermes
needs push credentials for this repo before it can write here.
