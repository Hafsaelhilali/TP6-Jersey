Ce projet est une application Spring Boot exposant une API RESTful pour la gestion des comptes bancaires. L’API est développée avec JAX-RS (Jersey) pour illustrer l’intégration d’un service REST dans un environnement Spring Boot.

Architecture du projet
<img width="357" height="320" alt="image" src="https://github.com/user-attachments/assets/5edeb380-bde5-4a2f-bcd7-475b2530e7ca" />
Technologies utilisées
Spring Boot (version 3+)

JAX-RS / Jersey pour l’API REST

Spring Data JPA

Hibernate

H2 / MySQL (selon configuration)

Lombok pour réduire le code boilerplate

Maven pour la gestion des dépendances

Lancement de l’application
Cloner le projet

git clone https://github.com/ton-utilisateur/banque-jaxrs.git cd banque-jaxrs

Configurer la base de données
Dans src/main/resources/application.properties :

spring.datasource.url=jdbc:h2:mem:banque spring.h2.console.enabled=true spring.jpa.hibernate.ddl-auto=update
