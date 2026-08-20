# STANDING BRIEF - CARBLAZZ

**Ce fichier ne se perime jamais.** Il sert des qu'aucun `DAILY-BRIEF-{date}-CARBLAZZ.md` n'existe
pour la nuit en cours. Un brief date, quand il existe, prime toujours sur celui-ci.

Ecrit le 2026-08-20, apres constat : trois nuits consecutives terminees en `BLOCKED_NO_BRIEF`
parce que Hermes n'a pas de credential GitHub. Une chaine de production ne doit pas s'arreter
parce qu'un fichier manque.

**A lire avant de generer, dans cet ordre :**
1. `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md`
2. `product-breakdowns/CARBLAZZ.md`
3. `MANIFEST.md`, section `refs/carblazz/`

Rien de ce qui suit ne remplace ces trois fichiers. Le brief ne redit pas les verrous produit :
il choisit le concept du jour et laisse les verrous a leur place.

---

## Cadre fixe

- Marche **FR**. Captions et hooks en **francais**. Lane **KLING**.
- CTA : `Commentez « V12 » pour recevoir les infos`. Guillemets francais. Aucun texte ecrit dans
  l'image, le hook arrive au montage.
- **3 posts par nuit, 3 scenes par post**, un coloris par post, jamais deux horloges dans une
  video.
- Toujours dire **"this clock"** dans les prompts. Jamais un nom de marque, jamais un nom de
  concurrent.
- **3 references maximum** par image. Passe vision obligatoire sur chaque start frame avant
  d'ecrire le prompt video.
- Diametre reel **35-40 cm**, a ecrire en centimetres dans tout prompt qui met l'horloge en
  relation avec un humain, un mur ou un meuble.
- Montage cible 10-13 s. **Aucun visage entier** dans le cadre.

## Rotation deterministe

Soit `D` = jour du mois de la date cible (1-31).

**Coloris du POST 1** = element numero `D mod 5` de cette liste, en partant de 0 :

```
0 -> horloge-carbone
1 -> horloge-compteur
2 -> horloge-metal-noir
3 -> horloge-metal-rouge
4 -> horloge-bois-f1
```

**POST 2** = element suivant dans la liste (`(D+1) mod 5`).
**POST 3** = element suivant encore (`(D+2) mod 5`).

Trois coloris differents chaque nuit, et le cycle ne se repete pas avant cinq jours. C'est ce qui
empeche l'epuisement du produit sur le compte.

**Concept du POST 1** = element numero `D mod 4` de la liste des concepts ci-dessous.
**POST 2** = `(D+1) mod 4`. **POST 3** = `(D+2) mod 4`.

URL brutes des references :
`https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/carblazz/[slug].png`

---

## CONCEPT 0 - Le mur vide (pattern P4, fandom lock)

- `hook_overlay:` **"Les fans de voitures ne marchez pas FONCEZ en Boutique"**
- `caption:` "Le mur qui manquait a la piece. Lien en bio" + `Commentez « V12 » pour recevoir les infos`
- `hashtags:` #passionauto #decoauto #horlogemurale #garage #voiture

**SCENE 1 - le manque**
- `SCENE FUNCTION` : hook, installer le vide avant de le combler.
- `START STATE` : salon ou bureau de passionne, fin de journee, un **grand pan de mur vide** sur
  la droite du cadre. Aucun produit visible.
- `SCALE` : le mur doit offrir au moins 60 cm de largeur libre, pour qu'une horloge de 38 cm y
  tienne sans etre a l'etroit.
- `HAND LOGIC` : aucune main.
- `CAMERA` : hauteur d'oeil, legere plongee, cadrage 9:16.
- `LOCATION SIGNALS` : parquet, moulures ou beton poli, lumiere naturelle rasante, un objet auto
  discret qui installe le monde (casque, maquette, magazine).
- `CONTINUITY FROM` : none. `MUST REMAIN IDENTICAL` : le mur, la lumiere, le mobilier.
- `NEGATIVE` : pas de produit, pas de texte, pas de visage.
- Refs : aucune.

