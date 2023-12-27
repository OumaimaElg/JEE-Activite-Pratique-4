# JEE-Activite-Pratique-4


L'objectif de cette activite est de créer une application de e-commerce basée sur une architecture de microservices. Le backend a été développé en utilisant le framework Spring Boot en intégrant Vault pour garantir le traitement sécurisé des informations sensibles et Consul pour la découverte des services et la configuration centralisée, tandis que le frontend a été implémenté avec Angular.

### Travail à faire ###

Créer une application de e-commerce basée sur les micro services :
1. Consul Discovery;
2. Spring Cloud Config;
3. Spring Cloud Gateway;
4. Customer-service;
5. Inventory Service;
6. Order Service;
7. Consul Config (Billing Service);
8. Vault (Billing Service);
9. Frontend Web avec Angular.

## Vidéos ressources : ##
- Part 1- https://www.youtube.com/watch?v=LPdfVmllSQo
- Part 2 : https://www.youtube.com/watch?v=L0mdrY36tpk
- Part 3 : https://www.youtube.com/watch?v=L36O1edFPJE
- Part 4 : https://www.youtube.com/watch?v=aQRgO2OxC0w
- Part 5 : https://www.youtube.com/watch?v=iMCjDRUXoeM

  ###Dépendences utilisées ### 

- **Spring Boot Starter Actuator** : Active les fonctionnalités prêtes pour la production, telles que les vérifications de santé et les points de surveillance, pour une application Spring Boot.
- **Spring Boot Starter Web** : Fournit des composants essentiels pour la construction d'applications web avec Spring MVC.
- **Spring Cloud Starter Consul Config** : Intègre Consul en tant que source de configuration pour les applications Spring Cloud.
- **Spring Cloud Starter Consul Discovery** : Active l'enregistrement et la découverte de services à l'aide de Consul dans un environnement Spring Cloud.
- **Spring Cloud Starter Vault Config** : Intègre HashiCorp Vault en tant que source de configuration pour les applications Spring Cloud.
- **Project Lombok** : Une bibliothèque qui simplifie le code Java en fournissant des annotations pour générer du code répétitif, tel que les getters, setters et constructeurs.
- **Spring Boot Starter Test** : Inclut les dépendances pour tester les applications Spring Boot, y compris JUnit et d'autres outils de test.
- **Spring Cloud Config Server** : Fournit un serveur de configuration centralisé pour les systèmes distribués, permettant la configuration externalisée.
- **Spring Boot Starter Data JPA** : Simplifie la configuration des référentiels Spring Data JPA pour l'accès aux données.
- **Spring Boot Starter Data REST** : Permet la création rapide d'API RESTful en utilisant les référentiels Spring Data.
- **H2 Database (runtime)** : Une base de données en mémoire utilisée pendant le développement et les tests.
- **Spring Cloud Starter Gateway** : Fournit les éléments essentiels pour la construction de passerelles API dans un environnement Spring Cloud.
- **Spring Cloud Starter OpenFeign** : Simplifie l'intégration de clients REST déclaratifs dans une application Spring Cloud.
