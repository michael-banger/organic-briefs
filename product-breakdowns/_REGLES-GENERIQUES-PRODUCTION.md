# Regles generiques de production, toutes marques

Ecrit le 2026-08-20. Source : deux sessions de production validees par Yann (CARBLAZZ horloges,
SPIRALEDAZUR sac coquillage). Ces regles ne sont pas theoriques : chacune vient d'une
regeneration reelle qu'il a fallu demander parce que le brief ne l'avait pas anticipee.

**Lecture obligatoire avant d'ecrire un brief, un prompt de start frame ou un prompt video.**
Le fichier `product-breakdowns/[MARQUE].md` s'y ajoute et prime en cas de conflit sur un point
specifique au produit.

Philosophie a retenir en une phrase : **on ne repare pas apres coup une scene mal pensee, on
concoit le brief pour que la bonne geometrie, la bonne physique, la bonne continuite et la bonne
action soient deja inevitables avant la premiere generation.**

---

## G1. REAL-WORLD SCALE LOCK

Quand la taille physique d'un produit influence l'interaction humaine, elle doit etre **connue et
ecrite en centimetres dans le brief**, et le prompt doit raisonner en taille physique, jamais en
adjectif ("large", "big", "oversized" ne verrouillent rien).

La dimension influence : taille relative aux mains, a une tete ou un torse, sur un mur ou un
meuble, dans un packaging, la profondeur, la distance camera et le cadrage.

Si la dimension reelle n'est pas connue, ne pas l'inventer : ecrire les **rapports relatifs**
(par rapport au corps, a une main, a un iPhone) et le dire explicitement dans le brief.

## G2. PRODUCT > COMPOSITION

Le decor s'adapte au produit. Jamais l'inverse.

Si le mur, le cadre, l'arche d'une story ou le crop ne laissent pas la place a la taille reelle du
produit : **changer le cadrage, le mur, l'arche ou le decor**. Ne jamais etirer, allonger,
retrecir ou grossir le produit pour remplir une forme ou simplifier une composition.

## G3. PHYSICAL INTERACTION CHECK

Chaque main visible doit avoir une **fonction identifiable**. Le brief dit laquelle agit, laquelle
stabilise, ou elle touche.

- Objet lourd, large ou rigide : **deux mains**, doigts autour du bord, poids et gravite lisibles.
- Objet leger manipule : une main agit, la seconde stabilise le cote oppose si necessaire.
- Interdits : deux mains tirant la meme zone du meme cote, mains flottantes, doigts fusionnes,
  main traversant une sangle, poignet impossible, main qui masque l'element produit principal,
  main qui deforme le produit pour accomplir le geste, mains decoratives sans raison.

Une mauvaise interaction ne degrade pas seulement l'esthetique : elle **fait reconstruire le
produit de travers** par le modele. C'est un FAIL produit, pas un FAIL de detail.

## G4. PHYSICAL STATE CONTINUITY

Un produit ne se teleporte jamais entre deux etats physiques : emballe, tenu, pose, installe,
utilise. Chaque transition demande son plan.

Consequence directe et frequente : un objet ne passe pas **de la boite au mur**. Il faut
UNBOXING, puis PRODUIT TENU, puis POSE PAR DES MAINS, puis seulement HERO SHOT seul.
Le plan de pose montre explicitement les mains **encore en contact** avec le produit.

## G5. PACKAGING MECHANICS

Avant d'ecrire une scene de deballage, **analyser la vraie cinematique d'ouverture depuis la
planche de reference** : couvercle articule, couvercle a soulever, sleeve avec tiroir coulissant,
sachet, film. Ne jamais inventer une mecanique generique.

Ecrire la mecanique dans le brief, en toutes lettres, et l'interdit correspondant.
Exemple reel : "lift the lid" sur un packaging qui est en realite un **sleeve avec tiroir
coulissant** a produit trois generations fausses le 18/08.

## G6. MATERIAL PROOF

Identifier les proprietes physiques qui donnent son realisme au produit (verre, metal brosse,
tissage, crochet, bois, cuir, liquide, nacre) et **prevoir au moins un plan qui les rend
visibles**, avec la lumiere et l'angle qui vont avec.

Le reflet, le grain, la fibre sont des **signaux de realisme**. Un produit sans eux se lit comme
une image plate collee dans la scene.

