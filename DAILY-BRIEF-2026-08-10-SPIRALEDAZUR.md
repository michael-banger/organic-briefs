---
date: 2026-08-10
brand: SPIRALEDAZUR
market: FR
account: "@spiraledazur"
batch: PIVOT-CROCHET-MARGUERITE
videos_locked: 7
boards_per_video: 3 (concept 1-6) / 1 (concept 7)
pattern_source: outlier post 2026-08-09, reel Db1EvUxRzpo (220 likes / 24 comments / 9 shares / 45k vues en ~21h, vs baseline compte 6-19 likes)
---

# SPIRALEDAZUR — Sac seau crochet fleurs, pivot prioritaire

Tout le volume de prod va sur ce produit jusqu'à validation. Sac cowgirl en pause.

## PRODUIT — verrous à tout instant
Sac seau en crochet, base beige/tan, grosses fleurs crochet ton sur ton (motif floral tout autour, PAS un motif léopard), une breloque fleur crochet + pompon-tassel assorti à la couleur, anse crochet courte + bandoulière longue amovible — **les deux anses/points d'attache doivent rester visibles, y compris sac ouvert (what's in my bag)**.
5 coloris réels : Blanc, Violet, Jaune, Bleu marine, Vert sauge. Prix **39,99 €**, format FR, uniquement quand un prix est visible à l'écran (jamais sur les décors marché/stand).
Refs locales : `~/Desktop/REFS-ORGA-AI/SPIRALEDAZUR/MARGUERITE/MARGUERITE-{BLANC,VIOLET,JAUNE,BLEU-MARINE,VERT}.png`, `NEW-HANDBAG-ALL-COLORS.png`, `MONOPRIX-RAYON.png`, `HANDBAG-AVATARS-REF.png`.

**Règle prompt (tous outils, toutes générations) : ne jamais nommer la marque, le compte Instagram ou l'entreprise dans un prompt de génération.** Décrire "this crochet bucket bag" / "this crochet flower charm" et renvoyer à la réf attachée. Les noms de lieux réels dépeints à l'écran (Monoprix, Zara) restent autorisés : ce sont des décors de la scène, pas des infos internes.

**Règle tenue (verrou ajouté 2026-08-10, tout board avec avatar/personnes visibles) : tenue d'été obligatoire, sans exception.** Manches courtes ou sans manches, bras nus, tissu léger, aucune pièce d'hiver visible même partiellement (pas de manche longue, pas de pull, pas de veste), peu importe l'avatar ou la réf utilisée. Ligne à inclure telle quelle dans chaque `seedance_prompt` concerné : "MANDATORY WARDROBE: light summer outfit only, short sleeves or sleeveless, bare arms, light summer fabric. NO long sleeves, NO jacket, NO sweater, NO winter clothing of any kind, even partially visible."

## TEST TECHNIQUE — durée de génération (Board 1, Post 1 uniquement)
Objectif : trancher 8s vs 12s de rendu continu Seedance sur la fidélité produit et la cohérence de mouvement, à réf/prompt strictement identiques.
- **Run A** : Board 1 généré en un seul clip continu de 8s (contenu = rayon + main qui attrape, comme scindé ci-dessous en 0:00-0:08).
- **Run B** : même contenu étendu à un seul clip continu de 12s (0:00-0:12, mêmes 2 actions mais rythme réparti sur 12s au lieu de 8s).
- Comparer : dérive de forme/coloris en fin de clip, fluidité du mouvement de foule, artefacts sur les mains. Décision appliquée aux 6 autres concepts une fois tranchée.
- Réglages fixes : Seedance 2.5, 9:16, 720p, Bitrate High, **Unlimited vérifié avant CHAQUE Generate**.

