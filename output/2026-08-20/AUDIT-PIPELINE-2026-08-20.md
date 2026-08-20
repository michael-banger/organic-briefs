# AUDIT PIPELINE ORGANIC - 2026-08-20 02:00 CEST

Audit demande par Yann : verifier que tout ce qui devait etre genere les 18 et 19 aout l'a bien
ete, pour Spiraledazur, Carblazz et Onsimplifie. Ce n'est pas un constat theorique : les fichiers
produits ont ete ouverts et regardes.

## 1. Ce qui a reellement tourne

| Nuit | Brief present | Images generees | Verdict |
|---|---|---|---|
| 17/08 | CARBLAZZ + SPIRALEDAZUR | 9 + 9 | genere |
| 18/08 | CARBLAZZ (US par erreur), SPIRALEDAZUR (montage, sans generation) | 9 pour Carblazz, en double sous deux conventions de nom | genere mais **non conforme** |
| 19/08 | aucun | 0 | `BLOCKED_NO_BRIEF` |
| 20/08 | aucun | 0 | `BLOCKED_NO_BRIEF` |
| ONSIMPLIFIE | aucun depuis le 06/08 | 0 | jamais relance |

La tache planifiee ChatGPT a bien tourne les 4 nuits. Preflight `READ OK / WRITE OK` a chaque
fois. **Ce n'est pas elle qui a echoue.**

## 2. Cause racine

Trois causes cumulees, mesurees, pas supposees.

**Cause 1 - Hermes n'a aucune automatisation organic active.**
Sur le VPS `hermes-linux-paris`, `profiles/organic-ai-operator/cron/jobs.json` contient 16 jobs.
**Les 7 jobs `[ORGANIC-AI]` sont tous `enabled: false`**, derniers passages entre le 29/06 et le
22/07. Seuls les 5 jobs `[WEBIZEO]` et 2 jobs `[INFRA]` tournent encore, quotidiennement, sans
incident. Aucun job n'a jamais eu pour role d'ecrire un `DAILY-BRIEF`.

**Cause 2 - Hermes ne peut pas ecrire dans `organic-briefs`.**
Verifie dans le conteneur : pas de clone du depot, pas de `.gitconfig`, pas de
`.git-credentials`, pas de `gh`, aucune variable `GH_*`. Tous les briefs dates existants ont ete
pousses a la main. Le CLI Higgsfield n'existe que sous `/tmp/hfcli/node_modules/.bin/higgsfield`,
c'est-a-dire dans un repertoire efface au prochain redemarrage du conteneur.

**Cause 3 - le perimetre de marques des deux taches ChatGPT etait faux.**
Dans `SYSTEM/PROMPT-STARTFRAMES.md` (tache A, lane KLING), les cles de marque supportees etaient
`ONSIMPLIFIE`, `MYTEAOVO`, `CARBLAZZ`, avec la consigne explicite **`Skip Carblazz until its
canonical brief and manifest explicitly unblock it`**. `SPIRALEDAZUR` n'y figurait **pas du tout**.
Il etait assigne a la tache B, lane SEEDANCE, avec Troputile. Or la lane Seedance est dormante
depuis la perte de l'Unlimited le 15/08, et Troputile est archive.

Autrement dit : la marque numero 1 du portefeuille n'avait plus aucune lane vivante, et la marque
ex-aequo numero 1 etait explicitement mise de cote. Le brief Spiraledazur du 18/08 n'a jamais pu
etre lu par la tache qui tournait.

Consequence : la chaine dependait d'un depot manuel quotidien, sur un perimetre de marques qui ne
correspondait plus a la realite du portefeuille. Des qu'il n'y a pas eu de depot manuel, tout s'est
arrete en silence.

## 3. Defauts de qualite trouves dans ce qui a ete genere

Les planches de reference ont ete rouvertes et comparees aux images produites.

**`output/2026-08-18/CARBLAZZ/` est declare non exploitable.** Ne pas monter ces images.

