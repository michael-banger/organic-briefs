# DAILY BRIEF — CARBLAZZ — publication 2026-08-17

- Marché : **US**, anglais américain. Aucune ligne de texte en français.
- Produit : **horloge murale de décoration pour passionnés d'automobile**. Déco de maison, jamais
  un accessoire d'habitacle. Le client n'a pas forcément la voiture — il affiche sa passion chez lui.
- Lane : **KLING** — start frames 9:16 par ChatGPT, puis vidéo image-to-video, audio désactivé.
- 3 posts, **un coloris différent par post**, jamais deux horloges dans la même vidéo.
- Concurrent de référence : `@carwake.co` (179,2 K abonnés, 6,67 M de vues sur « Comment "Lights"
  if you need this », 03/08). **Il vend un autre produit.** On transplante sa mécanique — décor
  automobile identifiable, reveal, tribu — pas son produit. C'est explicite et assumé : aucun
  concurrent direct n'existe sur l'horloge murale auto.

## Règles verrouillées qui s'appliquent à ce brief

- **CTA à mot-clé maintenu** — Yann confirme le 17/08 que le mot-clé déclenche ManyChat.
  Mot-clé unique pour la marque : **CLOCK**. Caption US : `Comment "CLOCK" for the link`.
  Exception au post 3 : un bait « send this to » vise le partage en DM, il ne se mélange jamais
  avec un mot-clé.
- Tout prompt de génération dit **« this clock »**, jamais « a clock like… », jamais le nom de la
  marque, jamais le nom du concurrent.
- Slugs de référence cités **verbatim** : `horloge-carbone`, `horloge-compteur`, `horloge-metal-rouge`.
- 3 références maximum par image.
- Aucun texte écrit dans l'image. Le hook est un overlay ajouté au montage.
- Durée cible du montage : **8-12 s**. La médiane du batch viral d'août est à 10 s.
- Passe vision obligatoire sur chaque start frame produite avant d'écrire le prompt vidéo.

## Références

| Slug | URL brute |
|---|---|
| `horloge-carbone` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/carblazz/horloge-carbone.png |
| `horloge-compteur` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/carblazz/horloge-compteur.png |
| `horloge-metal-rouge` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/carblazz/horloge-metal-rouge.png |

Pas d'avatar, pas de planche de lieu : les décors sont décrits en texte dans chaque prompt.
Le visage n'apparaît jamais en entier — trois des quatre meilleurs concurrents du batch sont
sous 20 % de visage à l'écran, et le meilleur est à 0 %.

---

## POST 1 — Carbone — pattern P1 (produit en contexte aspirationnel)

- `lane: KLING`
- `post_id: 1`
- `colorway: horloge-carbone`
- `pattern: P1`
- `hook_overlay:` **"POV: your garage has better taste than your living room"**
- `caption:` "Carbon fibre, brake caliper, real wheel spokes. It just tells time too. 🕒 Link in bio"
- `cta_keyword:` **CLOCK** — CTA mot-clé ManyChat, en anglais : `Comment "CLOCK" for the link`.
  Marché US : guillemets droits anglais. La règle des guillemets français « » ne vaut que pour les
  captions françaises.
- `hashtags:` #carguy #garagegoals #cardecor #carenthusiast #mancave

Mécanique : on ouvre sur l'environnement, pas sur le produit. C'est la leçon du reel à 6,67 M —
plan 1 = décor reconnaissable, plan 2 = le produit qui s'y intègre, plan 3 = le détail qui prouve
la matière. L'horloge carbone est la variante la plus spectaculaire des cinq : c'est celle qui
supporte un reveal.

**Scène 1 — le décor, sans le produit**
> A dark modern home garage at night, one performance car parked in profile under a single
> overhead strip light, polished concrete floor with soft reflections, tool wall in shadow,
> empty bare wall on the right side of the frame. Vertical 9:16, photorealistic, cool white and
> deep black palette, no text, no logo, no watermark, no people.
> Refs : aucune.

**Scène 2 — le reveal**
> The same dark garage wall, now with this clock mounted on it, lit by the overhead strip light.
> Reproduce this clock exactly as in the reference: carbon-fibre alloy-wheel face, yellow brake
> caliper visible behind the spokes, slim gold hands, white numerals, black bezel. Vertical 9:16,
> photorealistic, no text, no logo, no watermark, no people.
> Refs : `horloge-carbone`.

**Scène 3 — la preuve de matière**
> Macro shot of this clock's face, camera close on the woven carbon-fibre spokes and the yellow
> brake caliper behind them, gold second hand crossing the frame, shallow depth of field, single
> warm key light raking across the weave. Vertical 9:16, photorealistic, no text, no logo, no
> watermark.
> Refs : `horloge-carbone`.

Prompt vidéo, après passe vision — intention à réajuster sur l'image réelle :
1. lent travelling avant vers le mur vide, la lumière ne bouge pas ;
2. même axe, l'horloge est là, léger parallaxe ; le mouvement doit venir de la caméra, pas de l'objet ;
3. la trotteuse dorée avance, rien d'autre ne bouge. Aucun morphing du cadran, aucune dérive de couleur.

---

## POST 2 — Compteur — pattern P4 (fandom lock, fake-out reveal)

