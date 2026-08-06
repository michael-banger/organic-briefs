---
date: 2026-08-07
brand: MYTEAOVO
market: FR
account: "@myteaovo"
batch: NIGHT-PROD-12
videos_locked: 3
boards_per_video: 3
---

# MYTEAOVO — 3 vidéos SEEDANCE verrouillées

Structure source : analyse frame-par-frame de @ameliaspots (12 s / 9 plans / **0 % de visage**,
69,9K likes, 2,3K commentaires).
Mécanique : **fausse piste retail sans twist** — le rayon et le caddie servent de preuve de
légitimité, la vidéo se termine sur le payoff maison + CTA.
**Aucun visage humain sur aucune des 3 vidéos. Mains uniquement.** C'est un choix de
performance validé par la data, pas une contrainte technique : 69,9K likes sans un seul visage.
Adaptation FR : enseigne déco/maison = Ikea, Maisons du Monde. Jamais Target.

## POST 1
- lane: SEEDANCE
- product: Pot de plante sculpté — style 1
- pattern: fausse piste retail sans twist
- pattern_ref: ameliaspots 69,9K 2026-07-20 (frame-by-frame 12s / 9 plans / 0% visage)
- split_test_variable: hook
- concept: Une main attrape le pot en boîte dans un rayon type entrepôt, packaging bien montré, passage en caddie, puis payoff : le pot installé chez soi avec plantes retombantes au coucher de soleil.
- hook_overlay: "Le cadeau parfait pour celle qui aime les plantes"
- hook_overlay_end: "Commente POT pour le lien"
- cta_keyword: POT
- caption: "Commente 'POT' et je t'envoie le lien"
- hashtags: ["#potdeplante", "#deco", "#plantes", "#ideecadeau"]
- accounts: ["@myteaovo"]
- sound_mood: ambiance naturelle de magasin puis intérieur calme — pas de musique
- duration_target_s: 12
- face_ratio_target: 0%

