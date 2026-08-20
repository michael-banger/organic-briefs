# DAILY BRIEF — CARBLAZZ — publication 2026-08-21

**Ce brief est un rattrapage correctif.** Il reprend les 3 posts du 18/08, qui ont bien ete
generes mais avec des produits qui n'existent pas, et il les rejoue avec les descriptions
verifiees contre les planches le 2026-08-20. Les fichiers de `output/2026-08-18/CARBLAZZ/` sont
**a considerer comme non exploitables**, ils ne partent pas au montage.

Lecture obligatoire avant de generer :
1. `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md`
2. `product-breakdowns/CARBLAZZ.md` (revision du 2026-08-20)
3. `MANIFEST.md`, section `refs/carblazz/`

## Ce qui change par rapport au 18/08

| Point | 18/08 | Correct |
|---|---|---|
| Marche | US, hooks anglais, mot-cle `CLOCK` | **FR**, hooks francais, `Commentez « V12 » pour recevoir les infos` |
| `horloge-bois-f1` | "wood-toned face", macro sur le grain du bois | **aucun bois** : livree F1 rouge/blanc/noir, monoplace au centre, moyeu dore, **face plate sans vitre** |
| `horloge-metal-noir` | "brushed black metal face, machining texture" | **jante alliage noire brillante 5 branches**, etrier jaune, disque de frein, lunette flanc de pneu avec emblemes dores, **vitre reflechissante** |
| Packaging | `lifting the lid` | **sleeve 40 x 40 cm plat + tiroir qui coulisse lateralement**, decoupe circulaire, wordmark `blazz` |
| Deballage | boite -> mur directement | unboxing -> **produit tenu a deux mains** -> pose -> hero |
| Echelle | jamais ecrite | **35-40 cm ecrits dans chaque prompt** |

- Lane **KLING**. 3 posts, 3 scenes chacun. **Un coloris par post.**
- Coloris du jour : POST 1 `horloge-bois-f1`, POST 2 `horloge-metal-noir`, POST 3
  `horloge-metal-noir` + `horloge-packaging` pour l'ouverture.
- "this clock" dans tous les prompts. Jamais de nom de marque. Aucun visage entier.
- 3 references maximum. Passe vision obligatoire sur chaque start frame avant le prompt video.
- Montage cible 10-13 s.

## References

| Slug | URL brute |
|---|---|
| `horloge-bois-f1` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/carblazz/horloge-bois-f1.png |
| `horloge-metal-noir` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/carblazz/horloge-metal-noir.png |
| `horloge-packaging` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/carblazz/horloge-packaging.png |

---

## POST 1 — Livree F1 — pattern P4 (fandom lock)

- `lane: KLING` · `post_id: 1` · `colorway: horloge-bois-f1` · `pattern: P4`
- `hook_overlay:` **"Les fans de F1 ont tous le meme mur vide"**
- `caption:` "Le week-end de course commence sur le mur. Lien en bio"
- `cta:` `Commentez « V12 » pour recevoir les infos` · `hashtags:` #f1 #formule1 #passionauto #decoauto #salon

**SCENE 1 — le mur vide**
- `SCENE FUNCTION` : hook, installer le manque.
- `START STATE` : salon un soir de week-end de course, un grand televiseur en sourdine affiche des
  couleurs de sport auto floues, canape bas, lampe chaude, **large pan de mur gris chaud vide sur
  la droite du cadre**. Personne dans la piece.
- `SCALE` : le mur libre fait au moins 70 cm de large, de quoi accueillir une horloge de 38 cm
  sans etre a l'etroit.
- `CAMERA` : hauteur d'oeil, cadrage 9:16, legere plongee.
- `CONTINUITY FROM` : none.
- `NEGATIVE` : aucun produit, aucun texte, aucun visage.
- Refs : aucune.

**SCENE 2 — les mains posent**
- `SCENE FUNCTION` : transition d'etat, poids et echelle.
- `START STATE` : le meme mur, **deux mains tiennent l'horloge contre le mur**, doigts autour de
  la lunette, elle est **encore au contact des mains**, pas encore lachee.
