# STANDING BRIEF - SPIRALEDAZUR

**Ce fichier ne se perime jamais.** Il sert des qu'aucun `DAILY-BRIEF-{date}-SPIRALEDAZUR.md`
n'existe pour la nuit en cours. Un brief date, quand il existe, prime toujours.

**A lire avant de generer, dans cet ordre :**
1. `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md`
2. `product-breakdowns/SPIRALEDAZUR.md`
3. `MANIFEST.md`, section `refs/spiraledazur/`

---

## Cadre fixe

- Marche **FR**. Lane **KLING**. **3 posts par nuit, 3 scenes par post.**
- **Produit de tete : le sac coquillage.** Reference unique et obligatoire :
  `HANBAG-COQUILLAGE-REF`. C'est une **identity and geometry source**, pas une inspiration.
- Le prompt dit **"this bag"**. Jamais un nom de marque, jamais un nom de concurrent.
- **Aucun CTA a mot-cle** tant qu'aucun auto-DM ne tourne : il promet une reponse que personne
  n'envoie, c'est la cause numero 1 des zero vente. CTA lien en bio uniquement.
- Le **prix 39,99 EUR** n'apparait pas dans les start frames. C'est un plan de montage d'une
  seconde en fin de sequence.
- **3 references maximum** par image. Passe vision obligatoire avant le prompt video.
- Aucun texte, aucun hook, aucun watermark dans l'image. Aucun visage entier.
- Tenue **d'ete** obligatoire. Aucun fragment de vetement d'hiver visible, meme partiel.

## Rotation deterministe

Soit `D` = jour du mois de la date cible.

**Concept du POST 1** = `D mod 4` dans la liste ci-dessous. **POST 2** = `(D+1) mod 4`.
**POST 3** = `(D+2) mod 4`.

URL brute de la reference :
`https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/spiraledazur/HANBAG-COQUILLAGE-REF.png`
Lieu retail : `.../refs/spiraledazur/MONOPRIX-RAYON.png`.
Avatars disponibles : `HANDBAG-AVATARS-REF`, `MEUF-HANDBAG-V2`, `GRANDMA-HANDBAG-V2`.

---

## CONCEPT 0 - La ruee en boutique (pattern P4)

Squelette valide par Yann, scenes 1-2-6 de la Video 1.

- `hook_overlay:` **"J'ai cru que c'etait une boutique de creatrice"**
- `caption:` "Vous l'auriez pris quelle couleur ?" / lien en bio
- `hashtags:` #sacencrochet #crochet #faitmain #shopping

**SCENE 1 - le rayon**
- `SCENE FUNCTION` : scroll stopper + preuve sociale.
- `START STATE` : rayon de grande surface francaise, **rempli uniquement du sac coquillage blanc**,
  pas un patchwork de sacs crochet differents. **Foule dense de femmes** devant le rayon.
- `LOCATION SIGNALS` : doit se lire comme un Monoprix, une Galeries Lafayette, un Zara ou un H&M.
  Jamais un entrepot generique. **Aucune nourriture dans le champ.**
- `CROWD` : `large dense crowd of many women in summer outfits`. Deux ou trois personnes est un FAIL.
- `HAND LOGIC` : aucune main au premier plan.
- `CAMERA` : hauteur d'oeil, legere derive avant.
- `MORPHING RISKS` : foule anatomiquement cassee au fond, sacs differents sur le rayon.
- Refs : `HANBAG-COQUILLAGE-REF`, `MONOPRIX-RAYON`.

**SCENE 2 - la prise**
- `SCENE FUNCTION` : interaction + desirabilite.
- `START STATE` : meme rayon, **une main attrape un sac** sur le presentoir. **Aucun prix
  visible** nulle part.
- `HAND LOGIC` : une seule main, qui saisit l'anse en corde. Le sac ne se deforme pas sous la prise.
- `PRODUCT LOCK` : blanc pur, cotes rayonnantes, rosace centrale, mousquetons dores, chaine de
  perles.
