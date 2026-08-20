# Product breakdowns — à lire AVANT d'écrire un brief ou de générer

Un fichier par compte Instagram. **Lecture obligatoire avant toute production sur la marque
concernée**, par Hermès comme par ChatGPT. Le breakdown dit ce qu'est physiquement le produit,
comment il fonctionne, et ce qui ne doit jamais dériver. C'est ce qui évite les surprises à la
génération.

## Deux niveaux, lus dans cet ordre

1. **`_REGLES-GENERIQUES-PRODUCTION.md`** — les 16 règles valables pour toutes les marques :
   verrou d'échelle réelle, produit avant composition, interaction physique, continuité d'état,
   mécanique de packaging, preuve de matière, une scène une fonction, lieu lisible, la start frame
   est le contrat, minimalisme du mouvement, verrou des détails, fail avant dépense de crédit,
   gate d'animabilité, accessoire subordonné, planche de planification différente de la frame de
   génération, dominance de la référence. Plus les champs obligatoires d'une scène de brief et les
   deux QA gates génériques.
2. **`[MARQUE].md`** — ce que le produit est physiquement et ce qui ne doit jamais dériver.
   **Prime sur le fichier générique** en cas de conflit sur un point spécifique au produit.

Écrit le 2026-08-20 après audit : une génération lancée sans avoir lu ces deux niveaux est la
cause directe des régénérations demandées les 14, 17 et 18/08.

## Priorité, au 2026-08-20

Portefeuille resserré à **4 comptes actifs** par décision de Yann du 2026-08-17.

| Rang | Compte | Produit | État |
|---|---|---|---|
| **1** | `@spiraledazur` | sac coquillage (tête) + sac Marguerite | actif, seul compte avec un gagnant enregistré |
| **1** | `@carblazz` | horloges murales déco auto | actif, lancement — priorité égale à Spiraledazur |
| **1** | `@onsimplifie` | table de lavage chien portable | **actif depuis le 2026-08-20**, remis dans le périmètre par Yann |
| — | `@troputile` | sac boisson | **EN PAUSE.** Compte Instagram archivé, produit abandonné. Ne rien produire. Un nouveau produit sera cherché plus tard. |
| 4 | `@myteaovo` | pots de plante déco | actif — confirmé par Yann le 17/08 |
| — | `@whiskeysmok` | non tranché | ne rien produire |

**Périmètre de production quotidien depuis le 2026-08-20** : `@spiraledazur`, `@carblazz` et
`@onsimplifie`, trois marques, tous les jours. C'est le périmètre que couvrent les
`STANDING-BRIEF-*.md` à la racine du dépôt.

## Règle d'or du workflow automatisé — pas d'Elements

Les **Elements Higgsfield n'existent pas dans ce workflow**. Ils ne sont utilisés que lorsque Yann
génère lui-même, à la main, dans l'interface web. Toute génération automatisée — CLI Higgsfield,
MCP, ChatGPT — passe **exclusivement par des images de référence attachées**, résolues depuis les
URL brutes de `refs/[marque]/`.

Conséquence directe, et elle est lourde : sans Element pour verrouiller l'identité du produit d'une
génération à l'autre, **la fidélité repose entièrement sur la start frame**. Une start frame
approximative produit une vidéo fausse, et rien en aval ne la rattrape. D'où les deux règles
suivantes, non négociables :

1. La start frame est jugée **avant** d'écrire le prompt vidéo, en vision, une image à la fois.
2. Une start frame qui rate une contrainte dure du breakdown est **régénérée**, pas compensée au
   prompt vidéo.

## Périmètre de ces fichiers

Ce sont des breakdowns **de génération**, pas des fiches d'achat. Prix d'achat, fournisseurs,
dimensions et délais n'y figurent pas : ils ne changent rien à une image ni à un prompt. Le seul
prix qui apparaît est celui affiché à l'écran, quand une vidéo doit le montrer.
