---
date: 2026-08-07
brand: ONSIMPLIFIE
market: FR
account: "@onsimplifie"
batch: NIGHT-PROD-12
videos_locked: 3
boards_per_video: 3
---

# ONSIMPLIFIE — 3 vidéos SEEDANCE verrouillées

Structure source : analyse frame-par-frame de @thesilentdoggy (13 s / 8 plans / ~8 % de visage
humain, 64,1K likes, 5,5K commentaires).
Mécanique : **hook d'interdiction + curiosité mécanique** — le plan 1 (32 % de la vidéo) montre
un objet qu'on déplie sans qu'on comprenne à quoi il sert. La curiosité tient le hook seule.
Visage humain quasi nul. **La star émotionnelle est le chien.**
Arc du chien obligatoire : hésitation avant → détente visible dès que le produit résout le
problème (corps relâché, gueule légèrement ouverte, halètement doux, regard rassuré).
Jamais de sourire humain plaqué sur l'animal.

## POST 1
- lane: SEEDANCE
- product: Table de douche pour chien — coloris blue
- pattern: hook d'interdiction + curiosité mécanique
- pattern_ref: thesilentdoggy 64,1K 2026-07-31 (frame-by-frame 13s / 8 plans / plan 1 = 4,2s dépliage)
- split_test_variable: hook
- concept: On déplie un objet bleu incompréhensible en plongée pendant 4 secondes, puis déballage, installation dans la douche, et le chien est lavé dessus, visiblement détendu.
- hook_overlay: "Montrez surtout pas ça aux parents de chiens"
- cta_keyword: TOUTOU
- caption: "Commente 'TOUTOU' et je t'envoie le lien"
- hashtags: ["#chien", "#toilettagechien", "#astucechien", "#proprietairedechien"]
- accounts: ["@onsimplifie"]
- sound_mood: ambiance naturelle de salle de bain, eau — pas de musique
- duration_target_s: 13
- face_ratio_target: 8%

