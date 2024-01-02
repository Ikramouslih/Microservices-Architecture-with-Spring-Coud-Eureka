# JEE-Activite-Pratique-3
 
L'objectif de cette activité est de créer une application basée sur une architecture micro-service qui permet de gérer les factures contenant des produits et appartenant à un client.

### Travail à faire ###

1. Créer le micro-service customer-service qui permet de gérer les client;
2. Créer le micro-service inventory-service qui permet de gérer les produits;
3. Créer la Gateway Spring cloud Gateway;
4. Configuration statique du système de routage;
5. Créer l'annuaire Eureka Discrovery Service;
6. Faire une configuration dynamique des routes de la gateway;
7. Créer le service de facturation Billing-Service en utilisant Open Feign;
8. Créer un client Web Angular (Clients, Produits, Factures).
=> Vidéos à utiliser comme ressources : 
- https://www.youtube.com/watch?v=hVlEoKQG_2E.
- https://www.youtube.com/watch?v=XEzBA3yIII8

### Les dépendences utilisées ### 

- **spring-boot-starter-actuator**  : Ajoute des fonctionnalités prêtes pour la production pour surveiller et gérer l'application.
- **spring-boot-starter-data-jpa** : Fournit un support pour Spring Data JPA pour l'accès à la base de données.
- **spring-boot-starter-data-rest** : Implémente Spring Data REST pour exposer les référentiels JPA en tant que services RESTful.
- **spring-boot-starter-hateoas** : Permet la construction de services RESTful pilotés par l'hypermedia.
- **spring-boot-starter-web** : Fournit des capacités web et RESTful de base.
- **spring-cloud-starter-netflix-eureka-client** : Intègre l'application avec Eureka pour l'enregistrement et la découverte des services.
- **spring-cloud-starter-netflix-eureka-server** : Implémente le serveur Eureka pour la découverte des services.
- **spring-cloud-starter-openfeign** : Permet Feign, un client de service web déclaratif.
- **h2** : Une base de données en mémoire pour le développement et les tests.
- **lombok** : Une bibliothèque qui simplifie le code Java en fournissant des annotations pour réduire le code redondant.
- **spring-boot-starter-test** : Ajoute un support de test pour l'application Spring Boot.
- **spring-cloud-starter-gateway** : Fournit des capacités de routage et de filtrage pour une passerelle Spring Cloud.

# Tests