Corollaire strict : **ne jamais inventer une propriete que le produit n'a pas.** Pas de vitre sur
une variante sans vitre, pas de metal sur un modele sans metal. La planche de reference tranche.

## G7. ONE SCENE = ONE FUNCTION

Une scene existe pour une raison : hook, interaction, preuve produit, capacite, echelle,
projection lifestyle, transition, payoff, hero. Le brief ecrit la fonction.

Une scene qui n'apporte ni information, ni progression, ni preuve, ni emotion, ni payoff est
**supprimee ou remplacee**, pas gardee "parce qu'elle est jolie". Un macro passif ne merite pas
une scene par lui-meme : il lui faut une action, un reveal, ou une preuve.

Ne pas forcer un nombre de scenes. Deux scenes qui remplissent la meme fonction, c'est une scene.

## G8. RELATABLE ASPIRATIONAL LOCATION

Monde reel premium, jamais studio publicitaire abstrait ni fond sombre "luxury ad" gratuit.
Rendu vise : **social-native premium**.

Si le brief nomme un lieu, le decor doit le **communiquer visuellement**, pas seulement dans le
texte du prompt. "Paris" veut dire fenetre haute, garde-corps en fer forge, immeuble haussmannien,
moulures, parquet point de Hongrie. Un decor beige generique ne suffit pas.

**Crowd veut dire crowd.** Une scene de foule avec deux ou trois personnes est un FAIL. Ecrire
"large dense crowd of many people", jamais "several people".

## G9. START FRAME IS THE CONTRACT

La video **anime** la start frame, elle ne la redessine pas. Le prompt video decrit
**mouvement + camera + etat final**, et protege explicitement le produit :

```
Use this exact validated start frame as frame 1.
The product must remain exactly identical to the product visible in the start frame.
Preserve its exact geometry, proportions, materials, surface detail and real-world scale.
```

Le prompt video ne reinvente ni le decor, ni le produit, ni la lumiere.

## G10. MOTION MINIMALISM

Pour un produit statique : **petits mouvements de camera et de mains**, jamais d'animation
artificielle du produit lui-meme. Un objet pose reste en contact avec sa surface, ne glisse pas,
ne respire pas, ne tourne pas sans interaction, ne s'ouvre pas seul.

Le mouvement camera doit paraitre **motive par une personne qui filme**, pas par un bras robot de
publicite. Faible amplitude : micro push-in, leger arc, petite derive laterale, follow handheld.
Pas de drone, pas de slow motion sur un geste utilitaire, pas de mouvement spectaculaire.

## G11. EXACT PRODUCT TEXT / DETAIL LOCK

Quand des chiffres, graduations, index, motifs, coutures, logos physiques ou fenetres font partie
du produit reel, ils sont **compares un a un a la planche canonique**. Une derive sur un chiffre
ou une graduation est un FAIL produit.

Rappel connexe, deja verrouille : **aucun texte genere dans l'image.** Les seuls textes tolerés
sont ceux qui appartiennent physiquement au produit ou a son packaging reel.

## G12. FAIL BEFORE CREDIT SPEND

Une generation ne part pas si l'un de ces points est vrai :

- echelle douteuse ou non ecrite ;
- fidelite produit douteuse ou reference manquante ;
- mecanique de packaging non comprise ;
- scene physiquement impossible ;
- contradiction entre le brief et le breakdown produit ;
- fonction de scene absente.

On corrige le brief. On ne lance pas pour voir.

## G13. ANIMATEABILITY GATE

Une start frame n'est pas une belle photo : c'est un **etat initial de video**. Avant de la
valider, verifier qu'elle est animable :

