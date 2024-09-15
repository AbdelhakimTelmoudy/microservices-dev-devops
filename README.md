# Projet Microservices avec Intégration DevOps

## Description du Projet

Ce projet consiste en une architecture microservices utilisant **Java JEE**, **Spring Boot**, **Docker**, et **Kubernetes**, intégrée avec des pratiques DevOps complètes. L'objectif est de créer une solution évolutive et sécurisée pour la gestion des clients, des produits et des factures.

## Technologies Utilisées

- **Java JEE** : Développement des microservices.
- **Spring Boot** : Création des services backend.
- **Eureka** : Découverte des services.
- **Spring Cloud Gateway** : Routage des requêtes.
- **OpenFeign** : Communication entre services.
- **Keycloak** : Gestion des authentifications et des autorisations (**SSO**).
- **Kafka** : Gestion des événements en temps réel.
- **Angular** : Interface utilisateur.
- **Docker & Docker-Compose** : Conteneurisation et orchestration locale.
- **Kubernetes** : Orchestration et déploiement à grande échelle.
- **Jenkins & GitLab CI** : Automatisation des builds et des déploiements.
- **Prometheus & Grafana** : Surveillance en temps réel.
- **ELK Stack** : Gestion des logs (Elasticsearch, Logstash, Kibana).

## Architecture

![Diagramme de l'Architecture]


*Description du Diagramme* :
- Les microservices interagissent avec **Eureka** pour la découverte des services.
- **Spring Cloud Gateway** gère le routage des requêtes vers les microservices.
- **Keycloak** assure la sécurité des services.
- **Kafka** est utilisé pour les échanges d'événements.
- **Angular** communique avec **Spring Cloud Gateway**.
- **Docker** et **Kubernetes** sont utilisés pour l'orchestration.
- **Jenkins & GitLab CI** automatisent les processus CI/CD.
- **Prometheus & Grafana** assurent la surveillance.
- **ELK Stack** centralise les logs.

## Étapes de Développement

1. **Conception et Planification**
   - Définition des exigences.
   - Conception de l'architecture des microservices.

2. **Développement des Microservices**
   - Création des microservices (Client, Produit, Facturation).
   - Intégration de **Eureka** pour la découverte des services.
   - Configuration de **Spring Cloud Gateway** pour le routage.

3. **Intégration de la Sécurité**
   - Déploiement de **Keycloak** pour l'authentification et l'autorisation.

4. **Communication entre Services**
   - Mise en place de **OpenFeign** pour les appels inter-services.
   - Intégration de **Kafka** pour la gestion des événements.

5. **Développement du Frontend**
   - Création de l'application **Angular** & **React JS**.

6. **Conteneurisation et Orchestration**
   - Création des Dockerfiles.
   - Configuration de **Docker-Compose** pour le développement local.
   - Déploiement avec **Kubernetes**.

7. **Automatisation CI/CD**
   - Configuration des pipelines **Jenkins** et **GitLab CI**.

8. **Surveillance et Gestion des Logs**
   - Intégration de **Prometheus** et **Grafana** pour la surveillance.
   - Mise en place de **ELK Stack** pour la gestion des logs.


