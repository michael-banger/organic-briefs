# STANDING BRIEF - ONSIMPLIFIE

**Ce fichier ne se perime jamais.** Il sert des qu'aucun `DAILY-BRIEF-{date}-ONSIMPLIFIE.md`
n'existe pour la nuit en cours. Un brief date, quand il existe, prime toujours.

La marque n'avait plus recu de brief depuis le **2026-08-06**. Elle est remise en production le
2026-08-20.

**A lire avant de generer, dans cet ordre :**
1. `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md`
2. `product-breakdowns/ONSIMPLIFIE.md`
3. `MANIFEST.md`, section `refs/onsimplifie/`

---

## Cadre fixe

- Marche **FR**. Lane **KLING**. **3 posts par nuit, 3 scenes par post.**
- Le prompt dit **"this dog washing table"**. Jamais un nom de marque, jamais un concurrent.
- **CTA lien en bio uniquement.** Aucun mot-cle tant qu'aucun auto-DM ne tourne.
- **Un coloris par video**, jamais deux.
- **3 references maximum** par image. Passe vision obligatoire avant le prompt video.
- Aucun texte, aucun hook, aucun watermark dans l'image. Visage entier seulement si l'avatar
  `ons-av-clara` est reellement necessaire, sinon mains et avant-bras.
- **Verrou de comportement du chien** : reticent AVANT d'etre sur le plateau, heureux et detendu
  DES qu'il y est. Jamais l'inverse.

## Rotation deterministe

Soit `D` = jour du mois de la date cible.

**Coloris du POST 1** = `D mod 3` : `0 -> gray`, `1 -> blue`, `2 -> pink`.
**POST 2** = `(D+1) mod 3`. **POST 3** = `(D+2) mod 3`.

**Concept du POST 1** = `D mod 3` dans la liste ci-dessous. **POST 2** = `(D+1) mod 3`.
**POST 3** = `(D+2) mod 3`.

**Chien** : `ons-prop-chien-petit` par defaut, parce que le plateau est de la taille d'un tabouret
de camping. `ons-prop-chien-golden` seulement quand le cadrage permet de montrer ses quatre pattes
posees sans que l'echelle devienne impossible.

URL brutes :
`https://raw.githubusercontent.com/michael-banger/organic-briefs/main/refs/onsimplifie/[slug].png`

---

## CONCEPT 0 - Probleme puis soulagement (pattern P7 + couche P6)

- `hook_overlay:` **"Mon chien detestait le bain. Jusqu'a ce truc."**
- `caption:` "Il ne se debat plus. Lien en bio"
- `hashtags:` #chien #toilettage #astucechien #proprietairedechien

**SCENE 1 - le refus**
- `SCENE FUNCTION` : hook probleme.
- `START STATE` : salle de bain francaise carrelee, baignoire visible, **le chien au sol, reticent,
  qui recule**, une main tente doucement de le guider. Le produit n'est pas encore utilise.
- `LOCATION SIGNALS` : carrelage et robinetterie francaise, jamais un loft americain, jamais un
  spa canin de studio.
- `HAND LOGIC` : une main sur le collier ou le flanc, contact visible, geste doux.
- `NEGATIVE` : pas de chien qui souffre, pas de brutalite, pas de visage entier.
- Refs : `ons-lieu-sdb`, le chien du jour.

**SCENE 2 - la pose sur le plateau**
- `SCENE FUNCTION` : transition d'etat, le produit entre en scene.
- `START STATE` : **deux mains posent le chien sur le plateau**, ses quatre pattes touchent la
  toile, il est deja plus calme.
- `PRODUCT LOCK` : pietement tubulaire blanc en X, embouts noirs, toile a maille tendue, trous
  ovales asymetriques a passepoil assorti. Coloris du jour.
- `SCALE` : le chien tient physiquement sur le plateau, sans deborder de partout.
- `STATIC ELEMENTS` : le pietement ne plie pas, la toile se tend a peine.
- `CONTINUITY FROM` : scene 1. Meme salle de bain, meme chien, meme lumiere, meme etat sec.
- Refs : le coloris du jour, le chien du jour, `ons-lieu-sdb`.

**SCENE 3 - le soulagement + la preuve**
- `SCENE FUNCTION` : payoff emotionnel et preuve produit dans le meme plan.
- `START STATE` : le chien **debout sur le plateau, mouille, detendu, la queue qui remue**, une
  main le savonne ou le rince. **L'eau s'ecoule visiblement a travers la maille et les trous.**
