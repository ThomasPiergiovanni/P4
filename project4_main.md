
# PROJET 4

>L'idée de ce projet est de réalisé un "entonoir" vous permettant de présenter de manière détaillée une conception d'application.

	Q: Entonnoir inversé ?

	Q: Ce qui m'est demandé par  Alexandra :
		- Analyser le besoin client
		- Rédiger les spécifications fonctionnelles
		- Produire une orientation des spécificités techniques avec une courte argumentation de la solution technique
		- Dire si la solution part de scratch ou sur la base d’un CMS e-commerce*
		--> Je vois donc:
			- un document Specification Fonctionnelle, qu'il faudrait renommé,  qui est fait est divisé en 2 section) :
				- Analyse Besoin
				- Spécifications  Fonctionnelles

[exemple cahier des charges](https://openclassrooms.com/fr/courses/4296701-gerez-un-projet-digital-avec-une-methodologie-en-cascade/4303841-redigez-les-specifications-techniques-de-votre-projet#/id/r-4388329)

## SPECIFICATIONS FONCTIONNELLES (Titre a discuter)

> Pour réaliser le document, voici la trame suggérée :

	Q: J 'ai un peu un probleme avec le nom du document "Specification fonctionnelle"  car une partie ne fait pas partie des specifications fonctionnelles. A quel poiunt on peut être souple avec les sections faisant partie ou non des spécifications fonctionnelles?

### 1. ANALYSE DES BESOINS CLIENT

	Q: Ici, il me semble qu il me faut plus de contenu que celui proposé par la trame (exemple: faire un genre de benchmark pour que je puisse proposer une solution adaptée) non?

#### 1.1. *GÉNÉRALITÉS*

> rappel de l'énoncé succinct

	Q: Même gnere de question que la précédente: Cela va dans le cahier des charges normalement ? Du coup, tu intègre ça au specification fonctionnelle?

Moi: Développeur d’application junior  
Société :« IT Consulting & Development »  
Responsable : Alexandra  
Client : OC Pizza (Groupe de pizzeria)  
Interlocuteur client : Lola (Co-fondatrice)  
Objet :Besoin d’un système de gestion pour ces restaurants. Elle n’a pas trouvé son bonheur parmi les logiciels existants.  


#### 1.2. *CONTEXTE*
* « OC Pizza » est un jeune groupe de pizzeria en croissance.
* Frank et Lola sont les fondateur.
* « OC Pizza » est spécialisé dans la vente en livraison et à emporté
* « OC Pizza » à 5 points de ventes.
* « OC Pizza » prévoit d’avoir 8 points de ventes d’ici 6 mois.
* Le système informatique de « OC Pizza » est obsolète car il ne permet pas une gestion centralisée de toutes les pizzerias.
* Il est difficile pour les responsables de savoir ce qu’il se passe dans les points de ventes.
* Les livreurs ne peuvent pas indiquer qu’une livraison est effectuée en direct.

#### 1.3. *BESOIN EXPLICITE*
 
* Être plus efficace dans la gestion des commandes :
	*  Réception commande
	*  Préparation produit
	*  Livraison
* Suivre en temps réel les commandes :
	*  Passées
	*  En préparation
	*  En livraison
* Suivre en temps réel le stock disponible pour savoir quelle pizza peuvent encore être réalisées
* Proposer un site internet pour que les clients puissent :
	*  commander en ligne en plus de pouvoir téléphoner et commander sur place.
	*  Payer en ligne ou à la livraison
	*  Modifier ou annuler la commande tant que celle-ci n’a pas été préparée.
* Proposer un aide – mémoire aux pizzaiolo indiquant la recette de chaque pizza
* Date de livraison : Dans 6 mois.

#### 1.4. *BESOIN IMPLICITE*

* une application fixe pour le travail à la pizzeria
* une application mobile:
	* pour le livreur pour qu il puisse confimer la livraison effectuée.
	* pour le client.

		Q: Moins implicte non?

* la recette des pizzas doit être standardisée pour anticiper les stocks disponibles
* le client doit s'identifier (obligatoire car paiement possible a la livraison i.e. apres la préparation de la pizza)
 
#### 1.5. *BENCHMARK*
m’inspirer de agile
Me permet de faire un impact mapping plus solide.

#### 1.6. *CONSIDERATION MARKETING*

##### 1.5.1. PERSONA

> réaliser des profils personas vous permettant d'identifier les fonctionnalités implicites

	Q: Dans "Consideration marketing en cycle en v".

Pesona Min : Utilisateur occasionel
Persona Max : Utilisateur fidelisé.

##### 1.5.2. AUTRES CONSIDERATIONS MARKETING (optionnel)
* référencement
* branding
* charte éditoriale
* plan de lancement

#### 1.7. *IMPACT MAPPING*

> Réaliser l'impact mapping et expliquer en quoi c'est utile lors de la conception d'une documentation fonctionnelle - en quoi cela vous a-t-il aider ?

	Q: Selon cascade en V ça va dans les spécificités fonctionnelles
	Q: C’est çà a quoi fait reference  "pense à modéliser le processus de prise de commande" dans la fiche mission de OC?

### 2. SPECIFICATIONS FONCTIONNELLES

#### *2.1. DIAGRAMME DE CONTEXTE*

> Identification des acteurs & explications sur chacun d'entre eux.

[mon diagramme test]("data/test.jpg")

UML : diagramme de contexte

#### *2.2. LISTING DES FONCTIONNALITÉS*

> Lister l'ensemble des fonctionnalités. Une fois fait, regrouper celles-ci en les mettant en couleur (l'idée est de regrouper celles qui semblent concerner les même sujets)

	Q: En fait, c’est la liste de mes cas d’utilisations ?
	Q: est ce que je peux pas mettre ca juste avant l'impact mapping

