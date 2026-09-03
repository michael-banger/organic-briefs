Tu reprends la production SPIRALEDAZUR. Avant toute vision pass, tout prompt vidéo Kling/Higgsfield
et tout QC, tu appliques les règles ci-dessous. Elles viennent d'une session de production réelle
où Yann a validé les 8 start frames finales une par une, après une boucle de régénérations dont
chaque cause est devenue une règle ici.

SOURCE DE VÉRITÉ, dans cet ordre :
1. la planche `refs/spiraledazur/HANBAG-COQUILLAGE-REF.png` dans `organic-briefs`
2. `product-breakdowns/SPIRALEDAZUR.md`
3. `product-breakdowns/_REGLES-GENERIQUES-PRODUCTION.md`

RÈGLE ZÉRO : la référence produit est une IDENTITY AND GEOMETRY SOURCE, pas une inspiration
stylistique. Une génération qui reproduit le bon genre de sac mais reconstruit la géométrie est un
FAIL, même si l'image est belle.

Orthographe de la marque : Spiraledazur. Jamais "Spiradazur".

====================================================================
1. LE PRODUIT DE TÊTE : LE SAC COQUILLAGE
====================================================================

`HANBAG-COQUILLAGE-REF.png` est la SEULE référence valable. `SHELL-BLOOM.png` est archivé :
c'était un autre sac, utilisé par erreur dans le brief du 17/08.

GO — ce que la planche montre, vérifié le 2026-08-20 :
- GROSSE MAILLE crochet, BLANC PUR (pas du fil fin, pas du beige)
- forme de COQUILLAGE NAUTILE, volume COMPACT
- CÔTES RAYONNANTES qui partent du centre vers le bord
- ROSACE EN SPIRALE crochetée au centre de chaque face
- ANSE SUPÉRIEURE en CORDE BLANCHE ÉPAISSE et ronde
- MOUSQUETONS DORÉS de chaque côté de l'anse
- CHAÎNE DE PERLES NACRÉES amovible, portée en bandoulière
- DOUBLURE CRÈME visible à l'ouverture

NO-GO — substitutions interdites :
- un autre sac crochet, un sac beige, un sac marguerite
- un sac à fleur crochet colorée, un modèle avec pompon
- une variante générique "qui ressemble"
- CE SAC N'A NI FLEUR CROCHET NI POMPON, contrairement au Marguerite

La marque contient plusieurs produits. Les règles ne se transposent JAMAIS de l'un à l'autre.
Le sac Marguerite a sa propre référence (`FOUR-TOUT-BAG.png` + la planche du coloris, toujours
les deux ensemble) et ses propres règles. Par défaut, on produit le COQUILLAGE.

Le sac ne change pas de silhouette parce qu'une personne le porte, qu'une main le tient, qu'il est
ouvert, qu'un objet y entre, que la caméra change d'angle, ou qu'on passe d'un intérieur à un
extérieur.

====================================================================
2. GO / NO-GO — ÉCHELLE
====================================================================

La dimension exacte en centimètres n'a pas été établie. NE PAS EN INVENTER UNE. Ce sont les
rapports relatifs qui sont verrouillés.

GO
- largeur et hauteur relatives constantes, aspect COMPACT conservé
- épaisseur conservée, vraie ouverture conservée
- crédible contre un corps humain, crédible face à un iPhone, un rouge à lèvres, des lunettes,
  des clés, des AirPods, un portefeuille
- stories et encarts : LE CADRE SE CONFORME AU PRODUIT. Si l'arche est trop haute, on réduit
  l'arche, ou on réduit la taille d'affichage, ou on laisse plus d'air blanc.

NO-GO
- ÉTIRER ou ALLONGER le sac pour remplir une arche, un crop ou une composition
- un objet qui semble plus grand que la cavité, qui force l'ouverture, qui déforme la géométrie
- un objet qui rend le produit secondaire dans l'image

====================================================================
3. GO / NO-GO — MATIÈRE
====================================================================

GO : vrai crochet textile, fibres avec volume, côtes physiquement construites, rosace tressée
crédible, vraie corde tressée sur l'anse, vrais éléments métalliques dorés, vraies perles
nacrées, ombres de contact, poids réel.

NO-GO : plastique, CGI, objet gonflé, image plate collée dans la scène, motif crochet imprimé sur
une surface, forme fondue "AI smooth", maille qui devient du tissu lisse ou du tricot.

====================================================================
4. GO / NO-GO — MAINS ET INTERACTION PHYSIQUE
====================================================================

C'est le learning le plus coûteux de la session. Une génération avec DEUX MAINS MAL DISPOSÉES DU
MÊME CÔTÉ de l'anse a été rejetée : le problème n'était pas esthétique, cette mauvaise interaction
avait aussi fait RECONSTRUIRE LE SAC DE TRAVERS. Une mauvaise main est un FAIL produit.

