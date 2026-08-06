---
date: 2026-08-06
brand: TROPUTILE
market: FR
---

## POST 1
- lane: SEEDANCE
- product: sac boisson Sipsway, coloris coral blue
- pattern: P5 + P1 + P4
- pattern_ref: officialsipease 4.54M 2026-07-31 (comment-CTA baby product), sleepride 6.01M 2026-07-24 (aspirational context)
- split_test_variable: first frame
- concept: Groupe d'amis à la plage, quelqu'un galère avec ses boissons séparées, reveal du sac qui distribue directement — contexte été aspirationnel, tribu plage/festival.
- hook_overlay: "Le sac qui a sauvé notre après-midi plage"
- cta_keyword: PLAGE
- caption: "Comment 'PLAGE' pour ne plus jongler avec tes boissons"
- hashtags: ["#plage", "#ete2026", "#sacplage", "#astucevoyage"]
- accounts: ["@troputile"]
- sound_mood: silence + ambiance plage naturelle — pas de musique

### Boards
Board 1/3 — role: scroll stopper / tension
  refs: ["tro-av-groupe", "tro-lieu-plage"]
  seedance_prompt: "3-panel 16:9 storyboard, photorealistic phone-shot realism, same beach location, same group of 2-3 friends, same lighting throughout. Panel 1 (0-3s): friends arriving at a sunny beach spot, one person juggling separate drink cans and towels, slightly frustrated. Panel 2 (3-5s): same friend nearly spilling a drink while setting up towels, comedic tension. Panel 3 (5-8s): friend notices the coral-blue Sipsway drink bag another friend is holding, curious close look. No text, no logo, no watermark, no music, no subtitles, max 3 references."
  reference_slots: "@Image 1 = tro-av-groupe · @Image 2 = tro-lieu-plage"

Board 2/3 — role: product in action / payoff
  refs: ["tro-pr-sacboisson-sipsway-coralblue", "tro-av-groupe", "tro-lieu-plage"]
  seedance_prompt: "3-panel 16:9 storyboard, same beach location, same group, same lighting as previous board. Panel 1 (0-3s): close-up of the coral-blue Sipsway drink bag's built-in dispenser spout with red button. Panel 2 (3-5s): friend presses the button, drink pours directly into a cup, hands-free, satisfying clean pour. Panel 3 (5-8s): friend smiles, drink in hand, bag still worn normally over the shoulder. No text, no logo, no watermark, no music, no subtitles, max 3 references."
  reference_slots: "@Image 1 = tro-pr-sacboisson-sipsway-coralblue · @Image 2 = tro-av-groupe · @Image 3 = tro-lieu-plage"

Board 3/3 — role: desire / context / soft close
  refs: ["tro-av-groupe", "tro-lieu-beach-club-riviera-jour"]
  seedance_prompt: "3-panel 16:9 storyboard, same group, aspirational beach-club daylight setting, same lighting throughout. Panel 1 (0-3s): wide shot of the group relaxed at a beach club, drinks in hand, bag visible on one friend's shoulder. Panel 2 (3-5s): friend uses the bag as a normal handbag, reaching for sunglasses inside, showing it still functions normally. Panel 3 (5-8s): group laughing together, golden hour light, bag prominently but naturally in frame. No text, no logo, no watermark, no music, no subtitles, max 3 references."
  reference_slots: "@Image 1 = tro-av-groupe · @Image 2 = tro-lieu-beach-club-riviera-jour"

## POST 2 (EXCEPTIONAL 2026-08-06 — storyboard format, lane-agnostic: usable Kling CLI or Seedance manual)
- account: @troputile — STATUS: ACCOUNT_PENDING_CONFIRMATION. Prep only, DO NOT POST until Yann confirms.
- product: sac boisson Sipsway, coloris coral pink (vs coral blue in POST 1)
- pattern: P5 + P1 + P4 (même formule, lieu différent — round 0 split-test contexte)
- split_test_variable: lieu (plage → festival)
- concept: Groupe d'amis à un festival (Solidays), quelqu'un renverse presque une boisson en jonglant avec plusieurs gobelets, reveal du sac Sipsway coral pink qui règle le problème — même mécanique P5/P1/P4, contexte festival au lieu de plage pour varier l'algo.
- hook_overlay: "Le sac qui a sauvé notre festival"
- cta_keyword: FESTIVAL
- caption: "Comment 'FESTIVAL' pour ne plus jongler avec tes boissons"
- hashtags: ["#festival", "#solidays", "#sacete", "#astucevoyage"]
- sound_mood: silence + ambiance festival naturelle — pas de musique
- duration_target_s: 8

### Storyboard (3 boards, ~3s/board)
Board 1 (0-3s) — tension: friend juggling multiple drink cups at a festival, nearly spilling
  refs: ["tro-av-groupe", "tro-lieu-festival-solidays"]
  prompt: "3-panel 16:9 storyboard, photorealistic phone-shot realism, same festival location, same group of 2-3 friends, same lighting throughout. Panel 1 (0-3s): friends at a sunny festival, one juggling several drink cups, nearly spilling, mild comedic tension. Panel 2 (3-5s): friend notices another holding the coral-pink Sipsway drink bag, curious look. Panel 3 (5-8s): close reveal of the coral-pink drink bag being used easily, relief and smiles. No text rendered in image, no logo, no watermark, no music, no subtitles, max 3 references."
  reference_slots: "@Image 1 = tro-av-groupe · @Image 2 = tro-lieu-festival-solidays · @Image 3 = tro-pr-sacboisson-sipsway-coralpink"

## POST 3
Not planned today (exceptional cap = 2 videos/account, not 3).
