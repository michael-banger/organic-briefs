---
date: 2026-08-07
brand: SPIRALEDAZUR
market: FR
account: "@spiraledazur"
batch: NIGHT-PROD-12
videos_locked: 3
boards_per_video: 3
---

# SPIRALEDAZUR — 3 vidéos SEEDANCE verrouillées

Structure source : analyse frame-par-frame de @giddyuppacks (13,0 s / 7 plans / 17 % de visage).
Mécanique : fausse piste retail → reveal produit → twist d'aveu.
Règle visage : visible sur 1 plan maximum par vidéo. Ailleurs : mains, produit seul, ou de dos.
Adaptation FR : enseigne mode = Zara / H&M / Galeries Lafayette. Jamais Target. Prix en €.

## POST 1
- lane: SEEDANCE
- product: Sac Cowgirl (v2)
- pattern: fausse piste retail + reveal + twist d'aveu
- pattern_ref: giddyuppacks 16,7K 2026-07-28 (frame-by-frame 13,0s / 7 plans / 17% visage)
- split_test_variable: hook
- concept: On croit que le sac est vendu chez Zara — rayon, étiquettes 59,99 €, unboxing, reveal de l'intérieur, puis aveu final "c'est nous qui les faisons". Avatar exceptionnel : nouvelle jeune femme style estival Sud/parisienne.
- hook_overlay: "Les Parisiennes ne marchent pas elles COURENT chez Zara"
- hook_overlay_end: "Je rigole ! C'est nous qui les faisons"
- cta_keyword: SAC
- caption: "Commente 'SAC' et je t'envoie le lien"
- hashtags: ["#saccowgirl", "#faitmain", "#crochet", "#modefemme"]
- accounts: ["@spiraledazur"]
- sound_mood: ambiance naturelle de magasin puis de rue — pas de musique
- duration_target_s: 13
- face_ratio_target: 17%

