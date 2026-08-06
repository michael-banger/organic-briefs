---
date: 2026-08-07
brand: TROPUTILE
market: FR
account: "@troputile"
batch: NIGHT-PROD-12
videos_locked: 3
boards_per_video: 3
---

# TROPUTILE — 3 vidéos SEEDANCE verrouillées

Structure source : analyse frame-par-frame de @sips_way (14,8 s / 11 plans / 67 % de visage, 110,5K likes).
Mécanique inverse des autres marques : **un plan long en caméra fixe (39 % de la vidéo) où la
réaction d'une amie monte en crescendo**, puis rafale de plans courts.
La réaction EST le hook, pas le produit.
Visage central : exiger peau texturée, pores visibles, aucune peau lissée. C'est la raison pour
laquelle cette marque est en Seedance et pas en Kling.
Chaque coloris du sac doit apparaître au moins une fois sur l'ensemble des 3 vidéos.

## POST 1
- lane: SEEDANCE
- product: Sac boisson — coloris midnight charcoal
- pattern: plan long réaction + rafale (structure inverse)
- pattern_ref: sips_way 110,5K 2026-07-04 (frame-by-frame 14,8s / 11 plans / plan 1 = 5,83s fixe)
- split_test_variable: hook
- concept: Deux amies en terrasse parisienne le soir. Le sac est posé sur la table, une main actionne le robinet et sert un verre. La caméra ne bouge pas — ce qui évolue c'est la réaction de l'amie qui comprend progressivement. Dialogue court autorisé.
- hook_overlay: "Fais JAMAIS voir ça à ta pote qui boit"
- hook_overlay_end: "Le sac à boisson secret"
- cta_keyword: SOIF
- caption: "Commente 'SOIF' et je t'envoie le lien"
- hashtags: ["#sacaboisson", "#terrasseparis", "#astuce", "#soiree"]
- accounts: ["@troputile"]
- sound_mood: ambiance naturelle de terrasse + une réplique courte — pas de musique
- duration_target_s: 15
- face_ratio_target: 67%
- dialogue_exception: OUI — réplique unique "Mais meuf... nan ?!"