### Boards
Board 1/3 — role: HOOK rayon type Ikea, mains uniquement (0-8s)
  refs: ["myt-pr-pot-style1.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, bright warehouse-style store lighting, hands only — no face visible at any point, no people in frame. 0:00-0:03 a hand with a thin bracelet reaches toward a tall metal warehouse shelf and takes down a boxed sculpted ceramic plant pot, small price labels visible on the shelf edge. 0:03-0:05 the box is held up at arm's length, the packaging window showing the pot clearly. 0:05-0:07 the hand rotates the box slowly, packaging details legible. 0:07-0:08 the box is lowered toward a metal shopping trolley. Preserve exact product geometry, sculpting, materials and colorway from the reference. Natural store ambience only. No text rendered in image beyond diegetic packaging, no invented logo, no watermark, no music, no subtitles, no dialogue. No product deformation, no colour drift, no cinematic ad polish, no artificial bokeh."
  reference_slots: "@Image 1 = myt-pr-pot-style1.png"

Board 2/3 — role: caddie + déballage, mains uniquement (0-8s)
  refs: ["myt-pr-pot-style1.png", "CLEMENCE-POTERIE-VF.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, hands only — no face visible, no people in frame. 0:00-0:02 top-down view into a metal shopping trolley, the boxed pot resting inside, store floor moving below. 0:02-0:04 cut to indoors: hands open the box on a wooden table. 0:04-0:06 the ceramic pot is lifted out of its packaging, full sculpted form revealed. 0:06-0:08 macro close-up travelling across the matte ceramic surface, sculpting detail and subtle texture visible. Preserve exact product geometry, sculpting, materials and colorway. Ceramic must stay rigid and matte. Natural ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product deformation, no material change, no morphing, no extra hands."
  reference_slots: "@Image 1 = myt-pr-pot-style1.png · @Image 2 = CLEMENCE-POTERIE-VF.png"

Board 3/3 — role: payoff maison au coucher de soleil, produit seul (0-8s)
  refs: ["myt-pr-pot-style1.png", "myt-prop-plante.png", "myt-lieu-salon.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, warm golden-hour light through a window, no people at all. 0:00-0:03 the sculpted ceramic pot hanging or standing in a bright living space, a trailing string-of-pearls plant cascading from it, other potted plants around. 0:03-0:05 slow lateral camera drift across the arrangement, low sun backlighting the trailing foliage. 0:05-0:07 gentle push-in on the sculpted detail of the pot. 0:07-0:08 hold on the full arrangement against the window light. The pot stays completely still — all movement comes from the camera. Preserve exact product geometry, sculpting, materials and colorway. Natural indoor ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product movement, no floating, no rotation, no shape change, no artificial bokeh."
  reference_slots: "@Image 1 = myt-pr-pot-style1.png · @Image 2 = myt-prop-plante.png · @Image 3 = myt-lieu-salon.png"

## POST 2
- lane: SEEDANCE
- product: Pot de plante sculpté — style 2
- pattern: payoff maison direct, sans passage retail
- pattern_ref: ameliaspots 69,9K (partie payoff isolée) — test du pattern amputé
- split_test_variable: pattern (avec vs sans fausse piste retail)
- concept: On retire complètement le passage magasin et on démarre directement sur le produit installé chez soi. Test direct : la fausse piste retail est-elle nécessaire, ou le produit suffit-il ?
- hook_overlay: "J'ai enfin trouvé LE pot pour mes plantes retombantes"
- cta_keyword: POT
- caption: "Commente 'POT' pour le lien"
- hashtags: ["#plantesretombantes", "#deco", "#ceramique", "#plantaddict"]
- accounts: ["@myteaovo"]
- sound_mood: ambiance intérieure calme — pas de musique
- duration_target_s: 12
- face_ratio_target: 0%

### Boards
Board 1/3 — role: HOOK produit en situation, plan large (0-8s)
  refs: ["myt-pr-pot-style2.png", "myt-prop-plante.png", "myt-lieu-salon.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, soft natural daylight, no people at all. 0:00-0:03 wide shot of a bright French living space, the sculpted ceramic pot immediately visible with a long trailing plant cascading from it. 0:03-0:05 slow push-in toward the pot, the trailing foliage moving very slightly in a draught. 0:05-0:07 the camera settles on the sculpted form. 0:07-0:08 slight lateral drift revealing the room context. The pot stays completely still. Preserve exact product geometry, sculpting, materials and colorway. Natural indoor ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product movement, no floating, no shape change, no cinematic ad polish."
  reference_slots: "@Image 1 = myt-pr-pot-style2.png · @Image 2 = myt-prop-plante.png · @Image 3 = myt-lieu-salon.png"

Board 2/3 — role: macro matière + geste de rempotage (0-8s)
  refs: ["myt-pr-pot-style2.png", "myt-prop-plante.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, soft daylight, hands only — no face visible. 0:00-0:02 macro travelling across the matte ceramic surface, sculpting detail and fine texture. 0:02-0:04 hands lower a small trailing plant into the pot. 0:04-0:06 hands press soil around the base with realistic weight and contact. 0:06-0:08 hands adjust the trailing stems so they hang over the edge, then withdraw from frame. Preserve exact product geometry, sculpting, materials and colorway. Ceramic stays rigid and matte, soil behaves realistically. Natural indoor ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product deformation, no material change, no extra hands, no morphing."
  reference_slots: "@Image 1 = myt-pr-pot-style2.png · @Image 2 = myt-prop-plante.png"

Board 3/3 — role: payoff contre-jour terrasse (0-8s)
  refs: ["myt-pr-pot-style2.png", "myt-prop-plante.png", "myt-lieu-salon.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, late-afternoon backlight through a window or on a balcony, no people at all. 0:00-0:03 the pot with its trailing plant silhouetted against bright window light, foliage glowing at the edges. 0:03-0:05 slow vertical camera drift following the trailing stems downward. 0:05-0:07 close-up on the sculpted detail catching the warm light. 0:07-0:08 pull back slightly to the full arrangement. The pot stays completely still — all movement comes from the camera. Preserve exact product geometry, sculpting, materials and colorway. Natural ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product movement, no floating, no rotation, no shape change, no artificial bokeh."
  reference_slots: "@Image 1 = myt-pr-pot-style2.png · @Image 2 = myt-prop-plante.png · @Image 3 = myt-lieu-salon.png"

## POST 3
- lane: SEEDANCE
- product: Pot de plante sculpté — style 3
- pattern: fausse piste retail + angle cadeau
- pattern_ref: ameliaspots 69,9K (structure complète), angle "perfect gift"
- split_test_variable: angle (cadeau vs usage personnel)
- concept: Même structure retail que POST 1 mais l'angle bascule sur l'idée cadeau — emballage, remise, réaction implicite. Teste l'angle cadeau contre l'angle usage personnel.
- hook_overlay: "Elle a pleuré en ouvrant ça"
- cta_keyword: POT
- caption: "Commente 'POT' si tu connais quelqu'un qui adore les plantes"
- hashtags: ["#ideecadeau", "#cadeaufemme", "#plantes", "#ceramique"]
- accounts: ["@myteaovo"]
- sound_mood: ambiance intérieure calme — pas de musique
- duration_target_s: 12
- face_ratio_target: 0%

### Boards
Board 1/3 — role: HOOK rayon + sélection cadeau (0-8s)
  refs: ["myt-pr-pot-style3.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, warehouse-style store lighting, hands only — no face visible, no people in frame. 0:00-0:03 a hand hesitates between two boxed sculpted ceramic pots on a metal shelf, then chooses one. 0:03-0:05 the chosen box is held up, packaging window showing the pot. 0:05-0:07 the hand turns it to inspect the back of the packaging. 0:07-0:08 the box is placed into a metal shopping trolley. Preserve exact product geometry, sculpting, materials and colorway from the reference. Natural store ambience only. No text rendered in image beyond diegetic packaging, no invented logo, no watermark, no music, no subtitles, no dialogue. No product deformation, no colour drift, no cinematic polish."
  reference_slots: "@Image 1 = myt-pr-pot-style3.png"

Board 2/3 — role: emballage cadeau, mains uniquement (0-8s)
  refs: ["myt-pr-pot-style3.png", "CLEMENCE-POTERIE-VF.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, warm indoor daylight, hands only — no face visible. 0:00-0:02 the ceramic pot resting on a wooden table beside kraft paper and ribbon. 0:02-0:04 hands wrap the pot carefully in tissue paper. 0:04-0:06 hands tie a ribbon around the wrapped gift, realistic tension in the fabric. 0:06-0:08 the finished gift is placed down and the hands withdraw from frame. Preserve exact product geometry and materials while it is still visible. Ceramic stays rigid. Natural indoor ambience and paper sounds only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product deformation, no material change, no extra hands."
  reference_slots: "@Image 1 = myt-pr-pot-style3.png · @Image 2 = CLEMENCE-POTERIE-VF.png"

Board 3/3 — role: payoff — le cadeau ouvert et installé (0-8s)
  refs: ["myt-pr-pot-style3.png", "myt-prop-plante.png", "myt-lieu-salon.png"]
  seedance_prompt: "One continuous 8-second vertical 9:16 organic Instagram video, iPhone 17 Pro Max realism, warm indoor daylight, hands only — no face visible at any point. 0:00-0:02 hands pull away the tissue paper, revealing the sculpted ceramic pot. 0:02-0:04 the pot is lifted and turned slowly, sculpting detail visible. 0:04-0:06 cut to the pot already installed in a bright living space with a trailing plant cascading from it. 0:06-0:08 slow push-in on the finished arrangement in golden-hour light, the pot completely still. Preserve exact product geometry, sculpting, materials and colorway. Natural indoor ambience only. No text, no logo, no watermark, no music, no subtitles, no dialogue. No product movement in the final shot, no floating, no shape change, no artificial bokeh."
  reference_slots: "@Image 1 = myt-pr-pot-style3.png · @Image 2 = myt-prop-plante.png · @Image 3 = myt-lieu-salon.png"