GO — chaque main a une fonction physique claire :
- une main tient l'anse
- une main stabilise le corps du sac pendant que l'autre insère un objet
- une main attrape le sac depuis un rayon
- une seule main entre dans le cadre pour prendre un objet dans un flat lay

NO-GO
- deux mains tirant la même zone du même côté
- mains flottantes, doigts fusionnés, main traversant une sangle
- poignet impossible, main qui masque l'élément produit principal
- main qui déforme le sac pour accomplir l'action

Scène de packing : le sac est déjà correctement positionné, son ouverture est lisible, UNE main
réalise l'action, et si une seconde main est nécessaire elle stabilise clairement le côté opposé.

====================================================================
5. GO / NO-GO — LIEUX
====================================================================

BOUTIQUE
  GO   : magasin français ou européen crédible, rayon sacs, FORTE DENSITÉ HUMAINE, femmes en
         tenue d'été, esthétique retail réelle, produit immédiatement visible. Le rayon montre
         UNIQUEMENT le modèle coquillage blanc concerné. Doit se lire comme un Monoprix, une
         Galeries Lafayette, un Zara ou un H&M.
  NO-GO: un entrepôt générique. Un patchwork de sacs crochet différents sur le rayon. Un prix
         visible sur la scène de prise en main. De la nourriture ou un étal de fruits dans le
         champ près d'un stand de sacs.

FOULE = FOULE
  GO   : `large dense crowd of many women`. Référence de cadence et densité verrouillée :
         le reel Db1EvUxRzpo, 278 K vues, meilleur post du compte.
  NO-GO: deux ou trois personnes. L'effet de ruée ne se lit pas, c'est un FAIL.

APPARTEMENT PARISIEN
  GO   : il doit être IMMÉDIATEMENT LISIBLE comme parisien. Fenêtre haute, garde-corps en fer
         forgé, immeubles haussmanniens visibles dehors, moulures, lumière naturelle, textiles
         clairs, chambre élégante mais vécue.
  NO-GO: un décor beige générique. Écrire "Paris" dans le prompt ne suffit pas, le décor doit le
         MONTRER.

RUE HAUSSMANNIENNE
  GO   : architecture lisible, femme de dos, sac clairement visible, lumière naturelle, golden
         hour possible pour un hero shot.

STORIES
  GO   : sud de la France, ambiance méditerranéenne, beach club, Paris, lifestyle féminin, femme
         de dos, tenue d'été, atmosphère premium mais naturelle. Ce sont des OPTIONS de contexte,
         pas des obligations pour chaque post.

MIROIRS
  NO-GO: si le reflet ne peut pas être rigoureusement cohérent, ON RETIRE LE MIROIR. Il n'est
         jamais indispensable.

SON de fond : murmure indistinct OU français clair et pertinent. Jamais une langue confuse.

====================================================================
6. GO / NO-GO — AVATAR ET TENUE
====================================================================

GO : sans référence d'avatar fournie, belle femme brune, châtain ou blonde, TENUE D'ÉTÉ assortie
au sac. Planches disponibles selon le rôle : HANDBAG-AVATARS-REF, MEUF-HANDBAG-V2,
GRANDMA-HANDBAG-V2.

NO-GO : AUCUN fragment de vêtement d'hiver visible, même partiel, quel que soit l'avatar de
départ. Aucun visage entier clairement exposé dans la logique validée de cette vidéo.

====================================================================
7. GO / NO-GO — ACCESSOIRES
====================================================================

GO : un petit objet féminin du quotidien, reconnaissable, qui ENTRE PHYSIQUEMENT dans le sac et
ne l'occulte pas. Le rouge à lèvres Chanel fermé d'une itération précédente est un choix ponctuel,
pas une obligation de marque.

NO-GO : un téléphone. Il domine le plan et vole le produit. C'est le contre-exemple exact qui a
forcé une régénération. L'accessoire est TOUJOURS subordonné au produit.

====================================================================
8. SÉQUENCE VALIDÉE — LE SQUELETTE À DÉCLINER
====================================================================

Les 8 start frames ci-dessous ont été validées une par une par Yann. C'est le squelette de
référence, à décliner sur de nouveaux plans, pas à rejouer à l'identique.

1. boutique dense, rayon rempli uniquement du sac coquillage blanc   → scroll stopper + preuve sociale
2. une main prend le sac, même univers boutique, aucun prix visible  → interaction + désirabilité
3. appartement parisien lisible, sac sur le lit, préparation         → projection lifestyle
4. petit objet cosmétique fermé rangé dans le sac, produit dominant  → preuve d'usage
5. vue haute "what's in my bag", petits objets féminins autour       → capacité + curiosité
6. femme quittant l'univers boutique, sac porté                      → échelle sur corps + styling
7. femme de dos, rue haussmannienne, sac visible                     → projection + mouvement
8. hero shot produit, extérieur parisien, golden hour                → money shot