## SON — rotation verrouillée (compte)
1. Gunter Kallmann Choir — Daydream (son du post gagnant, priorité)
2. Santo & Johnny — And I Love Her (instrumental, même couloir nostalgique, zéro voix)
3. jkl — sweetly (71.78) (instrumental aesthetic, tendance IG 08/2026)
4. Fleetwood Mac — Sometimes (intemporel, couloir chaud)
Concept 7 (contemplatif) : **son original / bruit du produit**, pas de musique — dérogation volontaire, cf. concept.

## HOOK verrouillé pour cette série (posts 1-6)
Ligne 1 (overlay + caption) : hook validé par Yann le 2026-08-10, à reprendre tel quel — voir échange chat, ne pas régénérer une variante automatiquement.
CTA constant : « Commentez « Soleil » pour recevoir les infos 🕶️☀️👜 »
Hashtags constants : `#fashion #handmade #ete #sac #bag`

## STRUCTURE VERROUILLÉE (posts 1-6) — clone du post gagnant, 6 plans, ~12,4s
| Plan | Durée | Contenu |
|---|---|---|
| 1 | 2,25s | rayon/stand plein, plusieurs femmes de dos raflent les sacs (tous coloris visibles) |
| 2 | 1,04s | une main attrape LE sac de la couleur du jour |
| 3 | 4,47s | what's in my bag sur un lit — objets d'été/quotidien + 1 objet WTF (humour, ex. menottes fantaisie) |
| 4 | 1,16s | mise dans le tote |
| 5 | 1,86s | transition rue |
| 6 | 1,67s | marche dans Paris, sac porté, avatar de dos/de profil, jamais de face |

---

## POST 1 — Marché de rue parisien (PRIORITÉ #1)
- product_color: Blanc
- pattern_ref: reel Db1EvUxRzpo (post gagnant, même compte)
- split_test_variable: décor (vs Monoprix original)
- sound: 1. Daydream
- duration_target_s: 12.4
- face_ratio_target: ≤17%

### Boards
Board 1/3 — role: hook rayon/stand + main qui attrape (0-8s) — **TEST 8s vs 12s, voir section dédiée**
  refs: ["MARGUERITE-BLANC.png", "NEW-HANDBAG-ALL-COLORS.png", "HANDBAG-AVATARS-REF.png"]
  seedance_prompt: "One continuous vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, outdoor natural daylight, handheld micro-movement, French open-air street market stall with a neat awning, wicker baskets and summer produce around the edges. 0:00-0:02 a well-organized market stall table lined with crochet flower bucket bags in five colors, clearly displayed. 0:02-0:05 several women crowd the stall, reaching and picking up bags, animated but not chaotic. 0:05-0:08 one hand reaches into frame and picks up the white crochet flower bucket bag. MANDATORY WARDROBE: light summer outfit only, short sleeves or sleeveless, bare arms, light summer fabric. NO long sleeves, NO jacket, NO sweater, NO winter clothing of any kind, even partially visible. Preserve exact bag geometry, crochet texture, flower charm and tassel from the product reference at all times. No price tag visible anywhere in this board. Natural outdoor market ambience only. No text rendered in image, no logo, no watermark, no music, no subtitles, no dialogue, no morphing, no deformation, no color drift, no extra or abnormal hands, no cinematic ad polish."
  reference_slots: "@Image 1 = MARGUERITE-BLANC.png · @Image 2 = NEW-HANDBAG-ALL-COLORS.png · @Image 3 = HANDBAG-AVATARS-REF.png"

