# VIDEO-01 — CARBLAZZ — Export historique 2026-08-18

- **Date de production :** 2026-08-18
- **Compte IG cible :** carblazz
- **Produit exact utilisé lors de la génération :** `horloge-bois-f1`
- **Concept exact :** Bois F1 — pattern P4 (fandom lock)
- **Hook exact :** `Every F1 fan I know has the same empty wall`
- **Caption exacte :** `Race weekend starts on the wall. 🕒 Link in bio`
- **ManyChat keyword exact :** `CLOCK`
- **Marché / langue du brief original :** US / anglais
- **Brief original utilisé :** `DAILY-BRIEF-2026-08-18-CARBLAZZ.md`, POST 1
- **Run report original :** `output/2026-08-18/CARBLAZZ/POST-1/RUN-REPORT.md`
- **Commit de génération :** `6be3682083254c34c4c3dffecb234fb395d554a0`
- **Statut export :** **BLOCKED**
- **Raison BLOCKED :** `FAIL_PRODUCT_IDENTITY` + `FAIL_MARKET`

## Brief original utilisé — verbatim pour ce post

### Scène 1 — décor sans produit

> A living room on a race weekend evening, a large TV on mute showing blurred motorsport colours,
> a low sofa, warm lamp light, and a wide empty warm-grey wall on the right of the frame.
> Vertical 9:16, photorealistic, no text, no logo, no watermark, no people.
> Refs : aucune.

### Scène 2 — le produit en place

> The same living room wall, now with this clock mounted on it. Reproduce this clock exactly as in
> the reference: wood-toned F1-themed face, black bezel. Warm lamp light from the left, TV glow
> bouncing softly on the wall. Vertical 9:16, photorealistic, no text, no logo, no watermark,
> no people.
> Refs : `horloge-bois-f1`.

### Scène 3 — le détail bois

> Macro on this clock's wooden face, warm side light raking across the grain, hands crisp in focus,
> shallow depth of field. Vertical 9:16, photorealistic, no text, no logo, no watermark.
> Refs : `horloge-bois-f1`.

## Notes de production importantes

Le run du 18/08 avait initialement marqué les 3 scènes COMPLETE et les PNG ont bien été persistés et relus depuis GitHub. Ce statut technique ne signifie plus READY.

Le breakdown Carblazz révisé le 20/08 confirme que le brief original était faux sur l'identité produit : malgré son slug, `horloge-bois-f1` **ne contient aucun bois**. Le produit réel est un cadran à livrée F1 rouge/blanc/noir avec monoplace F1 vue de dessus, chiffres noirs 1–12, moyeu doré, lunette noire, face plate mate et **aucune vitre**. Le brief original demandait au contraire une face wood-toned et un macro sur le grain du bois.

Le marché du brief original était US avec keyword `CLOCK`; le source of truth corrigé est FR avec CTA français. Ne pas réinterpréter ou corriger ces frames dans Kling : elles sont conservées uniquement pour traçabilité.

**Hermès : NE PAS générer de vidéo depuis ces frames.** Utiliser le brief correctif `DAILY-BRIEF-2026-08-21-CARBLAZZ.md` pour une nouvelle génération de start frames.