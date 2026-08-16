# Product breakdown — @spiraledazur

- **Marché** : FR, français parlé naturel.
- **Produit** : sac en crochet fait main, modèle **Marguerite**.
- **Prix affiché en vidéo** : **39,99 €** — un plan d'une seconde, en fin de séquence.
- **Statut** : actif, priorité 1. Seul compte du portefeuille avec un post gagnant enregistré.
- **Orthographe de la marque** : **Spiraledazur**. Pas « Spiradazur ». Toutes les générations
  antérieures au 14/08 portaient la faute.

## Ce que le produit est, physiquement

Un sac en crochet, maille visible, avec des fleurs marguerite crochetées en relief sur le corps du
sac, anses souples, breloque fleur et pompon. Fait main : la maille irrégulière est un argument,
pas un défaut. La géométrie exacte du sac est figée par `FOUR-TOUT-BAG.png`.

**Verrou de référence** : toujours attacher **les deux** — `FOUR-TOUT-BAG.png` pour la géométrie,
**et** la planche du coloris exact. Jamais l'une sans l'autre.

Cinq coloris, une planche chacun dans `refs/spiraledazur/` :

| Slug | Notes |
|---|---|
| `MARGUERITE-BLANC` | **Base crochet beige/tan avec fleurs blanches.** Ce n'est PAS un sac blanc uni. Ne jamais rejeter ni relancer une génération « Blanc » pour manque de blanc pur — c'est le rendu réel du coloris. Quatre relances ont déjà été gaspillées là-dessus le 14/08. |
| `MARGUERITE-BLEU-MARINE` | — |
| `MARGUERITE-JAUNE` | — |
| `MARGUERITE-VERT` | vert sauge |
| `MARGUERITE-VIOLET` | — |

Un coloris par vidéo. Jamais deux coloris du même sac dans le même montage.

## Ce qui ne doit jamais dériver

- La **maille crochet**. Elle dérive facilement vers du tissu lisse ou du tricot : si la maille
  n'est plus lisible en gros plan, la génération est ratée.
- Les **fleurs marguerite en relief**, la breloque et le pompon.
- Les **anses**, qui restent intactes et attachées.
- Aucun prix, aucun texte, aucun logo rendu dans l'image.

## Avatar

Sans référence d'avatar fournie : belle femme brune, châtain ou blonde, **tenue d'été assortie au
sac**. Aucun fragment de vêtement d'hiver visible, même partiel, quel que soit l'avatar de départ.
Les planches `HANDBAG-AVATARS-REF.png`, `MEUF-HANDBAG-V2.png` et `GRANDMA-HANDBAG-V2.png` sont
disponibles selon le rôle.

## Décors

Rayon de grande surface française, marché, stand de créatrice, terrasse parisienne, appartement
haussmannien. La référence de lieu retail est `MONOPRIX-RAYON.png` — ça doit se lire comme un
Monoprix, une Galeries Lafayette, un Zara ou un H&M, jamais comme un entrepôt générique.

**Deux verrous de décor :**
- **Aucune nourriture près d'un stand de sacs.** Pas de fruits, pas d'étal alimentaire dans le champ.
- **Foule dense obligatoire** sur tout plan d'ouverture rayon, marché ou stand : « large dense
  crowd of many women », pas deux ou trois personnes, sinon l'effet de ruée ne se lit pas.
  Référence de cadence et de densité verrouillée : le reel `Db1EvUxRzpo`, 278 K vues, meilleur
  post du compte.

Son de fond : murmure indistinct **ou** français clair et pertinent. Jamais une langue confuse.

## Ce qui a marché

Le **hook objection** — « Arrête, personne va acheter ça » — est le seul gagnant enregistré du
compte. Il se décline sur de nouveaux décors et de nouveaux coloris, il ne se remplace pas.

Patterns prioritaires : **P4** (fandom esthétique), **P1** (contexte aspirationnel),
**P5** (send-this-to), **P6** (émotion, fait-main).

## Le problème de conversion, à traiter dans chaque brief

~320 K vues cumulées, **zéro vente**, back-end sain. Trois leviers, dans l'ordre :

1. **Le CTA à mot-clé est supprimé** tant qu'aucun auto-DM ne tourne. « Commentez "Soleil" »
   promet une réponse que personne n'envoie. C'est la cause n°1.
2. **Le prix apparaît une fois par vidéo**, un plan d'une seconde, en fin de séquence, jamais en
   ouverture. 39,99 € sur un sac fait main est un argument ; non dit, le spectateur suppose
   « artisanal donc cher » et ne cherche pas le lien.
3. **Le lien bio doit pointer sur la fiche produit**, pas sur l'accueil de la boutique. À vérifier.

## Stock existant

51 rushs Unlimited du 10 au 13/08, 720x1280, audio aac, sur le Mac dans
`~/Desktop/FOUR TOUT HANDBAG RUSHS/`. **Épuiser ce stock avant toute nouvelle génération.**
Ces rushs passent le gate avec `--legacy-res`, et eux seuls.

## Autres produits de la marque

Le sac cowgirl (`Cowboy Hat Mini Backpack`) est **en pause**. S'il revient : coloris unique,
suède tan/camel avec imprimé vache noir et blanc, jamais varié.
