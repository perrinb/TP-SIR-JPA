# SIR-TPJPA

## Synopsis

Ce TP a pour but de créer un backend en Java (TP2 eet 4).

Ce tp a été réalisé par :
* PERRIN Briac
* RANNOU Nicolas

## Mise en oeuvre (nous avons choisi IntelliJ comme IDE)

Etape 1 : Lancez votre serveur MySql.

Etape 2 : Lancez la classe JpaTest pour ajouter des données à la base.

Etape 3 : Allez dans "Run" -> "Edit configurations" -> "+" -> Séléctionnez "Tomcat Server Local".

Etape 4 : Lancez Tomcat.

Etape 5 : Rendez-vous sur localhost:8080 pour accéder a l'application.

## Partie JPA

Partie contenue dans le package 'domain'.Vous y trouverez les classes du diagram UML données dans le TP2.

## Partie Servlet

Partie contenue dans le package 'servlet'. Vous y trouverez la classe PersonServlet qui permet grâce a une méthode GET et une méthode POST d'afficher l'ensemble des personnes présentes dans la base et d'ajouter des personnes dans la base.

## Partie Objet d'Accès aux Données

Partie contenue dans le package DAO. Vous y trouverez les classes ElectroniqueDeviceDao, HeaterDao, HomeDao, Manager et PersonDao qui permettent de faire le lien entre la base de données et l'application (ajout création supression et modification).

## Partie WebService

Partie contenue dans le package'rest'. Vous y trouverez ElectronicDeviceWS, HeaterWS, HomeWS, PersonWS qui utilisent les classes DAO précédement décrites pour l'affichage des données de la base.





