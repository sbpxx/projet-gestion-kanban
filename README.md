# Application de Gestion de Projet (Type Trello/Jira)

## Description
Application web de gestion de projet avec tableaux Kanban, gestion des tâches en temps réel, notifications par email et historique des modifications.

## Fonctionnalités

### 1. Tableaux Kanban
- Création et gestion de tableaux personnalisés
- Colonnes configurables
- Déplacement des tâches par drag & drop

### 2. Gestion des Tâches
- Création, modification et suppression de tâches
- Assignation aux membres de l'équipe
- Niveaux de priorité (Basse, Moyenne, Haute, Critique)
- Définition de deadlines
- Commentaires et discussions

### 3. Notifications
- Notifications par email automatiques
- Alertes pour les deadlines approchantes
- Notifications de changements d'état

### 4. Historique
- Suivi complet des modifications
- Traçabilité des actions utilisateurs
- Journal d'audit

### 5. Temps Réel
- Mises à jour instantanées via WebSocket
- Synchronisation entre utilisateurs

## Stack Technique

### Backend
- **Java** 17+
- **Spring Boot** 3.x
  - Spring Web (API REST)
  - Spring Data JPA
  - Spring Security
  - Spring WebSocket
  - Spring Mail

### Base de Données
- PostgreSQL (recommandé) ou MySQL

### Build
- Maven ou Gradle

## Structure du Projet

```
projet-gestion-kanban/
├── src/
│   ├── main/
│   │   ├── java/com/gestion/projet/
│   │   │   ├── model/
│   │   │   ├── repository/
│   │   │   ├── service/
│   │   │   ├── controller/
│   │   │   ├── websocket/
│   │   │   ├── config/
│   │   │   └── dto/
│   │   └── resources/
│   └── test/
├── docs/
│   └── guide-java-springboot.pdf
├── pom.xml
└── README.md
```

## Installation

Instructions à venir...

## Utilisation

Instructions à venir...

## Contributeurs

Projet personnel de développement

## Licence

À définir
