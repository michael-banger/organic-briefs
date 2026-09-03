# Product breakdown - @carblazz

> **LOCK 2026-08-20 - SOURCE PRIORITAIRE ACTIVE.** Avant toute vision pass, prompt Kling/Higgsfield, generation ou QC, appliquer `product-breakdowns/CARBLAZZ-LOCK-2026-08-20.md`. Cette lock a ete fournie par Yann apres reverification image par image et prime sur les descriptions ci-dessous si contradiction. Ne jamais faire confiance au slug : ouvrir `refs/carblazz/[slug].png` et decrire ce qui est reellement visible.

> Revision majeure du 2026-08-20. Les descriptions de cadran des cinq coloris ont ete **verifiees
> une par une contre les planches de reference** et trois d'entre elles etaient fausses. Les
> briefs des 17 et 18/08 ont donc genere des produits qui n'existent pas. Lire la table ci-dessous
> avant d'ecrire quoi que ce soit, et ne jamais se fier au slug seul.
>
> Ce fichier s'ajoute a `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md`, qui porte les
> regles valables pour toutes les marques. En cas de conflit sur un point specifique au produit,
> c'est ce fichier qui prime.

- **Marche** : **FR**, francais parle naturel. Le classement US est invalide depuis le correctif
  du 17/08. Le brief du 18/08 est reparti en US par erreur : hooks et captions anglais,
  mot-cle `CLOCK`. C'est un defaut, pas un precedent.
- **Compte** : bio francaise, captions francaises, CTA ManyChat francais.
- **CTA** : `Commentez « V12 » pour recevoir les infos`. Guillemets francais.
- **Produit** : horloges murales decoratives sur theme automobile.
- **Niche** : decoration d'interieur pour passionnes d'automobile. Le client n'a pas forcement la
  voiture. Il veut afficher sa passion chez lui.
- **Statut** : relance active, priorite 1 a egalite avec Spiraledazur.

---

## 1. Ce que le produit est, physiquement

Une horloge murale ronde, a quartz, cadran unique, aiguilles heures / minutes / secondes, lunette
fine, **faible epaisseur** (le profil de cote de chaque planche le montre : un disque plat, pas un
boitier), fixation murale par un trou au dos. Le theme automobile est dans le cadran, pas dans la
forme.

### VERROU D'ECHELLE, non negociable

**Diametre reel : 35 a 40 cm.** Le packaging fait 400 x 400 mm, ce qui confirme la borne haute.

Cette dimension doit etre **ecrite en centimetres dans chaque prompt** qui met l'horloge en
relation avec un humain, un mur ou un meuble. "Large clock" ne verrouille rien.

Ce que la dimension impose :

- **Tenue en mains : deux mains.** Mains naturellement proches des bords opposes, doigts autour de
  la lunette, poids et rigidite lisibles. Une horloge de 38 cm ne se manipule pas negligemment
  d'une seule main comme un reveil de cuisine.
- **Au mur** : elle garde exactement cette echelle. On ne la grossit pas parce qu'il reste du mur,
  on ne la retrecit pas pour simplifier la composition.
- **Si le mur ou le cadrage ne laissent pas la place** : on change le cadrage ou le mur. Jamais la
  taille du produit.
- Reperes utiles a citer dans un prompt : environ deux largeurs d'epaule d'adulte en diametre,
  environ la hauteur d'un dossier de chaise, nettement plus large qu'une tete humaine.

INTERDIT : une horloge qui se lit comme un objet de 20 a 25 cm.

---

## 2. Les cinq coloris, verifies contre les planches le 2026-08-20

**Un coloris par video.** Jamais deux horloges differentes dans le meme montage. Un changement de
variante dans une scene n'est autorise que sur instruction explicite de Yann pour cette scene.

