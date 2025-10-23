# Site de gestion de projet

Le but de ce projet est de développer une application web de gestion de projet.
Le site contiendra les fonctionnalités suivantes :

- Gestion des utilisateurs
- Gestion des projets
- Gestion des User Stories et des tâches
- Gestion des sprints
- Gestion des versions
- Gestion des tests
- Gestion de la documentation

## Backlog

### Gestion des utilisateurs

- US1 - En tant que visiteur, je souhaite m’enregistrer comme utilisateur afin de gérer mes projets.
  - T1.1 - Développer la fonctionnalité d'inscription des utilisateurs.
  - T1.2 - Créer une page d’enregistrement avec les champs nécessaires (nom, mot de passe).
  - T1.3 - Sauvegarder les informations de l’utilisateur dans la base de données.
- US2 - En tant qu’utilisateur, je souhaite me connecter à mon compte afin d’accéder à mes projets.
  - T2.1 - Implémenter la logique de connexion des utilisateurs.
  - T2.2 - Créer une page de connexion avec les champs nom et mot de passe.
  - T2.3 - Vérifier les informations d’identification et autoriser l’accès si elles sont correctes.
- US28 - En tant qu'utilisateur, je souhaite que mes informations d'utilisateur soient sauvegardées dans la base de données afin de pouvoir les retrouver après un redémarrage du serveur.
  - T28.1 - Mettre en place la structure de la base de données pour les utilisateurs.
  - T28.2 - Assurer la persistance des données utilisateur entre les sessions.

### Gestion des projets

- US3 - En tant qu’utilisateur, je souhaite créer un nouveau projet afin de commencer à organiser mon travail.
- US4 - En tant qu’utilisateur, je souhaite visualiser la liste de mes projets afin de pouvoir y accéder facilement.
- US5 - En tant qu’utilisateur, je souhaite modifier les informations d’un projet (nom, description, collaborateurs) afin de les tenir à jour.
- US6 - En tant qu’utilisateur, je souhaite ajouter des collaborateurs à mon projet afin qu’ils puissent y participer.
- US7 - En tant qu’utilisateur, je souhaite que mes projets soient sauvegardés dans la base de données, afin de pouvoir les retrouver après un redémarrage du serveur.
- US8 - En tant qu’utilisateur, je souhaite supprimer un projet afin de libérer de l'espace.

### Gestion des User Stories et des tâches

- US9 - En tant qu’utilisateur, je souhaite ajouter des User Stories à mon projet afin de décrire les fonctionnalités à développer.
- US10 - En tant qu’utilisateur, je souhaite modifier ou supprimer une User Story afin de la mettre à jour.
- US11 - En tant qu’utilisateur, je souhaite visualiser la liste des User Stories d’un projet afin de suivre leur avancement.
- US12 - En tant qu’utilisateur, je souhaite prioriser mes User Stories afin d’organiser le développement selon leur importance.
- US13 - En tant qu’utilisateur, je souhaite découper mes User Stories en tâches afin de mieux planifier et suivre l’avancement du développement.
- US14 - En tant qu’utilisateur, je souhaite assigner une tâche à un collaborateur afin qu’il s’en charge.
- US15 - En tant qu’utilisateur, je souhaite modifier le statut d’une tâche (à faire, en cours, terminé) afin de notifier son avancement.
- US16 - En tant qu’utilisateur, je souhaite visualiser la liste des tâches d’une User Story afin de suivre leur avancement.

### Gestion des sprints

- US17 - En tant qu’utilisateur, je souhaite créer un sprint afin de planifier le développement des User Stories.
- US18 - En tant qu’utilisateur, je souhaite assigner des User Stories à un sprint afin de les organiser.
- US19 - En tant qu’utilisateur, je souhaite visualiser la liste des sprints d’un projet afin de suivre leur avancement.
- US20 - En tant qu’utilisateur, je souhaite cloturer un sprint afin de marquer la fin de son développement.

### Gestion des versions

- US21 - En tant qu'utilisateur, je souhaite ajouter des tags à un projet afin de le versionner.
- US22 - En tant qu'utilisateur, je souhaite visualiser l'historique des versions d'un projet afin de suivre son évolution.

### Gestion des tests

- US23 - En tant que testeur, je souhaite créer des cas de test associés à une tâche afin de vérifier son bon fonctionnement.
- US24 - En tant que testeur, je souhaite supprimer ou modifier un cas de test afin de le tenir à jour.

### Gestion de la documentation

- US25 - En tant qu'utilisateur, je souhaite créer de la documentation pour mon projet afin de faciliter sa compréhension.
- US26 - En tant qu'utilisateur, je souhaite mettre à jour la documentation de mon projet afin de refléter les changements apportés.
- US27 - En tant qu'utilisateur, je souhaite supprimer la documentation obsolète de mon projet afin de garder uniquement les informations pertinentes.


