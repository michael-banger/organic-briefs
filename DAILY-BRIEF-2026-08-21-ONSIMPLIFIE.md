# DAILY BRIEF - ONSIMPLIFIE - publication 2026-08-21

**Premier brief depuis le 2026-08-06.** La marque est remise en production sur decision de Yann du
2026-08-20. Elle avait des references pretes et aucun brief : c'est la marque la plus en retard du
portefeuille.

Lecture obligatoire avant de generer :
1. `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md`
2. `product-breakdowns/ONSIMPLIFIE.md` (revision du 2026-08-20)
3. `MANIFEST.md`, section `refs/onsimplifie/`

- Marche **FR**. Lane **KLING**. 3 posts, 3 scenes chacun. **Un coloris par post.**
- Coloris du jour : POST 1 `gray`, POST 2 `blue`, POST 3 `pink`.
- "this dog washing table" dans les prompts. Jamais de nom de marque, jamais de concurrent.
- **CTA lien en bio uniquement.** Aucun mot-cle tant qu'aucun auto-DM ne tourne.
- **Verrou de comportement du chien** : reticent AVANT d'etre sur le plateau, heureux et detendu
  DES qu'il y est. Jamais l'inverse, quel que soit le decor.
- **Verrou d'echelle** : le plateau a la taille d'un tabouret de camping. `ons-prop-chien-petit`
  par defaut. Le golden retriever seulement si le cadrage montre ses quatre pattes posees sans
  rendre l'echelle absurde. **On change de chien ou de cadrage, jamais la taille du produit.**
- **Aucun packaging.** Aucune planche n'existe : ne pas en inventer, aucune scene d'unboxing.
- 3 references maximum. Passe vision obligatoire avant le prompt video.
- Mains et avant-bras seulement, pas de visage entier.

## References

| Slug | URL brute |
|---|---|
| `ons-pr-douchechien-gray` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/onsimplifie/ons-pr-douchechien-gray.png |
| `ons-pr-douchechien-blue` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/onsimplifie/ons-pr-douchechien-blue.png |
| `ons-pr-douchechien-pink` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/onsimplifie/ons-pr-douchechien-pink.png |
| `ons-prop-chien-petit` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/onsimplifie/ons-prop-chien-petit.png |
| `ons-prop-chien-golden` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/onsimplifie/ons-prop-chien-golden.png |
| `ons-lieu-sdb` | https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/onsimplifie/ons-lieu-sdb.png |

---

## POST 1 - Probleme puis soulagement - pattern P7 + couche P6

- `lane: KLING` · `post_id: 1` · `colorway: gray` · `pattern: P7` · chien : `ons-prop-chien-petit`
- `hook_overlay:` **"Mon chien detestait le bain. Jusqu'a ce truc."**
- `caption:` "Il ne se debat plus. Lien en bio" · `hashtags:` #chien #toilettage #astucechien #proprietairedechien

**SCENE 1 - le refus**
- `SCENE FUNCTION` : hook probleme.
- `START STATE` : salle de bain francaise carrelee, baignoire visible, **le petit chien au sol,
  reticent, qui recule**, une main tente doucement de le guider par le flanc. Le produit n'est pas
  encore dans l'action.
- `LOCATION SIGNALS` : carrelage et robinetterie francaise, jamais un loft americain, jamais un
  spa canin de studio.
- `HAND LOGIC` : une main en contact visible avec le chien, geste doux.
- `NEGATIVE` : pas de chien qui souffre, pas de brutalite, pas de visage entier, aucun texte.
- `CONTINUITY FROM` : none.
- Refs : `ons-lieu-sdb`, `ons-prop-chien-petit`.

**SCENE 2 - la pose sur le plateau**
- `SCENE FUNCTION` : transition d'etat, le produit entre en scene.
- `START STATE` : **deux mains posent le chien sur le plateau**, ses quatre pattes touchent la
  toile, il est deja plus calme. Le produit est deploye, stable au sol.
- `PRODUCT LOCK` : **pietement tubulaire blanc en X pliant**, embouts caoutchouc noirs, entretoise
  laterale visible, **toile a maille tendue legerement concave** tendue entre deux barres, percee
  de **trous ovales de tailles differentes en disposition asymetrique**, **passepoil assorti a la
  toile**, surpiqure visible. Coloris gris.
- `SCALE` : le chien tient physiquement sur le plateau, quatre pattes posees, sans deborder.
- `STATIC ELEMENTS` : le pietement ne plie pas, la toile se tend a peine.
- `HAND LOGIC` : une main sous le poitrail, une main sous l'arriere-train.
- `MORPHING RISKS` : pattes qui traversent la toile, chien qui flotte au-dessus, plateau qui
  devient un bac ou une baignoire.
- `CONTINUITY FROM` : 1. Meme salle de bain, meme chien, meme lumiere, chien encore **sec**.
- Refs : `ons-pr-douchechien-gray`, `ons-prop-chien-petit`, `ons-lieu-sdb`.

**SCENE 3 - le soulagement et la preuve**
- `SCENE FUNCTION` : payoff emotionnel et preuve produit dans le meme plan.
- `START STATE` : le chien **debout sur le plateau, mouille, detendu, la queue qui remue**, une
  main le rince a la douchette. **L'eau s'ecoule visiblement a travers la maille et par les trous
  ovales**, vers le carrelage.
- `HAND LOGIC` : une main tient la douchette, l'autre stabilise le chien sur le flanc.
- `ACTION` video : l'eau coule vers le bas a travers la toile, la queue remue, camera tres stable.
  Le plateau ne bouge pas.
