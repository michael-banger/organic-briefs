# DAILY BRIEF — SPIRALEDAZUR — SAC COQUILLAGE — publication 2026-08-17

**Brief de génération.** Distinct du brief `DAILY-BRIEF-2026-08-17-SPIRALEDAZUR.md`, qui lui ne
contient que du montage sur rushs existants. Les deux tournent la même nuit.

- Marché **FR**. Lane **KLING** — start frames 9:16 par ChatGPT, puis image-to-video, audio coupé.
- Produit : **sac coquillage** (`SHELL-BLOOM`), pas le sac Marguerite.
- 3 posts, **une variante de coloris par post** : blanc, kaki, blanc.

## Le concept — on reproduit le gagnant du compte

Ces 3 vidéos rejouent **la vidéo la plus vue du compte** (~200 K vues et plus), celle du magasin :
on voit le rayon, une main prend le sac, l'achat se fait. On ne réinvente rien. On change le
produit, le coloris et le décor, la mécanique reste identique.

**Analyse préalable obligatoire, à la charge de Hermès** : aller chercher ce reel sur le compte
`@spiraledazur`, l'analyser **image par image** (`/youtube-watcher` ou `frame-by-frame-method`),
et en extraire le vrai découpage — nombre de plans, durée de chaque plan, échelle de plan, moment
exact où la main entre dans le cadre, moment du hook, densité de foule, cadence de coupe.
Le découpage ci-dessous est une reconstruction à partir de ce qui est déjà verrouillé au vault ;
**s'il diverge de l'analyse réelle, l'analyse réelle gagne** et le montage suit le vrai reel.

Référence de cadence et de densité déjà verrouillée pour tout plan d'ouverture rayon, marché ou
stand : le reel `https://www.instagram.com/reel/Db1EvUxRzpo/`.

## Humain à l'écran — règle de ce brief

Le moins possible, et **jamais de face**. Mains, avant-bras, silhouettes de dos ou coupées au
cadre. Si une personne apparaît, ce doit être **légitime dans la scène** — quelqu'un qui fouille
le rayon, quelqu'un qui passe — exactement comme dans le reel d'origine. Rien de posé, rien de
frontal. La fluidité prime sur la présence humaine.

## Références

| Slug | Rôle | URL brute |
|---|---|---|
| `SHELL-BLOOM` | **géométrie du sac, verrou produit** | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/spiraledazur/SHELL-BLOOM.png |
| `MONOPRIX-RAYON` | décor retail français | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/spiraledazur/MONOPRIX-RAYON.png |

Ce que montre `SHELL-BLOOM` : sac en crochet en forme de coquillage, corps côtelé en éventail,
teinte crème/ivoire, anse ronde souple, anneaux dorés, **fleur crochet corail**, **perle nacrée**
et **pompon pêche** suspendus. C'est le coloris « blanc ».

> **Point ouvert, une seule question, à trancher demain — n'attends pas pour produire.**
> Il n'existe **aucune planche du sac coquillage en kaki**. Le seul kaki du portefeuille est sur le
> sac Marguerite seau (`MARGUERITE-VERT`, vert sauge), qui est un autre modèle. Le post 2 est donc
> briefé comme *coquillage en fil kaki*, géométrie verrouillée par `SHELL-BLOOM` et couleur donnée
> au prompt. Si tu voulais en fait le seau vert sauge, dis-le et on bascule le post 2 dessus.

Le décor de retail français doit se lire comme un Monoprix, des Galeries Lafayette, un Zara ou un
H&M. Jamais un entrepôt générique.

---

## POST 1 — Blanc — le rayon pris d'assaut

- `lane: KLING` · `post_id: 1` · `colorway: blanc (crème/ivoire)` · `pattern: P4 + P1`
- `hook_overlay:` **"J'ai cru que c'était une boutique de créatrice"**
- `caption:` "Il est parti en 2 jours la dernière fois 🥹 Commentez « Coquillage » pour le lien"
- `cta_keyword:` **Coquillage** — écrit entre **guillemets français « »**, jamais entre apostrophes
- `hashtags:` #sacencrochet #faitmain #crochet #shopping

**Scène 1 — le rayon, foule dense**
> A busy French department store handbag aisle, a large dense crowd of many women browsing the
> racks, shoulders overlapping, natural movement, warm store lighting, shelves of woven and
> crochet bags. Shot from chest height, slightly over a shoulder. No faces toward camera.
> Vertical 9:16, photorealistic, no text, no logo, no watermark.
> Refs : `MONOPRIX-RAYON`.

