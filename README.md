# tp2_sir
* TP réalisé par le binôme SYLLA MOHAMED LAMINE et LE QUANG. 
* Nous avons utilisé un template de projet maven pour la construction d’application autonome utilisant JPA, hibernate et hsqldb, à partir du lien suivant : https://goo.gl/ofZbOu

## Objectifs
* Comprendre les mécanismes de JPA
* Réaliser une application en utilisant JPA en se plaçant dans un cadre classique de développement sans serveur d’application au départ.

## Sujet
L’objectif de ce projet est de construire une application type réseau social permettant de comparer sa consommation électrique avec ses amis, ses voisins, … dans la lignée de opower. 

## Persistances des instances
* Création des entitées (@@Entity)
* Création de l'id pour chaque instance persistante (@Id, @GeneratedValue)
* Création de liens entre les entitées (@OneToMany, @ManyToOne, @ManyToMany)
* Héritage (@Inheritance)

## Utilisation de JPA
Voir JpaTest.java
* Création de données en utilisant les Entity et les méthodes de JPA (avec 'tx.begin(); tx.commit();')
* Création de requêtes de sélection pour afficher les données dans la BDD.
	
## Question 7
Le join fetch est le plus efficace.
* Join Fetch = 0,370 s
* N+1 Select = 16,810 s
	
