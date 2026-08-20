# Product breakdown - @onsimplifie

> Revision du 2026-08-20. Remis dans le perimetre de production a la demande de Yann. La
> description du plateau a ete reverifiee contre la planche : le compte de trous annonce
> precedemment (6) ne correspond pas a ce que montre la reference.
>
> Ce fichier s'ajoute a `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md`, qui porte les
> regles valables pour toutes les marques. Sur un point specifique au produit, ce fichier prime.

- **Marche** : FR.
- **Produit** : table / douche portable pour chien, sur pieds pliants.
- **Statut** : **actif**, dans le perimetre de production depuis le 2026-08-20.
- **CTA** : CTA bio. Pas de CTA a mot-cle tant qu'aucun auto-DM ne tourne.

---

## 1. Ce que le produit est, physiquement

Un support de lavage pliable, verifie contre `ons-pr-douchechien-gray.png` :

- **Pietement tubulaire metallique blanc en X**, pliant, embouts caoutchouc noirs, entretoise
  laterale de blocage visible sur les vues de cote.
- **Plateau en toile a maille tendue**, legerement concave, tendu entre deux barres tubulaires
  aux extremites, comme une assise de tabouret de camping.
- Le plateau est perce de **trous ovales de tailles differentes, disposition asymetrique**
  (la planche en montre huit, pas six : **compter sur la planche avant d'ecrire un nombre dans
  un prompt**). Le **passepoil de chaque trou est de la meme couleur que la toile**, surpiqure
  visible en macro.
- L'eau s'ecoule a travers la maille. Le chien se tient **debout sur le plateau**, pas dedans.

Trois coloris, une planche 7 vues chacun : `ons-pr-douchechien-gray`, `ons-pr-douchechien-blue`,
`ons-pr-douchechien-pink`. **Un coloris par video, jamais deux.**

## 2. Echelle : le point le plus risque de cette marque

La dimension exacte n'est pas etablie, **ne pas en inventer une**. Mais la planche est sans
ambiguite sur les **rapports** : c'est un objet de la taille d'un **tabouret de camping**, plateau
d'environ une longueur de bras, hauteur mi-mollet a genou d'adulte.

Consequence directe, a verifier dans chaque brief :

- Un **golden retriever adulte** (`ons-prop-chien-golden`) est **a la limite** de ce que le
  plateau peut porter de facon credible. Si le plan doit se lire physiquement juste, preferer le
  **petit chien** (`ons-prop-chien-petit`), ou cadrer le golden de facon a ce que ses quatre pattes
  soient visiblement posees et le plateau visiblement adapte.
- Ne jamais agrandir le produit pour faire tenir un gros chien. **On change de chien ou de
  cadrage**, jamais l'echelle du produit (regle G2).
- Un chien qui semble flotter au-dessus du plateau, ou dont les pattes le traversent, est un FAIL.

## 3. Ce qui ne doit jamais deriver

- Les **trous ovales** et leur passepoil assorti a la toile.
- Les **pieds pliants metalliques blancs en X**. Ce n'est ni une baignoire, ni un tapis, ni un bac,
  ni une table pleine.
- La **toile a maille**, pas du plastique rigide, pas du tissu lisse.
- Le chien **debout sur** le plateau.

## 4. Verrou de comportement du chien, non negociable

Le chien est **reticent avant** d'etre sur la table de lavage : il se debat, il recule, il fait la
tete. **Des qu'il est sur la table**, il est heureux, detendu, la queue remue. Jamais l'inverse,
quel que soit l'avatar ou le decor. C'est ce qui donne l'arc probleme -> soulagement.

## 5. Mains et interaction physique

- Une main tient le chien ou le stabilise, l'autre agit (douchette, savon, brosse). Chaque main a
  une fonction (regle G3).
- Le contact main / chien doit etre visible et doux : pas de main flottante au-dessus de l'animal.
- Le produit ne se deforme pas sous la main. La toile peut se tendre legerement, le pietement ne
  plie pas.

## 6. Continuite d'etat

Pas de teleportation : le chien ne passe pas **du sol au plateau** sans un plan de transition, et
il ne passe pas de **sec a mouille** sans le plan qui le mouille. Sequence naturelle :

