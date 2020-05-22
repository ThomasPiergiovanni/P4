
# PROJET 4

>*L'idée de ce projet est de réalisé un "entonoir" vous permettant de présenter de manière détaillée une conception d'application.*

>**Q**:Ce qui m'est demandé par  Alexandra:
>* Analyser le besoin client
>* Rédiger les spécifications fonctionnelles
>* Produire une orientation des spécificités techniques avec une courte argumentation de la solution technique
>* Dire si la solution part de scratch ou sur la base d’un CMS e-commerce
>Je vois donc:
>* un document Specification Fonctionnelle, qu'il faudrait renommé,  qui est fait est divisé en 2 section) :
>	* Cadre du projet / contexte
>	* Spécifications  Fonctionnelles  
>Ca ressemble presque plus à un [cahier des charges](https://openclassrooms.com/fr/courses/4296701-gerez-un-projet-digital-avec-une-methodologie-en-cascade/4303841-redigez-les-specifications-techniques-de-votre-projet#/id/r-4388329) non?

>**A**:

## SPECIFICATIONS FONCTIONNELLES (Titre a discuter)

> *Pour réaliser le document, voici la trame suggérée :*

>**Q**: Je trouve utile d'ajouter les sections **Besoins explicite**, **Besoins implicite**, **Benchmark** et **Autre considérations marketing**. Ton avis?  
>**A**:

### 1. CADRE DU PROJET

#### 1.1. *GÉNÉRALITÉS*

> *rappel de l'énoncé succinct*

* Moi: Développeur d’application junior  
* Société :« IT Consulting & Development »  
* Responsable : Alexandra  
* Client : OC Pizza (Groupe de pizzeria)  
* Interlocuteur client : Lola (Co-fondatrice)  
* Objet :Besoin d’un système de gestion pour ces restaurants. Elle n’a pas trouvé son bonheur parmi les logiciels existants.  


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

> **Q:** Cette section devrais me permettre de lister mes fonctionnalités et de réaliser un impact mapping plus facilement. Ton avis  
> **A:** 
 
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

> **Q:** Cette section devrais me permettre de lister mes fonctionnalités et de réaliser un impact mapping plus facilement. Ton avis  
> **A:** 

* une application fixe pour le travail à la pizzeria
* une application mobile:
	* pour le livreur pour qu il puisse confimer la livraison effectuée.
	* pour le client.

> **Q:** Avoir une application mobile pour le client c'est moins implicte non?  
> **A:**

* la recette des pizzas doit être standardisée pour anticiper les stocks disponibles
* le client doit s'identifier (obligatoire car paiement possible a la livraison i.e. apres la préparation de la pizza)
* un client habitant a plus de x distance ne pourra être livré sans suplément de prix et devra payer d'avance

 
#### 1.5. *BENCHMARK*

> **Q:** Cela Me permet de faire un impact mapping plus solide a mon avis. Ton opinion?  
> **A:** 

Grandes chaines américaines:
* [Domino's](https://www.dominos.fr/)
* [Pizza Hut](https://www.pizzahut.fr/) 
Grandes chaines Francaise:
* [La Boite à Pizza](https://www.laboiteapizza.com/)
* [Speed Rabbit](https://www.speedrabbitpizza.com/)
* [Pizza Sprint](http://www.pizzasprint.com/)
Plus petite chaines Francaise:


1 - mauvais  
2 - pas terrible
3 - ok  
4 - bien  
5 - tres bien  

##### 1.5.1 DOMINO'S



* **Ergonomie** (navigation, adaptabilité mobile): **5** : Navigation simple. Fixe et mobile ont la meme structure--> facilité pour passer de l'un a l autre
* **Charte éditoriale** (ton, langues): **4** : ton direct clair
* **Charte graphique** (typographie, palette de couleurs) : **4** : clair, images propres, fon envie, couleur identifiable à la marque
* **Fonctionnalités** (ex. système de réservation, newsletter): **5**: incite à la vente, simple d'utilisation et intuitifs
	* **Systeme de commande**: **5**:  a partir de la selection de base à chaque suivant > entree, salades > Dessert > Boissons > PAiemnet
	* **Systeme de paiement: 4**: tous. mais Minimum 15€ et supplément livraison
	* **Newsletter:** n/a
* **Technologie utilisée:**
	* Hebergeur:
		* Microsoft Azur pour NDL, AUS
		* Amazon pour DEU

[*...une commande en progrès chez dominos.fr*](https://github.com/ThomasPiergiovanni/P4/blob/master/data/dominos.jpg)

> **Q:** Comment connaitre les technologies utilisée d'un site? Utilisant inspecteur, console débogueur ou autre?  
> **A:**


**Synthese:**  

**les "+":**  
* Navigation simple et adapatabilité sur pc et mobile (app aussi disponible)
* Syntaxe clair et direct
* Rendu graphique franchisé et propre
* Fonctionnalité du site optimisée, allant à l'essentiel, on s'éloigne pas de la commande, ça incite à la consommation

**les "-":**
* NA

*Notes:
* on peut se connnecter/creer un compte ou simplement saisir son adresse de livraison,
* Minimum de 15 E en livraison.
* --> saisir nom telephone*

##### 1.5.2 PIZZA HUT
...

*Notes:  
Sur le segment de la pizza en livraison, concurrence accrue avec la montée en puissance de Deiveroo, UberEats qui met les indépendant sur ce marché.*


#### 1.6. *CONSIDERATION MARKETING*

##### 1.5.1. PERSONA

> réaliser des profils personas vous permettant d'identifier les fonctionnalités implicites

* Utilisateur extremes
* Utilisateur type

* Caratactérisqiques de chacun:
	* Type utilisateur : age , genre, proffession, catégorie socioprofessionnelle)
	* besoins ou objectifs vis-à-vis du produit ou service
	* critères de choix et d'habitudes
	* façon de naviguer en ligne
	* expertise du domaine


*Notes:
Section placée ici comme dans methodo cascade en V.*


###### 1.5.1.1 UTILISATEUR TYPE HOMME URBAIN CSP

* Type utilisateur :
	* age: 30
	* genre: m
	* nom : Pierre
	* proffession: commercial dans une assurance
	* catégorie socioprofessionnelle: cadre
* besoins ou objectifs vis-à-vis du produit ou service: manger chaud, qui a du gout, pas besoin de cuisiner
* critères de choix et d'habitudes: facilement accessible, rapidement disponible, consome 2 x p/moi, curieux, cherche de nouvelles opportunité
* façon de naviguer en ligne: mobile et pc
* expertise du domaine: par sa curiosité et son pouvoir d'achat, il essaie bcp de pizzas. Capable de comparer --> Qualité

###### 1.5.1.2 UTILISATEUR TYPE MERE DE FAMILLE

* Type utilisateur :
	* age: 42
	* genre: F
	* prenom: Sabrina
	* proffession: employée dans un magasin de pret à porter
	* catégorie socioprofessionnelle: employée
* besoins ou objectifs vis-à-vis du produit ou service: qui plait à tous dans la famille, en quantité suffisante, pas besoin de cuisiner, prix accessible
* critères de choix et d'habitudes: facilement accessible, consome une fois p/semaine le vendredi soir, 
* façon de naviguer en ligne: mobile
* expertise du domaine: moyenne, son expertise est limitée par son budget (elle n 'a pas pu tout essayé). son critère --> Prix


###### 1.5.1.3 UTILISATEUR MAX, L'ACCRO
* Type utilisateur :
	* age: 40
	* genre: H
	* prenom: Joachim
	* proffession: ingénieur informaticien
	* catégorie socioprofessionnelle: cadre
* besoins ou objectifs vis-à-vis du produit ou service: addiction, en quantité suffisante, pas besoin de cuisiner, à ses habitudes, commande toujours pareils
* critères de choix et d'habitudes: facilement accessible, une fois qu'il a trouver qqch a sa convenance, il ne chereche pas plus loin
* façon de naviguer en ligne: fixe 
* expertise du domaine: moyenne, son expertise est limitée par son comportement (il a trouvé quelque chose qui lui plait, il s'y cantone). Son critère --> L'habittude, une affaire qui marche

###### 1.5.1.4 UTILISTAEUR MIN, L'ETUDIANTE
* Type utilisateur :
	* age: 18
	* genre: F
	* prenom: Céline
	* proffession: étudiante
	* catégorie socioprofessionnelle: étudiante
* besoins ou objectifs vis-à-vis du produit ou service: recoit des amis, quantité, prix, veut une présentation soignée
* critères de choix et d'habitudes: commande rarement, qques fois par année max.
* façon de naviguer en ligne: fixe et mobile 
* expertise du domaine: moyene, conosmme peu souvent. Son critère: Les yeux

##### 1.5.2. AUTRES CONSIDERATIONS MARKETING (optionnel)
* référencement
* branding
* charte éditoriale
* plan de lancement

#### 1.7. *IMPACT MAPPING*

> Réaliser l'impact mapping et expliquer en quoi c'est utile lors de la conception d'une documentation fonctionnelle - en quoi cela vous a-t-il aider ?

>**Q:** Selon cascade en V ça va dans les spécificités fonctionnelles. Ton avis?  
>**A:** 

### 2. SPECIFICATIONS FONCTIONNELLES

#### *2.1. DIAGRAMME DE CONTEXTE*

> Identification des acteurs & explications sur chacun d'entre eux.

UML : diagramme de contexte

#### *2.2. LISTING DES FONCTIONNALITÉS*

> Lister l'ensemble des fonctionnalités. Une fois fait, regrouper celles-ci en les mettant en couleur (l'idée est de regrouper celles qui semblent concerner les même sujets)

> **Q**: En fait, c’est la liste de mes cas d’utilisations ?  
> **A**: Non. Un cas d'utilisation aura tout une liste de fonctionnalité


#### *2.3. DIAGRAMME DE PACKAGE*

> Chaque couleur utilisée plus haut représente un package. Donner un nom à votre groupement et votre package est prêt.

UML : diagramme de package


##### 2.3.1. - Package 1

###### 2.3.1.1. - Cas d'utilisation (diagramme) :

> réaliser un use case reprenant l'ensemble des fonctionnalités listées de la couleur de votre package

> **Q**: Je dois réaliser un seul use case?  
> **A**:  

UML : diagramme cas d’utilissation

###### 2.3.1.2. - Cas d'utilisation (scenario) :

> Réaliser un ou plusieurs scénarios pour chaque use case. L'idée étant que vos scénarios doivent balayer l'ensemble des "bulles" de votre cas d'utilisation.

> **Q**: C'est la description textuelle des cas d'utilisation i.e. « la fiche descriptive »?  
> **A**:   

##### 2.3.2. - Package 2 ...


#### *2.4. CYCLE DE VIE D'UNE COMMANDE*

> *Réaliser un diagramme d'activité qui représente l'ensemble du cycle de vie d'une commande, de sa création à sa finalisation.*

> *Attention : Ceci est un système d'entonoir a chaque fois que vous ajouter une nouvelle information (par exemple un nouvel acteur lors de l'explication des package), vous devrez remonter sur l'ensemble des parties du document pour vous assurer que vous ajouterez ce nouvel acteur dans tous vos précédents schémas.*

> *Tips : Pour les scénarios, bien utiliser la partie finale de "question ouverte" pour démontrer les fonctionnalités non obligatoires mais que vous pouvez imaginer. Cela permettra de démontrer votre questionnement sur le projet et que vous êtes capable de voir plus loin que ce que l'on vous demande, sans pour autant nécessiter de tout représenter dans vos diagrammes UML !*

> **Q** : J'ai pas compris la partie tips?  
> **A** : 

### 2. SPECIFICATION TECHNIQUES

> Ne cherchez pas trop loin, les attentes sont :
> * Serveur web (OVH par exemple)
> * Python & Django
> * HTML / CSS / JS
> Pour chacune des informations ci-dessus, trouvez une source sur le net justifiant de la renommée et de la pertinence de ces choix, et intégrez-les à votre document de présentation de cette partie.

Scorecard(methode de la cascade en V).

> **Q**: Tu liste ces composant, mais comment je fais pour savoir que par exemple j'utilise pas de PHP?    
> **A**:

> **Q**: Pas de diagramme de classe? diagramme de déploiement ?  
> **A**


*Ressources:   
https://www.latribune.fr/carrieres/franchises/marche-de-la-pizza-le-formidable-appetit-des-chaines-de-franchise-495485.html  
https://www.observatoiredelafranchise.fr/dossier-franchise/la-livraison-stimule-le-marche-de-la-restauration-1470.html*    
