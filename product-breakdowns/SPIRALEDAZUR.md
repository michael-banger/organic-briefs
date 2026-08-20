# Product breakdown - @spiraledazur

> Revision du 2026-08-20. Integre les learnings de la session de production du sac coquillage
> validee par Yann : les 8 start frames de la Video 1 ont ete validees une par une, apres une
> boucle de regenerations dont chaque cause est desormais une regle ci-dessous.
>
> Ce fichier s'ajoute a `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md`, qui porte les
> regles valables pour toutes les marques. Sur un point specifique au produit, ce fichier prime.

- **Marche** : FR, francais parle naturel.
- **Orthographe de la marque** : **Spiraledazur**. Jamais "Spiradazur". Toutes les generations
  anterieures au 14/08 portent la faute.
- **Statut** : actif, priorite 1. Seul compte du portefeuille avec un post gagnant enregistre.
- **Prix affiche en video** : **39,99 EUR**, un plan d'une seconde en fin de sequence, jamais en
  ouverture.

## Deux produits, deux jeux de regles qui ne se melangent jamais

| Produit | Reference canonique | Statut |
|---|---|---|
| **Sac coquillage** | `HANBAG-COQUILLAGE-REF.png` | **produit de tete**, sequence 8 scenes validee |
| **Sac Marguerite** | `FOUR-TOUT-BAG.png` + la planche du coloris | actif, 5 coloris |
| Sac cowgirl | `SAC-COWGIRL-REF1/2.png` | en pause |

La marque contient plusieurs produits. **Les regles produit ne se transposent jamais de l'un a
l'autre.** Pour une video sur un sac donne, c'est la reference de CE sac qui est source de verite,
et elle seule.

---

# A. SAC COQUILLAGE, produit de tete

## A1. Identite produit, verrouillee

`HANBAG-COQUILLAGE-REF.png` est la **seule** reference valable. `SHELL-BLOOM.png` a ete archive :
c'etait un autre sac, utilise par erreur dans le brief du 17/08.

Ce que montre la planche, verifie le 2026-08-20 :

- **grosse maille crochet, blanc pur** (pas du fil fin, pas de beige) ;
- forme de **coquillage nautile**, volume **compact** ;
- **cotes rayonnantes** qui partent du centre vers le bord ;
- **rosace en spirale** crochetee au centre de chaque face ;
- **anse superieure en corde blanche epaisse et ronde** ;
- **mousquetons dores** de chaque cote de l'anse ;
- **chaine de perles nacrees amovible**, portee en bandouliere ;
- **doublure creme** visible a l'ouverture.

**Ce sac n'a ni fleur crochet, ni pompon**, contrairement au Marguerite.

### Substitutions interdites

Jamais un autre sac crochet, jamais un sac beige, jamais un sac marguerite, jamais un sac a fleur
crochet coloree, jamais un modele avec pompon, jamais une variante "qui y ressemble".

Le prompt doit dire que la reference est une **identity and geometry source**, pas une inspiration
stylistique. Une generation qui reproduit le bon genre de sac mais reconstruit la geometrie est un
**FAIL**.

Le sac ne change pas de silhouette parce qu'une personne le porte, qu'une main le tient, qu'il est
ouvert, qu'un objet y entre, que la camera change d'angle ou qu'on passe d'un interieur a un
exterieur.

## A2. Echelle et proportions

La dimension exacte en centimetres n'a pas ete etablie. **Ne pas en inventer une.** Ce sont les
rapports relatifs qui sont verrouilles :

- largeur et hauteur relatives constantes, aspect **compact** conserve ;
- epaisseur conservee, vraie ouverture conservee ;
- credible contre un corps humain ;
- credible par rapport a un iPhone, un rouge a levres, des lunettes, des cles, des AirPods,
  un portefeuille.

