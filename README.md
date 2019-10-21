# Groupe 1 Equipe 8
## Nicolas GIACHINO / Arthur HERMAN / Amel OULD AMARA

-----------------

## Issues

### **Gestion du projet** – Priorité 1

**US1** (Difficulté 1)- En tant que Utilisateur je veux arriver sur ma page d’accueil lorsque je me connecte afin d’avoir accès à ma liste de projets

**US2** (2)- En tant que Utilisateur je veux pouvoir créer un projet afin de pouvoir gérer un projet

**US3** (3)- En tant que Utilisateur je veux pouvoir consulter la liste de mes projets

**US4** (1)- En tant que Utilisateur je veux pouvoir revenir à ma page d’accueil afin d’avoir accès à ma liste de projets
</br></br>

### **Gestion des issues** – Priorité 1

**US5** (4)- En tant que Administrateur de projet/Collaborateur je veux pouvoir créer des issues

**US6** (4)- En tant que Administrateur de projet/Collaborateur je veux pouvoir modifier des issues

**US7** (2)- En tant que Administrateur de projet/Collaborateur je veux pouvoir supprimer des issues
</br></br>

### **Gestion des tâches** – Priorité 1

**US8** (4)- En tant que Administrateur de projet/Collaborateur je veux pouvoir créer des tâches

**US9** (4)- En tant que Administrateur de projet/Collaborateur je veux pouvoir modifier des tâches

**US10** (2)- En tant que Administrateur de projet/Collaborateur je veux pouvoir supprimer des tâches
</br></br>

### **Gestion des releases** – Priorité 2

**US11** (4)- En tant que Administrateur de projet/Collaborateur je veux pouvoir créer des releases

**US12** (4)- En tant que Administrateur de projet/Collaborateur je veux pouvoir modifier des releases

**US13** (2)- En tant que Administrateur de projet/Collaborateur je veux pouvoir supprimer des releases
</br></br>

### **Gestion des tests** – Priorité 2

**US14** (4)- En tant que Administrateur de projet/Collaborateur je veux pouvoir créer des tests

**US15** (4)- En tant que Administrateur de projet/Collaborateur je veux pouvoir modifier des tests

**US16** (2)- En tant que Administrateur de projet/Collaborateur je veux pouvoir supprimer des tests
</br></br>

### **Gestion de la documentation** – Priorité 2

**US17** (4)- En tant que Administrateur de projet/Collaborateur je veux pouvoir créer des documentation

**US18** (4)- En tant que Administrateur de projet/Collaborateur je veux pouvoir modifier des documentation

**US19** (2)- En tant que Administrateur de projet/Collaborateur je veux pouvoir supprimer des documentation
</br></br>

### **Gestion de l’identification** – Priorité 3

**US20** (3)- En tant que Visiteur je veux pouvoir m’identifier afin de pouvoir gérer mon espace

**US21** (3)- En tant que Visiteur je veux pouvoir m’inscrire

**US22** (1)- En tant que Utilisateur je veux pouvoir me déconnecter
</br></br>

### **Gestion des membres** – Priorité 4

**US23** (5)- En tant que Administrateur de projet je veux pouvoir ajouter des membres supplémentaires au projet afin qu’ils puissent participer au projet

**US24** (5)- En tant que Administrateur de projet je veux pouvoir assigner des droits aux autres membres afin qu’ils puissent éditer le projet

**US25** (2)– En tant que Administrateur de projet je veux pouvoir supprimer un membre du groupe
</br></br>

### **Gestion des notifications** – Priorité 5

**US26** (3)- En tant que Administrateur de projet/Collaborateur/Observateur je veux être notifié lorsque le projet a été édité afin d'être informé de la modification

**US27** (3)- En tant que Utilisateur je veux être notifié lorsque que j’ai été ajouté dans un projet afin d'être informé de mon ajout au projet
</br></br>

## Annexes

### ISSUES :
- identifiant
- titre
- description
- Prioritérité
- difficulté

### TASK :
- identifiant
- titre
- description
- temps de réalisation 
- liste de personnes assignées

### TEST : 
- titre
- description 
- état : Test réalisé
- état : Test réussi

### DOCUMENTATION : 
- titre
- description

### RELEASE : 
- identifiant 
- titre
- description
- lien vers docker

### ROLES : 
- **administrateur du projet :**
	=> a un compte / est connecté / a créé le projet (un seul administrateur par projet)
	=> voir / modifier / supprimer le projet // ajouter un utilisateur / supprimer / donner des droits à un membre du projet
- **collaborateur :**
	=> a un compte / est connecté / a été ajouté au projet / a reçu des droits de l’admin
	=> voir et modifier le projet
- **observateur :**
	=> a un compte / est connecté / a été ajouté au projet
	=> voir le projet
- **utilisateur :** (administrateur / collaborateur / observateur sont des utilisateurs)
	=> a un compte / est connecté
	=> rejoindre un projet dans lequel il a été invité
- **visiteur :**
	=> n’est pas connecté (n’a pas forcément de compte)
	=> créer un compte / se connecter


-----------------

**T1** DBconnect.php : Gérer les connexions à la base de donnée.

**T2** index.php : Créer la page d'accueil.
**T3** editProject.php : Gérer l'ajout/la suppression d'un projet.
**T4** issuesPage.php : Créer la page des issues.
**T5** taskPage.php : Créer la page des tasks.
**T6** testPage.php : Créer la page des tests.
**T7** documentationPage.php : Créer la page des documents.
**T8** releasePage.php : Créer la page des releases.

**T9** issue.php : Classe issue. (Les champs des classes sont décrits en annexe de la partie issues)
**T10** task.php : Classe task.
**T11** test.php : Classe test.
**T12** documentation.php : Classe documentation. 
**T13** release.php : Classe release. 

**T14** editIssue.php : Gérer l'ajout/la modification et la suppression d'issue.
**T15** editTask.php : Gérer l'ajout/la modification et la suppression de tasks.
**T16** editTest.php : Gérer l'ajout/la modification et la suppression de tests.
**T17** editDocumentation.php : Gérer l'ajout/la modification et la suppression de documents.
**T18** editRelease.php : Gérer l'ajout/la modification et la suppression de releases.

**T19** listProjet.php : Permettre de lister les projets d'un utilisateur.

**T20** style.css : Faire la feuille de style du site.

**T21** db.sql : Mettre en place la base de données

**T22** testIssues.php : Tester la classe Issues.
**T23** testTask.php : Tester la classe Task.
**T24** testTest.php : Tester la classe Test.
**T25** testDocumentation.php : Tester la classe Documentation.
**T26** testRelease.php : Tester la classe Release.

**T27** testEditIssues.php : Tester l'ajout/la modification et la suppression d'issue.
**T28** testEditTask.php : Tester l'ajout/la modification et la suppression de task.
**T29** testEditTest.php : Tester l'ajout/la modification et la suppression de test.
**T30** testEditDocumentation.php : Tester l'ajout/la modification et la suppression de documentation.
**T31** testEditRelease.php : Tester l'ajout/la modification et la suppression de release.

**T32** testedutProject.php : Tester l'ajout et la suppression de projet.

**T33** doc.md : Ecrire la documentation du site.