#### *2.3. DIAGRAMME DE PACKAGE*

> Chaque couleur utilisée plus haut représente un package. Donner un nom à votre groupement et votre package est prêt.

	Q: Pour la logique de création des packages ok de mettre package après Le listing des fo ctionnalité. Mais pour le rendu final, ça decvrait pas aller plutot avant: Diagramme de contexte > Diagramme de package > Liste des fonctionnalités > Diagramme des cas d'utilisation?

UML : diagramme de package


##### 2.3.1. - Package 1
###### 2.3.1.1. - Diagramme de cas d'utilisation 1 (Use case) :

> réaliser un use case reprenant l'ensemble des fonctionnalités listées de la couleur de votre package

	Q: Je dois réaliser un seul use case?.

UML : diagramme cas d’utilissation

###### 2.3.1.2. - Scenario de cas d'utilisation 1 (Use case) :

> Réaliser un ou plusieurs scénarios pour chaque use case. L'idée étant que vos scénarios doivent balayer l'ensemble des "bulles" de votre cas d'utilisation.

	Q:  UML, Description textuelle des cas d »utilisation i.e. « la fiche descriptive » :
			- Identification
			- Description du scenario
			- Fin et post conditions
			- Compléments
		Ou :
			- Utiliser les user stories ?


##### 2.3.2. - Package 2 ...


#### *2.4. CYCLE DE VIE D'UNE COMMANDE*

> Réaliser un diagramme d'activité qui représente l'ensemble du cycle de vie d'une commande, de sa création à sa finalisation.  
> Attention : Ceci est un système d'entonoir a chaque fois que vous ajouter une nouvelle information (par exemple un nouvel acteur lors de l'explication des package), vous devrez remonter sur l'ensemble des parties du document pour vous assurer que vous ajouterez ce nouvel acteur dans tous vos précédents schémas.  
> Tips : Pour les scénarios, bien utiliser la partie finale de "question ouverte" pour démontrer les fonctionnalités non obligatoires mais que vous pouvez imaginer. Cela permettra de démontrer votre questionnement sur le projet et que vous êtes capable de voir plus loin que ce que l'on vous demande, sans pour autant nécessiter de tout représenter dans vos diagrammes UML !

	Q : Pas compris la partie tips

### 2. SPECIFICATION TECHNIQUES

> Ne cherchez pas trop loin, les attentes sont :
> * Serveur web (OVH par exemple)
> * Python & Django
> * HTML / CSS / JS
>Pour chacune des informations ci-dessus, trouvez une source sur le net justifiant de la renommée et de la pertinence de ces choix, et intégrez-les à votre document de présentation de cette partie.

Scorecard  : methode de la cascade en V

	Q: Diagramme de classe ? Diagramme de déploiement ?