**Capacite** : tout objet mis en scene doit etre compatible avec le volume apparent. Un objet ne
doit jamais sembler plus grand que la cavite, forcer l'ouverture, deformer la geometrie, ni rendre
le produit secondaire dans l'image.

**Stories et encarts** : le produit ne se conforme jamais au cadre, **le cadre se conforme au
produit**. Si l'arche ou l'encart bas-droite est trop haut : reduire l'arche, ou reduire la taille
d'affichage du produit, ou laisser plus d'air blanc. **Jamais etirer ou allonger le sac** pour
remplir la forme.

## A3. Matieres et signaux de realisme

Doit se lire : vrai crochet textile, fibres avec volume, cotes physiquement construites, rosace
tressee credible, vraie corde tressee sur l'anse, vrais elements metalliques dores, vraies perles
nacrees, ombres de contact, poids reel.

Ne doit jamais ressembler a : du plastique, du CGI, un objet gonfle, une image plate collee dans la
scene, un motif crochet imprime sur une surface, une forme fondue "AI smooth".

## A4. Mains et interaction physique

C'est le learning le plus couteux de la session. Une generation avec **deux mains mal disposees du
meme cote de l'anse** a ete rejetee : le probleme n'etait pas esthetique, cette mauvaise
interaction avait aussi fait **reconstruire le sac de travers**.

Chaque main a une fonction physique claire. Valide :

- une main tient l'anse ;
- une main stabilise le corps du sac pendant que l'autre insere un objet ;
- une main attrape le sac depuis un rayon ;
- une seule main entre dans le cadre pour prendre un objet dans un flat lay.

Interdit : deux mains tirant la meme zone du meme cote, mains flottantes, doigts fusionnes, main
traversant une sangle, main masquant l'element produit principal, poignet impossible, main qui
deforme le sac pour accomplir l'action.

**Scene de packing** : le sac est deja correctement positionne, son ouverture est lisible, **une**
main realise l'action, et si une seconde main est necessaire elle stabilise clairement le cote
oppose.

## A5. Sequence validee, Video 1

Les 8 start frames ci-dessous ont ete **validees une par une par Yann**. C'est le squelette de
reference a decliner, pas a rejouer a l'identique.

| # | Scene | Fonction |
|---|---|---|
| 1 | Boutique dense, rayon rempli **uniquement** du sac coquillage blanc | scroll stopper + preuve sociale |
| 2 | Une main prend le sac dans le meme univers boutique, **aucun prix visible** | interaction + desirabilite |
| 3 | Appartement parisien clairement identifiable, sac sur le lit, preparation | projection lifestyle |
| 4 | Petit objet cosmetique **ferme** range dans le sac, produit dominant | preuve d'usage |
| 5 | Vue haute "what's in my bag", plusieurs petits objets feminins autour du sac | capacite + curiosite |
| 6 | Femme quittant l'univers boutique, sac porte | echelle sur corps + styling |
| 7 | Femme de dos marchant dans une rue haussmannienne | projection + mouvement |
| 8 | Hero shot produit en exterieur parisien, golden hour | money shot |

Chaines de continuite naturelles : **1 -> 2** (boutique), **3 -> 4 -> 5** (appartement),
**6 -> 7 -> 8** (exterieur). Un hard cut vers un nouveau setup n'a pas d'ancre de continuite.

**A ne pas surinterpreter** : les start frames de la Video 2 n'ont pas recu la meme validation
scene par scene, et les rendus video Kling n'ont pas eu de revue finale detaillee. Les mouvements
listes plus bas sont des principes approuves, pas une preuve que chaque rendu a passe une QA.

## A6. Scenes utilisables seulement avec justification

- **Macro crochet** : la premiere version de la scene 3 a ete rejetee parce qu'"il s'y passe
  rien". Un macro passif ne merite pas une scene. Il lui faut une preuve de qualite, une action,
  un reveal, une transition ou une information nouvelle.
- **Gros plan perles / mousquetons** : meme logique. Le detail est joli mais il ne doit pas
  remplacer une scene plus utile comme le "what's in my bag".