Board 2/3 — role: what's in my bag sur lit, mains uniquement (0-8s)
  refs: ["MARGUERITE-BLANC.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, soft indoor daylight on a bed with light linen, hands only — no face visible. 0:00-0:02 overhead shot, the white crochet flower bucket bag sits open on the bed, both handle and the crossbody strap clearly visible and attached. 0:02-0:04 hands lay out summer everyday items next to it: sunglasses, a phone, a lip balm, keys. 0:04-0:06 hands place one playful unexpected item into the scene (novelty fuzzy pink handcuffs) next to the other items, casual placement, not a focal close-up. 0:06-0:08 hands gather items back toward the bag. Preserve exact bag geometry, crochet texture, flower charm, tassel and both handles from the product reference at all times. Natural room ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue, no morphing, no deformation, no color drift, no extra or abnormal hands."
  reference_slots: "@Image 1 = MARGUERITE-BLANC.png"

Board 3/3 — role: mise dans tote + marche dans Paris de dos (0-8s)
  refs: ["MARGUERITE-BLANC.png", "HANDBAG-AVATARS-REF.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, natural daylight. 0:00-0:02 hands place the white crochet flower bucket bag, closed, into a larger tote bag. 0:02-0:03 quick transition cut to an exterior Parisian street. 0:03-0:08 a young woman seen from behind or in profile only, walking down a Haussmann-style Parisian street in bright sunny summer daylight, pale stone facades and wrought-iron balconies in the background, camera follows from behind at walking pace. From 0:03 onward the crochet flower bucket bag itself (not the tote) is the visible focal object on her shoulder, clearly identifiable and not obscured by the tote's fabric, swinging naturally with both handles visible. She never turns to face the camera. MANDATORY WARDROBE: light summer outfit only, short sleeves or sleeveless, bare arms, light summer fabric. NO long sleeves, NO jacket, NO sweater, NO winter clothing of any kind, even partially visible. Preserve exact bag geometry, colorway and both handles from the product reference. Natural street ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue, no face drift, no posed runway walk, no cinematic ad polish."
  reference_slots: "@Image 1 = MARGUERITE-BLANC.png · @Image 2 = HANDBAG-AVATARS-REF.png"

---

## POST 2 — Marché de rue parisien
- product_color: Jaune
- split_test_variable: coloris (vs Post 1)
- sound: 1. Daydream

### Boards
Identiques à Post 1, refs remplacées par `MARGUERITE-JAUNE.png`, même prompts avec "yellow crochet flower bucket bag".

---

## POST 3 — Rayon accessoires boutique mode
- product_color: Violet
- pattern_ref: pattern-level, mécanique rayon/stand identique
- split_test_variable: décor
- sound: 2. And I Love Her

### Boards
Board 1/3 — role: rayon boutique + main qui attrape (0-8s)
  refs: ["MARGUERITE-VIOLET.png", "NEW-HANDBAG-ALL-COLORS.png", "HANDBAG-AVATARS-REF.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, bright modern clothing store interior, accessories display wall with neat rounded shelving, warm retail lighting. 0:00-0:02 medium shot of a well-organized accessories shelf: several crochet flower bucket bags in five colors lined up. 0:02-0:05 several women browse and pick up bags from the shelf. 0:05-0:08 one hand reaches into frame and takes the violet crochet flower bucket bag off the shelf. MANDATORY WARDROBE: light summer outfit only, short sleeves or sleeveless, bare arms, light summer fabric. NO long sleeves, NO jacket, NO sweater, NO winter clothing of any kind, even partially visible. Preserve exact bag geometry, crochet texture, flower charm and tassel from the product reference at all times. No price tag visible. Natural store ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue, no morphing, no deformation, no color drift, no extra or abnormal hands, no cinematic ad polish."
  reference_slots: "@Image 1 = MARGUERITE-VIOLET.png · @Image 2 = NEW-HANDBAG-ALL-COLORS.png · @Image 3 = HANDBAG-AVATARS-REF.png"

Board 2/3 et 3/3 : identiques à Post 1 (what's in my bag + tote/rue), refs remplacées par `MARGUERITE-VIOLET.png`.

---

## POST 4 — Concept-store / boutique déco chaleureuse
- product_color: Bleu marine
- split_test_variable: décor
- sound: 2. And I Love Her

### Boards
Board 1/3 — role: présentoir boutique chaleureuse + main qui attrape (0-8s)
  refs: ["MARGUERITE-BLEU-MARINE.png", "NEW-HANDBAG-ALL-COLORS.png", "HANDBAG-AVATARS-REF.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, small concept-store interior, warm ambient lighting, wooden display table, curated aesthetic. 0:00-0:02 medium shot of a neatly curated table display: several crochet flower bucket bags in five colors arranged on a wooden table. 0:02-0:05 several women browse and pick up bags from the table, warm relaxed atmosphere. 0:05-0:08 one hand reaches into frame and takes the navy blue crochet flower bucket bag from the table. MANDATORY WARDROBE: light summer outfit only, short sleeves or sleeveless, bare arms, light summer fabric. NO long sleeves, NO jacket, NO sweater, NO winter clothing of any kind, even partially visible. Preserve exact bag geometry, crochet texture, flower charm and tassel from the product reference at all times. No price tag visible. Natural store ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue, no morphing, no deformation, no color drift, no extra or abnormal hands, no cinematic ad polish."
  reference_slots: "@Image 1 = MARGUERITE-BLEU-MARINE.png · @Image 2 = NEW-HANDBAG-ALL-COLORS.png · @Image 3 = HANDBAG-AVATARS-REF.png"

Board 2/3 et 3/3 : identiques à Post 1, refs remplacées par `MARGUERITE-BLEU-MARINE.png`.

---

## POST 5 — Rayon grande surface (regen fidèle à l'original)
- product_color: Blanc
- pattern_ref: reel Db1EvUxRzpo — reproduction fidèle du décor gagnant, prise 2
- split_test_variable: aucune (répétition contrôle)
- sound: 1. Daydream

### Boards
Board 1/3 — role: rayon grande surface + main qui attrape (0-8s)
  refs: ["MARGUERITE-BLANC.png", "MONOPRIX-RAYON.png", "HANDBAG-AVATARS-REF.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, bright French supermarket accessories aisle, neat white shelving under fluorescent retail lighting, matching the attached store reference layout. 0:00-0:02 medium shot of the shelf: several crochet flower bucket bags in five colors lined up on the shelf. 0:02-0:05 several women reach and pick up bags from the shelf, animated crowd. 0:05-0:08 one hand reaches into frame and takes the white crochet flower bucket bag off the shelf. MANDATORY WARDROBE: light summer outfit only, short sleeves or sleeveless, bare arms, light summer fabric. NO long sleeves, NO jacket, NO sweater, NO winter clothing of any kind, even partially visible. Preserve exact bag geometry, crochet texture, flower charm and tassel from the product reference, and preserve the exact shelf layout and lighting from the store reference. No price tag visible in this board. Natural store ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue, no morphing, no deformation, no color drift, no extra or abnormal hands, no cinematic ad polish."
  reference_slots: "@Image 1 = MARGUERITE-BLANC.png · @Image 2 = MONOPRIX-RAYON.png · @Image 3 = HANDBAG-AVATARS-REF.png"

Board 2/3 et 3/3 : identiques à Post 1.

---

## POST 6 — Magasin non identifiable (split test sans levier enseigne)
- product_color: Vert sauge
- split_test_variable: présence/absence d'un décor d'enseigne reconnaissable (vs Posts 1-5)
- sound: 3. sweetly (71.78)

### Boards
Board 1/3 — role: rayon générique non identifiable + main qui attrape (0-8s)
  refs: ["MARGUERITE-VERT.png", "NEW-HANDBAG-ALL-COLORS.png", "HANDBAG-AVATARS-REF.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, generic bright retail interior with plain neutral shelving, no visible store branding, signage, or logos anywhere in frame. 0:00-0:02 medium shot of a plain shelf: several crochet flower bucket bags in five colors lined up. 0:02-0:05 several women reach and pick up bags from the shelf. 0:05-0:08 one hand reaches into frame and takes the sage green crochet flower bucket bag off the shelf. MANDATORY WARDROBE: light summer outfit only, short sleeves or sleeveless, bare arms, light summer fabric. NO long sleeves, NO jacket, NO sweater, NO winter clothing of any kind, even partially visible. Preserve exact bag geometry, crochet texture, flower charm and tassel from the product reference at all times. No price tag, no store name, no logo anywhere in this board. Natural store ambience only. No text, no watermark, no music, no subtitles, no dialogue, no morphing, no deformation, no color drift, no extra or abnormal hands, no cinematic ad polish."
  reference_slots: "@Image 1 = MARGUERITE-VERT.png · @Image 2 = NEW-HANDBAG-ALL-COLORS.png · @Image 3 = HANDBAG-AVATARS-REF.png"

Board 2/3 et 3/3 : identiques à Post 1, refs remplacées par `MARGUERITE-VERT.png`.

---

## POST 7 — Format contemplatif (test de concept entier, pas un hook)
- product_color: Blanc
- pattern_ref: reel externe grand compte crochet US, ~41M vues (référence format, produit différent — cardigan crocheté à la main) — clone du FORMAT uniquement, pas repost
- split_test_variable: format entier (lent/contemplatif/son original vs rapide/musique/multi-plans)
- sound: son original / bruit du produit, PAS de musique
- caption: "Vous l'aimez ? 🥹❤️"
- hook_overlay: aucun — la caption porte tout le hook, comme sur la référence
- cta_keyword: aucun CTA commercial dans ce post — test pur de mécanique d'engagement
- duration_target_s: 8-10 (rythme lent, un seul plan continu)
- face_ratio_target: 0% (mains uniquement) — pas d'avatar grand-mère/enfant sur ce premier test

### Boards
Board 1/1 — role: manipulation lente du produit, mains uniquement, gros plan sur les détails (0-8s)
  refs: ["MARGUERITE-BLANC.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, extreme realism, soft warm indoor natural light, slow contemplative pacing, hands only, no face. 0:00-0:02 hands slowly lift the white crochet flower bucket bag into frame, holding it gently by the handle. 0:02-0:04 hands slowly rotate the bag to reveal the crochet flower charm and tassel in close-up. 0:04-0:06 fingers gently trace the crochet texture of the flower pattern. 0:06-0:08 the bag rests held at chest height, both handles visible, natural light catching the texture. Preserve exact bag geometry, crochet texture, flower charm and tassel from the product reference at all times. Ambient natural room sound only (fabric handling, soft background noise) — absolutely no music. No text, no logo, no watermark, no subtitles, no dialogue, no morphing, no deformation, no color drift, no extra or abnormal hands, no fast cuts, no cinematic ad polish."
  reference_slots: "@Image 1 = MARGUERITE-BLANC.png"

---

## Anti-morphing — check-list 5 points (appliquer à CHAQUE génération)
1. Tranches temporelles explicites, une action par tranche.
2. Coupes franches, jamais de fondu entre objets.
3. Verrou écrit forme + crochet + fleurs + coloris + deux anses, à tout instant.
4. Négatifs écrits systématiques : no morphing, no deformation, no color drift, no extra/abnormal hands, no cinematic ad polish.
5. Visionnage réel de chaque sortie avant validation — rejet + relance gratuite (Unlimited), rejets comptés dans le rapport de session.

## Livrable montage
Semi-manuel : Claude génère + télécharge + range les rushs, **Yann monte manuellement** sur ce produit pour l'instant. Brief de montage transmis dès que tous les rushs d'une vidéo sont prêts (pas en bloc).

## SON — détail Hermès
3-4 sons max en rotation sur @spiraledazur (liste ci-dessus). Le son ne change pas au sein d'une même série de split test tant que la variable testée n'est pas le son. CTA caption verrouillé sur posts 1-6 : « Commentez « Soleil » pour recevoir les infos ».
