# Product breakdowns — à lire AVANT d'écrire un brief ou de générer

Un fichier par compte Instagram. **Lecture obligatoire avant toute production sur la marque
concernée**, par Hermès comme par ChatGPT. Le breakdown dit ce qu'est physiquement le produit,
comment il fonctionne, et ce qui ne doit jamais dériver. C'est ce qui évite les surprises à la
génération.

## Priorité, au 2026-08-17

| Rang | Compte | Produit | État |
|---|---|---|---|
| **1** | `@spiraledazur` | sac crochet Marguerite | actif, seul compte avec un gagnant enregistré |
| **1** | `@carblazz` | horloges murales déco auto | actif, lancement — priorité égale à Spiraledazur |
| 3 | `@onsimplifie` | douche chien portable | froid, refs prêtes |
| 4 | `@myteaovo` | pots de plante déco | froid, refs prêtes |
| 5 | `@troputile` | sac boisson | froid, refs prêtes |
| — | `@whiskeysmok` | non tranché | **ne rien produire** |

Les deux marques de rang 1 sont les seules au périmètre des nuits du 17 et du 18/08.

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