## A7. Lieux

**Boutique** : magasin francais ou europeen credible, rayon sacs, **forte densite humaine**,
femmes en tenues d'ete, esthetique retail reelle, produit immediatement visible. Le rayon montre
**uniquement le modele coquillage blanc concerne**, pas un patchwork de sacs crochet differents.
Reference retail : `MONOPRIX-RAYON.png`. Doit se lire comme un Monoprix, une Galeries Lafayette,
un Zara ou un H&M, jamais comme un entrepot generique.

**Foule = foule.** "large dense crowd of many women", pas deux ou trois personnes, sinon l'effet
de ruee ne se lit pas. Reference de cadence et de densite verrouillee : le reel `Db1EvUxRzpo`,
278 K vues, meilleur post du compte.

**Appartement parisien** : il doit etre **immediatement lisible comme parisien**. Cues qui ont
fonctionne : fenetre haute, garde-corps en fer forge, immeubles haussmanniens visibles dehors,
lumiere naturelle, textiles clairs, chambre elegante mais vecue. Un decor beige generique ne
suffit pas.

**Rue haussmannienne** : architecture lisible, femme de dos, sac clairement visible, lumiere
naturelle, golden hour possible pour un hero shot.

**Terrasse parisienne** : concept valide en direction creative, pas encore valide en rendu.

**Stories** : sud de la France, ambiance mediterraneenne, beach club, Paris, lifestyle feminin,
femme de dos, tenue d'ete, atmosphere premium mais naturelle. Ce sont des **options de contexte**,
pas des obligations pour chaque post.

Deux verrous de decor deja acquis :
- **Aucune nourriture pres d'un stand de sacs.** Pas de fruits, pas d'etal alimentaire dans le champ.
- Son de fond : murmure indistinct **ou** francais clair et pertinent. Jamais une langue confuse.

## A8. Avatar et tenue

Sans reference d'avatar fournie : belle femme brune, chataine ou blonde, **tenue d'ete assortie
au sac**. **Aucun fragment de vetement d'hiver visible**, meme partiel, quel que soit l'avatar de
depart. Planches disponibles selon le role : `HANDBAG-AVATARS-REF.png`, `MEUF-HANDBAG-V2.png`,
`GRANDMA-HANDBAG-V2.png`.

## A9. Accessoires du "what's in my bag"

Le learning generique : **un petit objet feminin du quotidien, reconnaissable, qui entre
physiquement dans le sac et ne l'occulte pas.**

Le rouge a levres Chanel ferme d'une iteration precedente est un **choix ponctuel**, pas une
obligation de marque. Un telephone qui domine le plan est le contre-exemple a ne jamais
reproduire : **l'accessoire est subordonne au produit**.

## A10. Format des assets

**Une image autonome verticale 9:16 par scene.** Pas de collage, pas de grille, pas de contact
sheet comme input d'animation. Un storyboard de planification peut exister en amont, il ne
remplace jamais `IMG-SCENE[N]`.

Look : iPhone 17 Pro Max, photorealiste, net, detail eleve, lumiere naturelle, HDR naturel, faible
profondeur de champ **seulement quand elle est physiquement plausible**, micro-imperfections de
prise smartphone acceptables, social-native.

Image propre : aucun hook imprime, aucun texte, aucun sous-titre, aucun watermark, aucun logo
ajoute, aucun visage entier clairement expose dans la logique validee de cette video. Les hooks et
captions arrivent au montage.

## A11. Continuite

Ne pas ecrire "same style as previous image". Ecrire ce qui doit rester identique : identite
produit, dimensions produit, etat du produit, identite de la femme si recurrente, tenue, cheveux,
mains, manucure, lieu, heure de la journee, direction de la lumiere, props proches, langage camera.

Chaque scene porte deux champs explicites :

```
CONTINUITY FROM: [numero de scene | none]
MUST REMAIN IDENTICAL: [...]
```