- `HAND LOGIC` : une main tient la douchette, l'autre stabilise le chien.
- `ACTION` video : l'eau coule vers le bas a travers la toile, la queue remue, camera tres stable.
- `CONTINUITY FROM` : scene 2, avec passage sec vers mouille assume dans ce plan.
- Refs : le coloris du jour, la version mouillee du chien.

---

## CONCEPT 1 - La preuve mecanique (pattern P3, demonstration)

- `hook_overlay:` **"Regarde ou passe l'eau"**  (remplacer par une formule non directive au
  montage si le hook doit rester organique)
- `caption:` "L'eau part toute seule. Rien ne stagne. Lien en bio"
- `hashtags:` #astucechien #toilettage #chien #objetutile

**SCENE 1 - le produit seul, deploye**
- `SCENE FUNCTION` : lisibilite produit.
- `START STATE` : le plateau **deploye**, seul, sur le carrelage d'une salle de bain francaise,
  lumiere naturelle laterale. Personne dans le cadre.
- `PRODUCT LOCK` : compter les trous sur la planche avant d'ecrire quoi que ce soit. Passepoil
  assorti a la toile, surpiqure visible.
- `CAMERA` : trois-quarts bas, pour montrer le X du pietement.
- Refs : le coloris du jour, `ons-lieu-sdb`.

**SCENE 2 - macro avec action**
- `SCENE FUNCTION` : preuve de matiere. Ce n'est **pas** un macro passif.
- `START STATE` : macro sur la toile, **une main verse de l'eau** dessus, l'eau traverse la maille
  et sort par les trous.
- `ACTION` video : l'eau tombe, la toile ne bouge pas, rien d'autre ne se passe.
- Refs : le coloris du jour.

**SCENE 3 - le pliage**
- `SCENE FUNCTION` : preuve de commodite, payoff.
- `START STATE` : **deux mains replient le pietement a plat**, le produit devient plat et fin.
- `HAND LOGIC` : une main sur chaque montant, mouvement symetrique.
- `MORPHING RISKS` : pietement qui se plie dans le mauvais sens, toile qui se dechire.
- `CONTINUITY FROM` : scene 2. Meme salle de bain, meme lumiere.
- Refs : le coloris du jour.

---

## CONCEPT 2 - Le lavage exterieur (pattern P6, soin)

- `hook_overlay:` **"Plus jamais la salle de bain a nettoyer apres"**
- `caption:` "Dehors, 5 minutes, zero degat. Lien en bio"
- `hashtags:` #chien #jardin #astucechien #toilettage

**SCENE 1 - le contexte**
- `SCENE FUNCTION` : hook contexte.
- `START STATE` : terrasse ou jardin francais credible, fin d'apres-midi, le plateau deploye sur
  les dalles, un tuyau d'arrosage a cote, le chien sec assis a distance.
- `LOCATION SIGNALS` : mobilier de jardin francais, mur en pierre ou cloture bois, vegetation
  temperee. Jamais un backyard americain.
- Refs : le coloris du jour, le chien du jour.

**SCENE 2 - le chien monte**
- `SCENE FUNCTION` : transition d'etat.
- `START STATE` : **deux mains soulevent le chien** et le posent sur le plateau, quatre pattes
  posees, chien deja detendu une fois dessus.
- `SCALE` : verifier que le chien choisi tient sur le plateau. Si le golden ne tient pas, prendre
  le petit chien. **Ne jamais agrandir le produit.**
- `CONTINUITY FROM` : scene 1.
- Refs : le coloris du jour, le chien du jour.

**SCENE 3 - le sechage heureux**
- `SCENE FUNCTION` : payoff.
- `START STATE` : le chien **encore sur le plateau**, une serviette passee par une main, poil
  ebouriffe, queue qui remue, gouttes qui tombent a travers la maille.
- `ACTION` video : la serviette bouge, le chien secoue legerement la tete, le plateau reste
  parfaitement stable.
- `CONTINUITY FROM` : scene 2, chien mouille.
- Refs : le coloris du jour, la version mouillee du chien.

---

## Avant de lancer une generation

Refuser et corriger le brief si (regle G12) :

- le chien est **dans** un bac plutot que **debout sur** le plateau ;
- le chien choisi ne tient pas physiquement sur un plateau de taille tabouret ;
- le chien est heureux avant d'etre sur la table, ou reticent une fois dessus ;
- une scene invente un packaging, une boite, un sachet ou un logo ;
- une scene montre l'eau stagner sur une surface pleine ;
- le produit passe du sol au plateau, ou de sec a mouille, sans plan de transition ;
- deux coloris apparaissent dans la meme video.

QA start frame et QA video : sections 11 et 12 de `product-breakdowns/ONSIMPLIFIE.md`.