### Boards
Board 1/3 — role: LE HOOK, plan fixe, crescendo de réaction (0-8s)
  refs: ["tro-pr-sacboisson-sipsway-midnightcharcoal.png", "tro-av-groupe.png", "tro-lieu-soiree-appartement-parisien-filles.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, evening Parisian terrace, warm ambient light, CAMERA COMPLETELY STATIC on a tripod-like fixed frame for the entire shot. Two young women sit at a table. The dark tote bag rests upright on the table between them. 0:00-0:02 the left woman's hand reaches to a small tap on the lower side of the bag and turns it; a dark drink starts pouring into a glass below. 0:02-0:04 the right woman watches, expression still neutral, then her eyebrows rise. 0:04-0:06 her mouth opens in genuine disbelief, she leans slightly forward. 0:06-0:08 she bursts into natural laughter and claps once. She says only: 'Mais meuf... nan ?!' — spontaneous, amused, disbelieving tone, nothing else spoken. The drink colour stays identical in the bag, in the stream and in the glass throughout. Realistic skin texture with visible pores, absolutely no smoothed or airbrushed skin. Natural terrace ambience. No text, no logo, no watermark, no music, no subtitles beyond nothing. No camera movement, no cut, no bag deformation, no liquid colour change, no extra hands, no cinematic ad polish."
  reference_slots: "@Image 1 = tro-pr-sacboisson-sipsway-midnightcharcoal.png · @Image 2 = tro-av-groupe.png · @Image 3 = tro-lieu-soiree-appartement-parisien-filles.png"

Board 2/3 — role: rafale preuve produit, mains uniquement (0-8s)
  refs: ["tro-pr-sacboisson-sipsway-midnightcharcoal.png", "tro-pr-sacboisson-aliexpress.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, indoor evening light, hands only — no face visible. 0:00-0:02 hands open the tote bag and pull the top apart to reveal the insulated inner pocket, silver lining clearly visible. 0:02-0:04 a bottle is lowered into the insulated pocket. 0:04-0:05 close-up on the small tap on the outside of the bag. 0:05-0:07 macro shot: a hand turns the tap and a dark drink pours into a clear cup, steady stream, correct gravity, the stream visibly coming from the tap. 0:07-0:08 the filled cup is lifted out of frame. Liquid colour identical in bag, stream and cup. Preserve exact bag geometry, materials and mechanism. Natural room ambience and pouring sound. No text, no logo, no watermark, no music, no subtitles, no dialogue. No liquid colour change, no foam appearing, no bag deformation, no liquid passing through the fabric, no extra hands."
  reference_slots: "@Image 1 = tro-pr-sacboisson-sipsway-midnightcharcoal.png · @Image 2 = tro-pr-sacboisson-aliexpress.png"

Board 3/3 — role: payoff festif multi-situations (0-8s)
  refs: ["tro-pr-sacboisson-sipsway-midnightcharcoal.png", "tro-av-groupe.png", "tro-lieu-trocadero-nuit.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, Parisian evening, hard cuts between short beats. 0:00-0:02 two friends clink their cups together, laughing, the dark tote bag visible on the table beside them. 0:02-0:04 wider shot: the group standing outdoors at night with the Eiffel Tower lit in the background, one woman wearing the bag on her shoulder. 0:04-0:06 close-up of a hand discreetly turning the tap and refilling a cup, other people around, playful conspiratorial energy. 0:06-0:08 the group raises their cups together, natural genuine smiles. Realistic skin texture with visible pores, no smoothed skin. Preserve exact bag geometry and colorway. Natural crowd ambience and laughter only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No identity drift between shots, no bag redesign, no liquid colour change, no cinematic ad polish."
  reference_slots: "@Image 1 = tro-pr-sacboisson-sipsway-midnightcharcoal.png · @Image 2 = tro-av-groupe.png · @Image 3 = tro-lieu-trocadero-nuit.png"

## POST 2
- lane: SEEDANCE
- product: Sac boisson — coloris coral blue
- pattern: plan long réaction + rafale, contexte plage/Riviera
- pattern_ref: sips_way 110,5K (structure), variante lieu
- split_test_variable: lieu + coloris
- concept: Même mécanique de crescendo mais en plein jour au beach club de la Riviera. La réaction se joue en maillot, contexte vacances. Teste si le contexte diurne performe autant que le nocturne.
- hook_overlay: "Ma pote a compris trop tard ce que c'était"
- hook_overlay_end: "Le sac à boisson secret"
- cta_keyword: SOIF
- caption: "Commente 'SOIF' pour le lien"
- hashtags: ["#sacaboisson", "#plage", "#riviera", "#astuceete"]
- accounts: ["@troputile"]
- sound_mood: ambiance naturelle de plage — pas de musique
- duration_target_s: 15
- face_ratio_target: 67%
- dialogue_exception: OUI — réplique unique "Attends... c'est quoi ça ?!"

### Boards
Board 1/3 — role: LE HOOK, plan fixe, crescendo (0-8s)
  refs: ["tro-pr-sacboisson-sipsway-coralblue.png", "tro-av-groupe.png", "tro-lieu-beach-club-riviera-jour.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, bright Mediterranean daylight at a Riviera beach club, CAMERA COMPLETELY STATIC for the entire shot. Two young women on sun loungers, the blue tote bag standing between them on a small table. 0:00-0:02 one woman's hand turns a small tap on the side of the bag; a pale drink pours into a clear cup. 0:02-0:04 the other woman looks over, neutral at first, then her eyebrows lift. 0:04-0:06 she pulls down her sunglasses, mouth open in disbelief. 0:06-0:08 she laughs out loud and reaches toward the bag. She says only: 'Attends... c'est quoi ça ?!' — surprised, amused tone, nothing else spoken. Drink colour identical in bag, stream and cup. Realistic sun-exposed skin texture with visible pores, no smoothed skin. Natural beach ambience. No text, no logo, no watermark, no music, no subtitles. No camera movement, no cut, no bag deformation, no liquid colour change, no cinematic ad polish."
  reference_slots: "@Image 1 = tro-pr-sacboisson-sipsway-coralblue.png · @Image 2 = tro-av-groupe.png · @Image 3 = tro-lieu-beach-club-riviera-jour.png"

Board 2/3 — role: démo mécanisme en extérieur, mains uniquement (0-8s)
  refs: ["tro-pr-sacboisson-sipsway-coralblue.png", "tro-lieu-plage.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, bright beach daylight, hands only — no face visible. 0:00-0:02 hands open the blue tote on the sand and reveal the insulated inner pocket. 0:02-0:04 a bottle and ice are placed inside the pocket. 0:04-0:06 the bag is closed, then a hand turns the external tap. 0:06-0:08 macro: a cold drink pours into a cup, condensation visible on the outside of the cup, correct gravity, stream clearly coming from the tap. Liquid colour identical throughout. Preserve exact bag geometry, materials, mechanism and colorway. Natural sea and wind ambience. No text, no logo, no watermark, no music, no subtitles, no dialogue. No liquid colour change, no bag deformation, no liquid through fabric, no extra hands."
  reference_slots: "@Image 1 = tro-pr-sacboisson-sipsway-coralblue.png · @Image 2 = tro-lieu-plage.png"

Board 3/3 — role: payoff Saint-Tropez / promenade (0-8s)
  refs: ["tro-pr-sacboisson-sipsway-coralblue.png", "tro-av-groupe.png", "tro-lieu-saint-tropez-jour.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, warm afternoon light in a Saint-Tropez style harbour setting, hard cuts between beats. 0:00-0:02 three friends walking together along the harbour, one carrying the blue tote on her shoulder, natural unposed movement. 0:02-0:04 they sit on a low wall, the bag placed beside them. 0:04-0:06 close-up of a hand refilling a cup from the tap, the others watching amused. 0:06-0:08 they raise their cups together, laughing, sea and boats behind them. Realistic skin texture with visible pores, no smoothed skin. Preserve exact bag geometry and colorway. Natural harbour ambience and chatter only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No identity drift, no bag redesign, no liquid colour change, no posed advertising behaviour."
  reference_slots: "@Image 1 = tro-pr-sacboisson-sipsway-coralblue.png · @Image 2 = tro-av-groupe.png · @Image 3 = tro-lieu-saint-tropez-jour.png"

## POST 3
- lane: SEEDANCE
- product: Sac boisson — coloris coral pink
- pattern: tag-a-friend (variante CTA), contexte festival
- pattern_ref: sips_way 110,5K "Tag someone who can't see this bag" (mécanique de partage plutôt que commentaire)
- split_test_variable: CTA (tag-a-friend vs mot-clé commentaire)
- concept: Contexte festival. On teste la mécanique de partage : au lieu du mot-clé commentaire, on demande d'identifier une amie. Objectif reach plutôt que conversion — comparaison directe avec POST 1 et POST 2.
- hook_overlay: "Identifie la pote qui doit PAS voir ce sac"
- cta_keyword: (aucun — mécanique tag)
- caption: "Identifie-la, elle va comprendre"
- hashtags: ["#festival", "#sacaboisson", "#entrepotes", "#solidays"]
- accounts: ["@troputile"]
- sound_mood: ambiance naturelle de festival — pas de musique
- duration_target_s: 15
- face_ratio_target: 67%
- dialogue_exception: NON — réaction non verbale uniquement

### Boards
Board 1/3 — role: LE HOOK, plan fixe, crescendo non verbal (0-8s)
  refs: ["tro-pr-sacboisson-sipsway-coralpink.png", "tro-av-groupe.png", "tro-lieu-solidays-jour.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, open-air festival in daylight, crowd blurred naturally in the background, CAMERA COMPLETELY STATIC for the entire shot. Two young women sitting on the grass, the pink tote bag upright between them. 0:00-0:02 one hand turns the small tap on the bag and pours a drink into a cup. 0:02-0:04 the friend turns her head, sees it, expression neutral then surprised. 0:04-0:06 her eyes widen, she covers her mouth with her hand. 0:06-0:08 she laughs and shakes her head in disbelief. No spoken dialogue at any point — the reaction is purely physical. Drink colour identical in bag, stream and cup. Realistic skin texture with visible pores, no smoothed skin. Natural festival crowd ambience. No text, no logo, no watermark, no music, no subtitles, no dialogue. No camera movement, no cut, no bag deformation, no liquid colour change."
  reference_slots: "@Image 1 = tro-pr-sacboisson-sipsway-coralpink.png · @Image 2 = tro-av-groupe.png · @Image 3 = tro-lieu-solidays-jour.png"

Board 2/3 — role: démo discrète en contexte festival (0-8s)
  refs: ["tro-pr-sacboisson-sipsway-coralpink.png", "tro-lieu-festival.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, festival daylight, hands and torso only — no face visible. 0:00-0:02 the pink tote worn on the shoulder, seen from the wearer's own downward point of view. 0:02-0:04 a hand discreetly opens the top and reveals the insulated pocket inside. 0:04-0:06 the hand turns the tap low against the body, filling a cup held close. 0:06-0:08 the cup is raised out of frame, the bag looking like an ordinary tote again. Liquid colour identical throughout. Preserve exact bag geometry, materials, mechanism and colorway. Natural festival ambience. No text, no logo, no watermark, no music, no subtitles, no dialogue. No liquid colour change, no bag deformation, no extra hands, no cinematic polish."
  reference_slots: "@Image 1 = tro-pr-sacboisson-sipsway-coralpink.png · @Image 2 = tro-lieu-festival.png"

Board 3/3 — role: payoff groupe festival (0-8s)
  refs: ["tro-pr-sacboisson-sipsway-coralpink.png", "tro-av-groupe.png", "tro-lieu-solidays.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, festival at golden hour turning to evening, hard cuts between beats. 0:00-0:02 a group of friends dancing loosely in the crowd, one wearing the pink tote across her body. 0:02-0:04 they huddle together, one pours refills from the bag's tap into their cups. 0:04-0:06 close-up on their faces laughing, genuine unposed expressions. 0:06-0:08 they raise their cups together against the evening sky. Realistic skin texture with visible pores, no smoothed skin. Preserve exact bag geometry and colorway. Natural festival ambience and crowd noise only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No identity drift between shots, no bag redesign, no liquid colour change, no staged advertising choreography."
  reference_slots: "@Image 1 = tro-pr-sacboisson-sipsway-coralpink.png · @Image 2 = tro-av-groupe.png · @Image 3 = tro-lieu-solidays.png"