## A12. Prompt video

Le produit n'est jamais anime comme un objet autonome. Pour un reveal ou un beauty shot :
**produit stable + mouvement camera**, jamais un sac qui glisse, avance, flotte ou se teleporte.

- **Sac pose** sur une table, un lit, un rayon : il reste mecaniquement en contact avec la
  surface. Il ne change pas de volume, ne respire pas, ne glisse pas, ne tourne pas sans
  interaction, ne s'ouvre pas seul.
- **Sac porte** : legere oscillation, inertie de la marche, mouvement naturel de l'anse, leger
  balancement. Pas de bouncing excessif, pas de torsion, pas de changement de taille, pas de
  deformation de la coquille.
- **Packing** : les objets non manipules restent statiques. Un seul objet bouge a la fois.

Mouvements valides par scene :

| Scene | Mouvement |
|---|---|
| Crowd hook | forward drift, legere derive laterale, mouvement naturel de foule, rapide mais fluide |
| Pickup | la main prend ou tire legerement le sac, petit push camera, arriere-plan vivant mais secondaire |
| Appartement | micro push-in, main qui approche ou souleve legerement, mouvements textiles minimes |
| Packing | l'objet descend proprement dans l'ouverture, main de support si necessaire, camera tres stable |
| What's in my bag | camera haute tres legerement flottante, un seul objet manipule, le reste du flat lay statique |
| Porte / sortie | trailing handheld follow, marche naturelle |
| Rue | follow shot de dos, mouvement organique du corps et du sac |
| Hero shot | micro push-in, eventuellement micro-arc, produit dominant et stable |

Principe transversal : **controlled handheld**. Ni trepied publicitaire parfait, ni shaky-cam.

### NO-GO video

Sac qui change de geometrie ou s'allonge, rosace qui derive, cotes qui bougent ou fondent, crochet
qui devient une autre texture, chaine de perles qui apparait ou disparait sans cause, metal qui
change, sac qui flotte ou glisse seul, objet qui traverse le sac, mains qui fusionnent, objet qui
se teleporte, telephone ou accessoire qui devient dominant, arriere-plan qui change dans un plan
continu, vetements qui changent en continuite, reflet ou miroir qui cree une seconde realite
incoherente, mouvement cinema spectaculaire qui detruit le style smartphone, foule anatomiquement
cassee, texte ou logo ajoute, moteur qui reconstruit un autre modele de sac.

**Miroirs** : si le miroir ne peut pas etre genere avec un reflet rigoureusement coherent,
**on retire le miroir**. Il n'est jamais indispensable.

## A13. QA start frame

```
IDENTITE
[ ] bonne reference produit, bon modele, pas un autre sac Spiraledazur
[ ] blanc pur, silhouette nautile, compacite, epaisseur
[ ] cotes rayonnantes correctes, rosace centrale correcte
[ ] anse corde blanche, mousquetons dores, chaine de perles
[ ] aucun detail invente, ni fleur ni pompon

ECHELLE
[ ] credible par rapport au corps et aux mains
[ ] accessoires compatibles avec le volume
[ ] aucun etirement pour remplir le cadre

PHYSIQUE
[ ] mains anatomiquement credibles, chaque main a une fonction
[ ] aucun conflit main / anse, aucun objet fusionne
[ ] sac pose sur une vraie surface avec ombre de contact
[ ] frame exploitable sans morphing evident

COMPOSITION
[ ] produit suffisamment visible, aucun accessoire dominant
[ ] action future lisible, une seule fonction de scene claire

LIEU
[ ] Paris reconnaissable quand Paris est demande
[ ] boutique reconnaissable quand retail est demande
[ ] foule reellement dense quand crowd est demande

FORMAT
[ ] 9:16, une seule frame autonome, pas de collage
[ ] aucun texte, watermark ou logo
[ ] pas de visage entier quand la video impose cette regle
```

