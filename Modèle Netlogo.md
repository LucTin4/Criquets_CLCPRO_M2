 # SYNTHESE

## Quelles formes ce jeu devrait-il prendre? 

#### Quel support? 
Physique ou numérique. Déterminer les avantage et inconveniants de chacun?

#### Quel degré de généralité/spécificité? 
Le modèle a pour vocation de diserner les cultures locales de traitement. Il ne semble donc pouvoir être trop spécifique (intégration de SIG / l'implémentation d'un environnement détaillé semble peu problable)

#### Quelle échelle? 
Où/A quel moment les agents prennent leurs décisions? 
Où/A quel moment les décisions "déviantes" (un peu négatif) sont-elles prises? 
Où/A quel moment le prospecteur a-t-il le plus de liberté? 

#### Quelle temporalité? 

#### Quelles entités / paramètres?

- prospecteurs (agents)
- Criquets (agents ou patchs - densité de)
- Zones accessibles/ zones pas accessibles (paramètre d'accessibilité d'un patch)
- Habitation/villages (activités humaine fixes)
- Elevage nomade (activité humaine nomade)
- entités naturelles polluables (plus se renseigner sur la protection de la nature en Mauritanie - cf. programmes du Ministère de l'environnement)

Paramètres d'entrée (variables)
1) fixé par le modérateur 
2) fixé par les joueurs


# CHRONOLOGIE 

## 28/02 

#### Quel support? 

Le modèle numérique semble plus intéressant cela pour plusieurs raisons: 
- les utilisateurs cibles sont à l'aise avec le numérique et l'usage d'ordinateurs 
- Le modèle comprendra potentiellement un grand nombre de paramètres
- possibilité de monitorer plus efficacement

#### Quelle échelle au modèle? 

- Cette question dépend du moment où la décision d'intervention est prise. En d'autre terme est-ce que les prospecteurs ont déjà ciblé, au moment de partir de Nouakchott, l'intégralité des lieux où ils vont intervenir (planification) ou la majorité des interventions sont planifiés au grès de l'expédition/prospection? 
- Elle dépend également du moment, dans le processus de décision, où les décisions des prospecteurs s'écartent le plus de la "norme officielle". Où (et non plus quand) les prospecteurs ont le plus de liberté/ prennent des décisions déviantes? 

Echelles possibles: 
- La Mauritanie: avec les foyers grégaires réprésenter par un figuré ponctuel (un agent statique)
- Une échelle plus grande (X km2) avec un environnement fixe et les véhicules/les prospecteurs agents mouvants
- La même échelle mais avec un environnement changeant (tenter de représenter la progression/ l'avancer des prospecteurs en changeant l'environnement)

#### Quelle pas de temps? 

Paramètre fortement lié à l'échelle. Si le modèle représente l'évolution des équipes sur le terrain, il serait difficile de définir un pas de temps plus long qu'une heure ou quelques heures. Si on s'intéresse à la décision de départ en mission le pas de temps peut-être plus long. 

Pas de temps possible: 
- L'heure (impossibilité d'intégrer l'expérience/la formation, qui dure souvent de nombreuses années)
- Le jour (perte de toutes les décisions/changements d'avis pendant la journée)

#### Quelles entités / paramètres?
- prospecteurs (agents)
	- Doit-on distinguer les expérimentés et les non-expérimenter (paramètre croissant d'expérience) - potentiellement définissable par chaque prospecteur/joueur? 
	- Si les joueurs incarnent chacun un prospecteur, pas de distinction nécessaire (on va pouvoir par contre suivre si les expérimenter et les autres ont le même comportement?)
- Criquets (agents - essaim ou patchs - densité)
	- Doit-on distinguer les phases: grégaires, transiens, solitaires + les stades de croissances: larves vs ailés? **Consulter le modèle de Cyril.** 
- Zones accessibles/ zones pas accessibles (paramètre d'accessibilité d'un patch)
- Habitation/villages (activités humaine fixes)
	- 
- Elevage nomade (activité humaine nomade)
- entités naturelles polluables (plus se renseigner sur la protection de la nature en Mauritanie - cf. programmes du Ministère de l'environnement)
- 

# 02/03/23

Interrogation sur les éléments du modèle, si celui-ci représente une large surface

**- Accessibilité des zones géographiques**

Variable d'accessibilité sur les patchs?
Quels sont les critères qui entrent en jeu dans l'accessibilité d'une zone? Semble y avoir deux grands facteurs: 1) Contexte environnemental (frontière/obstacle "naturel", topographique, climatique etc.) 2) Contexte politico-sociaux (Conflits et traces des conflits -mines) Faut-il distinguer ces deux contextes ou définir seulement un critère d'accessibilité? Contrainte enviro forme des zones PEU accessible vs contrainte politico-sécuritaire forme des zones PAS accessibles? 

En bref: variable d'accessibilité d'un patch qui peut prendre 3 valeurs: PAS, PEU, Accessible.


**- Criquets**

Quelles formes dans le modèle? 
1) Densités: Pas des criquets eux-même (agents - serait trop nombreux) mais des densités (variables de patchs). Le problème c'est que les densités des solitaires sont faibles et qu'ils n'agissent pas en groupe - peuvent-ils parcourir de longues distances? Pas de problème si ils restent dans le même endroit. Plusieurs problèmes: 
	1) Mouvements difficiles à simuler avec les patchs
	2) supérposition de différents éléments sur les patchs (végétation pr exemple)
	3) Le fonctionnement du traitement est moins lisible car plus simple/plus clair de tuer/faire disparaitre un agent. 
