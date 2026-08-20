# Manifest — what each reference file is, exactly

> **Aucun Element Higgsfield dans le workflow automatisé.** Les Elements ne servent que lorsque
> Yann génère lui-même, à la main, dans l'interface web. CLI, MCP et ChatGPT passent
> **exclusivement** par des images de référence attachées, résolues depuis les URL brutes de
> `refs/[marque]/`. Sans Element pour verrouiller l'identité du produit, la fidélité repose
> entièrement sur la start frame : elle est jugée en vision avant le prompt vidéo, et régénérée
> si elle rate une contrainte dure du breakdown.
>
> Lire d'abord `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md` puis
> `product-breakdowns/[MARQUE].md` — le premier porte les règles valables partout (échelle réelle,
> mécanique de packaging, logique des mains, continuité d'état, gates QA), le second dit ce qu'est
> le produit et ce qui ne doit jamais dériver. Ce MANIFEST ne sert qu'à savoir **quel fichier est
> quoi** ; il ne remplace jamais le breakdown.

Read this before fetching any file. Filenames already encode the type via prefix:
`pr` = product, `av` = avatar, `lieu` = location, `prop` = prop (in-scene, not sold).
This file spells out what each one shows and which product it belongs to, so nothing is
guessed from the filename alone.

## refs/onsimplifie/ (brand: Onsimplifie, product: portable dog wash)

| File | Type | What it is |
|---|---|---|
| `ons-pr-douchechien-gray.png` | Product | Portable dog wash/bath stand, gray mesh variant. 7-view sheet: **white tubular X-frame folding legs** with black rubber feet, taut mesh top slung between two tube bars, pierced with **oval holes of varying sizes in an asymmetric layout** (the plate shows eight, not six — count on the plate before writing a number into a prompt), hole trim matches fabric colour. Camping-stool scale: check the dog actually fits. |
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

**Produit de tête = sac coquillage**, référence unique `HANBAG-COQUILLAGE-REF.png` (mise à jour du
2026-08-20). C'est le produit de la séquence 8 scènes validée par Yann. `SHELL-BLOOM.png` est
archivé : c'était un autre sac, utilisé par erreur le 17/08.

| File | Type | What it is |
|---|---|---|
| `HANBAG-COQUILLAGE-REF.png` | Product | **Seule référence valable du sac coquillage.** Grosse maille crochet **blanc pur**, forme de coquillage nautile, volume compact, **côtes rayonnantes**, **rosace en spirale** au centre, **anse en corde blanche épaisse** avec **mousquetons dorés**, **chaîne de perles nacrées amovible**, doublure crème. **Ni fleur crochet, ni pompon** — c'est ce qui le distingue du Marguerite. |

**Second produit = sac crochet Marguerite.** Cinq coloris, ajoutés le 2026-08-17. Toujours
attacher **deux** références ensemble : `FOUR-TOUT-BAG.png` pour la géométrie **et** la planche du
coloris. `MARGUERITE-BLANC` = base crochet beige avec fleurs blanches, pas un blanc uni — ne jamais
la rejeter pour ça. **Les règles des deux sacs ne se mélangent jamais.**

| File | Type | What it is |
|---|---|---|
| `MARGUERITE-BLANC.png` | Product colorway | base beige/tan, fleurs blanches |
| `MARGUERITE-BLEU-MARINE.png` | Product colorway | bleu marine |
| `MARGUERITE-JAUNE.png` | Product colorway | jaune |
| `MARGUERITE-VERT.png` | Product colorway | vert sauge |
| `MARGUERITE-VIOLET.png` | Product colorway | violet |

Fichiers plus anciens, antérieurs à la convention de nommage :

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
| `horloge-carbone.png` | Product | **Hero variant.** Wall clock built as a carbon-fibre alloy wheel seen face-on: glossy woven-carbon spokes with real mechanical depth, a real brake disc and a **yellow brake caliper** visible behind the spokes, slim **gold** hour/minute/second hands, white numerals 1-12 around the rim, black bezel. **Domed glass front, strongly reflective.** No third-party wordmark. |
| `horloge-metal-noir.png` | Product | **Glossy black 5-spoke alloy wheel** (NOT a brushed-metal plate), yellow caliper, brake disc behind. Bezel imitates a **black tyre sidewall** with moulded lettering and small **gold emblems** around the rim. White paddle hands, thin white seconds hand, white numerals 1-12. **Glass front, reflective.** |
| `horloge-metal-rouge.png` | Product | Same construction as metal-noir but a **bright red glossy 5-spoke wheel**. Yellow caliper, black disc, tyre-sidewall bezel with gold emblems, white paddle hands, white numerals. Red must not drift orange or burgundy. **Glass front.** |
| `horloge-compteur.png` | Product | Wall clock built as a vintage car speedometer: matte black dial, white markers + white numerals **10-120 km/h in steps of 10**, **four orange dots at 12/3/6/9**, the `NISMO` wordmark under the 12, a white odometer window reading `170884`, a second window reading `1984`, `km/h` text, white paddle hands + thin white sweep second hand, slim black bezel. **Domed glass front, strong reflection.** |
| `horloge-bois-f1.png` | Product | **There is NO wood on this product — the slug is misleading.** Red/white/black **F1 livery dial** with a top-down **F1 single-seater** printed at the centre, black numerals 1-12, black markers, gold centre hub, black bezel. Face is **flat and matte: NO GLASS.** Never give this variant a glass front or a wood grain. |
| `horloge-packaging.png` | Packaging | **400 x 400 mm matte black sleeve with a large circular cut-out and the `blazz` wordmark, plus an inner drawer that slides out sideways.** Flat, roughly 5 cm deep. **NOT a hinged or lift-off lid box** — never write "lift the lid". Unboxing/delivery scenes only, never the hero product. |

One colorway per video. Never mix two clocks in the same video.

**All five dial descriptions above were re-verified against the plates on 2026-08-20.** Three of
them were wrong in the previous revision, and the 17-18/08 briefs generated products that do not
exist. Trust this table and the plate, never the slug.

**Real diameter: 35-40 cm.** Write the centimetres into any prompt that puts the clock next to a
human, a wall or a piece of furniture.

Do **not** use the files under `ELEMENTS HIGGSFIELD/` on Yann's Mac: they are screenshots of the
Higgsfield "New Element" dialog, full app UI around a 300 px thumbnail. Only the plates above are
references.

Trademark note: the compteur dial carries a third-party automotive wordmark. Keep it as-is when
reproducing the real product, but never build a hook, caption, or brand claim around that mark.

## refs/whiskeysmok/

Empty. No product chosen — do not generate, do not invent a reference.

## Nightly brief drop (Hermes -> here)

`DAILY-BRIEF-[date]-[BRAND].md` files land at the repo root — one per brand per night.

**État réel au 2026-08-20 : Hermès n'a toujours aucun credential GitHub**, donc il ne peut pas
écrire ici. Tous les briefs datés existants ont été poussés à la main. Résultat mesuré : aucun
brief pour le 19 ni le 20/08, et trois runs ChatGPT terminés en `BLOCKED_NO_BRIEF`.

**Le correctif est en place** : trois `STANDING-BRIEF-[BRAND].md` à la racine du dépôt. Si aucun
brief daté n'existe pour la nuit, la tâche planifiée bascule sur le standing brief de la marque et
génère quand même, en faisant tourner concept, coloris et pattern à partir de la date. La chaîne ne
s'arrête plus jamais sur un brief manquant. Un brief daté, quand il existe, prime toujours.