```
CHIEN RETICENT AU SOL  ->  POSE SUR LE PLATEAU (mains visibles)  ->  LAVAGE, CHIEN DETENDU
->  PREUVE : L'EAU S'ECOULE PAR LA MAILLE  ->  PAYOFF : CHIEN SEC ET HEUREUX
```

`ons-prop-chien-golden` fournit le chien mouille **et** sec, quatre angles : utiliser la bonne
version selon le moment de la sequence.

## 7. Packaging

**Aucun packaging Onsimplifie n'a ete valide.** Ne pas en inventer : ni boite, ni sachet, ni
notice, ni logo. Aucune scene d'unboxing tant qu'une planche de packaging n'existe pas
(regle G5). Ne pas importer la mecanique du packaging Carblazz.

## 8. Decor et avatar

`ons-lieu-sdb` : une vraie salle de bain francaise carrelee avec baignoire. Jamais un loft
americain, jamais un spa canin de studio. Un jardin ou une terrasse francaise credible est une
alternative valable pour un lavage exterieur.

Avatar `ons-av-clara` (femme 25-35, francaise, tenue decontractee) **uniquement si un humain est
necessaire dans le cadre**. Sinon : mains et avant-bras seulement, pas de visage entier.

## 9. Fonctions de scene qui marchent

1. **Hook probleme** : le chien qui refuse, la salle de bain qui deborde, le desordre.
2. **Pose sur le plateau** : mains visibles, transition d'etat.
3. **Preuve produit** : l'eau qui s'ecoule a travers la maille et les trous. C'est **la** preuve
   propre a ce produit, elle doit apparaitre dans presque chaque video (regle G6).
4. **Chien detendu** : queue qui remue, contraste avec le hook.
5. **Pliage / rangement** : le pietement se replie a plat. Preuve de commodite.
6. **Payoff** : chien sec, salle de bain propre.

Un macro sans action ne merite pas une scene (regle G7).

## 10. Concurrents de reference

`@puppfloat`, `@pupfloats`, `@thesilentdoggy` en priorite. Secondaires : `@puppynest.co` (sac),
`@track.paws` (lit / siege auto), `@wash_your_pet` (brosse). `@pawnestify_` est ecarte, contenu IA
repere en commentaires.

Repere mesure : `@puppfloat` et `@pupfloats` ont sorti **le meme crea, la meme caption, le meme
jour, sur deux comptes** : 2,70 M et 2,69 M de vues, ecart 0,4 %. Aucune penalite de duplication.

Patterns prioritaires : **P7** (probleme -> soulagement, 5-10 s) avec une couche **P6** (soin d'un
etre vulnerable) pour corriger le faible taux d'adhesion du P7 pur, plus **P3** quand l'auto-DM
sera en place.

## 11. QA start frame ONSIMPLIFIE

```
[ ] bon coloris, un seul par video
[ ] pietement blanc en X pliant, embouts noirs, entretoise visible
[ ] toile a maille tendue, trous ovales asymetriques, passepoil assorti
[ ] echelle credible : le chien choisi tient physiquement sur le plateau
[ ] chien DEBOUT sur le plateau, quatre pattes posees, aucun membre qui traverse
[ ] comportement du chien conforme au moment de la sequence
[ ] mains avec fonction claire, contact visible avec le chien
[ ] etat sec / mouille coherent avec la scene precedente
[ ] salle de bain francaise credible, jamais un loft americain
[ ] pas de visage entier si l'avatar n'est pas necessaire
[ ] aucun packaging invente
[ ] 9:16, frame autonome, aucun texte ni logo genere
```

## 12. QA video ONSIMPLIFIE

```
[ ] frame 1 = start frame validee
[ ] produit ne morph pas : pietement, toile et trous stables
[ ] le plateau ne se deforme pas de facon impossible sous le chien
[ ] anatomie du chien stable, pas de patte supplementaire, pas de fusion
[ ] mains stables, geste realisable
[ ] l'eau coule vers le bas, a travers la maille, jamais a travers une surface pleine
[ ] continuite sec / mouille respectee
[ ] camera handheld de faible amplitude, pas de mouvement publicitaire
[ ] aucun texte, logo ou dialogue genere
```
