# REDAL – Plateforme de Consultation et Paiement de Factures

Application web développée dans le cadre d'un stage d'initiation chez REDAL, permettant aux clients de consulter et de payer en ligne leurs factures d'eau et d'électricité en toute sécurité.

## Fonctionnalités

- Consultation des factures d'eau et d'électricité
- Paiement sécurisé en ligne
- Gestion de compte client
- Interface utilisateur optimisée pour l'expérience client

## Technologies utilisées

- **Backend :** Java, Spring Boot, Spring Data JPA
- **Frontend :** Thymeleaf, HTML, CSS
- **Base de données :** H2 Database

## Architecture

Le projet suit une architecture MVC classique avec Spring Boot :
- Couche contrôleur pour la gestion des requêtes HTTP
- Couche service pour la logique métier
- Couche repository (Spring Data JPA) pour l'accès aux données
- Templates Thymeleaf pour le rendu des vues

## Lancer le projet en local

```bash
# Cloner le dépôt
git clone https://github.com/siasmae/redal-facturation-webapp.git
cd redal-facturation-webapp

# Lancer avec Maven
mvn spring-boot:run
```

L'application est ensuite accessible sur `http://localhost:8080`.

## Auteur

Asmae Ait Ouali — Étudiante en Master Génie Logiciel et Cloud Computing (GLCC), Université Ibn Toufaïl
