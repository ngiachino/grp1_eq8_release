# Liste des tâches du Sprint 2

|  ID  |  Description |   Definition of Done   |   US correspondante   |   Durée (jours/homme)    | Développeurs | Avancement |
|:----:|:-------------|:----------------------:|:---------------------:|:------------------------:|:------------:|:----------:|
|T1|Gestion de l'ouverture de la page du projet correspondant en cas de clique sur le nom du projet depuis la page de profil.|En cas de clique sur le nom d'un projet dans la liste des projets de la page de profil, l'utilisateur doit être redirigé vers la page de projet correspondante|US3|0.5|Arthur|Done|
|T2|Gestion du retour à la page de profil depuis n'importe quel endroit du site, lorsque l'utilisateur clique sur le nom du site :"GoProject".(à partir du moment où l'utilisateur est connecté).|Depuis n'importe quelle page (sauf la page de connexion/inscription), l'utilisateur peut revenir à sa page de profil en cliquant sur "GoProject", en tête de page.|US4|0.5|Nicolas|Done|
|T3|Gestion de la déconnexion et de la redirection vers la page d'index depuis n'importe quel endroit du site (Sauf la page de connexion/inscription).|L'utilisateur pourra cliquer sur "deconnexion" à tout endroit du site et sera redirigé vers la page de connexion/inscription. Ses données de session seront supprimées.|US24|0.5|Amel|Done|
|T4|Liste des membres d'un projet avec un champ pour entrer le nom du membre à ajouter, avec un bouton supprimer à coté du nom d'un membre pour le sortir du projet. Il n'y aura pas de bouton supprimer pour le créateur du projet.|Sur la page du projet, il y aura un tableau avec la liste des membres déjà ajoutés, un champ pour en ajouter et un bouton pour supprimer un membre (sauf pour le créateur du projet).|US25,US26,US27|0.5|Nicolas|Done|
|T5|Mettre en place l'ajout et la suppression d'un membre. Pour l'ajout, il suffira de remplir le champ "name" et de valider. Il faudra alors vérifier que l'utilisateur existe et qu'il n'est pas déjà dans le projet. Si l'utilisateur peut être ajouté, alors ce projet sera ajouté à sa liste de projet.|Un membre pourra ajouter un utilisateur au projet. Celui-ci sera ajouté à la liste et il pourra accéder à la page du projet correspondant. Le bouton supprimer, sortira l'utilisateur de la liste. Il n'aura alors plus accès au projet.|US25,US26,US27|0.5|Arthur, Nicolas|Done|
|T6|Page des issues avec la liste des issues déjà créés (Numéro de l'issue, description, priorité, difficulté) avec un bouton modifier et supprimer pour chaque issue. Ainsi qu'une ligne réservée à la saisie d'une nouvelle issue avec tous les champs énoncés précedemment (N.B : Numéro de l'issue créé automatiquement,Priorité : HIGH/MEDIUM/LOW) et un bouton créer pour valider l'issue.|Sur la page issues, il y aura un tableau avec les colonnes décrites précedemment ainsi qu'une ligne dédiée à l'ajout d'issue. (La gestion des actions se fera dans la task suivante).|US5,US6,US7|0.5|Nicolas|Done|
|T7|Mettre en place les fonctionnalités d'ajout, de suppression et de modification d'issue. Pour l'ajout et la modification, afficher un modal avec les champs à compléter. Le bouton supprimer, supprimera directement l'issue. Pour la modification, les champs du modal seront déjà remplis avec les informations de l'issue, l'utilisateur pourra ainsi les modifier sans avoir à tout réécrire. Gérer les réquetes avec la base de données pour mettre à jour la liste des issues en conséquence.|L'utilisateur pourra créer une issue, celle-ci s'affichera alors dans la liste. Il pourra également modifier ou supprimer une issue. La liste se mettra alors à jour, en conséquence|US5,US6,US7|1|Nicolas|Done|
|T8|Page des sprints avec tous les sprints (sous forme de cards) déjà créés (Nom du sprint, date de début, date de fin) avec un bouton modifier et supprimer pour chaque sprint. Ainsi qu'un bouton "Créer un sprint" qui ouvrira un modal demandant les champs à remplir.|Sur la page Sprints, il y aura tous les sprints (ajoutés manuellement à la BDD en attendant la mise en place de la prochaine task) avec des boutons supprimer et modifier pour chaque sprint. Ainsi qu'un bouton "Créer un Sprint" en haut de la page|US8,US9,US10|0.5|Arthur,Nicolas|Done|
|T9|Mettre en place les fonctionnalités d'ajout, de suppression et de modification de sprint. Pour l'ajout et la modification, afficher un modal avec les champs à compléter. Le bouton supprimer, supprimera directement le sprint. Pour la modification, les champs du modal seront déjà remplis avec les informations du sprint, l'utilisateur pourra ainsi les modifier sans avoir à tout réécrire. Gérer les réquetes avec la base de données pour mettre à jour les sprints en conséquence.|L'utilisateur pourra créer un sprint, celle-ci s'affichera alors sous forme de card, sur la page. Il pourra également modifier ou supprimer un sprint. les sprints se mettront à jour, en conséquence|US8,US9,US10|1|Arthur,Amel|Done|
|T10|Page des tâches avec la liste des tâches déjà créés (Nom de la tâche, description, Definition of Done, US correspondate(s), durée, développeurs assignés, avancement) avec un bouton modifier et supprimer pour chaque tâche. Ainsi qu'une ligne réservée à la saisie d'une nouvelle tâche avec tous les champs énoncés précedemment (N.B : Avancement : TO DO, ON GOING, DONE) et un bouton créer pour valider la tâche.|Sur la page tâche, il y aura un tableau avec les colonnes décrites précedemment ainsi qu'une ligne dédiée à l'ajout de tâche. (La gestion des actions se fera dans la task suivante).|US11,US12,US13|0.5|Amel|On Going|
|T11|Mettre en place les fonctionnalités d'ajout, de suppression et de modification dde tâche. Pour l'ajout et la modification, afficher un modal avec les champs à compléter. Le bouton supprimer, supprimera directement la tâche. Pour la modification, les champs du modal seront déjà remplis avec les informations de de la tâche, l'utilisateur pourra ainsi les modifier sans avoir à tout réécrire.Pour l'ajout et la modification, l'utilisateur pourra séléctionner/déselectionner un (ou plusieurs) développeur à assigner ainsi qu'une (ou plusieurs) issue correspondante.  Gérer les réquetes avec la base de données pour mettre à jour la liste des tâches en conséquence.|L'utilisateur pourra créer une tâche, celle-ci s'affichera alors dans la liste. Il pourra également modifier ou supprimer une tâche. La liste se mettra alors à jour, en conséquence|US11,US12,US13|1.5|Amel|Done|
|T12|Page des releases avec la liste des releases déjà créés (Version de la release, lien vers la release, description (optionnel), date) avec un bouton modifier et supprimer pour chaque release. Ainsi qu'une ligne réservée à la saisie d'une nouvelle release avec tous les champs énoncés précedemment et un bouton créer pour valider la release.|Sur la page releases, il y aura un tableau avec les colonnes décrites précedemment ainsi qu'une ligne dédiée à l'ajout de larelease. (La gestion des actions se fera dans la task suivante).|US14,US15|0.5|Arthur,Amel|Done|
|T13|Mettre en place les fonctionnalités d'ajout, de suppression et de modification de release. Pour l'ajout et la modification, afficher un modal avec les champs à compléter. Le bouton supprimer, supprimera directement la release. Pour la modification, les champs du modal seront déjà remplis avec les informations de la release, l'utilisateur pourra ainsi les modifier sans avoir à tout réécrire. Gérer les réquetes avec la base de données pour mettre à jour la liste des releases en conséquence.|L'utilisateur pourra créer une release, celle-ci s'affichera alors dans la liste. Il pourra également modifier ou supprimer une release. La liste se mettra alors à jour, en conséquence|US14,US15|1|Arthur|Done|
|T14|Page des tests avec la liste des tests déjà créés (Description du test, Etat du test, date du dernier lancement) avec un bouton modifier et supprimer pour chaque test. Ainsi qu'une ligne réservée à la saisie d'un nouveau test avec tous les champs énoncés précedemment (N.B : Etat : TO TEST/SUCCESS/FAILURE) et un bouton créer pour valider le test.|Sur la page tests, il y aura un tableau avec les colonnes décrites précedemment ainsi qu'une ligne dédiée à l'ajout de test. (La gestion des actions se fera dans la task suivante).|US16,US17,US18|0.5|Arthur|To Do|
|T15|Mettre en place les fonctionnalités d'ajout, de suppression et de modification de test. Pour l'ajout et la modification, afficher un modal avec les champs à compléter. Le bouton supprimer, supprimera directement le test. Pour la modification, les champs du modal seront déjà remplis avec les informations du test, l'utilisateur pourra ainsi les modifier sans avoir à tout réécrire. Gérer les réquetes avec la base de données pour mettre à jour la liste des tests en conséquence.|L'utilisateur pourra créer une test, celle-ci s'affichera alors dans la liste. Il pourra également modifier ou supprimer une test. La liste se mettra alors à jour, en conséquence|US16,US17,US18|1|Amel|To Do|
|T16|Page des documents avec la liste des documents déjà créés (Titre du document, lien pour télécharger le document, date de la dernière modification du document) avec un bouton modifier et supprimer pour chaque document. Ainsi qu'une ligne réservée à la saisie d'un nouveau document avec tous les champs énoncés précedemment (N.B : pour le lien du document, l'utilisateur devra pouvoir séléctionner un document sur son ordinateur) et un bouton créer pour valider le document.|Sur la page documents, il y aura un tableau avec les colonnes décrites précedemment ainsi qu'une ligne dédiée à l'ajout de document. (La gestion des actions se fera dans la task suivante).|US19,US20,US21|0.5|Nicolas|To Do|
|T17|Mettre en place les fonctionnalités d'ajout, de suppression et de modification de document. Pour l'ajout et la modification, afficher un modal avec les champs à compléter. Le bouton supprimer, supprimera directement le document. Pour la modification, les champs du modal seront déjà remplis avec les informations du document, l'utilisateur pourra ainsi les modifier sans avoir à tout réécrire. Pour le lien de téléchargement du document, l'utilisateur choisira un document sur son ordinateur. Ce document sera sauvegardé par le site. Le lien de téléchargement permettra de le télécharger. Gérer les réquetes avec la base de données pour mettre à jour la liste des documents en conséquence.|L'utilisateur pourra créer une document, celle-ci s'affichera alors dans la liste. Il pourra également modifier ou supprimer une document. La liste se mettra alors à jour, en conséquence|US19,US20,US21|1|Arthur,Amel|To Do|
