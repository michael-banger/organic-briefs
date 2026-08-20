# DAILY BRIEF - SPIRALEDAZUR - publication 2026-08-21

**Rattrapage.** Le brief du 18/08 etait un brief de montage sur stock, sans generation, et il n'y
a rien eu les 19 et 20/08. Ce brief relance la generation sur le **sac coquillage**, produit de
tete de la marque.

Lecture obligatoire avant de generer :
1. `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md`
2. `product-breakdowns/SPIRALEDAZUR.md` (revision du 2026-08-20)
3. `MANIFEST.md`, section `refs/spiraledazur/`

- Marche **FR**. Lane **KLING**. 3 posts, 3 scenes chacun.
- **Produit : sac coquillage.** Reference unique et obligatoire : `HANBAG-COQUILLAGE-REF`, traitee
  comme **identity and geometry source**. Aucun autre sac de la marque n'apparait.
- "this bag" dans les prompts. Jamais de nom de marque.
- **Aucun CTA a mot-cle.** Lien en bio uniquement. Le prix 39,99 EUR n'apparait pas dans les start
  frames, c'est un plan de montage d'une seconde en fin de sequence.
- Tenue d'ete obligatoire, aucun fragment de vetement d'hiver. Aucun visage entier.
- 3 references maximum. Passe vision obligatoire avant le prompt video.
- Les 3 posts couvrent les 3 chaines de continuite validees de la Video 1 : boutique,
  appartement, exterieur. C'est le squelette approuve par Yann, decline sur de nouveaux plans.

## References

| Slug | URL brute |
|---|---|
| `HANBAG-COQUILLAGE-REF` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/spiraledazur/HANBAG-COQUILLAGE-REF.png |
| `MONOPRIX-RAYON` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/spiraledazur/MONOPRIX-RAYON.png |
| `MEUF-HANDBAG-V2` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/spiraledazur/MEUF-HANDBAG-V2.png |

---

## POST 1 - La ruee en boutique - pattern P4

- `lane: KLING` · `post_id: 1` · `pattern: P4`
- `hook_overlay:` **"J'ai cru que c'etait une boutique de creatrice"**
- `caption:` "Vous l'auriez pris quelle couleur ? Lien en bio" · `hashtags:` #sacencrochet #crochet #faitmain #shopping

**SCENE 1 - le rayon**
- `SCENE FUNCTION` : scroll stopper + preuve sociale.
- `START STATE` : rayon de grande surface francaise, **rempli uniquement du sac coquillage blanc**,
  plusieurs exemplaires identiques alignes. **Foule dense de femmes en tenue d'ete** devant le
  rayon, mouvement de magasin reel.
- `CROWD` : `large dense crowd of many women`. Deux ou trois personnes est un FAIL.
- `LOCATION SIGNALS` : doit se lire comme un Monoprix, une Galeries Lafayette, un Zara ou un H&M.
  Jamais un entrepot generique. **Aucune nourriture, aucun etal de fruits dans le champ.**
- `HAND LOGIC` : aucune main au premier plan.
- `CAMERA` : hauteur d'oeil, cadrage 9:16.
- `PRODUCT LOCK` : blanc pur, grosse maille, forme nautile compacte, cotes rayonnantes, rosace
  centrale, anse en corde blanche, mousquetons dores, chaine de perles.
- `MORPHING RISKS` : foule anatomiquement cassee au fond, sacs differents melanges sur le rayon,
  maille qui devient du tissu lisse.
- `CONTINUITY FROM` : none.
- Refs : `HANBAG-COQUILLAGE-REF`, `MONOPRIX-RAYON`.

**SCENE 2 - la prise**
- `SCENE FUNCTION` : interaction + desirabilite.
- `START STATE` : meme rayon, **une seule main attrape un sac** par l'anse en corde. **Aucune
  etiquette de prix visible** nulle part dans le cadre.
- `HAND LOGIC` : une main, qui saisit l'anse. Le sac ne se deforme pas sous la prise, il garde sa
  silhouette compacte.
- `STATIC ELEMENTS` : les autres sacs du rayon restent en place.
- `CONTINUITY FROM` : 1. `MUST REMAIN IDENTICAL` : rayon, lumiere, foule au fond, manucure, manche.
- Refs : `HANBAG-COQUILLAGE-REF`, `MONOPRIX-RAYON`.

**SCENE 3 - la sortie**
- `SCENE FUNCTION` : echelle sur corps + styling.
- `START STATE` : une femme quitte l'univers boutique, **sac porte a l'epaule par l'anse en
  corde**, tenue d'ete, vue de trois-quarts arriere, visage non entier.
- `SCALE` : le sac reste compact contre le corps, jamais allonge pour remplir le cadre.
- `ACTION` video : trailing handheld follow, leger balancement du sac, inertie de la marche,
  aucune deformation de la coquille, aucune torsion.
- `CONTINUITY FROM` : 2. Meme femme, meme tenue, memes cheveux.
- Refs : `HANBAG-COQUILLAGE-REF`, `MEUF-HANDBAG-V2`.

---

## POST 2 - La preparation parisienne - pattern P1

- `lane: KLING` · `post_id: 2` · `pattern: P1`
- `hook_overlay:` **"Arrete, personne va acheter ca"**  (hook objection, seul gagnant enregistre
  du compte, a decliner et jamais a remplacer)