- `PRODUCT LOCK` : cadran a **livree F1 rouge, blanche et noire**, **monoplace F1 vue de dessus**
  imprimee au centre, chiffres noirs 1-12, index et points noirs, **moyeu dore**, lunette noire,
  **face plate et mate**.
- `NEGATIVE` : **aucun bois, aucun grain de bois, aucune vitre, aucun reflet specular.** Cette
  variante n'a pas de verre.
- `SCALE` : diametre 35-40 cm, environ deux largeurs d'epaule d'adulte.
- `HAND LOGIC` : deux mains, une de chaque cote, avant-bras et manches decontractees seulement.
- `STATIC ELEMENTS` : toutes les aiguilles immobiles.
- `CONTINUITY FROM` : 1. `MUST REMAIN IDENTICAL` : mur, televiseur, lampe, lumiere, mobilier.
- Refs : `horloge-bois-f1`.

**SCENE 3 — hero mounted**
- `SCENE FUNCTION` : payoff.
- `START STATE` : l'horloge est en place sur le mur, les mains sont sorties du cadre, la lueur du
  televiseur rebondit doucement sur la face mate.
- `ACTION` video : micro push-in, la trotteuse noire fine avance. Le cadran ne tourne pas.
- `CONTINUITY FROM` : 2.
- Refs : `horloge-bois-f1`.

---

## POST 2 — Jante noire — pattern P1 (contexte aspirationnel, garage)

- `lane: KLING` · `post_id: 2` · `colorway: horloge-metal-noir` · `pattern: P1`
- `hook_overlay:` **"Le garage etait deja beau. Il manquait ca."**
- `caption:` "Quand le mur raconte la meme histoire que la voiture. Lien en bio"
- `cta:` `Commentez « V12 » pour recevoir les infos` · `hashtags:` #garage #supercar #passionauto #decoauto #jante

**SCENE 1 — le garage**
- `SCENE FUNCTION` : scroll stopper aspirationnel.
- `START STATE` : garage de passionne, beton poli, lignes LED credibles, etabli, rangements, une
  **belle voiture de sport** en arriere-plan legerement floue, **mur libre au premier plan**.
- `LOCATION SIGNALS` : vrai espace habite, pas un showroom irrealiste, pas de fond noir
  publicitaire. Plaque francaise si elle est lisible.
- `CONTINUITY FROM` : none.
- Refs : aucune.

**SCENE 2 — les mains ajustent**
- `SCENE FUNCTION` : le produit prend sa place, echelle.
- `START STATE` : le meme mur, **deux mains ajustent l'horloge** deja presque en place, petite
  correction d'alignement, doigts sur la lunette.
- `PRODUCT LOCK` : **jante alliage noire brillante 5 branches** vue de face, **etrier de frein
  jaune** bien visible derriere les branches, **disque de frein** derriere, lunette imitant un
  **flanc de pneu noir** avec lettrages moules en relief et **petits emblemes dores** repartis sur
  le pourtour, **aiguilles blanches** style pelle, trotteuse fine blanche, chiffres blancs 1-12.
- `PRODUCT LOCK` : **vitre plate reflechissante en facade**, reflet partiel des LED du garage,
  qui ne lave pas le cadran et ne masque pas les chiffres.
- `NEGATIVE` : **jamais "brushed metal", jamais "machining texture", jamais une plaque de metal
  pleine.** C'est une jante, pas un disque brosse.
- `SCALE` : diametre 35-40 cm, environ la moitie du diametre d'une roue de la voiture au fond.
- `HAND LOGIC` : deux mains, une de chaque cote, avant-bras seulement.
- `CONTINUITY FROM` : 1. `MUST REMAIN IDENTICAL` : **meme voiture, meme couleur, memes jantes,
  meme plaque, meme garage, meme lumiere.**
- Refs : `horloge-metal-noir`.