### Boards
Board 1/3 — role: hook fausse piste retail (0-8s)
  refs: ["HANDBAG-AVATARS-REF.png", "SAC-COWGIRL-REF1.png", "MONOPRIX-RAYON.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, natural store lighting, handheld micro-movement. 0:00-0:02 young woman in a light summer dress walking up a French clothing store aisle holding a shopping basket, shocked open-mouth expression, camera follows at shoulder height. 0:02-0:04 medium shot of the shelf: several crochet cowgirl bags lined up in boxes, price tags reading 59,99 € clearly legible under each one, euro symbol visible. 0:04-0:06 close-up push-in on one price tag then tilt up to the bag. 0:06-0:08 her hand reaches into frame and takes one box off the shelf. Preserve exact bag geometry, materials and colorway from the product reference. Natural store ambience only. No text rendered in image, no logo, no watermark, no music, no subtitles, no dialogue. No face drift, no bag redesign, no cinematic ad polish, no artificial bokeh."
  reference_slots: "@Image 1 = HANDBAG-AVATARS-REF.png · @Image 2 = SAC-COWGIRL-REF1.png · @Image 3 = MONOPRIX-RAYON.png"

Board 2/3 — role: unboxing + reveal fonction (0-8s), mains uniquement
  refs: ["SAC-COWGIRL-REF1.png", "SAC-COWGIRL-REF2.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, soft indoor daylight, hands only — no face visible at any point. 0:00-0:01 two hands open a plain box on a wooden table, tissue paper inside. 0:01-0:03 hands lift the crochet cowgirl bag out of the box, holding it by the sides, full silhouette visible. 0:03-0:05 hands rotate the bag slowly to show the braided handle and the flower detail. 0:05-0:06 the bag is opened, interior clearly visible. 0:06-0:08 macro close-up on the crochet texture, thick fibrous yarn, visible handmade irregularities. Preserve exact product geometry, materials, colorway and construction from the references. Natural room ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product deformation, no color drift, no extra hands, no morphing."
  reference_slots: "@Image 1 = SAC-COWGIRL-REF1.png · @Image 2 = SAC-COWGIRL-REF2.png"

Board 3/3 — role: démo capacité + payoff lifestyle de dos (0-8s)
  refs: ["SAC-COWGIRL-REF2.png", "HANDBAG-AVATARS-REF.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, natural daylight. 0:00-0:01 overhead shot, hands drop a phone into the open crochet bag. 0:01-0:02 sunglasses go in. 0:02-0:03 a lip balm and keys go in. 0:03-0:04 hands close the bag. 0:04-0:08 cut to exterior: the same young woman seen from behind, walking away down a Parisian Haussmann street in summer daylight, the crochet bag on her shoulder swinging naturally, recognizable pale stone facades and wrought-iron balconies, camera follows from behind at walking pace. She never turns to camera. Preserve exact bag geometry and colorway. Natural street ambience and footsteps only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No face drift, no posed runway walk, no cinematic ad polish, no fake background blur."
  reference_slots: "@Image 1 = SAC-COWGIRL-REF2.png · @Image 2 = HANDBAG-AVATARS-REF.png"

## POST 2
- lane: SEEDANCE
- product: Four Tout Bag
- pattern: fausse piste retail SANS twist d'aveu (variante @ameliaspots)
- pattern_ref: ameliaspots 69,9K 2026-07-20 (rayon + caddie = preuve de légitimité, fin sur CTA, 0% visage)
- split_test_variable: pattern (twist vs sans twist)
- concept: Même fausse piste retail que POST 1 mais on retire le twist d'aveu — le rayon et le caddie servent uniquement de preuve de légitimité, et la vidéo se termine sur le payoff maison + CTA. Test direct de la variante sans aveu.
- hook_overlay: "Le sac que toutes les Parisiennes s'arrachent cet été"
- cta_keyword: SAC
- caption: "Commente 'SAC' pour le lien"
- hashtags: ["#sacfaitmain", "#crochet", "#modeete", "#paris"]
- accounts: ["@spiraledazur"]
- sound_mood: ambiance naturelle — pas de musique
- duration_target_s: 13
- face_ratio_target: 0%

### Boards
Board 1/3 — role: hook rayon, mains uniquement (0-8s)
  refs: ["FOUR-TOUT-BAG.png", "MONOPRIX-RAYON.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, natural store lighting, hands only — no face visible at any point. 0:00-0:02 a hand reaches toward a store shelf and takes a crochet tote bag, price tags visible on the shelf edge. 0:02-0:04 the bag is held up at arm's length, full silhouette against the aisle background. 0:04-0:06 the hand rotates it slowly, braided handle and texture visible. 0:06-0:08 the bag is lowered into a metal shopping trolley. Preserve exact bag geometry, materials and colorway from the reference. Natural store ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product deformation, no color drift, no cinematic polish."
  reference_slots: "@Image 1 = FOUR-TOUT-BAG.png · @Image 2 = MONOPRIX-RAYON.png"

Board 2/3 — role: détail matière + capacité (0-8s)
  refs: ["FOUR-TOUT-BAG.png", "NEW-HANDBAG-ALL-COLORS.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, soft indoor daylight, hands only. 0:00-0:02 macro close-up travelling across the crochet texture, thick yarn, visible handmade irregularities. 0:02-0:04 hands open the tote and hold it open, interior visible. 0:04-0:06 a phone, sunglasses and a small pouch are dropped in one by one. 0:06-0:08 wider shot: several colorways of the same bag laid side by side on a light linen surface. Preserve exact product geometry and each distinct colorway. Natural room ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No morphing between colorways, no product deformation, no extra hands."
  reference_slots: "@Image 1 = FOUR-TOUT-BAG.png · @Image 2 = NEW-HANDBAG-ALL-COLORS.png"

Board 3/3 — role: payoff maison / terrasse, produit seul (0-8s)
  refs: ["FOUR-TOUT-BAG.png", "SUNSET-RIVIERA.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, warm late-afternoon daylight, no people at all. 0:00-0:03 the crochet tote bag resting on a Parisian balcony ledge or café table, soft summer light, plants and street visible behind. 0:03-0:05 slow lateral camera drift across the bag, texture catching the light. 0:05-0:08 slight push-in on the flower detail, then hold on the full bag in its setting. The bag stays completely still — all movement comes from the camera. Preserve exact bag geometry, materials and colorway. Natural outdoor ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product movement, no floating, no shape change, no artificial bokeh."
  reference_slots: "@Image 1 = FOUR-TOUT-BAG.png · @Image 2 = SUNSET-RIVIERA.png"

## POST 3
- lane: SEEDANCE
- product: Sac coquillage / Shell Bloom
- pattern: fausse piste retail + reveal, hook orienté prix
- pattern_ref: giddyuppacks 16,7K (structure), ameliaspots 69,9K (0% visage)
- split_test_variable: produit + hook (angle prix)
- concept: Même mécanique de rayon mais le hook joue sur le prix affiché — on croit à une trouvaille en magasin à 59,99 €, puis reveal du produit en contexte estival Riviera.
- hook_overlay: "59,99 € en magasin... j'ai cru rêver"
- cta_keyword: SAC
- caption: "Commente 'SAC' si tu le veux"
- hashtags: ["#saccoquillage", "#crochet", "#faitmain", "#modeete"]
- accounts: ["@spiraledazur"]
- sound_mood: ambiance naturelle — pas de musique
- duration_target_s: 13
- face_ratio_target: 0%

### Boards
Board 1/3 — role: hook prix en rayon (0-8s)
  refs: ["SHELL-BLOOM.png", "MONOPRIX-RAYON.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, natural store lighting, hands only — no face at any point. 0:00-0:02 close-up on a shelf price tag reading 59,99 € with the euro symbol clearly legible, slightly imperfect handheld framing. 0:02-0:04 camera tilts up from the tag to reveal a shell-detailed crochet bag on the shelf above. 0:04-0:06 a hand takes the bag off the shelf. 0:06-0:08 the bag is held up, full silhouette, shell and flower details visible. Preserve exact bag geometry, materials and colorway from the reference. The price must read exactly 59,99 € — no other figure. Natural store ambience only. No text rendered in image beyond the diegetic price tag, no logo, no watermark, no music, no subtitles, no dialogue. No product deformation, no color drift."
  reference_slots: "@Image 1 = SHELL-BLOOM.png · @Image 2 = MONOPRIX-RAYON.png"

Board 2/3 — role: détail produit macro (0-8s)
  refs: ["SHELL-BLOOM.png", "LEMON-BLOSSOM.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, soft natural daylight, hands only. 0:00-0:02 macro shot of the shell detail on the crochet bag, thick yarn texture, handmade irregularities visible. 0:02-0:04 hands rotate the bag to show the braided handle. 0:04-0:06 the bag is opened, interior visible, hands hold it open. 0:06-0:08 a second colorway of the same model is placed next to the first on a light linen surface. Preserve exact product geometry and both distinct colorways. Natural room ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No morphing between the two bags, no product deformation, no extra hands."
  reference_slots: "@Image 1 = SHELL-BLOOM.png · @Image 2 = LEMON-BLOSSOM.png"

Board 3/3 — role: payoff Riviera, de dos (0-8s)
  refs: ["SHELL-BLOOM.png", "SUNSET-RIVIERA.png", "HANDBAG-AVATARS-REF.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, warm golden-hour daylight on the French Riviera. 0:00-0:03 a young woman in a light summer dress seen strictly from behind, walking along a seaside promenade, the shell crochet bag on her shoulder. 0:03-0:05 the bag swings naturally with her steps, camera follows from behind at walking pace. 0:05-0:08 she stops at a low wall overlooking the sea, still seen from behind, and sets the bag down beside her. She never turns toward the camera, her face is never visible. Preserve exact bag geometry, materials and colorway. Natural seaside ambience and footsteps only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No face reveal, no posed runway walk, no cinematic ad polish, no fake blur."
  reference_slots: "@Image 1 = SHELL-BLOOM.png · @Image 2 = SUNSET-RIVIERA.png · @Image 3 = HANDBAG-AVATARS-REF.png"