- `CONTINUITY FROM` : 2, avec passage sec vers mouille assume dans ce plan.
- Refs : `ons-pr-douchechien-gray`, `ons-prop-chien-golden` (version mouillee) ou
  `ons-prop-chien-petit` selon le chien retenu en scene 1, `ons-lieu-sdb`.

---

## POST 2 - La preuve mecanique - pattern P3

- `lane: KLING` · `post_id: 2` · `colorway: blue` · `pattern: P3`
- `hook_overlay:` **"Personne ne regarde ou passe l'eau"**
- `caption:` "L'eau part toute seule, rien ne stagne. Lien en bio" · `hashtags:` #astucechien #toilettage #chien #objetutile

**SCENE 1 - le produit seul, deploye**
- `SCENE FUNCTION` : lisibilite produit.
- `START STATE` : le plateau **deploye**, seul, sur le carrelage d'une salle de bain francaise,
  lumiere naturelle laterale. Personne dans le cadre.
- `PRODUCT LOCK` : coloris bleu, pietement blanc en X, embouts noirs, toile a maille tendue, trous
  ovales asymetriques a passepoil assorti. **Compter les trous sur la planche avant d'ecrire un
  nombre.**
- `CAMERA` : trois-quarts bas, pour montrer le X du pietement et la concavite de la toile.
- `CONTINUITY FROM` : none.
- Refs : `ons-pr-douchechien-blue`, `ons-lieu-sdb`.

**SCENE 2 - macro avec action**
- `SCENE FUNCTION` : preuve de matiere. **Ce n'est pas un macro passif** : il y a une action.
- `START STATE` : macro sur la toile, **une main verse de l'eau dessus** avec un petit seau ou une
  douchette, l'eau traverse la maille et sort par les trous.
- `ACTION` video : l'eau tombe, la toile reste immobile, rien d'autre ne se passe.
- `NEGATIVE` : l'eau ne stagne jamais sur une surface pleine.
- `CONTINUITY FROM` : 1. Meme salle de bain, meme lumiere.
- Refs : `ons-pr-douchechien-blue`.

**SCENE 3 - le pliage**
- `SCENE FUNCTION` : preuve de commodite, payoff.
- `START STATE` : **deux mains replient le pietement**, le produit devient plat et fin, prêt a
  ranger.
- `HAND LOGIC` : une main sur chaque montant, mouvement symetrique.
- `MORPHING RISKS` : pietement qui se plie dans le mauvais sens, toile qui se dechire, barre qui
  disparait.
- `ACTION` video : mouvement court et credible, puis stabilisation.
- `CONTINUITY FROM` : 2.
- Refs : `ons-pr-douchechien-blue`.

---

## POST 3 - Le lavage exterieur - pattern P6

- `lane: KLING` · `post_id: 3` · `colorway: pink` · `pattern: P6` · chien : `ons-prop-chien-golden`
- `hook_overlay:` **"Plus jamais la salle de bain a nettoyer apres"**
- `caption:` "Dehors, 5 minutes, zero degat. Lien en bio" · `hashtags:` #chien #jardin #astucechien #toilettage

**SCENE 1 - le contexte**
- `SCENE FUNCTION` : hook contexte.
- `START STATE` : terrasse ou jardin francais credible, fin d'apres-midi, le plateau rose deploye
  sur les dalles, un tuyau d'arrosage a cote, le golden **sec, assis a distance**, l'air peu
  enthousiaste.
- `LOCATION SIGNALS` : mobilier de jardin francais, mur en pierre ou cloture bois, vegetation
  temperee. Jamais un backyard americain.
- `CONTINUITY FROM` : none.
- Refs : `ons-pr-douchechien-pink`, `ons-prop-chien-golden`.

**SCENE 2 - le chien monte**
- `SCENE FUNCTION` : transition d'etat.
- `START STATE` : **deux mains guident le golden** sur le plateau, ses **quatre pattes posees et
  visibles** sur la toile. Il est deja detendu une fois dessus.
- `SCALE` : cadrer de facon a ce que le chien tienne credible sur un plateau de taille tabouret.
  **Si ce n'est pas credible dans le cadre choisi, changer de cadrage ou basculer sur
  `ons-prop-chien-petit`. Ne jamais agrandir le produit.**
- `STATIC ELEMENTS` : le pietement ne plie pas, ne s'enfonce pas dans les dalles.
- `CONTINUITY FROM` : 1. Meme jardin, meme lumiere, chien encore sec.
- Refs : `ons-pr-douchechien-pink`, `ons-prop-chien-golden`.

**SCENE 3 - le sechage heureux**
- `SCENE FUNCTION` : payoff.
- `START STATE` : le chien **encore sur le plateau**, mouille, une main passe une serviette sur
  son dos, poil ebouriffe, queue qui remue, gouttes qui tombent a travers la maille sur les dalles.
- `HAND LOGIC` : une main tient la serviette, l'autre stabilise le chien.
- `ACTION` video : la serviette bouge, le chien secoue legerement la tete, le plateau reste
  parfaitement stable et en contact avec le sol.
- `CONTINUITY FROM` : 2, chien mouille.
- Refs : `ons-pr-douchechien-pink`, `ons-prop-chien-golden` (version mouillee).

---

## Controle avant de marquer pret

Gates : sections 11 et 12 de `product-breakdowns/ONSIMPLIFIE.md`. Un chien qui flotte, une patte
qui traverse la toile, un plateau qui se deforme, ou un chien heureux avant d'etre sur la table :
regeneration.
