# VIDEO-03 — CARBLAZZ — Export historique 2026-08-18

- **Date de production :** 2026-08-18
- **Compte IG cible :** carblazz
- **Produit exact utilisé lors de la génération :** `horloge-metal-noir` + `horloge-packaging`
- **Concept exact :** Déballage — pattern P5 (send-this-to / cadeau)
- **Hook exact :** `Send this to whoever still buys him socks`
- **Caption exacte :** `One box. Solved. 🕒 Link in bio`
- **ManyChat keyword exact :** aucun — bait de partage
- **Marché / langue du brief original :** US / anglais
- **Brief original utilisé :** `DAILY-BRIEF-2026-08-18-CARBLAZZ.md`, POST 3
- **Run report original :** `output/2026-08-18/CARBLAZZ/POST-3/RUN-REPORT.md`
- **Commit de génération :** `6be3682083254c34c4c3dffecb234fb395d554a0`
- **Statut export :** **BLOCKED**
- **Raison BLOCKED :** `FAIL_PACKAGING_MECHANICS` + `FAIL_WRONG_VARIANT` + `FAIL_STATE_CONTINUITY` + `FAIL_MARKET`

## Brief original utilisé — verbatim pour ce post

### Scène 1 — la boîte

> A closed retail box sitting on a wooden table in warm daylight, hands not yet touching it.
> Reproduce this packaging exactly as in the reference. Vertical 9:16, photorealistic, no text
> overlay, no logo beyond what the reference already shows, no watermark, no face.
> Refs : `horloge-packaging`.

### Scène 2 — l'ouverture

> The same table, a pair of hands lifting the lid of this box, the black metal clock face just
> becoming visible inside. Only hands and forearms in frame, casual sleeves, warm daylight.
> Vertical 9:16, photorealistic, no face, no text, no logo, no watermark.
> Refs : `horloge-packaging`, `horloge-metal-noir`.

### Scène 3 — au mur

> This clock now mounted on a plain warm-grey wall, the empty open box on the table below, warm
> daylight. Reproduce this clock exactly as in the reference. Vertical 9:16, photorealistic,
> no text, no logo, no watermark, no people.
> Refs : `horloge-metal-noir`.

## Notes de production importantes

Le vrai packaging n'est **pas** une boîte à couvercle. C'est une sleeve noire mate plate 400 × 400 mm avec grande découpe circulaire, wordmark `blazz` et **tiroir intérieur qui coulisse latéralement**. Le prompt historique `lifting the lid` est donc explicitement invalide.

Le contrôle du 20/08 confirme aussi que la scène 2 montre une variante carbone dans un post prévu pour `horloge-metal-noir` (`FAIL_WRONG_VARIANT`). Enfin, la séquence historique passe directement du déballage au produit monté au mur, alors que l'état correct exige : unboxing → produit tenu → pose/installation → hero mounted.

Le marché US du 18/08 est lui aussi invalidé par la source actuelle, qui place Carblazz en FR.

**Hermès : NE PAS générer de vidéo depuis ces frames, et en particulier NE PAS exécuter le mouvement historique de scène 2.** Conserver uniquement pour audit/traçabilité. La reprise correcte est définie par `DAILY-BRIEF-2026-08-21-CARBLAZZ.md`.