Stories, en plus : encart adapte au sac et jamais l'inverse, produit desirable mais fidele,
realisme humain credible, image orientee conversion sans devenir une publicite studio.

## A14. QA video

```
[ ] meme sac a la premiere et a la derniere frame
[ ] proportions, crochet, rosace, anse, perles, hardware stables
[ ] camera fluide, micro-mouvement smartphone naturel
[ ] produit statique quand aucune force ne l'anime, sway realiste quand il est porte
[ ] anatomie des mains stable, aucun doigt supplementaire, geste realisable
[ ] un seul objet manipule, objets secondaires en place, rien ne traverse le sac
[ ] meme femme, meme tenue, memes cheveux, meme environnement, meme direction de lumiere
[ ] iPhone-like, net, HDR naturel, pas de bokeh publicitaire, pas de grade cinema
[ ] premiere seconde comprehensible
```

Tout echec produit, physique ou anatomique = **regenerer**, jamais "ca passe au montage".

---

# B. SAC MARGUERITE

Sac en crochet fait main, maille visible, **fleurs marguerite crochetees en relief** sur le corps,
anses souples, breloque fleur et pompon. La maille irreguliere est un argument, pas un defaut.
Geometrie figee par `FOUR-TOUT-BAG.png`.

**Verrou de reference** : toujours attacher **les deux**, `FOUR-TOUT-BAG.png` pour la geometrie
**et** la planche du coloris exact. Jamais l'une sans l'autre.

| Slug | Notes |
|---|---|
| `MARGUERITE-BLANC` | **Base crochet beige/tan avec fleurs blanches.** Ce n'est PAS un sac blanc uni. Ne jamais rejeter ni relancer une generation "Blanc" pour manque de blanc pur. Quatre relances ont deja ete gaspillees la-dessus le 14/08. |
| `MARGUERITE-BLEU-MARINE` | - |
| `MARGUERITE-JAUNE` | - |
| `MARGUERITE-VERT` | vert sauge |
| `MARGUERITE-VIOLET` | - |

Un coloris par video. Ce qui ne doit jamais deriver : la maille crochet (elle glisse facilement
vers du tissu lisse ou du tricot), les fleurs en relief, la breloque, le pompon, les anses
intactes et attachees.

Les regles A2 a A14 s'appliquent au Marguerite en substituant son identite produit. Les elements
propres au coquillage (rosace, cotes rayonnantes, corde, perles) n'existent pas sur ce modele.

---

# C. Marque, hooks et conversion

Le **hook objection**, "Arrete, personne va acheter ca", est le seul gagnant enregistre du compte.
Il se decline sur de nouveaux decors et de nouveaux coloris, il ne se remplace pas.

Patterns prioritaires : **P4** (fandom esthetique), **P1** (contexte aspirationnel),
**P5** (send-this-to), **P6** (emotion, fait-main).

## Le probleme de conversion, a traiter dans chaque brief

Environ 320 K vues cumulees, **zero vente**, back-end sain. Trois leviers, dans l'ordre :

1. **Le CTA a mot-cle est supprime** tant qu'aucun auto-DM ne tourne. "Commentez Soleil" promet
   une reponse que personne n'envoie. Cause numero 1.
2. **Le prix apparait une fois par video**, un plan d'une seconde en fin de sequence, jamais en
   ouverture. 39,99 EUR sur un sac fait main est un argument.
3. **Le lien bio doit pointer sur la fiche produit**, pas sur l'accueil de la boutique.

## Stock existant

51 rushs Unlimited du 10 au 13/08, 720x1280, audio aac, sur le Mac dans
`~/Desktop/FOUR TOUT HANDBAG RUSHS/`. Concerne le **Marguerite**. Epuiser ce stock avant toute
nouvelle generation Marguerite. Ces rushs passent le gate avec `--legacy-res`, et eux seuls.
Le sac coquillage n'a pas de stock : il se genere.