| Slug | Ce que montre REELLEMENT la planche | Vitre | Aiguilles |
|---|---|---|---|
| `horloge-carbone` | **Jante alliage en fibre de carbone vue de face.** Rayons en vrai tissage carbone brillant, avec de la profondeur mecanique. Derriere les rayons : un **vrai disque de frein** et un **etrier jaune** tres visible. Chiffres blancs 1-12 sur le pourtour, lunette noire. | **OUI**, vitre bombee tres reflechissante | **dorees**, fines, les trois |
| `horloge-metal-noir` | **Jante alliage noire brillante 5 branches**, etrier jaune visible, disque de frein derriere. Lunette imitant un **flanc de pneu noir** avec lettrages moules en relief et **petits emblemes dores** repartis sur le pourtour. Chiffres blancs 1-12. | **OUI**, vitre plate reflechissante | **blanches**, style pelle, trotteuse fine blanche |
| `horloge-metal-rouge` | Meme construction que le metal noir, mais **jante rouge vif brillante 5 branches**. Etrier jaune, disque noir, lunette flanc de pneu noir avec emblemes dores, chiffres blancs. Le rouge ne doit deriver ni vers l'orange ni vers le bordeaux. | **OUI** | **blanches**, style pelle |
| `horloge-compteur` | **Compteur de vitesse ancien.** Cadran noir mat texture, wordmark **NISMO** en blanc sous le 12, fenetre odometre **`170884`**, seconde fenetre **`1984`**, mention **`km/h`**, chiffres blancs **10 a 120 par pas de 10**, index blancs rectangulaires, **quatre points orange** aux positions 12 / 3 / 6 / 9, lunette noire fine. | **OUI**, vitre **bombee**, reflet marque | **blanches** style pelle + trotteuse fine blanche |
| `horloge-bois-f1` | **Il n'y a AUCUN bois.** Le slug est trompeur. Cadran a **livree F1 rouge / blanc / noir** avec une **monoplace F1 vue de dessus** imprimee au centre, chiffres noirs 1-12 sur fond blanc et rouge, index et points noirs, moyeu dore, lunette noire. Face **plate et mate**. | **NON.** Aucune vitre, aucun reflet specular. Ne jamais lui en inventer une. | **noires**, trotteuse fine noire |
| `horloge-packaging` | Voir section 4. | n/a | n/a |

**Defauts confirmes des generations du 18/08**, a ne pas reproduire :
- `bois-f1` brieffe comme "wood-toned face" avec un macro "sur le grain du bois" : le produit n'a
  pas de bois. FAIL_PRODUCT_IDENTITY.
- `metal-noir` brieffe comme "brushed black metal face, machining texture" : le produit est une
  jante avec etrier jaune, pas une plaque de metal brosse. FAIL_PRODUCT_IDENTITY.
- POST 3 scene 2 : couvercle souleve sur un packaging qui est un tiroir. FAIL_PACKAGING_MECHANICS.
- POST 3 scene 2 : l'horloge visible dans la boite est une carbone alors que le post est en
  metal-noir. FAIL_WRONG_VARIANT.

---

## 3. Vitre et reflets

Sur les quatre variantes qui ont reellement une facade en verre (`carbone`, `metal-noir`,
`metal-rouge`, `compteur`), **la vitre doit etre visuellement perceptible**. C'est le principal
signal de realisme du produit : sans elle, l'horloge se lit comme une image plate collee au mur.

A demander explicitement dans le prompt :

```
glass front, natural reflections, controlled specular highlight,
reflection of the window / ceiling light / environment across the glass
```

Mais le reflet ne doit **ni masquer les chiffres, ni laver le cadran, ni ressembler a une plaque
blanche opaque**. La camera, la lumiere ou l'angle sont choisis pour que le reflet soit lisible
et partiel :

- plan tenu en mains : une **legere inclinaison** de l'horloge fait glisser le reflet ;
- hero shot : leger angle ou lumiere laterale.

**`horloge-bois-f1` n'a pas de vitre.** Aucun prompt ne doit lui en donner une. Sa preuve de
matiere, c'est la nettete de la livree et le moyeu dore, pas un reflet.

---

## 4. Packaging : sleeve + tiroir coulissant

`horloge-packaging` = **400 x 400 mm**, noir mat, faible epaisseur (environ 5 cm).
Face avant : une **grande decoupe circulaire** qui laisse voir l'interieur noir, et le wordmark
**`blazz`** en blanc en bas a gauche.

**Ce n'est PAS une boite a couvercle.** La mecanique reelle, montree en vue 5 de la planche, est :

```
ENVELOPPE EXTERIEURE (sleeve)  +  TIROIR INTERIEUR QUI COULISSE LATERALEMENT
```

Le tiroir sort par le cote, avec une petite encoche de prise. L'interieur reste noir.

### Interdits absolus

- `lift the lid`, `open the lid`, `hinged box`, `flip the box open` : **FAIL_PACKAGING_MECHANICS**.
- Une boite profonde de type coffret. Le packaging est **plat**.
- Omettre la decoupe circulaire ou le wordmark `blazz`.

### Deballage correct