- `lane: KLING`
- `post_id: 2`
- `colorway: horloge-compteur`
- `pattern: P4`
- `hook_overlay:` **"I told him it was a speedometer. He believed me for 3 hours."**
- `caption:` "It's a clock. It has always been a clock. 🕒 Link in bio"
- `cta_keyword:` **CLOCK** — CTA mot-clé ManyChat, en anglais : `Comment "CLOCK" for the link`.
  Marché US : guillemets droits anglais. La règle des guillemets français « » ne vaut que pour les
  captions françaises.
- `hashtags:` #jdm #carguy #cardecor #petrolhead #giftforhim

Mécanique du fake-out reveal, celle du reel à 967 K : on laisse croire à autre chose, puis on
révèle. Ici la confusion est **dans le produit lui-même** — le cadran est un compteur de vitesse,
la révélation est qu'il donne l'heure. Le hook porte toute la vidéo, les plans restent sobres.

**Scène 1 — le doute**
> Extreme close-up on this clock's dial, filling the frame like a real car instrument cluster:
> black dial, white markers, white numerals from 10 to 120, orange dot accents, the white odometer
> window. Reproduce this object exactly as in the reference. Shot slightly off-axis as if seen from
> a driver's seat, warm interior light. Vertical 9:16, photorealistic, no text overlay, no logo,
> no watermark.
> Refs : `horloge-compteur`.

**Scène 2 — l'échelle qui trahit**
> Wide shot pulling back: this clock is mounted on a plain warm-grey living room wall next to a
> narrow shelf with two small objects, daylight from the left. The scale now reads clearly as wall
> decor, not a car part. Vertical 9:16, photorealistic, no text, no logo, no watermark, no people.
> Refs : `horloge-compteur`.

**Scène 3 — la main**
> A man's hand entering frame from the right, adjusting this clock slightly straighter on the wall,
> only the hand and forearm visible, casual dark sleeve, warm daylight. Vertical 9:16,
> photorealistic, no face, no text, no logo, no watermark.
> Refs : `horloge-compteur`.

Prompt vidéo, après passe vision :
1. micro-mouvement de la trotteuse, caméra fixe — l'ambiguïté doit tenir ;
2. dézoom lent et régulier, aucune coupe, la révélation vient de l'échelle ;
3. la main ajuste, se retire, la trotteuse continue. Anatomie de la main à vérifier en QC.

---

## POST 3 — Métal rouge — pattern P1 + P5 (cadeau / send-this-to)

- `lane: KLING`
- `post_id: 3`
- `colorway: horloge-metal-rouge`
- `pattern: P1 + P5`
- `hook_overlay:` **"Send this to the guy who has everything"**
- `caption:` "He has three watches and nothing on the wall. Fix that. 🕒 Link in bio"
- `cta_keyword:` aucun — le bait « send this to » vise le partage en DM, pas le commentaire.
  Ne jamais le mélanger avec un CTA à mot-clé, même quand l'auto-DM sera en place.
- `hashtags:` #giftforhim #carguy #cardecor #birthdaygift #mancave

**Scène 1 — le mur vide au-dessus du bureau**
> A tidy home office corner at golden hour, dark wood desk, a closed laptop, a single car model on
> a shelf, and a large empty warm-grey wall above it. Vertical 9:16, photorealistic, warm low sun
> from the left, no text, no logo, no watermark, no people.
> Refs : aucune.

**Scène 2 — le produit posé**
> The same home office corner, now with this clock mounted on the empty wall above the desk.
> Reproduce this clock exactly as in the reference: red brake-disc styled face, metal detailing,
> black bezel. Golden hour light raking across it. Vertical 9:16, photorealistic, no text,
> no logo, no watermark, no people.
> Refs : `horloge-metal-rouge`.

**Scène 3 — le détail rouge**
> Macro on this clock's red metal face, low warm sunlight sliding across the brushed surface,
> shallow depth of field, the hands crisp in focus. Vertical 9:16, photorealistic, no text,
> no logo, no watermark.
> Refs : `horloge-metal-rouge`.

Prompt vidéo, après passe vision :
1. très léger travelling latéral, la lumière dorée se déplace sur le mur vide ;
2. même décor, produit en place, caméra qui monte doucement vers lui ;
3. la lumière glisse sur le métal, l'aiguille avance. Aucun changement de couleur du rouge.

---

## Ce qui bloque encore la chaîne, à ne pas contourner

- Le CLI Higgsfield n'est pas installé sur Hermès : la génération Kling ne peut pas partir de
  son côté. Si ChatGPT tient la chaîne bout en bout via son MCP Higgsfield, il la tient seul.
- La tâche planifiée ChatGPT tourne à **22:00 Europe/Paris**. Ce brief étant déposé après cette
  heure, la première exécution automatique possible est le soir du 17/08. Pour ce soir, la tâche
  doit être déclenchée à la main.
- Convention de nommage : ce fichier porte la **date de publication**. Si la tâche ChatGPT
  cherche `DAILY-BRIEF-{today}`, elle ne le trouvera pas le 16 au soir. Voir la note dans
  `SYSTEM/PROMPT-STARTFRAMES.md`.