Chaînes de continuité naturelles : 1→2 boutique, 3→4→5 appartement, 6→7→8 extérieur.
Un hard cut vers un nouveau setup n'a PAS d'ancre de continuité : ne pas en forcer une.

À NE PAS SURINTERPRÉTER : les start frames de la Vidéo 2 n'ont pas reçu la même validation scène
par scène, et les rendus vidéo n'ont pas eu de revue finale détaillée. Les mouvements listés plus
bas sont des principes approuvés, pas une preuve que chaque rendu a passé une QA.

SCÈNES À JUSTIFIER
- macro crochet : la première version de la scène 3 a été rejetée parce qu'"il s'y passe rien".
  Un macro passif ne mérite pas une scène. Il lui faut une preuve de qualité, une action, un
  reveal, une transition ou une information nouvelle.
- gros plan perles / mousquetons : même logique. Joli, mais il ne doit pas remplacer une scène
  plus utile comme le "what's in my bag".

====================================================================
9. GO / NO-GO — FORMAT ET STYLE
====================================================================

GO : UNE IMAGE AUTONOME VERTICALE 9:16 PAR SCÈNE. Look iPhone 17 Pro Max, photoréaliste, net,
détail élevé, lumière naturelle, HDR naturel, faible profondeur de champ seulement quand elle est
physiquement plausible, micro-imperfections de prise smartphone acceptables, social-native.

NO-GO : collage, grille, planche multi-scènes ou contact sheet comme input d'animation. Un
storyboard de planification peut exister en amont, il ne remplace JAMAIS `IMG-SCENE[N]`.
Aucun hook imprimé, aucun texte, aucun sous-titre, aucun watermark, aucun logo ajouté. Les hooks
et captions arrivent au montage.

====================================================================
10. CONTINUITÉ — ÉTAT, PAS AMBIANCE
====================================================================

Ne jamais écrire "same style as previous image". Écrire ce qui doit rester identique : identité
produit, dimensions, état du produit, identité de la femme si récurrente, tenue, cheveux, mains,
manucure, lieu, heure de la journée, direction de la lumière, props proches, langage caméra.

Chaque scène porte deux champs explicites :
  CONTINUITY FROM: [numéro de scène | none]
  MUST REMAIN IDENTICAL: [...]

Priorité en cas de conflit, sans exception :
  RÉFÉRENCE PRODUIT CANONIQUE > CONTRAINTES DU BRIEF > FRAME DE CONTINUITÉ PRÉCÉDENTE
Une frame précédente ratée ne contamine jamais l'identité produit.

====================================================================
11. PROMPT VIDÉO — LE BLOC OBLIGATOIRE
====================================================================

Tout prompt Kling/Higgsfield commence par :

  Use this exact validated start frame as frame 1.
  This bag must remain exactly identical to the bag visible in the start frame.
  Preserve its exact geometry, proportions, chunky crochet weave, radiating ribs, central
  spiral rosette, thick white rope handle, gold clasps and pearl chain.
  Do not redesign, stretch, simplify or replace it.

Ensuite : MOUVEMENT + CAMÉRA + ÉTAT FINAL, en nommant ce qui bouge et ce qui reste immobile.

Le produit n'est JAMAIS animé comme un objet autonome. Pour un reveal ou un beauty shot :
PRODUIT STABLE + MOUVEMENT CAMÉRA.

Sac posé (table, lit, rayon) : il reste mécaniquement en contact avec la surface. Il ne change pas
de volume, ne respire pas, ne glisse pas, ne tourne pas sans interaction, ne s'ouvre pas seul.
Sac porté : légère oscillation, inertie de la marche, mouvement naturel de l'anse, léger
balancement. Pas de bouncing excessif, pas de torsion, pas de changement de taille, pas de
déformation de la coquille.
Packing : les objets non manipulés restent statiques, un seul objet bouge à la fois.

Mouvements GO par scène :
  crowd hook       → forward drift, légère dérive latérale, foule vivante, rapide mais fluide
  pickup           → la main prend ou tire légèrement le sac, petit push caméra
  appartement      → micro push-in, main qui approche ou soulève, textiles quasi immobiles
  packing          → l'objet descend proprement dans l'ouverture, caméra très stable
  what's in my bag → caméra haute très légèrement flottante, un seul objet manipulé
  porté / sortie   → trailing handheld follow, marche naturelle
  rue              → follow shot de dos, mouvement organique du corps et du sac
  hero shot        → micro push-in, éventuellement micro-arc, produit dominant et stable

Principe transversal : CONTROLLED HANDHELD. Ni trépied publicitaire parfait, ni shaky-cam.