**SCENE 3 — macro material proof**
- `SCENE FUNCTION` : preuve de matiere.
- `START STATE` : macro sur le cadran, lumiere rasante. Doivent etre lisibles : le **brillant de
  la jante**, l'**etrier jaune**, le **disque de frein**, le **lettrage moule du flanc de pneu**,
  un **embleme dore**, et le **reflet de la vitre** qui glisse sur la surface.
- `ACTION` video : derive laterale minuscule, la lumiere revele la matiere. La jante ne tourne
  pas, l'etrier ne bouge pas, seule la trotteuse fine peut avancer.
- `CONTINUITY FROM` : 2.
- Refs : `horloge-metal-noir`.

---

## POST 3 — Le deballage — pattern P5 (send-this-to / cadeau)

- `lane: KLING` · `post_id: 3` · `colorway: horloge-metal-noir` · `pattern: P5`
- `hook_overlay:` **"Envoie ca a celui qui offre encore des chaussettes"**
- `caption:` "Un carton. Probleme regle. Lien en bio"
- `cta:` aucun mot-cle, bait de partage. Ne jamais melanger un bait de partage et un mot-cle
  ManyChat dans le meme post. · `hashtags:` #cadeauhomme #decoauto #passionauto #ideecadeau

**SCENE 1 — la boite fermee**
- `SCENE FUNCTION` : curiosite.
- `START STATE` : le packaging **pose a plat** sur une table en bois, lumiere du jour chaude,
  personne ne le touche encore.
- `PRODUCT LOCK` : **sleeve noir mat 40 x 40 cm, plat, environ 5 cm d'epaisseur, grande decoupe
  circulaire en facade qui laisse voir l'interieur noir, wordmark `blazz` en blanc en bas a
  gauche.**
- `NEGATIVE` : **pas de coffret profond, pas de couvercle, pas de charniere.**
- `CAMERA` : trois-quarts, hauteur de table.
- `CONTINUITY FROM` : none.
- Refs : `horloge-packaging`.

**SCENE 2 — le tiroir coulisse**
- `SCENE FUNCTION` : preuve produit + reveal.
- `START STATE` : **une main a plat stabilise l'enveloppe, l'autre tire le tiroir interieur
  lateralement**, sorti d'environ un tiers. On apercoit le cadran noir de la jante a l'interieur.
  L'interieur du packaging reste noir.
- `HAND LOGIC` : main gauche a plat sur le sleeve, main droite sur l'encoche du tiroir. Avant-bras
  seulement, manches decontractees.
- `NEGATIVE` : **jamais "lift the lid"**, jamais un couvercle souleve. C'est un tiroir.
- `MORPHING RISKS` : boite qui devient un coffret, ouverture par le haut, mains fusionnees.
- `ACTION` video : le tiroir coulisse reellement, mouvement fluide et assez rapide, pas de slow
  motion.
- `CONTINUITY FROM` : 1. Meme table, meme lumiere, memes manches.
- Refs : `horloge-packaging`, `horloge-metal-noir`.

**SCENE 3 — tenue a deux mains, hors de la boite**
- `SCENE FUNCTION` : echelle et matiere. **C'est le plan qui manquait au 18/08** : l'horloge ne
  passe jamais de la boite au mur.
- `START STATE` : **deux mains** tiennent l'horloge sortie du tiroir, **legerement inclinee** pour
  que le reflet glisse sur la vitre. Le packaging ouvert reste visible en bas de cadre, tiroir
  encore sorti.
- `SCALE` : diametre 35-40 cm, nettement plus large qu'une tete humaine.
- `STATIC ELEMENTS` : **toutes les aiguilles immobiles** tant que l'horloge est dans les mains.
- `ACTION` video : inclinaison de quelques degres seulement, le reflet glisse. Rien d'autre ne
  bouge.
- `CONTINUITY FROM` : 2.
- Refs : `horloge-metal-noir`.

---

## Controle avant de marquer pret

Gates : sections 12 et 13 de `product-breakdowns/CARBLAZZ.md`. Un FAIL se regenere avant
promotion. Une start frame qui rate une contrainte dure ne se compense pas au prompt video.
