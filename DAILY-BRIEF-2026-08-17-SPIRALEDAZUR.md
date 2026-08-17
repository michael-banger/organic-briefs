# DAILY BRIEF — SPIRALEDAZUR — publication 2026-08-17

- Marché : **FR**, français naturel. Jamais de traduction littérale d'un hook anglais.
- Produit : sac crochet Marguerite, 39,99 €.
- Lane : **AUCUNE GÉNÉRATION**. Les 3 vidéos se montent intégralement à partir des rushs
  Unlimited déjà payés du 10 au 13/08. Zéro crédit dépensé sur ce brief.

## Le stock réel, mesuré le 2026-08-17 à 01:20

51 clips rapatriés d'iCloud et matérialisés sur le disque, dans
`~/Desktop/FOUR TOUT HANDBAG RUSHS/` :

| Emplacement | Clips |
|---|---|
| `CONTENU 10 AOUT/HIGGSFIELD GEN 10 AOUT/archive/` | 23 |
| `CONTENU 10 AOUT/HIGGSFIELD GEN 10 AOUT/archive2/` | 6 |
| `archive (1)/` | 22 |

Profil technique, uniforme : **720x1280**, piste audio `aac` sur tous.
Durées : 24 clips de 8 s, 22 de 12 s, 2 de 16 s, 2 de 15 s, 1 de 4 s en 496x864 — **ce dernier
est à écarter**, sa définition ne tient pas.

Environ 8 min 30 de rushs pour 3 vidéos de 8 à 12 s. Le stock n'est pas la contrainte : la
sélection l'est.

Conséquence pour le gate : ce lot est en 720x1280, il passe avec `--legacy-res`. C'est réservé
aux anciens rushs. Tout contenu neuf reste en 1080x1920 à 30 fps.

## Règles de sélection — non négociables

1. **On coupe dans le clip, on ne jette pas le clip.** Un plan de marché avec un étal de fruits
   dans le champ ne s'écarte pas : on garde les secondes où la nourriture n'est pas visible.
   Le verrou est « aucune nourriture près du stand de sacs », pas « aucun plan de marché ».
2. **Si le début d'un rush est instable, on coupe par la fin** : `ss = durée_source − durée_cible`,
   la durée cible ne change pas.
3. **Sélectionner, pas tout prendre.** 8 plans tenus valent mieux que 24 plans moyens. Un plan qui
   ne sert ni le hook, ni le désir, ni la preuve produit ne rentre pas au montage.
4. **Un coloris par vidéo.** Jamais deux coloris du même sac dans le même montage.
   Rappel verrouillé : le coloris « Blanc » est une base crochet beige avec des fleurs blanches,
   pas un sac blanc uni — ne jamais le rejeter pour manque de blanc pur.
5. **Musique téléchargée et mixée dans le rendu**, jamais laissée « à ajouter sur Instagram ».
   Le drop se cale sur le moment fort. Un lit audio technique passe le gate mais n'est pas un son
   tendance : le son exact se relève sur un reel via `/viral-research` avant publication.
6. **Hook permanent**, présent sur au moins 95 % de la durée, jamais traité comme une intro.
   Marge latérale 40 px en 720 legacy. Aucune coupure de texte de plus d'une seconde.
7. Durée cible du montage : **8-12 s**. La médiane du batch viral d'août est à 10 s, aucune vidéo
   longue n'y figure.

## Règle de CTA — mise à jour du 2026-08-17

**Le CTA à mot-clé est maintenu.** Yann confirme que le mot-clé déclenche ManyChat.

Format d'écriture verrouillé : le mot-clé s'écrit entre **guillemets français « »**, jamais entre
apostrophes simples, jamais entre guillemets droits ou anglais.
Exemple : `Commentez « Soleil » pour recevoir le lien`.

Le lien bio doit pointer sur la fiche produit du sac, pas sur l'accueil de la boutique — à
vérifier avant publication, c'est la seconde fuite possible sur les ~320 K vues sans vente.

Chaque vidéo porte **un plan de 1 s montrant le prix**, en fin de séquence, jamais en ouverture.
39,99 € sur un sac crochet fait main est un argument, pas une objection. Non dit, le spectateur
suppose « artisanal donc cher » et ne cherche pas le lien.

---

## POST 1 — Hook objection — pattern P4

- `colorway:` un seul, au choix parmi les coloris disponibles dans les rushs, **différent** de
  celui des posts 2 et 3.
- `hook_overlay:` **"Arrête, personne va acheter ça 🤣"**
- `caption:` "Vous en pensez quoi ? 🥹"
- `cta_keyword:` Soleil — `Commentez « Soleil » pour recevoir le lien`
- `hashtags:` #faitmain #crochet #sacenchochet #petitecreatrice

C'est le **seul post gagnant enregistré du compte**. Il se décline, il ne se remplace pas : même
esprit de hook, décor et coloris jamais testés ensemble. Structure : hook posé sur un plan large,
puis le sac de près qui contredit l'objection, puis le prix.

## POST 2 — Send-this-to — pattern P5

- `colorway:` distinct du post 1.
- `hook_overlay:` **"Envoie ça à celle qui adore les sacs faits main"**
- `caption:` "Envoie ça à ta best qui collectionne les sacs 👜✨"
- `cta_keyword:` aucun sur ce post — le bait « envoie ça à » vise le partage en DM, pas le
  commentaire. Ne jamais mélanger un bait de partage avec un mot-clé ManyChat.
- `hashtags:` #sacfaitmain #crochet #cadeaufille #bestfriend

## POST 3 — Aspirationnel — pattern P1

- `colorway:` distinct des posts 1 et 2.
- `hook_overlay:` **"Le sac qu'on croise en terrasse à Paris"**
- `caption:` "Le sac qu'on croise en terrasse à Paris ☕️"
- `cta_keyword:` Soleil — `Commentez « Soleil » pour recevoir le lien`
- `hashtags:` #paris #terrasse #sacencrochet #modeete

Ouvre sur le lieu, pas sur le produit — plan 1 l'environnement reconnaissable, plan 2 le sac qui
s'y intègre, plan 3 le détail crochet. C'est la mécanique du meilleur reel du batch.

Tenue d'été obligatoire sur tous les plans retenus : aucun vêtement d'hiver visible, même
partiellement, quel que soit l'avatar.

---

## Contrôle avant de marquer une vidéo prête

Le gate déterministe doit sortir en code 0, avec `--legacy-res` pour ce lot uniquement, sur :
hook présent ≥ 95 %, aucun trou de texte > 1 s, marges respectées, aucun plan sous 0,8 s,
niveau audio réel et musique mixée.

Ensuite seulement, la passe visuelle. Tant qu'elle ne rend pas un verdict exploitable, la vidéo
reste `manual_review_required` et ne part pas en push. Pas de push sur gate déterministe seul.
