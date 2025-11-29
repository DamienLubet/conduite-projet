# Tâches 2

## Authentification (finir le sprint 1)

- T1.2 - Créer les pages d'inscription et de connexion (email, mot de passe).
- T1.4 - Permettre la déconnexion de l’utilisateur et la redirection vers la page d’accueil.

## Gestion des projets (finir Sprint 1 + suite)

- US2 - En tant qu’utilisateur, je souhaite créer un nouveau projet afin de pouvoir organiser mon travail.
  - T2.2 - Créer un formulaire de création de projet avec les champs nécessaires (nom, description).
- US3 - En tant qu’utilisateur, je souhaite visualiser la liste de mes projets afin de pouvoir y accéder facilement.
  - T3.1 - Créer une page listant les projets de l'utilisateur.
  - T3.2 - Implémenter la récupération des projets depuis la base de donnée.
- US4 - En tant qu’utilisateur, je souhaite modifier/supprimer un projet  afin de les tenir à jour.
  - T4.1 - Créer une page pour l'édition de projet.
  - T4.2 - Implémenter la logique de modification et de suppression des projets
  - T4.3 - Gérer la mise à jour de la base de donnée lors des modifications.
- US5 - En tant que product owner, je souhaite gérer les collaborateurs d’un projet (ajout, suppression, modification des rôles).
  - T5.1 - Créer une interface pour rechercher et inviter des utilisateurs existants.
  - T5.2 - Définir les rôles possibles (admin, membre, lecteur).
  - T5.3 - Implémenter la logique de gestion des collaborateurs et des permissions.
  
## Gestion des User Stories

- US6 - En tant qu’utilisateur, je souhaite ajouter des User Stories à mon projet afin de décrire les fonctionnalités à développer.
  - T6.1 - Créer la table "UserStories" dans la base de donnée.
  - T6.2 - Créer un formulaire de création des User Stories avec les champs nécessaire (titre).
  - T6.3 - Implémenter la logique de création des US.
- US7 - En tant qu’utilisateur, je souhaite modifier ou supprimer une User Story afin de la mettre à jour.
  - T7.1 - Créer une interface pour l'édition et la suppression des User Stories.
  - T7.2 - Implémenter la logique de mise à jour et de suppression des User Stories
  - T7.3 - Ajouter la possibilité de modifier la priorité (“haute”, “moyenne”, “basse”) et les story points.
- US8 - En tant qu’utilisateur, je souhaite visualiser la liste des User Stories d’un projet afin de suivre leur avancement.
  - T8.1 - Créer une page listant les User Stories du projet.
  - T8.2 - Implémenter la récupération des User Stories du projet.
  - T8.3 - Afficher les informations principales des User Stories (numéro, titre, priorité, story_points)
  
## Gestion des tâches

- US9 - En tant qu’utilisateur, je souhaite découper mes User Stories en tâches afin de mieux planifier et suivre l’avancement du développement.
  - T9.1 - Créer la table "Task" dans la base de donnée.
  - T9.2 - Créer un formulaire de création de tâche avec les champs nécessaires (description)
  - T9.3 - Implémenter la logique de création de tâche
- US10 - En tant qu’utilisateur, je souhaite modifier une tâche (description, responsable, statut) afin de tenir à jour son avancement.
  - T10.1 - Créer une interface d’édition d’une tâche existante.
  - T10.2 - Implémenter la logique d’attribution d’une tâche à un collaborateur.
  - T10.3 - Implémenter la modification du statut d’une tâche (“à faire”, “en cours”, “terminée”).
- US21 - En tant qu’utilisateur, je souhaite visualiser la liste des tâches associées à une User Story afin de suivre leur avancement.
  - T21.1 - Créer une page listant les tâches d’une User Story.
  - T21.2 - Implémenter la récupération des tâches associées à une User Story.
  - T21.3 - Afficher les informations principales des tâches (description, responsable, statut).