**Scène 2 — la main saisit ce sac**
> Close on a store shelf where this crochet shell-shaped bag sits among other bags. Reproduce this
> bag exactly as in the reference: fan-ribbed shell body, cream ivory crochet, round soft handle,
> gold rings, coral crochet flower charm, pearl bead and peach tassel. A woman's hand and forearm
> enter from the right and take it off the shelf. Only hand and forearm visible, summer sleeve.
> Warm store lighting. Vertical 9:16, photorealistic, no face, no text, no logo, no watermark.
> Refs : `SHELL-BLOOM`, `MONOPRIX-RAYON`.

**Scène 3 — l'achat**
> The same store, at the counter: this crochet shell bag resting on the checkout surface next to a
> card terminal, a hand placing a card on the terminal. Reproduce this bag exactly as in the
> reference. Only hands and forearms visible. Warm store lighting. Vertical 9:16, photorealistic,
> no face, no text, no logo, no watermark.
> Refs : `SHELL-BLOOM`.

Prompt vidéo, après passe vision : 1. la foule bouge en continu, la caméra dérive lentement le
long du rayon, aucune coupe ; 2. la main entre, saisit le sac, le sort du rayon d'un seul geste,
la maille crochet doit rester lisible pendant le mouvement ; 3. la main pose la carte, le sac ne
bouge pas. Anatomie des mains à vérifier en QC sur les scènes 2 et 3.

---

## POST 2 — Kaki — le même rayon, autre lumière

- `lane: KLING` · `post_id: 2` · `colorway: kaki` · `pattern: P4 + P1`
- `hook_overlay:` **"Personne ne devine qu'il est fait main"**
- `caption:` "Vous le prendriez en blanc ou en kaki ? 🥹 Commentez « Coquillage » pour le lien"
- `cta_keyword:` **Coquillage**, entre guillemets français « »
- `hashtags:` #sacencrochet #faitmain #crochet #modeete

Même découpage en 3 plans que le post 1, **décor changé** : un marché de créatrices en extérieur
plutôt qu'un grand magasin, fin d'après-midi, lumière chaude et rasante. Foule dense obligatoire
sur le plan d'ouverture. **Aucune nourriture, aucun étal alimentaire dans le champ.**

Instruction de couleur, à ajouter aux 3 prompts, la géométrie restant verrouillée par la référence :
> Reproduce this bag exactly as in the reference — same fan-ribbed shell shape, same round handle,
> same gold rings, same flower charm, pearl bead and tassel — but crocheted in a **muted khaki /
> olive yarn** instead of cream. Only the yarn colour changes. Nothing else about the bag changes.

---

## POST 3 — Blanc — la version terrasse

- `lane: KLING` · `post_id: 3` · `colorway: blanc (crème/ivoire)` · `pattern: P1`
- `hook_overlay:` **"Le sac qu'on croise en terrasse à Paris"**
- `caption:` "Fait main, et il tient tout 👜 Commentez « Coquillage » pour le lien"
- `cta_keyword:` **Coquillage**, entre guillemets français « »
- `hashtags:` #paris #terrasse #sacencrochet #faitmain

Variante aspirationnelle : ouverture sur une terrasse parisienne en fin de journée, le sac posé
sur une chaise en rotin à côté d'un café, puis une main qui le reprend en partant, puis un macro
sur la maille et le pompon. Pas de foule sur ce post. Toujours aucun visage.

---

## Règles qui s'appliquent aux 3 posts

- « this bag », jamais « a crochet bag like… ». Aucun nom de marque dans un prompt.
- 3 références maximum par image. `SHELL-BLOOM` est la référence produit sur **tous** les plans où
  le sac est visible — c'est elle qui empêche la dérive de forme.
- La **maille crochet** doit rester lisible. Si elle devient du tissu lisse, la génération est ratée.
- Tenue d'été sur toute silhouette visible, aucun fragment d'hiver.
- Aucun texte dans l'image. Le hook est un overlay de montage, permanent, ≥ 95 % de la durée.
- Montage 8-12 s, musique mixée dans le rendu, plan prix d'une seconde en fin de séquence.
- Passe vision obligatoire sur chaque start frame avant d'écrire le prompt vidéo.

## Format des guillemets — verrou d'écriture

Dans **toute** caption, le mot-clé déclencheur ManyChat s'écrit entre **guillemets français
« »**, avec l'espace insécable d'usage : `Commentez « Coquillage » pour le lien`.

Jamais d'apostrophes simples `'Coquillage'`, jamais de guillemets droits `"Coquillage"`, jamais de
guillemets anglais `"Coquillage"`. Un mot-clé mal encadré se lit mal et casse le réflexe de
commentaire. Cette règle vaut pour toutes les marques et tous les briefs.