- aucun membre ambigu, aucune main fusionnee ;
- aucun objet coince ou traversant un autre ;
- pas d'occlusion critique du produit ;
- geometrie stable, action suivante evidente ;
- pas de miroir dont le reflet ne peut pas etre coherent (**si le reflet est douteux, retirer le
  miroir** : il n'est jamais indispensable) ;
- profondeur exploitable pour un petit mouvement camera.

## G14. ACCESSORY SUBORDINATE

Un objet utilise pour demontrer le produit ne doit jamais voler le plan. Il doit etre **plus
petit que le produit**, compatible avec son volume reel, et ne jamais l'occulter.
Contre-exemple reel : un telephone qui remplit le sac et devient le sujet de l'image.

## G15. PLANNING BOARD != GENERATION FRAME

Une planche multi-scenes ou un storyboard 16:9 sert a **planifier**. Il ne remplace jamais
l'asset d'animation. Pour un moteur image-to-video, l'input est **une frame autonome verticale
9:16 par scene**. Un collage envoye comme start frame est un FAIL de format.

## G16. REFERENCE DOMINANCE

La reference produit est une **source d'identite et de geometrie**, pas une inspiration
stylistique. Le prompt doit le dire dans ces termes.

Ordre de priorite en cas de conflit, sans exception :

```
REFERENCE PRODUIT CANONIQUE  >  CONTRAINTES DU BRIEF  >  FRAME DE CONTINUITE PRECEDENTE
```

Une frame precedente ratee ne contamine jamais l'identite produit. Et on n'utilise la frame
precedente comme ancre que **quand la continuite est requise**, pas mecaniquement sur chaque
scene : un hard cut vers un nouveau decor n'a pas d'ancre.

---

## Champs obligatoires d'une scene de brief

Un brief ne doit plus jamais contenir "Scene 4 : quelqu'un pose l'objet au mur". Chaque scene
porte au minimum :

| Champ | Contenu |
|---|---|
| `SCENE FUNCTION` | pourquoi la scene existe (G7) |
| `START STATE` | ou sont exactement produit, personne, mains, accessoires |
| `PRODUCT LOCK` | ce qui ne doit pas varier, en clair |
| `SCALE` | dimension physique ou rapport relatif (G1) |
| `ACTION` | l'action simple prevue pour la video |
| `HAND LOGIC` | quelle main agit, quelle main stabilise (G3) |
| `STATIC ELEMENTS` | ce qui ne bouge surtout pas |
| `CAMERA` | position et mouvement attendu (G10) |
| `LOCATION SIGNALS` | ce qui rend le lieu immediatement lisible (G8) |
| `CONTINUITY FROM` | numero de scene precedente, ou `none` |
| `MUST REMAIN IDENTICAL` | attributs verrouilles |
| `MORPHING RISKS` | ce qu'il faut eviter dans la start frame |
| `NEGATIVE` | erreurs connues a interdire |

Precis sur les contraintes dures, simple sur ce que le modele sait deja faire. Le brief ne doit
pas devenir un roman.

---

## QA START FRAME, gate generique

Fail sur un seul point critique. Un FAIL se **regenere**, il ne se compense pas au montage ni au
prompt video.

```
[ ] bonne variante / bon coloris / bon modele
[ ] echelle physique credible (G1)
[ ] fidelite a la planche de reference : geometrie, materiaux, details (G16, G11)
[ ] proprietes physiques reelles presentes, aucune inventee (G6)
[ ] mains anatomiquement plausibles, chaque main a une fonction (G3)
[ ] packaging avec la bonne mecanique s'il est present (G5)
[ ] etat physique du produit coherent avec la scene precedente (G4)
[ ] une fonction de scene claire (G7)
[ ] lieu immediatement lisible, foule reellement dense si demandee (G8)
[ ] accessoires subordonnes, produit non masque (G14)
[ ] frame animable, pas de miroir douteux (G13)
[ ] 9:16, une frame autonome, pas de collage (G15)
[ ] aucun texte, logo, watermark ou caption genere (G11)
[ ] rendu social-native iPhone, pas de look publicite IA
```

## QA VIDEO, gate generique

```
[ ] frame 1 = la start frame validee (G9)
[ ] le produit ne morph pas, ne change ni de taille ni de geometrie
[ ] les details verrouilles (chiffres, motifs, hardware) restent identiques
[ ] rien ne bouge qui ne devrait pas bouger (G10)
[ ] objet pose : contact conserve, aucun glissement, aucune levitation
[ ] mains anatomiquement stables du debut a la fin
[ ] un seul objet manipule a la fois, les autres restent en place
[ ] packaging : mecanique d'ouverture conservee
[ ] continuite : meme personne, meme tenue, meme lumiere, meme decor
[ ] mouvement camera fluide, faible amplitude, pas de look publicitaire
[ ] aucun dialogue invente, aucun texte ou logo genere
[ ] premiere seconde comprehensible
```

Tout echec produit, physique ou anatomique se **regenere**. Jamais "ca passera au montage".
