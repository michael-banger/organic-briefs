En attendant, prends en compte ça : 

Tu reprends la production CARBLAZZ. Avant toute vision pass, tout prompt vidéo Kling/Higgsfield
et tout QC, tu appliques les règles ci-dessous. Elles viennent d'une session de production réelle
validée par Yann, et d'une revérification image par image des planches de référence faite le
2026-08-20. Elles priment sur toute description produit que tu aurais en mémoire.

SOURCE DE VÉRITÉ, dans cet ordre :
1. la planche de référence `refs/carblazz/[slug].png` dans `organic-briefs`
2. `product-breakdowns/CARBLAZZ.md`
3. `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md`

RÈGLE ZÉRO : ne jamais faire confiance au slug, au nom de fichier ni à une description écrite.
Ouvre la planche, regarde-la, décris ce qu'elle montre réellement. Trois des cinq descriptions de
cadran étaient fausses avant le 20/08 et ont produit des générations à jeter.

====================================================================
1. CE QU'EST LE PRODUIT
====================================================================

Horloge murale décorative, ronde, quartz, cadran unique, aiguilles heures/minutes/secondes,
lunette fine, faible épaisseur, fixation murale par un trou au dos. Le thème automobile est dans
le cadran, pas dans la forme.

Ce n'est PAS un accessoire d'habitacle, PAS une horloge de bureau, PAS un objet miniature.

DIAMÈTRE RÉEL : 35 à 40 cm. Le packaging fait 400 x 400 mm, ce qui confirme la borne haute.

====================================================================
2. LES CINQ COLORIS — CE QUE MONTRE VRAIMENT CHAQUE PLANCHE
====================================================================

horloge-carbone
  GO   : jante alliage en fibre de carbone vue de face, rayons en vrai tissage carbone brillant
         avec profondeur mécanique, vrai disque de frein et ÉTRIER JAUNE bien visible derrière
         les rayons, chiffres blancs 1-12, lunette noire, AIGUILLES DORÉES fines,
         VITRE BOMBÉE très réfléchissante.
  NO-GO: une surface qui ressemble à une photo de jante collée derrière une horloge. Il faut une
         vraie impression d'objet mécanique en profondeur.

horloge-metal-noir
  GO   : jante alliage NOIRE BRILLANTE 5 branches, étrier jaune, disque de frein derrière,
         lunette imitant un FLANC DE PNEU noir avec lettrages moulés en relief et petits
         EMBLÈMES DORÉS sur le pourtour, aiguilles BLANCHES style pelle, trotteuse fine blanche,
         chiffres blancs 1-12, VITRE PLATE réfléchissante.
  NO-GO: "brushed metal", "machining texture", une plaque de métal brossé, un disque de frein
         seul. C'est une jante. Cette erreur a fait jeter tout le batch du 18/08.

horloge-metal-rouge
  GO   : même construction que le metal noir, jante ROUGE VIF BRILLANTE 5 branches, étrier jaune,
         disque noir, lunette flanc de pneu avec emblèmes dorés, aiguilles blanches, vitre.
  NO-GO: un rouge qui dérive vers l'orange ou le bordeaux.

horloge-compteur
  GO   : compteur de vitesse ancien. Cadran noir mat texturé, wordmark NISMO en blanc sous le 12,
         fenêtre odomètre 170884, seconde fenêtre 1984, mention km/h, chiffres blancs 10 à 120
         par pas de 10, index blancs rectangulaires, QUATRE POINTS ORANGE aux positions 12/3/6/9,
         lunette noire fine, aiguilles blanches style pelle + trotteuse fine blanche,
         VITRE BOMBÉE avec reflet marqué.
  NO-GO: un chiffre, une graduation, une fenêtre ou un point orange qui dérive. Comparer un par un
         à la planche. Ne jamais construire un hook ou une revendication autour du wordmark NISMO.