- `caption:` "Soyez honnetes, vous l'achèteriez ? Lien en bio" · `hashtags:` #faitmain #crochet #petitecreatrice #sacencrochet

**SCENE 1 - la chambre parisienne**
- `SCENE FUNCTION` : projection lifestyle.
- `START STATE` : chambre elegante mais vecue, **le sac pose sur le lit**, ombre de contact
  visible sous le sac, une femme en tenue d'ete a proximite, visage non entier.
- `LOCATION SIGNALS` : **fenetre haute, garde-corps en fer forge, immeubles haussmanniens visibles
  dehors**, moulures au plafond, textiles clairs, lumiere naturelle laterale. Un decor beige
  generique est un FAIL.
- `NEGATIVE` : **pas de miroir.** S'il en fallait un et que son reflet n'est pas rigoureusement
  coherent, on le retire, il n'est jamais indispensable.
- `CONTINUITY FROM` : none.
- Refs : `HANBAG-COQUILLAGE-REF`, `MEUF-HANDBAG-V2`.

**SCENE 2 - le packing**
- `SCENE FUNCTION` : preuve d'usage et de capacite.
- `START STATE` : le sac deja bien positionne sur le lit, **ouverture lisible**, doublure creme
  visible. **Une** main descend un **petit objet cosmetique ferme** dans l'ouverture. Le sac reste
  l'element dominant de l'image.
- `HAND LOGIC` : main droite qui descend l'objet, main gauche qui stabilise le cote oppose du sac.
  Jamais deux mains du meme cote.
- `ACCESSORY` : petit objet feminin du quotidien, reconnaissable, **qui entre physiquement** dans
  le sac. **Jamais un telephone** : il domine le plan et vole le produit.
- `STATIC ELEMENTS` : tout le reste immobile, y compris le lit et les textiles.
- `CONTINUITY FROM` : 1. Meme lit, meme lumiere, meme manucure, meme tenue.
- Refs : `HANBAG-COQUILLAGE-REF`.

**SCENE 3 - what's in my bag**
- `SCENE FUNCTION` : capacite + curiosite.
- `START STATE` : vue haute legerement plongeante, le sac au centre, **plusieurs petits objets
  feminins disposes autour**, tous compatibles avec son volume apparent.
- `CAMERA` : camera haute tres legerement flottante.
- `ACTION` video : un seul objet manipule a la fois, le reste du flat lay reste strictement
  statique.
- `CONTINUITY FROM` : 2.
- Refs : `HANBAG-COQUILLAGE-REF`.

---

## POST 3 - La rue haussmannienne - pattern P5

- `lane: KLING` · `post_id: 3` · `pattern: P5`
- `hook_overlay:` **"Envoie ca a celle qui cherche un sac depuis 3 mois"**
- `caption:` "Elle va le reconnaitre tout de suite. Lien en bio" · `hashtags:` #paris #sacencrochet #modeete #faitmain

**SCENE 1 - le depart**
- `SCENE FUNCTION` : transition, mise en mouvement.
- `START STATE` : trottoir parisien devant une porte cochere, une femme en tenue d'ete **passe
  l'anse sur son epaule**, vue de trois-quarts arriere.
- `HAND LOGIC` : une main passe l'anse, l'autre reste le long du corps.
- `LOCATION SIGNALS` : facade haussmannienne, porte cochere, trottoir parisien.
- `CONTINUITY FROM` : none.
- Refs : `HANBAG-COQUILLAGE-REF`, `MEUF-HANDBAG-V2`.

**SCENE 2 - la marche**
- `SCENE FUNCTION` : projection + mouvement naturel.
- `START STATE` : **femme de dos** marchant dans une rue haussmannienne, sac clairement visible et
  lisible, lumiere naturelle de fin d'apres-midi.
- `ACTION` video : follow shot de dos, oscillation naturelle du sac, inertie de la marche. Aucune
  torsion, aucun changement de taille, aucune deformation de la coquille.
- `CONTINUITY FROM` : 1. Meme femme, meme tenue, memes cheveux, meme lumiere.
- Refs : `HANBAG-COQUILLAGE-REF`, `MEUF-HANDBAG-V2`.

**SCENE 3 - hero shot golden hour**
- `SCENE FUNCTION` : money shot, boucle visuelle.
- `START STATE` : le sac tres lisible au premier plan, exterieur parisien doux en arriere-plan,
  golden hour. Produit dominant et stable.
- `PRODUCT LOCK` : la grosse maille, les cotes rayonnantes, la rosace centrale, la corde de
  l'anse, les mousquetons dores et la chaine de perles doivent tous etre lisibles dans ce plan.
- `ACTION` video : micro push-in, eventuellement micro-arc. Le sac ne bouge pas de lui-meme, ne
  glisse pas, ne flotte pas.
- `CONTINUITY FROM` : 2.
- Refs : `HANBAG-COQUILLAGE-REF`.

---

## Controle avant de marquer pret

Gates : sections A13 et A14 de `product-breakdowns/SPIRALEDAZUR.md`. Tout echec produit, physique
ou anatomique = regenerer, jamais "ca passe au montage".