**SCENE 2 - les mains posent**
- `SCENE FUNCTION` : transition d'etat, la preuve que l'objet est reel et lourd.
- `START STATE` : le meme mur, **deux mains tiennent l'horloge contre le mur**, doigts autour de
  la lunette, l'horloge encore au contact des mains, pas encore lachee.
- `PRODUCT LOCK` : le coloris du post, reproduit exactement comme sur la planche.
- `SCALE` : diametre 35-40 cm, environ deux largeurs d'epaule.
- `HAND LOGIC` : **deux mains**, une de chaque cote, poids lisible. Avant-bras et manches
  decontractees uniquement.
- `STATIC ELEMENTS` : toutes les aiguilles immobiles a ce stade.
- `CAMERA` : legerement en contre-plongee, meme piece.
- `CONTINUITY FROM` : scene 1. `MUST REMAIN IDENTICAL` : mur, lumiere, mobilier, heure du jour.
- `MORPHING RISKS` : mains fusionnees, horloge trop petite, horloge deja fixee.
- Refs : le coloris du post.

**SCENE 3 - hero mounted**
- `SCENE FUNCTION` : payoff, le produit installe.
- `START STATE` : l'horloge est au mur, les mains sont sorties du cadre.
- `PRODUCT LOCK` : vitre visible avec un reflet partiel de la fenetre, sauf sur `horloge-bois-f1`
  qui n'a pas de vitre.
- `ACTION` video : micro push-in, la trotteuse fine avance.
- `CONTINUITY FROM` : scene 2. Meme mur, meme lumiere, meme hauteur d'accrochage.
- Refs : le coloris du post.

---

## CONCEPT 1 - Le deballage (pattern P5, send-this-to)

- `hook_overlay:` **"Envoie ca a celui qui offre encore des chaussettes"**
- `caption:` "Un carton. Probleme regle. Lien en bio" + `Commentez « V12 » pour recevoir les infos`
- `hashtags:` #cadeauhomme #decoauto #passionauto #idéecadeau

**SCENE 1 - la boite fermee**
- `SCENE FUNCTION` : curiosite. `START STATE` : le packaging **pose a plat** sur une table en bois,
  lumiere du jour chaude, personne ne le touche encore.
- `PRODUCT LOCK` : **sleeve noir mat 40 x 40 cm, plat (environ 5 cm), grande decoupe circulaire en
  facade, wordmark `blazz` en blanc en bas a gauche.** Ce n'est pas un coffret profond.
- `CAMERA` : trois-quarts, hauteur de table.
- `NEGATIVE` : pas de couvercle articule, pas de boite haute, pas de texte ajoute.
- Refs : `horloge-packaging`.

**SCENE 2 - le tiroir coulisse**
- `SCENE FUNCTION` : preuve produit + reveal.
- `START STATE` : **une main stabilise l'enveloppe, l'autre tire le tiroir interieur
  lateralement.** Le tiroir est sorti d'environ un tiers. Le cadran de l'horloge commence a
  apparaitre a l'interieur.
- `HAND LOGIC` : main gauche a plat sur le sleeve, main droite sur l'encoche du tiroir. Avant-bras
  seulement.
- `NEGATIVE` : **jamais "lift the lid"**, jamais un couvercle souleve, jamais une charniere.
- `MORPHING RISKS` : boite qui devient un coffret, tiroir qui s'ouvre par le haut.
- Refs : `horloge-packaging` + le coloris du post.

**SCENE 3 - tenue en mains, hors de la boite**
- `SCENE FUNCTION` : echelle et matiere.
- `START STATE` : **deux mains** tiennent l'horloge sortie de la boite, legerement inclinee pour
  que le reflet glisse sur la vitre. La boite ouverte reste visible en bas de cadre.
- `SCALE` : diametre 35-40 cm, nettement plus large qu'une tete.
- `STATIC ELEMENTS` : toutes les aiguilles immobiles.
- `CONTINUITY FROM` : scene 2. Meme table, meme lumiere, memes manches.
- Refs : le coloris du post.

---

## CONCEPT 2 - Le garage (pattern P1, contexte aspirationnel)

- `hook_overlay:` **"Le garage etait deja beau. Il manquait ca."**
- `caption:` "Quand le mur du garage raconte la meme histoire que la voiture. Lien en bio"
  + `Commentez « V12 » pour recevoir les infos`