horloge-bois-f1
  GO   : livrée F1 ROUGE / BLANC / NOIR avec une MONOPLACE F1 vue de dessus imprimée au centre,
         chiffres noirs 1-12, index et points noirs, MOYEU DORÉ, lunette noire,
         face PLATE et MATE, aiguilles NOIRES.
  NO-GO: IL N'Y A AUCUN BOIS. Le slug est trompeur. Aucun grain de bois, aucune teinte bois,
         aucun macro sur "le grain". Et AUCUNE VITRE : cette variante n'a pas de verre, donc
         aucun reflet spéculaire, aucune brillance de vitre.

UN COLORIS PAR VIDÉO. Jamais deux horloges différentes dans le même montage. Un changement de
variante dans une scène n'est autorisé que sur instruction explicite de Yann pour cette scène.

====================================================================
3. GO / NO-GO — ÉCHELLE
====================================================================

GO
- écrire 35-40 cm en toutes lettres dans chaque prompt qui met l'horloge face à un humain,
  un mur ou un meuble ;
- repères utilisables : environ deux largeurs d'épaule d'adulte, nettement plus large qu'une tête,
  environ un tiers de la largeur d'un manteau de cheminée, environ la moitié du diamètre d'une
  roue de voiture au second plan ;
- si le mur ou le cadrage ne laissent pas la place : CHANGER le cadrage ou le mur.

NO-GO
- une horloge qui se lit comme un objet de 20 à 25 cm ;
- une horloge manipulée négligemment d'une seule main, comme une petite horloge de cuisine ;
- grossir l'horloge parce qu'il reste du mur, ou la rapetisser pour simplifier la composition ;
- déformer les proportions du produit pour l'adapter au décor. On adapte le décor au produit.

====================================================================
4. GO / NO-GO — VITRE ET REFLETS
====================================================================

GO, sur carbone / metal-noir / metal-rouge / compteur uniquement :
- demander explicitement : glass front, natural reflections, controlled specular highlight,
  reflection of the window / ceiling light / environment across the glass ;
- plan tenu en mains : une légère inclinaison fait glisser le reflet ;
- hero shot : léger angle ou lumière latérale pour que la vitre se lise.

NO-GO
- un reflet qui masque les chiffres, lave le cadran, ou ressemble à une plaque blanche opaque ;
- INVENTER une vitre sur bois-f1, qui n'en a pas ;
- une horloge sans aucun signal de vitre alors que la variante en a une : elle se lit alors comme
  une image plate collée au mur.

====================================================================
5. GO / NO-GO — PACKAGING
====================================================================