| Defaut | Detail |
|---|---|
| `FAIL_PRODUCT_IDENTITY` | POST 1 : le brief demandait un cadran "wood-toned" avec un macro sur le grain du bois. `horloge-bois-f1` **n'a aucun bois** : c'est une livree F1 rouge/blanc/noir avec une monoplace imprimee au centre. |
| `FAIL_PRODUCT_IDENTITY` | POST 2 : le brief demandait "brushed black metal face, machining texture". `horloge-metal-noir` est une **jante alliage noire brillante 5 branches avec etrier de frein jaune**. |
| `FAIL_PACKAGING_MECHANICS` | POST 3 scene 2 : mains soulevant un couvercle sur un coffret profond. Le packaging reel est un **sleeve plat 40 x 40 cm avec decoupe circulaire, wordmark `blazz`, et un tiroir qui coulisse lateralement**. |
| `FAIL_WRONG_VARIANT` | POST 3 scene 2 : l'horloge visible dans la boite est une **carbone**, alors que le post est en metal-noir. |
| `FAIL_STATE_CONTINUITY` | POST 1 et POST 2 : l'horloge apparait directement au mur, sans plan de pose par des mains. |
| `FAIL_MARKET` | Tout le batch est parti en **US**, hooks anglais et mot-cle `CLOCK`, alors que le compte est repasse en **FR** au correctif du 17/08. |
| Gaspillage | Les 9 scenes existent en double, `start-frame-sceneN.png` **et** `IMG-SCENEN.png`. Deux conventions de nom, deux depenses d'images pour le meme resultat. |

Cause commune : **le brief a fait confiance au slug et a l'ancien breakdown au lieu de la planche.**
Trois des cinq descriptions de cadran du breakdown Carblazz etaient fausses.

## 4. Ce qui a ete corrige, et ou

| Correctif | Fichier |
|---|---|
| 16 regles generiques de production, champs obligatoires d'une scene, deux gates QA | `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md` (nouveau) |
| Les 5 cadrans Carblazz reverifies un par un, verrou d'echelle 35-40 cm, vitre par variante, mecanique du packaging, mains, installation avant hero, hard lock aiguilles, QA | `product-breakdowns/CARBLAZZ.md` |
| Sac coquillage promu produit de tete, logique des mains, foule, Paris lisible, accessoire subordonne, miroirs, sequence 8 scenes validee, QA | `product-breakdowns/SPIRALEDAZUR.md` |
| Marque remise en production, echelle du plateau contre taille du chien, trous reverifies, continuite sec/mouille, aucun packaging invente, QA | `product-breakdowns/ONSIMPLIFIE.md` |
| Descriptions produits corrigees, packaging, coquillage, perimetre standing brief | `MANIFEST.md` |
| Perimetre corrige (`SPIRALEDAZUR` ajoute et prioritaire, `CARBLAZZ` desormais actif), fallback `STANDING-BRIEF`, gate preflight, passe QA vision, nom de fichier unique | `organic-ai-workflow/SYSTEM/PROMPT-STARTFRAMES.md` |
| Lane SEEDANCE declaree dormante, plus aucune marque active, sortie propre en `NO_ACTIVE_SCOPE` au lieu de faux blocages | `organic-ai-workflow/SYSTEM/PROMPT-STORYBOARDS.md` |
| Briefs permanents, rotation deterministe par date | `STANDING-BRIEF-CARBLAZZ.md`, `STANDING-BRIEF-SPIRALEDAZUR.md`, `STANDING-BRIEF-ONSIMPLIFIE.md` (nouveaux) |
| Rattrapage date, avec les corrections integrees | `DAILY-BRIEF-2026-08-21-{CARBLAZZ,SPIRALEDAZUR,ONSIMPLIFIE}.md` (nouveaux) |

## 5. Ce que ca change concretement

La tache planifiee ChatGPT du 2026-08-20 22:00 trouvera trois briefs dates pour le 21/08 et
produira **27 start frames sur 9 posts**, trois marques. Les nuits suivantes, meme si personne ne
depose de brief, elle basculera sur les standing briefs et continuera a produire, en faisant
tourner concepts et coloris a partir du jour du mois.

`BLOCKED_NO_BRIEF` ne peut plus se produire tant qu'un standing brief existe.

## 6. Ce qui reste ouvert, et qui n'est pas bloquant

**Hermes ne peut toujours pas ecrire ici.** Il lui faudrait un PAT a portee fine, limite au seul
depot `organic-briefs`, droit `contents:write`. Aucun credential n'a ete cree ou installe pendant
cet audit. Ce n'est plus un point de blocage pour la production, seulement pour la variete
editoriale : sans Hermes, les concepts tournent sur la rotation deterministe des standing briefs
au lieu d'etre choisis chaque soir a partir des performances reelles.

Second point, sans effet sur la generation : le lien en bio de Carblazz pointe sur
`carblazz.com/products/lampes-resine-art`, pas sur une horloge murale.
