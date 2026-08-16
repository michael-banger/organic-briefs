# Product breakdown — @carblazz

- **Marché** : US, anglais américain.
- **Produit** : horloge murale décorative sur thème automobile.
- **Niche** : **décoration de maison pour passionnés d'automobile.** Le client n'a pas forcément
  la voiture. Il veut afficher sa passion chez lui.
- **Statut** : lancement, priorité 1 à égalité avec Spiraledazur.

## Ce que le produit est, physiquement

Une horloge murale ronde, à quartz, cadran unique, aiguilles heures/minutes/secondes, lunette
fine, faible épaisseur, fixation murale par un trou au dos. Le thème automobile est **dans le
cadran**, pas dans la forme : chaque coloris rejoue une pièce automobile différente.

Cinq coloris, tous documentés par une planche 7 vues dans `refs/carblazz/`. **Un coloris par
vidéo. Jamais deux horloges dans le même montage.**

| Slug | Ce que rejoue le cadran | Notes de génération |
|---|---|---|
| `horloge-carbone` | jante alliage en fibre de carbone vue de face, disque de frein et **étrier jaune** visibles derrière les rayons, aiguilles dorées fines, chiffres blancs 1-12, lunette noire | Le plus spectaculaire des cinq. C'est celui qui supporte un reveal. Le tissage du carbone doit rester lisible en macro — s'il devient un aplat noir, la génération est ratée. |
| `horloge-compteur` | compteur de vitesse ancien : cadran noir, index blancs, chiffres 10 à 120 km/h, points orange à 12/3/6/9, fenêtre d'odomètre `170884`, seconde fenêtre `1984`, trotteuse blanche fine | Porte une **marque automobile tierce** sous le 12. On la reproduit si on montre le produit réel ; on ne construit jamais un hook, une caption ou une revendication autour. Les deux fenêtres de chiffres sont un détail signature : si elles disparaissent, l'objet n'est plus le bon. |
| `horloge-metal-noir` | disque de frein, métal brossé noir | Le grain du métal doit rester visible sous une lumière rasante. |
| `horloge-metal-rouge` | disque de frein, métal rouge | Le rouge ne doit jamais dériver vers l'orange ou le bordeaux. |
| `horloge-bois-f1` | thème bois / F1 | — |
| `horloge-packaging` | boîte retail | Scènes de déballage ou de livraison uniquement. **Jamais le produit héros.** |

## Ce qui ne doit jamais dériver

- La **rondeur et la finesse** de l'objet. Ce n'est ni une pendule épaisse, ni une roue posée au mur.
- Le **cadran du coloris cité**, à l'identique de la planche. Une horloge carbone dont l'étrier
  jaune a disparu n'est plus le produit.
- L'**échelle**. C'est un objet mural d'environ la taille d'une horloge de cuisine, pas une pièce
  de garage grandeur nature. La scène doit permettre de lire cette échelle au moins une fois.
- Le produit est **une décoration d'intérieur**. Jamais dans un habitacle, jamais fixé sur une
  carrosserie, jamais un accessoire embarqué.

## Ce que ce produit n'est pas

LED d'intérieur de voiture, support de téléphone, tapis de sol, housse, parfum, éclairage de
seuil, accessoire de tableau de bord, sticker de carrosserie. Tout ça est hors niche.

## Décors qui marchent

Garage domestique de nuit sous une réglette, bureau à domicile, salon un soir de course, mur nu
au-dessus d'un bureau. Toujours **un mur vide identifiable avant le produit** : la mécanique
gagnante ouvre sur l'environnement, pas sur l'objet.

## Humain à l'écran

Jamais de visage entier. Mains et avant-bras uniquement, manches sobres. Trois des quatre
meilleurs concurrents du batch d'août sont sous 20 % de visage, le meilleur est à 0 %.

## Concurrent de référence

`@carwake.co` — 179,2 K abonnés, 6,67 M de vues le 03/08 sur « Comment "Lights" if you need this ».
**Il vend un autre produit** : aucun concurrent direct n'existe sur l'horloge murale auto. On
transplante sa mécanique — décor automobile identifiable, reveal, hashtags de tribu — pas son
produit. Le brief doit le dire explicitement.

Patterns prioritaires : **P1** (produit en contexte aspirationnel), **P4** (fandom lock, hashtags
de tribu type #f1, #jdm, #dodgechallenger), **P5** (send-this-to, angle cadeau).

## CTA

CTA bio explicite. **Pas de CTA à mot-clé** tant qu'aucun auto-DM ne tourne.
