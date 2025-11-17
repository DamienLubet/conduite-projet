# Site de gestion de projet

Le but de ce projet est de développer une application web de gestion de projet.
Le site contiendra les fonctionnalités suivantes :

- Authentification des utilisateurs
- Gestion des projets
- Gestion des User Stories et des tâches
- Gestion des sprints
- Gestion des versions
- Gestion des tests
- Gestion de la documentation

## Architecture technique

L'application sera développée en utilisant les technologies suivantes :

- Frontend : React.js + Vite
- Backend : Node.js avec Express pour l'API REST, Mongoose pour la gestion de la base de données
- Authentification : JWT (JSON Web Tokens)
- Base de données : MongoDB
- Documentation : Markdown
- Gestion de versions : Git avec GitHub
- Tests : Jest

## Backlog

### Authentification des utilisateurs

- US1 - En tant que visiteur, je souhaite m’enregistrer et me connecter afin de gérer mes projets. ( Priorité: Haute | Story point: 5)
  - T1.1 - Créer la table "User" dans la base de donnée
  - T1.2 - Créer les pages d'inscription et de connexion (email, mot de passe).
  - T1.3 - Implémenter la logique d’enregistrement et d’authentification
  - T1.4 - Permettre la déconnexion de l’utilisateur et la redirection vers la page d’accueil.

### Gestion des projets

- US2 - En tant qu’utilisateur, je souhaite créer un nouveau projet afin de commencer à organiser mon travail. ( Priorité: Haute | Story point: 5)
  - T2.1 - Créer la table "Project" dans la base de donnée
  - T2.2 - Créer une page/formulaire de création pour un projet avec les champs nécessaires (nom)
  - T2.3 - Implémenter la logique de création du projet.
  - T2.4 - Redirection vers la page du projet après sa création
- US3 - En tant qu’utilisateur, je souhaite visualiser la liste de mes projets afin de pouvoir y accéder facilement. ( Priorité: Moyenne | Story point: 2)
  - T3.1 - Créer une page listant les projets de l'utilisateur.
  - T3.2 - Implémenter la récupération des projets depuis la base de donnée.
- US4 - En tant qu’utilisateur, je souhaite modifier/supprimer un projet  afin de les tenir à jour. ( Priorité: Moyenne | Story point: 3)
  - T4.1 - Créer une page pour l'édition de projet.
  - T4.2 - Implémenter la logique de modification et de suppression des projets
  - T4.3 - Gérer la mise à jour de la base de donnée lors des modifications.
- US5 - En tant que product owner, je souhaite gérer les collaborateurs d’un projet (ajout, suppression, modification des rôles). ( Priorité: Moyenne | Story point: 5)
  - T5.1 - Créer une interface pour rechercher et inviter des utilisateurs existants.
  - T5.2 - Définir les rôles possibles (admin, membre, lecteur).
  - T5.3 - Implémenter la logique de gestion des collaborateurs et des permissions.

### Gestion des User Stories

- US6 - En tant qu’utilisateur, je souhaite ajouter des User Stories à mon projet afin de décrire les fonctionnalités à développer. ( Priorité: Haute | Story point: 5)
  - T6.1 - Créer la table "UserStories" dans la base de donnée.
  - T6.2 - Créer un formulaire de création des User Stories avec les champs nécessaire (titre).
  - T6.3 - Implémenter la logique de création des US.
- US7 - En tant qu’utilisateur, je souhaite modifier ou supprimer une User Story afin de la mettre à jour. ( Priorité: Moyenne | Story point: 3)
  - T7.1 - Créer une interface pour l'édition et la suppression des User Stories.
  - T7.2 - Implémenter la logique de mise à jour et de suppression des User Stories
  - T7.3 - Ajouter la possibilité de modifier la priorité (“haute”, “moyenne”, “basse”) et les story points.
- US8 - En tant qu’utilisateur, je souhaite visualiser la liste des User Stories d’un projet afin de suivre leur avancement. ( Priorité: Moyenne | Story point: 2)
  - T8.1 - Créer une page listant les User Stories du projet.
  - T8.2 - Implémenter la récupération des User Stories du projet.
  - T8.3 - Afficher les informations principales des User Stories (numéro, titre, priorité, story_points)
  
### Gestion des tâches

- US9 - En tant qu’utilisateur, je souhaite découper mes User Stories en tâches afin de mieux planifier et suivre l’avancement du développement. ( Priorité: Haute | Story point: 5)
  - T9.1 - Créer la table "Task" dans la base de donnée.
  - T9.2 - Créer un formulaire de création de tâche avec les champs nécessaires (description)
  - T9.3 - Implémenter la logique de création de tâche
