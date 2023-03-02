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

Financements 
Moyens matériels 



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
Quels sont les critères qui entrent en jeu dans l'accessibilité d'une zone? Semble y avoi deux grands facteurs: 1)Contexte environnemental (frontière/obstacle "naturel", topographique, climatique etc.) 2) Contexte politico-sociaux (Conflits et traces des conflits -mines) Faut-il distinguer ces deux contextes ou définir seulement un critère d'accessibilité? Contrainte enviro forme des zones PEU accessible vs contrainte politico-sécuritaire forme des zones PAS accessibles? 

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