====================================================================
12. NO-GO VIDÉO — REFUSER LE RENDU
====================================================================

Le sac change de géométrie ou s'allonge. La rosace dérive. Les côtes bougent ou fondent. Le
crochet devient une autre texture. La chaîne de perles apparaît ou disparaît sans cause. Le métal
change. Le sac flotte ou glisse seul. Un objet traverse le sac. Les mains fusionnent. Un objet se
téléporte. Le téléphone ou un accessoire devient dominant. Le background change brutalement dans
un plan continu. Les vêtements changent en continuité. Un miroir crée une seconde réalité
incohérente. La caméra fait un mouvement cinéma spectaculaire qui détruit le style smartphone. La
foule devient anatomiquement cassée. La scène ajoute du texte ou un logo. Le moteur reconstruit un
autre modèle de sac.

====================================================================
13. QC — FAIL = REGÉNÉRER
====================================================================

Start frame :
[ ] bonne référence, bon modèle, pas un autre sac Spiraledazur
[ ] blanc pur, silhouette nautile, compacité, épaisseur
[ ] côtes rayonnantes, rosace centrale, anse corde, mousquetons dorés, chaîne de perles
[ ] aucun détail inventé, ni fleur ni pompon
[ ] crédible par rapport au corps et aux mains, accessoires compatibles avec le volume
[ ] aucun étirement pour remplir le cadre
[ ] mains anatomiquement crédibles, chaque main a une fonction, aucun conflit main / anse
[ ] sac posé sur une vraie surface avec ombre de contact
[ ] produit suffisamment visible, aucun accessoire dominant
[ ] action future lisible, une seule fonction de scène claire
[ ] Paris reconnaissable quand Paris est demandé, foule réellement dense quand crowd est demandé
[ ] 9:16, une seule frame autonome, pas de collage
[ ] aucun texte, watermark ou logo, pas de visage entier

Vidéo :
[ ] même sac à la première et à la dernière frame
[ ] proportions, crochet, rosace, anse, perles, hardware stables
[ ] caméra fluide, micro-mouvement smartphone naturel
[ ] produit statique quand aucune force ne l'anime, sway réaliste quand il est porté
[ ] anatomie des mains stable, geste réalisable dans la vraie vie
[ ] un seul objet manipulé, objets secondaires en place, rien ne traverse le sac
[ ] même femme, même tenue, mêmes cheveux, même environnement, même direction de lumière
[ ] iPhone-like, net, HDR naturel, pas de bokeh publicitaire, pas de grade cinéma
[ ] première seconde compréhensible

Tout échec produit, physique ou anatomique = REGÉNÉRER. Jamais "ça passe au montage".

====================================================================
14. CADRE ÉDITORIAL ET CONVERSION
====================================================================

Marché FR. Dans les prompts, dire "this bag". Jamais de nom de marque, jamais de concurrent.

Le hook objection — "Arrête, personne va acheter ça" — est le SEUL gagnant enregistré du compte.
Il se décline sur de nouveaux décors et de nouveaux coloris, il ne se remplace pas.
Patterns prioritaires : P4 fandom esthétique, P1 contexte aspirationnel, P5 send-this-to,
P6 émotion fait-main.

Le problème à traiter dans chaque brief : ~320 K vues cumulées, ZÉRO vente, back-end sain.
1. AUCUN CTA à mot-clé tant qu'aucun auto-DM ne tourne. "Commentez Soleil" promet une réponse que
   personne n'envoie. C'est la cause n°1. CTA lien en bio uniquement.
2. Le prix 39,99 € apparaît UNE FOIS par vidéo, un plan d'une seconde en fin de séquence, jamais
   en ouverture, et JAMAIS dans une start frame.
3. Le lien bio doit pointer sur la fiche produit, pas sur l'accueil de la boutique.

====================================================================
15. AVANT DE DÉPENSER UN CRÉDIT
====================================================================

Refuse la génération et corrige la scène si :
- la référence attachée n'est pas HANBAG-COQUILLAGE-REF sur un post coquillage ;
- une scène demande un sac beige, marguerite, à fleur crochet ou à pompon ;
- une scène dit "foule" mais décrit deux ou trois personnes ;
- une scène dit "Paris" sans aucun cue visuel parisien ;
- un accessoire proposé est plus grand que la cavité du sac ;
- deux mains agissent du même côté de la même anse sans nécessité ;
- un miroir est présent sans reflet garanti cohérent ;
- une scène est un macro sans action ;
- un collage multi-scènes est proposé comme frame d'animation.

On corrige le brief. On ne lance pas pour voir.

NOTE : le sac Marguerite dispose de 51 rushs Unlimited des 10-13/08. Ce stock s'épuise AU MONTAGE,
pas à la génération. Un post Marguerite ne se génère que si un brief daté le demande
explicitement.