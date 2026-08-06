---
date: 2026-08-06
brand: ONSIMPLIFIE
market: FR
---

## POST 1
- lane: KLING
- product: douche-chien (portable dog wash stand)
- pattern: P7 + P3 + P6
- pattern_ref: puppfloat/pupfloats 2.70M+2.69M 2026-08-02, wash_your_pet 1.39M 2026-08-03
- split_test_variable: hook
- concept: Un chien qui se débat au bain classique, calmé instantanément par le nouveau support de douche pliant — tension puis soulagement visible, le chien comme être vulnérable qu'on soulage.
- hook_overlay: "Le bain qui rendait mon chien fou..."
- cta_keyword: TOUTOU
- caption: "Comment 'TOUTOU' si ton chien déteste le bain aussi"
- hashtags: ["#chien", "#doglover", "#bainchien", "#astucechien"]
- accounts: ["@onsimplifie"]
- sound_mood: silence + bruits naturels (eau, chien, tissu) — pas de musique

### Scenes
1. beat: tension — chien qui se débat dans une baignoire classique, propriétaire (mains seulement) qui galère à le tenir
   startframe_prompt: "Handheld iPhone shot, French bathroom, a wet golden retriever struggling and slightly panicked in a standard bathtub, owner's hands only visible trying to hold him steady, realistic water splashes, natural daylight, no text"
   video_prompt: "Dog squirms and tries to climb out of the tub, owner's hands gently but firmly holding him, water splashing, 5s, natural sound only, no music"
   refs: ["ons-prop-chien-golden", "ons-lieu-sdb"]
   duration_s: 5
2. beat: reveal — mise en place du support de douche pliant, mains uniquement
   startframe_prompt: "Close-up handheld shot of hands unfolding a gray mesh dog wash stand with white folding metal legs in a French bathroom, oval paw holes visible, realistic texture, no text"
   video_prompt: "Hands unfold and set down the folding dog wash stand on the bathtub floor, metal legs click into place, 5s, natural sound of metal and fabric"
   refs: ["ons-pr-douchechien-gray", "ons-lieu-sdb"]
   duration_s: 5
3. beat: payoff — chien placé dans le support, se calme immédiatement, pattes dans les trous ovales
   startframe_prompt: "Golden retriever standing calmly with paws through the oval holes of the gray mesh dog wash stand, visibly relaxed, water gently running, French bathroom, natural light, no text"
   video_prompt: "Dog stands calm and stable in the wash stand, tail relaxed, owner's hands gently washing him, water running, 5s, natural sound only"
   refs: ["ons-pr-douchechien-gray", "ons-prop-chien-golden", "ons-lieu-sdb"]
   duration_s: 5
4. beat: détail produit — texture mesh, bordure de trou couleur assortie, pieds pliants
   startframe_prompt: "Macro handheld shot of the gray mesh fabric and matching-color oval hole trim of the folding dog wash stand, wet texture, realistic detail, French bathroom light, no text"
   video_prompt: "Slow handheld pan across the wet mesh texture and folding metal leg mechanism, 5s, natural water sound only"
   refs: ["ons-pr-douchechien-gray"]
   duration_s: 5
5. beat: résolution — chien propre, calme, séché à la serviette, propriétaire satisfait (mains/silhouette)
   startframe_prompt: "Golden retriever calm and clean, being dried with a towel by hands only, French bathroom, warm natural light, relaxed body language, no text"
   video_prompt: "Dog stands still and relaxed while being towel-dried, gentle natural movement, 5s, natural sound only"
   refs: ["ons-prop-chien-golden", "ons-lieu-sdb"]
   duration_s: 5

## POST 2 (EXCEPTIONAL 2026-08-06 — storyboard format, lane-agnostic: usable Kling CLI or Seedance manual)
- account: @onsimplifie — STATUS: ACCOUNT_PENDING_CONFIRMATION. Prep only, DO NOT POST until Yann confirms.
- product: douche-chien (portable dog wash stand), variant blue, secondary dog (chien-petit) for variety vs POST 1
- pattern: P7 + P3 + P6 (même formule, hook + chien différents — round 0 split-test)
- split_test_variable: hook + chien (golden→petit)
- concept: Petit chien poil frisé qui panique dès qu'il voit l'eau couler, propriétaire hésitant, puis support pliant bleu qui le stabilise et le calme en quelques secondes — variation du POST 1 avec un chien plus "fragile visuellement" pour renforcer P6.
- hook_overlay: "Il tremblait avant chaque bain... jusqu'à ça"
- cta_keyword: TOUTOU
- caption: "Comment 'TOUTOU' si ton chien flippe aussi du bain"
- hashtags: ["#chien", "#doglover", "#bainchien", "#astucechien"]
- sound_mood: silence + bruits naturels (eau, chien, tissu) — pas de musique
- duration_target_s: 9

### Storyboard (3 boards, 3s/board)
Board 1 (0-3s) — tension: petit chien poil frisé qui recule et tremble devant l'eau qui coule dans la baignoire, propriétaire (mains seules) hésitant
  refs: ["ons-prop-chien-petit", "ons-lieu-sdb"]
  prompt: "3-panel 16:9 storyboard, photorealistic phone-shot realism, same French bathroom, same small curly-haired dog, same daylight throughout. Panel 1 (0-3s): small curly dog backing away and trembling as bathtub water runs, owner's hands only visible, hesitant. Panel 2 (3-6s): hands unfold a blue mesh folding dog wash stand, oval paw holes visible, set it in the tub. Panel 3 (6-9s): dog stands calm with paws through the holes, relaxed, water gently running. No text rendered in image, no logo, no watermark, no music, no subtitles, max 3 references."
  reference_slots: "@Image 1 = ons-prop-chien-petit · @Image 2 = ons-pr-douchechien-blue · @Image 3 = ons-lieu-sdb"
kling_split (if lane=KLING): clip1 = panel 1 (3s, natural sound), clip2 = panel 2 (3s, metal/fabric sound), clip3 = panel 3 (3s, water sound)

## POST 3
Not planned today (exceptional cap = 2 videos/account, not 3).