Une main stabilise l'enveloppe, l'autre **tire le tiroir lateralement**. Mouvement naturel et
fluide, pas de slow motion. L'horloge se decouvre progressivement. Selon l'angle, on en apercoit
deja une partie encore a l'interieur.

---

## 5. Mains et interaction physique

Des mains dans presque tous les plans. **Aucun visage entier dans le cadre.** Avant-bras et
manches decontractees suffisent.

- **Tenir** l'horloge : deux mains, doigts autour du bord, gravite et poids lisibles.
- **Poser** l'horloge au mur : deux mains, et l'horloge **encore au contact des mains**. Elle
  n'apparait jamais deja fixee.
- **Ajuster** l'horloge : une vraie petite correction, pas une installation rejouee.
- Chaque main a une fonction. Pas de main decorative.

---

## 6. Installation avant hero shot

L'horloge ne passe **jamais** de la boite au mur. Sequence obligatoire des qu'un unboxing est
present :

```
UNBOXING  ->  PRODUIT TENU  ->  POSE / INSTALLATION PAR DES MAINS  ->  HERO SHOT AU MUR
```

Le plan de pose montre explicitement les mains encore en contact. Le hero shot seul vient
**apres**, jamais a la place.

---

## 7. Aiguilles : hard lock

Sur toutes les variantes :

```
1. seule la TROTTEUSE (la plus fine) peut bouger
2. sinon, horloge entierement statique
3. JAMAIS l'aiguille des heures ou des minutes
```

Restent immobiles, sans exception : heures, minutes, jante, rayons, disque de frein, etrier,
cadran, chiffres, fenetres de l'odometre. **Aucune rotation globale du cadran.**

- Horloge **dans les mains ou en cours d'installation** : preferer **toutes les aiguilles
  immobiles**. Le risque de confusion du modele est trop eleve.
- Horloge **posee au mur** : la trotteuse peut avancer, mouvement subtil et realiste. Il n'a pas
  besoin d'etre horlogerement exact, il doit etre visuellement credible.

---

## 8. Decors valides

Relatable mais aspirationnel. Jamais de studio publicitaire abstrait, jamais de fond sombre
"luxury ad" gratuit. Rendu vise : social-native premium.

**A. Appartement haussmannien parisien** : moulures, parquet point de Hongrie, cheminee marbre,
miroir dore, grande fenetre, garde-corps en fer forge, belle lumiere naturelle de fin de journee.

**B. Garage de passionne** : vrai espace habite, belle voiture en arriere-plan, beton poli, lignes
LED credibles, etabli, rangements, deco automobile. Pas besoin d'un showroom irrealiste.

**C. Bureau ou salon de passionne auto**, lumiere naturelle.

### La voiture

Ne pas surcontraindre tous les briefs a un modele unique. Une Porsche 992 GT3 RS fonctionne, une
Ferrari 812 Superfast fonctionne aussi. Le principe : **une voiture aspirationnelle coherente avec
le monde visuel**. Elle est un support narratif, **l'horloge reste le produit principal**.

Si la meme voiture revient dans plusieurs scenes : meme modele, meme couleur, memes jantes, meme
plaque, meme garage.

**Plaques francaises** : format francais reel, jamais de cadre ou de format americain. Si la plaque
est lisible et fait partie de la continuite, elle garde les memes caracteres.

---

## 9. Repertoire de scenes

Une scene = une fonction. Ne pas forcer huit scenes si deux remplissent la meme fonction.

1. **Scroll stopper / context hook** : produit visible vite, environnement auto ou retail fort.
2. **Unboxing** : ouverture reelle du tiroir.
3. **Product in hands** : deux mains, echelle reelle, leger angle pour la matiere et le reflet.
4. **Installation** : deux mains posent physiquement l'horloge au mur.
5. **Hero mounted** : produit installe, composition propre.
6. **Macro / material proof** : carbone, etrier, disque, compteur, chiffres, vitre.
7. **Human adjustment** : micro-interaction credible.
8. **Environmental payoff** : plan plus large, ce que l'objet fait au garage ou au salon.

Une scene qui n'apporte ni information, ni progression, ni preuve produit, ni emotion, ni payoff
est supprimee ou remplacee.

---

## 10. Style des start frames

Vertical 9:16, photorealiste, tres haute qualite, details nets, social-native, look iPhone 17
Pro Max. Peu de profondeur de champ, pas de gros bokeh cinema, exposition realiste, couleurs
naturelles, perspective smartphone credible. Pas de look publicite studio artificielle.