### Boards
Board 1/3 — role: HOOK curiosité mécanique, mains uniquement (0-8s)
  refs: ["ons-pr-douchechien-blue.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, indoor daylight, high-angle top-down view looking down at the floor, hands only — no face visible at any point. 0:00-0:03 two hands hold a folded blue and white object and slowly unfold it, the purpose not yet readable. 0:03-0:05 the hands rotate it, revealing a mesh surface and thin white metal legs. 0:05-0:07 the legs are pulled open and lock into position with a clear mechanical motion. 0:07-0:08 the object now stands as a low folding table, still ambiguous in purpose. Preserve exact product geometry, materials, colorway and folding mechanism from the reference. Realistic hinge behaviour and gravity. Natural room ambience and light mechanical sounds only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product deformation, no floating, no morphing, no extra hands, no legs appearing or disappearing."
  reference_slots: "@Image 1 = ons-pr-douchechien-blue.png"

Board 2/3 — role: déballage + installation salle de bain (0-8s)
  refs: ["ons-pr-douchechien-blue.png", "ons-lieu-sdb.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, soft bathroom daylight, hands only — no face visible. 0:00-0:02 the product wrapped in clear plastic packaging resting on a living-room table, hands begin to unwrap it. 0:02-0:04 the plastic is pulled away, the blue mesh surface revealed. 0:04-0:06 cut to a French bathroom: hands carry the folded table into the shower area. 0:06-0:08 the table is unfolded and set down inside the shower, legs stable on the tiled floor. Preserve exact product geometry, materials and colorway. Realistic weight and gravity. Natural bathroom ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product deformation, no size change between shots, no morphing."
  reference_slots: "@Image 1 = ons-pr-douchechien-blue.png · @Image 2 = ons-lieu-sdb.png"

Board 3/3 — role: le chien sur la table, arc émotionnel (0-8s)
  refs: ["ons-pr-douchechien-blue.png", "ons-prop-chien-golden.png", "ons-lieu-sdb.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, bathroom daylight, human presence limited to hands and forearms only. 0:00-0:02 a medium-sized dog stands on the blue mesh table inside the shower, body slightly tense, ears back, hesitant. 0:02-0:04 a hand gently strokes its back and begins to lather shampoo, the dog's body visibly relaxes, shoulders drop. 0:04-0:06 a handheld shower head rinses the dog, water running through the mesh and draining below, the dog now calm with mouth slightly open and soft panting, bright relaxed eyes. 0:06-0:08 close-up on the dog's paw resting on the mesh, then a hand gently lifts it. The dog must never show a human-like smile. Preserve exact product geometry, mesh structure and colorway. Water behaves realistically and drains through the mesh. Natural water and bathroom ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No dog identity change, no product deformation, no dog floating, no anxious expression after the washing begins."
  reference_slots: "@Image 1 = ons-pr-douchechien-blue.png · @Image 2 = ons-prop-chien-golden.png · @Image 3 = ons-lieu-sdb.png"

## POST 2
- lane: SEEDANCE
- product: Table de douche pour chien — coloris gray
- pattern: hook d'interdiction, variante formulation
- pattern_ref: thesilentdoggy 64,1K (structure), sips_way 110,5K (formule d'interdiction)
- split_test_variable: hook (formulation de l'interdiction)
- concept: Même structure mais le hook cible l'aveu de galère plutôt que l'interdiction pure. Petit chien cette fois, pour tester la taille d'animal.
- hook_overlay: "Laver mon chien c'était l'enfer... jusqu'à ça"
- cta_keyword: TOUTOU
- caption: "Commente 'TOUTOU' pour le lien"
- hashtags: ["#chien", "#petitchien", "#toilettage", "#astucemaison"]
- accounts: ["@onsimplifie"]
- sound_mood: ambiance naturelle — pas de musique
- duration_target_s: 13
- face_ratio_target: 8%

### Boards
Board 1/3 — role: HOOK problème avant produit (0-8s)
  refs: ["ons-prop-chien-petit.png", "ons-lieu-sdb.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, bathroom daylight, hands and forearms only — no face visible. 0:00-0:03 a small dog stands in a wet bathtub, clearly reluctant, body low, trying to step away as hands try to hold it still. 0:03-0:05 water splashes, the dog shakes itself, the scene reads as a struggle. 0:05-0:08 a hand wipes the fogged shower screen, the bathtub visibly messy, conveying frustration without any face on screen. The dog is uncomfortable but never distressed or mistreated. Natural bathroom and water ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No dog identity change, no rough handling, no cinematic ad polish."
  reference_slots: "@Image 1 = ons-prop-chien-petit.png · @Image 2 = ons-lieu-sdb.png"

Board 2/3 — role: le produit arrive, dépliage mécanique (0-8s)
  refs: ["ons-pr-douchechien-gray.png", "ons-lieu-sdb.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, indoor daylight, hands only — no face visible. 0:00-0:02 high-angle view: hands hold a folded grey and white object. 0:02-0:04 they unfold it, mesh surface and thin metal legs appearing. 0:04-0:06 the legs lock open with a clear mechanical motion. 0:06-0:08 the unfolded table is carried into the shower and set down on the tiled floor, stable. Preserve exact product geometry, materials, colorway and folding mechanism. Realistic hinge behaviour and gravity. Natural room ambience and light mechanical sounds. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product deformation, no floating, no morphing, no leg count change."
  reference_slots: "@Image 1 = ons-pr-douchechien-gray.png · @Image 2 = ons-lieu-sdb.png"

Board 3/3 — role: résolution, petit chien détendu (0-8s)
  refs: ["ons-pr-douchechien-gray.png", "ons-prop-chien-petit.png", "ons-lieu-sdb.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, bathroom daylight, hands and forearms only. 0:00-0:02 the small dog stands calmly on the grey mesh table inside the shower, body relaxed, no attempt to escape. 0:02-0:04 hands lather shampoo along its back, the dog stays still, mouth slightly open, soft panting, bright calm eyes. 0:04-0:06 a handheld shower head rinses it, water draining through the mesh below. 0:06-0:08 hands wrap the dog in a towel and lift it off the table, the dog visibly comfortable throughout. The dog must never show a human-like smile. Preserve exact product geometry, mesh structure and colorway. Water drains realistically through the mesh. Natural water ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No dog identity change, no product deformation, no return to an anxious expression."
  reference_slots: "@Image 1 = ons-pr-douchechien-gray.png · @Image 2 = ons-prop-chien-petit.png · @Image 3 = ons-lieu-sdb.png"

## POST 3
- lane: SEEDANCE
- product: Table de douche pour chien — coloris pink
- pattern: fausse piste retail (transfert du pattern @ameliaspots sur la niche chien)
- pattern_ref: ameliaspots 69,9K (rayon + panier = preuve de légitimité, 0% visage)
- split_test_variable: pattern (curiosité mécanique vs fausse piste retail)
- concept: Test croisé — on applique la mécanique de fausse piste retail (rayon animalerie type Maxi Zoo) au produit chien, pour comparer avec la curiosité mécanique des POST 1 et 2.
- hook_overlay: "Trouvé ça en animalerie, j'ai foncé"
- cta_keyword: TOUTOU
- caption: "Commente 'TOUTOU' si ton chien déteste le bain"
- hashtags: ["#animalerie", "#chien", "#toilettagechien", "#bonplan"]
- accounts: ["@onsimplifie"]
- sound_mood: ambiance naturelle de magasin puis salle de bain — pas de musique
- duration_target_s: 13
- face_ratio_target: 0%

### Boards
Board 1/3 — role: HOOK rayon animalerie, mains uniquement (0-8s)
  refs: ["ons-pr-douchechien-pink.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, bright pet-store lighting, hands only — no face visible at any point. 0:00-0:03 a hand reaches toward a metal warehouse-style shelf and takes down a boxed pink and white folding pet product, price labels visible on the shelf edge. 0:03-0:05 the box is held up and rotated, packaging clearly legible. 0:05-0:07 close-up on the product image printed on the box. 0:07-0:08 the box is lowered into a metal shopping trolley. Preserve exact product geometry and colorway. Natural store ambience only. No text rendered in image beyond diegetic packaging, no logo invented, no watermark, no music, no subtitles, no dialogue. No product deformation, no colour drift, no cinematic ad polish."
  reference_slots: "@Image 1 = ons-pr-douchechien-pink.png"

Board 2/3 — role: déballage + montage à la maison (0-8s)
  refs: ["ons-pr-douchechien-pink.png", "ons-lieu-sdb.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, indoor daylight, hands only — no face visible. 0:00-0:02 hands open the box on a living-room floor and lift out the folded pink product. 0:02-0:04 high-angle view: the hands unfold it, mesh surface appearing. 0:04-0:06 the metal legs are pulled open and lock into place. 0:06-0:08 the unfolded table is carried into the bathroom and placed inside the shower, stable on the tiles. Preserve exact product geometry, materials, colorway and folding mechanism. Realistic hinges and gravity. Natural room ambience and light mechanical sounds. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product deformation, no floating, no morphing."
  reference_slots: "@Image 1 = ons-pr-douchechien-pink.png · @Image 2 = ons-lieu-sdb.png"

Board 3/3 — role: usage + payoff chien détendu (0-8s)
  refs: ["ons-pr-douchechien-pink.png", "ons-prop-chien-golden.png", "ons-lieu-sdb.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, bathroom daylight, hands and forearms only. 0:00-0:02 a medium-sized dog stands on the pink mesh table inside the shower, calm and settled. 0:02-0:04 hands lather shampoo along its back, the dog relaxed, mouth slightly open, soft panting. 0:04-0:06 a handheld shower head rinses it, water draining through the mesh below. 0:06-0:08 final close-up on the clean wet dog standing comfortably on the table, bright relaxed eyes. The dog must never show a human-like smile. Preserve exact product geometry, mesh structure and colorway. Water drains realistically through the mesh. Natural water ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No dog identity change, no product deformation, no anxious expression once washing has begun."
  reference_slots: "@Image 1 = ons-pr-douchechien-pink.png · @Image 2 = ons-prop-chien-golden.png · @Image 3 = ons-lieu-sdb.png"