- `CONTINUITY FROM` : scene 1. Meme rayon, meme lumiere, meme foule au fond.
- Refs : `HANBAG-COQUILLAGE-REF`, `MONOPRIX-RAYON`.

**SCENE 3 - la sortie**
- `SCENE FUNCTION` : echelle sur corps + styling.
- `START STATE` : une femme quitte l'univers boutique, **le sac porte a l'epaule**, tenue d'ete,
  vue de trois-quarts arriere, visage non entier.
- `SCALE` : le sac doit rester compact contre le corps, jamais allonge pour remplir le cadre.
- `ACTION` video : trailing handheld follow, leger balancement du sac, aucune deformation de la
  coquille.
- `CONTINUITY FROM` : scene 2.
- Refs : `HANBAG-COQUILLAGE-REF`, un avatar.

---

## CONCEPT 1 - La preparation parisienne (pattern P1)

Squelette valide par Yann, scenes 3-4-5 de la Video 1.

- `hook_overlay:` **"Arrete, personne va acheter ca"**  (hook objection, seul gagnant enregistre)
- `caption:` "Soyez honnetes, vous l'achèteriez ?" / lien en bio
- `hashtags:` #faitmain #crochet #petitecreatrice #sacencrochet

**SCENE 1 - la chambre parisienne**
- `SCENE FUNCTION` : projection lifestyle.
- `START STATE` : chambre elegante mais vecue, **le sac pose sur le lit**, ombre de contact
  visible, une femme en tenue d'ete a proximite, visage non entier.
- `LOCATION SIGNALS` : **fenetre haute, garde-corps en fer forge, immeubles haussmanniens visibles
  dehors**, moulures, textiles clairs, lumiere naturelle. Un decor beige generique est un FAIL.
- `NEGATIVE` : pas de miroir. S'il en faut un et que son reflet n'est pas rigoureusement coherent,
  **on le retire**.
- Refs : `HANBAG-COQUILLAGE-REF`, un avatar.

**SCENE 2 - le packing**
- `SCENE FUNCTION` : preuve d'usage et de capacite.
- `START STATE` : le sac deja bien positionne, **ouverture lisible**. **Une** main descend un
  **petit objet cosmetique ferme** dans l'ouverture. Le produit reste dominant dans l'image.
- `HAND LOGIC` : la main droite descend l'objet, la main gauche stabilise le cote oppose du sac.
- `ACCESSORY` : petit objet feminin du quotidien, reconnaissable, qui **entre physiquement** dans
  le sac. Jamais un telephone : il domine le plan et vole le produit.
- `STATIC ELEMENTS` : tout le reste immobile.
- `CONTINUITY FROM` : scene 1. Meme lit, meme lumiere, meme manucure, meme tenue.
- Refs : `HANBAG-COQUILLAGE-REF`.

**SCENE 3 - what's in my bag**
- `SCENE FUNCTION` : capacite + curiosite.
- `START STATE` : vue haute legerement plongeante, le sac au centre, **plusieurs petits objets
  feminins disposes autour**, tous compatibles avec son volume.
- `CAMERA` : camera haute tres legerement flottante.
- `ACTION` video : un seul objet manipule a la fois, le reste du flat lay reste statique.
- `CONTINUITY FROM` : scene 2.
- Refs : `HANBAG-COQUILLAGE-REF`.

---

## CONCEPT 2 - La rue haussmannienne (pattern P5)

- `hook_overlay:` **"Envoie ca a celle qui cherche un sac depuis 3 mois"**
- `caption:` "Elle va le reconnaitre tout de suite" / lien en bio
- `hashtags:` #paris #sacencrochet #modeete #faitmain

**SCENE 1 - le depart**
- `SCENE FUNCTION` : transition, mise en mouvement.
- `START STATE` : porte cochere ou trottoir parisien, une femme en tenue d'ete met le sac a
  l'epaule, vue de trois-quarts arriere.
- `HAND LOGIC` : une main passe l'anse sur l'epaule, l'autre reste le long du corps.
- Refs : `HANBAG-COQUILLAGE-REF`, un avatar.