Aucun hook, aucune caption, aucun watermark, aucun texte marketing ajoute, aucun visage entier.
Les seuls textes toleres sont ceux qui appartiennent physiquement au produit ou au packaging
reel : `NISMO`, `170884`, `1984`, `km/h`, `blazz`.

---

## 11. Ce que le prompt video doit verrouiller

```
Use this exact validated start frame as frame 1.
This clock must remain exactly identical to the clock visible in the start frame.
Preserve its exact geometry, diameter, bezel, numerals, hands, glass and mechanical detail.
Only the thin seconds hand may move. The hour and minute hands stay perfectly still.
The wheel, brake disc, caliper and dial never rotate.
```

Mouvements valides :

| Scene | Mouvement |
|---|---|
| Unboxing | fluide, naturel, assez rapide, le tiroir coulisse reellement. Pas de slow motion. |
| Produit en mains | inclinaison de quelques degres pour reveler le reflet et la matiere. Rien de plus. |
| Installation | mouvement court et credible : alignement, puis stabilisation. |
| Hero shot | petit push-in, ou leger mouvement lateral. Tres faible amplitude. |
| Macro | derive laterale minuscule, la lumiere revele la matiere. |
| Plan large | leger push-in handheld ou parallaxe. Pas de drone. |

### NO-GO video

Produit qui morph, chiffres qui changent, jante qui tourne, etrier qui se deplace, aiguilles
heures/minutes qui bougent, produit qui change de taille, voiture ou plaque qui change, reflets
impossibles, mains supplementaires, packaging qui change de mecanique, mouvements camera
spectaculaires, bokeh publicitaire, dialogue ou talking-head invente.

**Aucun `@element` Higgsfield ecrit dans un prompt s'il n'est pas reellement attache.** Ecrire un
faux element ne verrouille rien. Sans element : start frame stricte + prompt de preservation.

---

## 12. QA start frame CARBLAZZ

Fail sur un seul point. Un FAIL se regenere avant promotion, il ne se compense pas.

```
[ ] bonne variante, verifiee contre la planche, pas contre le slug
[ ] diametre visuellement coherent avec 35-40 cm
[ ] prise en mains realiste, deux mains quand l'horloge est portee
[ ] geometrie, lunette, chiffres, aiguilles conformes a la planche
[ ] compteur : NISMO, 170884, 1984, km/h, chiffres 10-120, 4 points orange
[ ] jante : vrais rayons avec profondeur, disque de frein, etrier jaune identifiable
[ ] carbone : tissage visible, pas une photo de jante collee derriere une horloge
[ ] vitre visible sur carbone / metal-noir / metal-rouge / compteur
[ ] AUCUNE vitre sur bois-f1, et aucun bois nulle part
[ ] packaging : sleeve + tiroir, decoupe circulaire, wordmark blazz, boitier plat
[ ] lieu logique, une fonction claire pour la scene
[ ] continuite voiture / plaque / decor si applicable
[ ] pas de visage entier, pas de texte genere
[ ] iPhone social-native, pas de look publicite IA
```

## 13. QA video CARBLAZZ

```
[ ] frame 1 = start frame validee
[ ] produit ne morph pas, taille ne derive pas
[ ] chiffres et fenetres identiques du debut a la fin
[ ] jante immobile, disque immobile, etrier immobile
[ ] heures immobiles, minutes immobiles
[ ] seule la trotteuse fine bouge, ou rien du tout
[ ] vitre et reflets restent physiques
[ ] mains anatomiquement plausibles
[ ] packaging garde la mecanique du tiroir
[ ] voiture et plaque coherentes
[ ] mouvement camera fluide et de faible amplitude
[ ] aucun dialogue, aucune information visuelle inventee
```

---

## 14. Hook gagnant a decliner

Format transplante de Spiraledazur, valide sur la relance du 16/08 :

`Les fans de voitures ne marchez pas FONCEZ en Boutique`

Au moins la moitie d'un batch Carblazz doit decliner ce format plutot qu'inventer un hook neuf.
Le hook est en **francais**.

Format final du montage : 1080x1920, 30 fps, 10 a 13 s, 8 a 10 plans.

---

## 15. Points restes ouverts

1. La reference du 16/08 montre deux coloris dans la meme video, alors que le verrou dit un
   coloris par video. **Tant que Yann n'a pas tranche, la regle appliquee est : un coloris par
   video.**
2. Le lien en bio pointe sur `carblazz.com/products/lampes-resine-art`, pas sur une horloge
   murale. A corriger cote boutique, sans effet sur la generation.