2) Groupes: un agent représentent plusieurs criquets grégaires. Si l'échelle est grande, un agent peut aussi représenter un solitaire. Est-il nécessaire de distinguer solitaires et grégaires? 

**- Habitations / activités humaines sédentaires** 

Déterminer quelles sont les activités humaines sédentaires à proximité des zones de reproduction/ prospecté? 
Agent statique (comme pour Diohine)
Mécanisme de signalisation ou les agent ne font rien à part potentiellement induire une hésitation sur le traitement/ augmenter le seuil critique de traitement? 

**- Eleveurs nomades** 

Agents mouvants dans le paysage (Saisonnalité)
Interagissent avec les prospecteurs (signalisation de criquets)
Interagissent avec les prospecteurs (entre dans l'équation au nv du traitement)

# 03/03/23

Problème de taille: 
- Doit-on reproduire au maximum la réalité (// session de jeu se substitue à une mission de prospection). Dans ce cas c'est comme si le joueur était lui-même en prospection => modèle particulièrement difficile à réaliser
- Doit-on avoir une approche plus classique en réfléchissant à 

Relfexion sur l'intégration de la rationalité limité / manque d'information dans le modèle. 
Si on simule un espace large, type l'ensemble de la Mauritanie avec des informations sur les points zones où il y a des criquets etc., le problème est que le joueur a potentiellement trop d'informations en comparaison avec l'ensemble des info qu'il détient vraiment avant une prospection/traitement réel. Il y a un certain nombre d'incertitudes: la densité des criquets, est-ce que telle signalisation était avisée etc. 
Comment rendre compte de cela? Est-ce un élément important à intégrer ou faut-il s'écarter de la réalité en réfléchissant dans un contexte hypothétique où l'information détenue par les prospecteurs est quasiment parfaite? (ca semble avoir aucun intérer)
- Potentiellement laisser des zones grises/sans aucun figuré qui sont dévoilées petit à petit (// mini-map dans les jeux video)

=> Zone grise (sans activité) => signalisation (agent clignotant au niveau de la zone) => quand les prospecteurs vont vérifier (découverte de la zone, degré d'infestation)

Si le jeu permet de disserner les pratiques inconscientes/dissimulées, en faisant office de substitut à l'expérience, a-t-il une réelle utilité? Pourquoi pas simplement multiplier les observations participantes - l'acquisition de données comportementales serait surement moins biaisée (?). 
Le jeu doit donc avec une autre fonction, mais laquelle? 

# 03/04/2023

### Fonction du jeu 

Le jeu est une mise en situation virtuelle, où on tente de respecter plus ou moins fidèlement l'expérience du prospecteur sur le terrain. Il a un intérêt pratique et scientifique
- Pratique parce que partir sur le terrain avec les prospecteurs n'est pas chose aisée et qu'il est difficile de multiplier les expériences et(// les stagiaires sont formés pendant de longues années pour pouvoir être confronté à un panel varié de situations qui pour certaines s'avèrent assez rares)
- Scientifique parce que la mise en situation fictive et virtuelle permet:
	- la simplification de l'expérience (développer mais fonction de filtre)
	- le choix des contraintes - ce qui permet de remédier au problème pratique ci-dessus (voir une variété de situation). 

### Echelle

2 voir 3 étapes semblent intervenir (liée à des échelles/pdv différents)
1) Itinéraire et la planification (échelle du secteur - map avec des points de passage)
2) la prospection dans le véhicule (orientation, observation et décision d'arrêt)
3) la prospection hors du véhicule (observation et qualification du lieu)

Peut-être 1) et 2) peuvent être regroupés? 

## Itinéraire et planification

L'idée ici est d'avoir un paysage fictif, avec certains éléments renseignés (qui sont ceux figurant sur les cartes et les GPS) et d'avoir des éléments qui apparaissent au fil des rencontres/de la récupération d'info du centre etc. 
L'intérêt est de s'avoir: 
- Comment le prospecteur se dirigie et s'oriente dans le secteur? 
- Qu'est-ce qu'il priorise? 
- Comment va-t-il chercher de l'information et comment la considère-t-il? 

#### Entités 

Les éléments initiaux
- **topographie** 
	- A quoi sert-elle? Contrainte aux déplacements plus qu'indicateur de lieu intéressant. 
- **localités** (peut-être inutiles mais peuvent être plus investies par certains prospecteurs que par d'autres?) 
- **Voiture** (agent mouvant représentant le joueur)

Les éléments apparaissants
- les **populations** (peut-être pas d'intérêt de distinguer plus finement nomades agriculteurs etc. sauf que les nomades sont mouvants)
	- Faut-il distinguer différents types de populations? Nomades agents mobiles vs agricutleurs/locaux habitants des villages plutôt statiques? 
	- L'information est-elle différentes et différemment considérées selon les sources? 
- les **signalisations** - agents clignotants apparaissant après une rencontre ou un appel du centre. 
	- Faut-il distinguer les signalisations selon leur objet (pluie vs verdure vs présence criquets)
	- Faut-il leur désigner un degré de validité? (inutile si les prospecteurs vont nécessairement vérifier)
	- Faut-il leur désigner un degré d'urgence? (plutot au prospecteur de le faire mais ce paramètre d'urgent pourrait aider à créer des situations tendues -cf ci-dessous)

#### Pas de temps

Comment l'itinéraire est-il planifié? A la journée, sur plusieurs jour? On peut faire l'hypothèse que le pas de temps conditionne l'échelle de l'itinéraire. 
On peut tester l'adaptation des réactions à des contextes tendus (avec beaucoup de situations préoccupantes) en faisant jouer le participant pendant des périodes calmes et des périodes tendues.

#### Trajectoires et déplacements de la voiture 

C'est un point central. Est-ce que la voiture se déplace par point (itinéraire faire de point) ou par ligne, avec le joueur qui peut a tout moment définir la trajectoire (cf. modèle de déplacement dans *Bug Hunter Competition*)


## Prospection dans le véhicule

Ici il s'agit plus de comprendre les logiques d'arrêt et de déplacement entre deux points de l'itinéraire. 
Cependant est-ce qu'elle nécessite une autre interface//autre pdv? 
- OUI (version ambitieuse). On pourrait intégrer une nouvelle vue, représentant la vue de la voiture. Le propsecteur/joueur peut changer quand il le souhaite de vue (entre vue itinéraire et celle de la fenetre de la voiture) 
- NON. Jouer avec le pdv du joueur en créant une zone autour de l'agent voiture, qui se complexifie avec le biotope (couverture végétale, état de verdure etc.) et de potentielles apparitions de criquets (en forme d'agent cette fois) etc. (la zone proche détaillée correspondrait à la fenetre joueur hubnet et la carte à celle du modérateur). Problème = le prospecteur a-t-il assez d'informations pour prendre une décision d'arrêt (si pas assez d'info, pas de possibilité de le mettre face à des situations variées et d'analyser ses choix en conséquence)

Les arrêts marchent avec des conditions suffisantes (IF) et des mécanismes de mémorisations pour les contextualisées (nombre de criquets vu auparavant, nature des biotopes antérieurs etc.). 

## Prospection hors du véhicule

Cette partie est fortement structurées par les éléments du réseau bayesien. Il s'agit de comprendre, en reprennant tous les éléments du réseau, pour une combinaison donnée comment le propsecteur interprète les risques et qualifie le lieu. Les éléments apparaissent après un zoom, un changement d'interface - mais comment le faire???

Ce que le jeu permet par rapport au réseau bayesien: les prises de décisions (ntm de qualification) sont contextualisées (relative à d'autres situations, avec une contrainte temporelle, et une spatialité)

#### Entités

2 possibilités
- Les éléments sont disposés de façon a reproduire fidélement ce que le prospecteur pourrait voir. La couverture végétale seraient représentées par une multitude d'agents herbes, plus ou moins jaune selon leur état de verdure etc.  
	- (+) :Plus grande similitude avec la situation réelle + permet de voir plus finement comment le prospecteur se comporte (comment se dirige-t-il, jusqu'à quel nv d'info prospecte-t-il? etc.)
	- (-) : Alourdi le modèle, parce que potentiellement beaucoup d'agent + difficulté de reproduire des environnements complexes, et donc une mauvaise reproduction pourrait amenée à des problèmes d'interprétation des réponses (si pendant l'animation on demande au prospecteur d'expliquer ces choix, moins de pb)

- Les éléments apparaissent juste comme des indicateurs, un peu comme une légende de carte. 
	- (+) : facile à implémenter / + formalisés donc moins de risque d'écart entre les raisons du choix du joueur et l'interprétation que l'on en fait
	- (-) : Les possibilités du modèle agent ne sont plus mises à profit + écart énorme avec la situation réelle.





















