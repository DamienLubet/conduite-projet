# Tâches 3

## Documentation

- Rédiger la documentation administrative du projet.
- Rédiger la documentation technique pour les développeurs.
- Rédiger la documentation utilisateur pour les utilisateurs finaux.

## Docker de production

- Ajouter les Dockerfile et Docker Compose pour la production.

## Gestion des sprints

- US11 - En tant qu’utilisateur, je souhaite créer un sprint afin de planifier le développement des User Stories.
  - T11.1 - Créer la table "Sprint" dans la base de donnée.
  - T11.2 - Créer une page/formulaire de création de sprint (numéro) avec un champ pour la durée
  - T11.3 - Implémenter la création de sprint.
- US12 - En tant qu’utilisateur, je souhaite visualiser la liste des sprints d’un projet afin de suivre leur avancement.
  - T12.1 - Créer une page affichant tout les sprints
  - T12.2 - Implémenter la récupération des Sprints du projet
  - T12.3 - Afficher les information principales du sprint (numéro, User Story, durée)
- US13 - En tant que product owner ou Scrum Master, je souhaite assigner des User Stories à un sprint afin de les organiser.
  - T13.1 - Créer un page pour la gestion d'un sprint
  - T13.2 - Ajouter la possibilité de modifier la durée et d'assigner des User Stories.
  - T13.3 - Implémenter la logique d'assignation des User Stories au sprint.
- US14 - En tant que Scrum Master, je souhaite gérer le cycle de vie d'un Sprint (lancement, fin).
  - T14.1 - Ajouter un bouton pour lancer et terminer le Sprint.
  - T14.2 - Implémenter le lancement d'un sprint
  - T14.3 - Implémenter la fin d'un sprint

## Gestion des versions

- US15 - En tant qu'utilisateur, je souhaite ajouter des tags à un projet afin de le versionner.
  - T15.1 - Créer la table "version" dans la base de donnée.
  - T15.2 - Ajouter une option de choix de versionning (semantic, date, alpha/beta...)
  - T15.3 - Implémenter la génération automatique d'une version à la fin d'un sprint.
  - T15.4 - Implémenter la logique de l'ajout et mise à jours des versions
- US16 - En tant qu'utilisateur, je souhaite visualiser l'historique des versions d'un projet afin de suivre son évolution.
  - T16.1 - Créer une page affichant l'historique des versions du projet
  - T16.2 - Implémenter la récupération des Versions du projet.
  - T16.3 - Afficher les informations principales des version (tag, description, sprint associé).
