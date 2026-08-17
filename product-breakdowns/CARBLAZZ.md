# Product breakdown - @carblazz

- **Marche** : FR, francais parle naturel. Ancien classement US invalide depuis le correctif du 17/08.
- **Compte** : bio francaise, captions francaises, CTA ManyChat francais.
- **CTA** : `Commentez « V12 » pour recevoir les infos`.
- **Produit** : horloges murales decoratives sur theme automobile.
- **Niche** : decoration de maison pour passionnes d'automobile. Le client n'a pas forcement la voiture. Il veut afficher sa passion chez lui.
- **Statut** : relance active, priorite 1 a egalite avec Spiraledazur.

## Ce que le produit est, physiquement

Une horloge murale ronde, a quartz, cadran unique, aiguilles heures/minutes/secondes, lunette fine, faible epaisseur, fixation murale par un trou au dos. Le theme automobile est dans le cadran, pas dans la forme.

Cinq coloris, tous documentes par une planche 7 vues dans `refs/carblazz/`. **Un coloris par video**, sauf contradiction non tranchee avec la reference du 16/08 qui montre deux coloris. Tant que Yann n'a pas tranche, les nouveaux briefs restent un coloris par video.

| Slug | Ce que rejoue le cadran | Notes de generation |
|---|---|---|
| `horloge-carbone` | jante alliage en fibre de carbone vue de face, disque de frein et etrier jaune visibles derriere les rayons, aiguilles dorees fines, chiffres blancs 1-12, lunette noire | Le plus spectaculaire. Le tissage carbone doit rester lisible en macro. |
| `horloge-compteur` | compteur de vitesse ancien : cadran noir, index blancs, chiffres 10 a 120 km/h, points orange, fenetres `170884` et `1984`, trotteuse blanche fine | Porte une marque automobile tierce visible sur le produit reel. Ne jamais construire un hook ou une revendication autour. |
| `horloge-metal-noir` | disque de frein, metal brosse noir | Le grain du metal doit rester visible sous lumiere rasante. |
| `horloge-metal-rouge` | disque de frein, metal rouge | Le rouge ne doit pas deriver orange/bordeaux. |
| `horloge-bois-f1` | theme bois / F1 | Decor salon course ou bureau. |
| `horloge-packaging` | boite retail | Scenes de deballage uniquement, jamais produit heros. |

## Verrous video Carblazz

- Produit visible des le premier frame sur les formats de relance.
- Des mains dans presque tous les plans. Aucun visage porteur.
- L'horloge n'apparait jamais d'un coup sur un mur. Des mains la posent.
- Seule l'aiguille des secondes bouge, la plus fine. Les heures/minutes restent immobiles. A defaut, aucune aiguille ne bouge.
- Produit = decoration murale d'interieur, jamais accessoire d'habitacle.
- Format final : 1080x1920, 30 fps, 10 a 13 s, 8 a 10 plans.

## Decors qui marchent

- Appartement haussmannien parisien : moulures, cheminee marbre, miroir dore, parquet point de Hongrie, fenetre balcon fer forge.
- Garage parisien avec belles voitures : supercar visible en arriere-plan, mur disponible, lumiere realiste.
- Bureau / salon de passionne auto, jamais rendu publicitaire sombre.

## Hook gagnant a decliner

Format transplante de Spiraledazur et valide sur la relance du 16/08 :

`Les fans de voitures ne marchez pas FONCEZ en Boutique`

Au moins la moitie d'un batch Carblazz doit decliner ce format plutot qu'inventer un hook neuf.

## Contradictions a trancher par Yann

1. La reference Carblazz du 16/08 montre deux coloris dans la meme video, alors que le verrou produit dit un coloris par video.
2. Le lien en bio pointe sur `carblazz.com/products/lampes-resine-art`, pas sur une horloge murale.