- US10 - En tant qu’utilisateur, je souhaite modifier une tâche (description, responsable, statut) afin de tenir à jour son avancement. ( Priorité: Moyenne | Story point: 3)
  - T10.1 - Créer une interface d’édition d’une tâche existante.
  - T10.2 - Implémenter la logique d’attribution d’une tâche à un collaborateur.
  - T10.3 - Implémenter la modification du statut d’une tâche (“à faire”, “en cours”, “terminée”).
- US21 - En tant qu’utilisateur, je souhaite visualiser la liste des tâches associées à une User Story afin de suivre leur avancement. ( Priorité: Moyenne | Story point: 2)
  - T21.1 - Créer une page listant les tâches d’une User Story.
  - T21.2 - Implémenter la récupération des tâches associées à une User Story.
  - T21.3 - Afficher les informations principales des tâches (description, responsable, statut).

### Gestion des sprints

- US11 - En tant qu’utilisateur, je souhaite créer un sprint afin de planifier le développement des User Stories. ( Priorité: Moyenne | Story point: 3)
  - T11.1 - Créer la table "Sprint" dans la base de donnée.
  - T11.2 - Créer une page/formulaire de création de sprint (numéro) avec un champ pour la durée
  - T11.3 - Implémenter la création de sprint.
- US12 - En tant qu’utilisateur, je souhaite visualiser la liste des sprints d’un projet afin de suivre leur avancement. ( Priorité: Moyenne | Story point: 2)
  - T12.1 - Créer une page affichant tout les sprints
  - T12.2 - Implémenter la récupération des Sprints du projet
  - T12.3 - Afficher les information principales du sprint (numéro, User Story, durée)
- US13 - En tant que product owner ou Scrum Master, je souhaite assigner des User Stories à un sprint afin de les organiser. ( Priorité: Moyenne | Story point: 3)
  - T13.1 - Créer un page pour la gestion d'un sprint
  - T13.2 - Ajouter la possibilité de modifier la durée et d'assigner des User Stories.
  - T13.3 - Implémenter la logique d'assignation des User Stories au sprint.
- US14 - En tant que Scrum Master, je souhaite gérer le cycle de vie d'un Sprint (lancement, fin). ( Priorité: Moyenne | Story point: 3)
  - T14.1 - Ajouter un bouton pour lancer et terminer le Sprint.
  - T14.2 - Implémenter le lancement d'un sprint
  - T14.3 - Implémenter la fin d'un sprint

### Gestion des versions

- US15 - En tant qu'utilisateur, je souhaite ajouter des tags à un projet afin de le versionner. ( Priorité: Moyenne | Story point: 3)
  - T15.1 - Créer la table "version" dans la base de donnée.
  - T15.2 - Ajouter une option de choix de versionning (semantic, date, alpha/beta...)
  - T15.3 - Implémenter la génération automatique d'une version à la fin d'un sprint.
  - T15.4 - Implémenter la logique de l'ajout et mise à jours des versions
- US16 - En tant qu'utilisateur, je souhaite visualiser l'historique des versions d'un projet afin de suivre son évolution. ( Priorité: Basse | Story point: 2)
  - T16.1 - Créer une page affichant l'historique des versions du projet
  - T16.2 - Implémenter la récupération des Versions du projet.
  - T16.3 - Afficher les informations principales des version (tag, description, sprint associé).

### Gestion des tests

- US17 - En tant qu'utilisateur, je souhaite créer des cas de test associés à une tâche afin de définir les critères d'acceptation. ( Priorité: Moyenne | Story point: 3)
  - T17.1 - Créer une table "TestCase" dans la base de donnée.
  - T17.2 - Permettre la création de tests au format Gherkin (Given / When / Then) depuis la page de tâche.
  - T17.3 - Implémenter la logique de création de test.
- US18 - En tant qu'utilisateur, je souhaite supprimer ou modifier un cas de test afin de le tenir à jour. ( Priorité: Basse | Story point: 2)
  - T18.1 - Créer une interface pour l’édition et la suppression des cas de test.
  - T18.2 - Implémenter la mise à jour et la suppression des test.

### Gestion de la documentation

- US19 - En tant qu'utilisateur, je souhaite avoir de la documentation pour mon projet afin de faciliter sa compréhension. ( Priorité: Basse | Story point: 3)
  - T19.1 - Créer une table "Doc" dans la base de donnée.
  - T19.2 - Créer un formulaire d’ajout de documentation (titre, contenu).
  - T19.3 -  Implémenter la logique de création de document.
  - T19.4 - Afficher la documentation associée à un projet sur une page dédiée.
- US20 - En tant qu'utilisateur, je souhaite mettre à jour ou supprimer la documentation de mon projet afin de refléter les changements apportés. ( Priorité: Basse | Story point: 2)
  - T20.1 - Créer une interface d’édition et de suppression pour les documents existants.
  - T20.2 - Implémenter la logique de mise à jour et de suppression.
