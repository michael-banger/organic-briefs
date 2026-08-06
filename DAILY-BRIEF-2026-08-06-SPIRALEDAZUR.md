---
date: 2026-08-06
brand: SPIRALEDAZUR
market: FR
---

## POST 1
- lane: SEEDANCE
- product: Sac Cowgirl (v2)
- pattern: P4 + P1 + P5
- pattern_ref: saiyan.boots 967K 2026-08-03 (fandom fake-out reveal), track.paws 3.02M 2026-07-20 (aspirational context)
- split_test_variable: hook
- concept: Commentaire moqueur reçu sur le téléphone dans la voiture, retour à l'atelier soutenu par la mentor, reveal du sac cowgirl fini en contexte retail français (Monoprix) — fandom esthétique + validation.
- hook_overlay: "Personne va acheter tes sacs, arrête ça..."
- cta_keyword: SAC
- caption: "Comment 'SAC' si tu veux voir la suite"
- hashtags: ["#faitmain", "#crochet", "#saccowgirl", "#artisanat"]
- accounts: ["@spiraledazur"]
- sound_mood: silence + ambiance naturelle — pas de musique

### Boards
Board 1/3 — role: scroll stopper / tension
  refs: ["MEUF-HANDBAG-V2.png"]
  seedance_prompt: "3-panel 16:9 storyboard, photorealistic phone-shot realism, same young woman founder, same car interior, same daylight throughout. Panel 1 (0-3s): founder sitting in a parked car, looking at her phone, reading a mocking comment, hurt expression. Panel 2 (3-5s): she lowers the phone, visibly affected but composed. Panel 3 (5-8s): she starts the car, determined expression, Paris street visible through the window. No text rendered in image, no logo, no watermark, no music, no subtitles, max 3 references."
  reference_slots: "@Image 1 = MEUF-HANDBAG-V2.png"

Board 2/3 — role: product in action / payoff (atelier + mentor support)
  refs: ["MEUF-HANDBAG-V2.png", "GRANDMA-HANDBAG-V2.png", "SAC-COWGIRL-REF1.png"]
  seedance_prompt: "3-panel 16:9 storyboard, same founder, same atelier, same warm window daylight throughout. Panel 1 (0-3s): founder at a worktable, crochet materials around her, focused despite being upset. Panel 2 (3-5s): an older mentor woman gently places a hand near her shoulder, supportive silent gesture. Panel 3 (5-8s): close-up of hands crocheting the cowgirl bag shape, thick fibrous texture, handmade imperfections visible. No text, no logo, no watermark, no music, no subtitles, max 3 references."
  reference_slots: "@Image 1 = MEUF-HANDBAG-V2.png · @Image 2 = GRANDMA-HANDBAG-V2.png · @Image 3 = SAC-COWGIRL-REF1.png"

Board 3/3 — role: desire / context / soft close
  refs: ["SAC-COWGIRL-REF2.png", "MONOPRIX-RAYON.png"]
  seedance_prompt: "3-panel 16:9 storyboard, same finished cowgirl bag, French retail location, same daylight throughout. Panel 1 (0-3s): the finished cowgirl bag held up in the atelier, proud restrained framing. Panel 2 (3-5s): founder walking into a French retail store aisle (Monoprix-style), bag on her shoulder, natural everyday context. Panel 3 (5-8s): close-up of the bag in the retail aisle, credible French shopping scene, product hero but still iPhone-native realism. No text, no logo, no watermark, no music, no subtitles, max 3 references."
  reference_slots: "@Image 1 = SAC-COWGIRL-REF2.png · @Image 2 = MONOPRIX-RAYON.png"

## POST 2 (EXCEPTIONAL 2026-08-06 — storyboard format, lane-agnostic: usable Kling CLI or Seedance manual)
- account: @spiraledazur — confirmed, OK to produce/post.
- product: Four Tout Bag (vs Sac Cowgirl in POST 1), avatar grandma/mentor (vs young founder in POST 1)
- pattern: P4 + P1 + P5 (même formule, produit + avatar différents — round 0 split-test)
- split_test_variable: produit + avatar
- concept: Grand-mère/mentor qui présente le Four Tout Bag fini dans le rayon Monoprix, contexte retail FR crédible, tribu esthétique "savoir-faire" plutôt que fandom jeune — validation-question en clôture (pattern historique gagnant du performance-tracker: "vous en porteriez un?").
- hook_overlay: "Le sac que ma grand-mère aurait fait"
- cta_keyword: SAC
- caption: "Honnêtement vous en porteriez un ?"
- hashtags: ["#faitmain", "#crochet", "#artisanat", "#savoirfaire"]
- sound_mood: silence + ambiance naturelle — pas de musique
- duration_target_s: 8

### Storyboard (3 boards, ~3s/board)
Board 1 (0-3s) — reveal: grandma/mentor holding the finished Four Tout Bag in a French retail aisle
  refs: ["GRANDMA-HANDBAG-V2.png", "MONOPRIX-RAYON.png"]
  prompt: "3-panel 16:9 storyboard, photorealistic phone-shot realism, same French retail store aisle (Monoprix-style), same older woman, same daylight throughout. Panel 1 (0-3s): mentor/grandmother figure holding up the finished crochet Four Tout Bag near a retail shelf, warm proud expression. Panel 2 (3-5s): close detail pan on the bag's handmade texture. Panel 3 (5-8s): she looks to camera, gentle validation-question expression. No text rendered in image, no logo, no watermark, no music, no subtitles, max 3 references."
  reference_slots: "@Image 1 = GRANDMA-HANDBAG-V2.png · @Image 2 = FOUR-TOUT-BAG.png · @Image 3 = MONOPRIX-RAYON.png"

## POST 3
Not planned today (exceptional cap = 2 videos/account, not 3).