**SCENE 2 - la marche**
- `SCENE FUNCTION` : projection + mouvement naturel.
- `START STATE` : **femme de dos** marchant dans une rue haussmannienne, sac clairement visible,
  lumiere naturelle.
- `ACTION` video : follow shot de dos, oscillation naturelle du sac, inertie de la marche, aucune
  torsion, aucun changement de taille.
- `CONTINUITY FROM` : scene 1. Meme tenue, memes cheveux, meme lumiere.
- Refs : `HANBAG-COQUILLAGE-REF`, un avatar.

**SCENE 3 - hero shot golden hour**
- `SCENE FUNCTION` : money shot, boucle visuelle.
- `START STATE` : le sac tres lisible au premier plan, exterieur parisien en arriere-plan doux,
  golden hour. Produit dominant et stable.
- `PRODUCT LOCK` : la maille grosse, les cotes, la rosace, la corde, les mousquetons dores et les
  perles doivent tous etre lisibles.
- `ACTION` video : micro push-in, eventuellement micro-arc. Le sac ne bouge pas de lui-meme.
- Refs : `HANBAG-COQUILLAGE-REF`.

---

## CONCEPT 3 - Le stand de creatrice (pattern P6)

- `hook_overlay:` **"Fait main. Et pourtant."**
- `caption:` "Il y a des heures de travail la-dedans" / lien en bio
- `hashtags:` #faitmain #crochet #petitecreatrice #artisanat

**SCENE 1 - le stand**
- `SCENE FUNCTION` : hook, densite + artisanat.
- `START STATE` : stand de creatrice ou marche francais, **foule dense de femmes**, le sac
  coquillage blanc presente en nombre. **Aucune nourriture, aucun etal de fruits dans le champ.**
- Refs : `HANBAG-COQUILLAGE-REF`.

**SCENE 2 - la matiere, avec une action**
- `SCENE FUNCTION` : preuve de qualite. **Pas un macro passif** : il faut une action.
- `START STATE` : une main fait tourner lentement le sac pour reveler la **rosace centrale** et
  les **cotes rayonnantes**, lumiere rasante sur la grosse maille.
- `HAND LOGIC` : une main tient l'anse, l'autre soutient le fond du sac.
- `NEGATIVE` : pas de gros plan statique sur les perles seules, il n'apporte rien de neuf.
- Refs : `HANBAG-COQUILLAGE-REF`.

**SCENE 3 - portage**
- `SCENE FUNCTION` : echelle sur corps.
- `START STATE` : le sac porte en bandouliere par la **chaine de perles**, tenue d'ete, terrasse
  ou rue ensoleillee, visage non entier.
- `PRODUCT LOCK` : la chaine de perles est attachee aux mousquetons dores, elle n'apparait ni ne
  disparait.
- `CONTINUITY FROM` : scene 2.
- Refs : `HANBAG-COQUILLAGE-REF`, un avatar.

---

## Avant de lancer une generation

Refuser et corriger le brief si (regle G12) :

- la reference attachee n'est pas `HANBAG-COQUILLAGE-REF` alors que le post porte sur le sac
  coquillage ;
- une scene demande un sac beige, marguerite, a fleur crochet ou a pompon sur un post coquillage ;
- une scene dit "foule" mais decrit deux ou trois personnes ;
- une scene dit "Paris" sans cue visuel parisien ;
- un accessoire propose est plus grand que la cavite du sac ;
- deux mains agissent du meme cote de la meme anse sans necessite ;
- un miroir est present sans reflet garanti coherent ;
- une scene est un macro sans action.

QA start frame et QA video : sections A13 et A14 de `product-breakdowns/SPIRALEDAZUR.md`.

## Note sur le sac Marguerite

Le Marguerite dispose de 51 rushs Unlimited des 10-13/08 sur le Mac de Yann. **Ce stock s'epuise
au montage, pas a la generation.** Un post Marguerite ne se genere que si un brief date le demande
explicitement. Par defaut, ce standing brief produit du **sac coquillage**.