Le packaging réel : 400 x 400 mm, noir mat, PLAT (environ 5 cm d'épaisseur), grande DÉCOUPE
CIRCULAIRE en façade qui laisse voir l'intérieur noir, wordmark `blazz` en blanc en bas à gauche.
Mécanique : ENVELOPPE EXTÉRIEURE (sleeve) + TIROIR INTÉRIEUR QUI COULISSE LATÉRALEMENT, avec une
petite encoche de prise.

GO
- une main stabilise l'enveloppe, l'autre TIRE LE TIROIR LATÉRALEMENT ;
- mouvement naturel et fluide, assez rapide, le tiroir coulisse réellement ;
- l'horloge se découvre progressivement, l'intérieur reste noir ;
- selon l'angle, on aperçoit déjà une partie de l'horloge encore dans le tiroir.

NO-GO
- "lift the lid", "open the lid", "hinged box", "flip the box open" ;
- un coffret profond à couvercle : le packaging est PLAT ;
- omettre la découpe circulaire ou le wordmark `blazz` ;
- du slow motion sur l'ouverture.

====================================================================
6. GO / NO-GO — MAINS ET INSTALLATION
====================================================================

GO
- des mains dans presque tous les plans, avant-bras et manches décontractées ;
- TENIR l'horloge : DEUX MAINS, doigts autour de la lunette, poids et rigidité lisibles ;
- POSER l'horloge : deux mains, et l'horloge ENCORE AU CONTACT DES MAINS ;
- AJUSTER : une vraie petite correction d'alignement, pas une installation rejouée ;
- chaque main a une fonction identifiable.

NO-GO
- AUCUN VISAGE ENTIER dans le cadre ;
- l'horloge qui apparaît directement au mur, déjà fixée, sans plan de pose ;
- des mains décoratives sans raison, des doigts fusionnés, un poignet impossible ;
- une main qui masque le cadran pendant l'action principale.

SÉQUENCE OBLIGATOIRE dès qu'un unboxing est présent :
UNBOXING → PRODUIT TENU À DEUX MAINS → POSE PAR DES MAINS → HERO SHOT AU MUR.
Le hero shot seul vient APRÈS, jamais à la place. Le produit ne se téléporte jamais entre deux
états physiques.

====================================================================
7. GO / NO-GO — AIGUILLES, HARD LOCK
====================================================================

Priorité, sans exception :
  1. seule la TROTTEUSE, la plus fine, peut bouger
  2. sinon, horloge entièrement statique
  3. JAMAIS l'aiguille des heures ni celle des minutes

Restent immobiles : heures, minutes, jante, rayons, disque de frein, étrier, cadran, chiffres,
fenêtres de l'odomètre. AUCUNE rotation globale du cadran.

- Horloge dans les mains ou en cours d'installation : préférer TOUTES les aiguilles immobiles.
- Horloge posée au mur : la trotteuse peut avancer, mouvement subtil. Il n'a pas besoin d'être
  horlogèrement exact, il doit être visuellement crédible.

Si le modèle risque de confondre les aiguilles, il vaut mieux qu'aucune ne bouge.

====================================================================
8. GO / NO-GO — DÉCORS ET VOITURE
====================================================================

GO
- appartement haussmannien parisien : moulures, parquet point de Hongrie, cheminée marbre, miroir
  doré, grande fenêtre, garde-corps en fer forgé, belle lumière de fin de journée ;
- garage de passionné : vrai espace habité, belle voiture au second plan, béton poli, lignes LED
  crédibles, établi, rangements ;
- bureau ou salon de passionné auto, lumière naturelle ;
- la voiture est un support narratif : une Porsche 992 GT3 RS marche, une Ferrari 812 Superfast
  aussi. Le principe est "voiture aspirationnelle cohérente avec le monde visuel" ;
- si la même voiture revient : même modèle, même couleur, mêmes jantes, même plaque, même garage ;
- plaques FRANÇAISES, format français réel.

NO-GO
- studio publicitaire abstrait, fond noir "luxury ad" gratuit, showroom irréaliste ;
- une voiture qui devient le sujet : L'HORLOGE RESTE LE PRODUIT PRINCIPAL ;
- une plaque au format américain, ou dont les caractères changent d'une scène à l'autre ;
- surcontraindre tous les briefs à un seul modèle de voiture.

====================================================================
9. GO / NO-GO — STYLE DES START FRAMES
====================================================================

GO : vertical 9:16, photoréaliste, très haute qualité, détails nets, social-native, look iPhone 17
Pro Max, peu de profondeur de champ, exposition réaliste, couleurs naturelles, perspective
smartphone crédible, haut et bas du cadre dégagés.

NO-GO : hook imprimé, caption, sous-titre, watermark, logo ajouté, texte marketing, gros bokeh
cinéma, look publicité studio, look IA. Les seuls textes tolérés sont ceux qui appartiennent
physiquement au produit ou au packaging réel : NISMO, 170884, 1984, km/h, blazz.

====================================================================
10. PROMPT VIDÉO — LE BLOC OBLIGATOIRE
====================================================================

Tout prompt Kling/Higgsfield commence par :

  Use this exact validated start frame as frame 1.
  This clock must remain exactly identical to the clock visible in the start frame.
  Preserve its exact geometry, diameter, bezel, numerals, hands, glass and mechanical detail.
  Only the thin seconds hand may move. The hour and minute hands stay perfectly still.
  The wheel, brake disc, caliper and dial never rotate.

Ensuite, le prompt ne décrit que MOUVEMENT + CAMÉRA + ÉTAT FINAL, en nommant explicitement ce qui
bouge et ce qui reste immobile. Il ne redécrit pas la scène, ne réinvente pas le décor.

Mouvements GO :
  unboxing        → fluide, naturel, assez rapide, le tiroir coulisse réellement
  produit en mains→ inclinaison de quelques degrés pour révéler reflet et matière
  installation    → mouvement court et crédible : alignement puis stabilisation
  hero shot       → petit push-in ou léger mouvement latéral, très faible amplitude
  macro           → dérive latérale minuscule, la lumière révèle la matière
  plan large      → léger push-in handheld ou parallaxe

Mouvements NO-GO : drone, slow motion sur un geste utilitaire, mouvement publicitaire
spectaculaire, grande amplitude. Le mouvement doit paraître motivé par une personne qui filme.

JAMAIS d'`@element` écrit dans un prompt s'il n'est pas réellement attaché. Un faux element ne
verrouille rien. Sans element : start frame stricte + bloc de préservation.

====================================================================
11. QC — FAIL = REGÉNÉRER, JAMAIS "ça passe au montage"
====================================================================

Start frame :
[ ] bonne variante, vérifiée contre la planche et pas contre le slug
[ ] diamètre cohérent avec 35-40 cm
[ ] deux mains quand l'horloge est portée, anatomie plausible
[ ] géométrie, lunette, chiffres, aiguilles conformes à la planche
[ ] compteur : NISMO, 170884, 1984, km/h, 10-120, 4 points orange
[ ] jante : vrais rayons avec profondeur, disque, étrier jaune identifiable
[ ] carbone : tissage visible, pas une photo collée
[ ] vitre visible sur carbone / metal-noir / metal-rouge / compteur
[ ] AUCUNE vitre et AUCUN bois sur bois-f1
[ ] packaging : sleeve + tiroir, découpe circulaire, wordmark blazz, boîtier plat
[ ] une fonction claire pour la scène, lieu logique
[ ] continuité voiture / plaque / décor
[ ] pas de visage entier, aucun texte généré
[ ] iPhone social-native, pas de look publicité IA

Vidéo :
[ ] frame 1 = la start frame validée
[ ] le produit ne morphe pas, la taille ne dérive pas
[ ] chiffres et fenêtres identiques du début à la fin
[ ] jante immobile, disque immobile, étrier immobile
[ ] heures immobiles, minutes immobiles
[ ] seule la trotteuse fine bouge, ou rien
[ ] vitre et reflets restent physiques
[ ] mains anatomiquement plausibles
[ ] packaging garde la mécanique du tiroir
[ ] voiture et plaque cohérentes
[ ] caméra fluide, faible amplitude
[ ] aucun dialogue, aucune information visuelle inventée

====================================================================
12. CADRE ÉDITORIAL
====================================================================

Marché FR. Hooks et captions en FRANÇAIS. Le batch du 18/08 est parti en US par erreur : c'est un
défaut, pas un précédent.

CTA : `Commentez « V12 » pour recevoir les infos`, guillemets français. Un bait de partage et un
mot-clé ManyChat ne se mélangent jamais dans le même post.

Hook gagnant à décliner sur au moins la moitié d'un batch :
`Les fans de voitures ne marchez pas FONCEZ en Boutique`

Dans les prompts, dire "this clock". Jamais de nom de marque, jamais de nom de concurrent.
Montage cible : 1080x1920, 30 fps, 10 à 13 s, 8 à 10 plans.

====================================================================
13. AVANT DE DÉPENSER UN CRÉDIT
====================================================================

Refuse la génération et corrige la scène si :
- l'échelle n'est pas écrite en centimètres ;
- une vitre est demandée sur bois-f1, ou du bois n'importe où ;
- une scène fait passer l'horloge de la boîte au mur sans plan de pose ;
- une scène demande de soulever un couvercle ;
- une aiguille autre que la trotteuse doit bouger ;
- la référence produit manque ou n'est pas la planche canonique ;
- la scène n'a aucune fonction : ni information, ni progression, ni preuve, ni émotion, ni payoff.

On corrige le brief. On ne lance pas pour voir.