- `hashtags:` #garage #supercar #decoauto #passionauto #horlogemurale

**SCENE 1 - le monde**
- `SCENE FUNCTION` : scroll stopper aspirationnel.
- `START STATE` : garage de passionne, beton poli, lignes LED credibles, etabli, rangements, une
  **belle voiture de sport** en arriere-plan legerement floue, un mur libre au premier plan.
- `LOCATION SIGNALS` : vrai espace habite, pas un showroom irrealiste, pas de fond noir publicitaire.
- `NEGATIVE` : la voiture ne doit pas devenir le sujet. Plaque francaise si elle est lisible.
- Refs : aucune.

**SCENE 2 - le produit dans le monde**
- `SCENE FUNCTION` : le produit prend sa place.
- `START STATE` : le meme mur, **deux mains ajustent l'horloge** deja presque en place, petite
  correction d'alignement.
- `SCALE` : comparer visuellement au diametre d'une roue de la voiture au fond : l'horloge fait
  environ la moitie.
- `CONTINUITY FROM` : scene 1. **Meme voiture, meme couleur, memes jantes, meme plaque, meme garage.**
- Refs : le coloris du post.

**SCENE 3 - macro material proof**
- `SCENE FUNCTION` : preuve de matiere.
- `START STATE` : macro sur le cadran. Selon le coloris : le **tissage carbone** et l'**etrier
  jaune** pour `carbone`, `metal-noir`, `metal-rouge` ; le wordmark `NISMO`, les fenetres `170884`
  et `1984` et les points orange pour `compteur` ; la livree F1 et le moyeu dore pour `bois-f1`.
- `PRODUCT LOCK` : chiffres et graduations compares un a un a la planche.
- `ACTION` video : derive laterale minuscule, la lumiere revele la matiere. Rien d'autre ne bouge.
- Refs : le coloris du post.

---

## CONCEPT 3 - L'appartement haussmannien (pattern P6, emotion)

- `hook_overlay:` **"Ma copine a dit non. Puis elle l'a accroche elle-meme."**
- `caption:` "Meme dans un salon classique, ca passe. Lien en bio"
  + `Commentez « V12 » pour recevoir les infos`
- `hashtags:` #decoration #interieur #decoauto #haussmannien #horlogemurale

**SCENE 1 - le salon**
- `START STATE` : appartement haussmannien parisien, moulures, parquet point de Hongrie, cheminee
  marbre, grande fenetre, garde-corps en fer forge, lumiere naturelle de fin de journee. Mur libre
  au-dessus de la cheminee.
- `SCENE FUNCTION` : contraste, installer un decor ou personne n'attend ce produit.
- Refs : aucune.

**SCENE 2 - la pose**
- `START STATE` : **deux mains** posent l'horloge au-dessus de la cheminee, encore au contact.
- `HAND LOGIC` : deux mains, doigts autour de la lunette, poids lisible.
- `SCALE` : l'horloge fait environ un tiers de la largeur du manteau de cheminee.
- `CONTINUITY FROM` : scene 1.
- Refs : le coloris du post.

**SCENE 3 - payoff large**
- `START STATE` : plan plus large du salon, l'horloge en place, la lumiere de fin de journee
  traverse la piece, reflet partiel sur la vitre (sauf `bois-f1`).
- `SCENE FUNCTION` : environmental payoff.
- `ACTION` video : leger push-in handheld, la trotteuse avance.
- `CONTINUITY FROM` : scene 2.
- Refs : le coloris du post.

---

## Avant de lancer une generation

Refuser et corriger le brief si l'un de ces points est vrai (regle G12) :

- le coloris choisi n'est pas celui de la rotation du jour ;
- l'echelle n'est pas ecrite en centimetres dans la scene ;
- une scene fait passer l'horloge de la boite au mur sans plan de pose ;
- une scene demande de soulever un couvercle ;
- une vitre est demandee sur `horloge-bois-f1`, ou du bois est demande n'importe ou ;
- une aiguille autre que la trotteuse doit bouger.

QA start frame et QA video : sections 12 et 13 de `product-breakdowns/CARBLAZZ.md`.
