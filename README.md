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

<img width="960" alt="customer 1" src="https://github.com/Ikramouslih/Microservices-Architecture-with-Spring-Coud-Eureka/assets/60039200/62818cf9-e177-4dca-86c3-81173359fea4">

<img width="960" alt="customer projection" src="https://github.com/Ikramouslih/Microservices-Architecture-with-Spring-Coud-Eureka/assets/60039200/0f577c96-e510-499e-b8a1-55b47bd542ad">

<img width="960" alt="customers gateway 8888" src="https://github.com/Ikramouslih/Microservices-Architecture-with-Spring-Coud-Eureka/assets/60039200/6c2dc1db-e1a5-4969-85dd-a9ab55bf7a28">

<img width="960" alt="customers" src="https://github.com/Ikramouslih/Microservices-Architecture-with-Spring-Coud-Eureka/assets/60039200/f72d86ec-0db3-4e6b-8241-f099d366505d">

<img width="960" alt="eureka" src="https://github.com/Ikramouslih/Microservices-Architecture-with-Spring-Coud-Eureka/assets/60039200/58e17371-5ae2-4cff-8363-ba81da81c79f">

<img width="960" alt="products" src="https://github.com/Ikramouslih/Microservices-Architecture-with-Spring-Coud-Eureka/assets/60039200/50f55180-52cc-41e9-8aea-5764a958bb45">

<img width="960" alt="products gateway 8888" src="https://github.com/Ikramouslih/Microservices-Architecture-with-Spring-Coud-Eureka/assets/60039200/3916e961-0f58-480b-aa4e-6c382bed6d06">

<img width="960" alt="Screenshot 2023-12-29 201730" src="https://github.com/Ikramouslih/Microservices-Architecture-with-Spring-Coud-Eureka/assets/60039200/02dcda34-8ab6-4464-92a2-190f86a8cf6b">

<img width="960" alt="Screenshot 2024-01-02 211748" src="https://github.com/Ikramouslih/Microservices-Architecture-with-Spring-Coud-Eureka/assets/60039200/6933f363-8b63-4284-ac28-8779f60f4531">

<img width="960" alt="Screenshot 2024-01-02 211903" src="https://github.com/Ikramouslih/Microservices-Architecture-with-Spring-Coud-Eureka/assets/60039200/eeed5247-edde-4f48-9a85-6db0a0effb52">



