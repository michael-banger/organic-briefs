---
date: 2026-08-06
brand: MYTEAOVO
market: FR
---

## POST 1
- lane: KLING
- product: pot poterie style2 (succulent violet)
- pattern: P6 + P7 + P1
- pattern_ref: cozystarbaby 45.2M 2026-07-27 (vulnerability transposed: plant instead of baby), calmorarelax 1.44M 2026-07-29
- split_test_variable: avatar (Clemence vs Julie split-test — this post uses Clemence)
- concept: Une plante qui dépérit dans un pot terne, replantée dans le nouveau pot artisanal, transformation visible et émouvante — la plante comme être vulnérable qu'on sauve, pas juste un objet déco.
- hook_overlay: "Elle allait mourir dans ce pot..."
- cta_keyword: PLANTE
- caption: "Comment 'PLANTE' pour sauver la tienne aussi"
- hashtags: ["#plante", "#deco", "#poterie", "#interieur"]
- accounts: ["@myteaovo"]
- sound_mood: silence + ambiance salon calme — pas de musique

### Scenes
1. beat: tension — plante fanée, feuilles tombantes, dans un pot en plastique terne
   startframe_prompt: "Handheld iPhone shot, bright French living room, a wilting succulent with drooping leaves in a plain dull plastic pot, natural window light, slightly sad framing, no text"
   video_prompt: "Slow handheld push-in on the wilting plant, leaves slightly moving, 5s, natural room tone only"
   refs: ["myt-prop-plante", "myt-lieu-salon"]
   duration_s: 5
2. beat: reveal — mains (Clemence) qui présentent le nouveau pot artisanal, texture visible
   startframe_prompt: "Close-up handheld shot of a woman's hands (Clemence) holding a decorative purple succulent-style ceramic pot, French living room background, natural daylight, no text"
   video_prompt: "Hands turn the new pot slowly to show its texture and shape, 5s, natural sound only"
   refs: ["CLEMENCE-POTERIE-VF", "myt-pr-pot-style2"]
   duration_s: 5
3. beat: transition — replantation, terre et racines visibles, geste soigneux
   startframe_prompt: "Close-up of hands carefully repotting a succulent from the old pot into the new decorative one, soil visible, French living room daylight, no text"
   video_prompt: "Hands gently transfer the plant and soil into the new pot, natural careful motion, 5s, natural sound only"
   refs: ["myt-prop-plante", "myt-pr-pot-style2"]
   duration_s: 5
4. beat: payoff — plante vibrante dans le nouveau pot, salon lumineux, transformation complète
   startframe_prompt: "Wide handheld shot of the now-vibrant succulent in its new purple decorative pot, placed on a shelf in a bright French living room, warm afternoon light, no text"
   video_prompt: "Slow reveal pan across the living room to the plant in its new pot looking healthy and vibrant, 5s, natural room tone only"
   refs: ["myt-pr-pot-style2", "myt-prop-plante", "myt-lieu-salon"]
   duration_s: 5

## POST 2 (EXCEPTIONAL 2026-08-06 — storyboard format, lane-agnostic: usable Kling CLI or Seedance manual)
- account: @myteaovo — confirmed, OK to produce/post.
- product: pot poterie style1 (airplant/fern), avatar Julie (split-test B vs Clémence in POST 1)
- pattern: P6 + P7 + P1 (même formule, avatar différent — round 0 split-test avatar)
- split_test_variable: avatar (Clémence → Julie)
- concept: Même mécanique sauvetage-plante que POST 1 mais pot style1 + mains de Julie, pour isoler l'avatar comme variable et laisser les vues trancher.
- hook_overlay: "Personne ne pensait qu'elle allait s'en remettre..."
- cta_keyword: PLANTE
- caption: "Comment 'PLANTE' pour sauver la tienne aussi"
- hashtags: ["#plante", "#deco", "#poterie", "#interieur"]
- sound_mood: silence + ambiance salon calme — pas de musique
- duration_target_s: 9

### Storyboard (3 boards, 3s/board)
Board 1 (0-3s) — tension: plante fanée dans un pot terne, Julie qui la regarde, inquiète
  refs: ["myt-av-julie", "myt-prop-plante", "myt-lieu-salon"]
  prompt: "3-panel 16:9 storyboard, photorealistic phone-shot realism, same French living room, same young woman (Julie), same daylight throughout. Panel 1 (0-3s): Julie looking concerned at a wilting succulent in a plain dull pot. Panel 2 (3-6s): her hands carefully repotting it into the new style1 decorative pot, soil visible. Panel 3 (6-9s): wide shot, plant now vibrant in its new pot on a shelf, Julie smiling softly. No text rendered in image, no logo, no watermark, no music, no subtitles, max 3 references."
  reference_slots: "@Image 1 = myt-av-julie · @Image 2 = myt-pr-pot-style1 · @Image 3 = myt-prop-plante"
kling_split (if lane=KLING): clip1 = panel 1 (3s), clip2 = panel 2 (3s), clip3 = panel 3 (3s), natural sound only throughout

## POST 3
Not planned today (exceptional cap = 2 videos/account, not 3).
