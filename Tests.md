# Tests
Nous n'avons pas encore fait de test unitaire, nous n'avons pas encore de fonction pour lesquels des tests unitaires seraient pertinants.
Nous avons mis en place plusieurs tests End to End avec Selenium et automatisé avec Python.
Les tests se trouvent dans le dossier tests, à la racine du projet.

## Automatisation
Nous avons utilisé Python pour automatiser les tests. Pour l'instant il y a des problèmes d'erreur de délais qui provoquent l'échec du script. (script qui essaye d'intéragir avant que certaines pages ne soient chargées).

## Suivi des tests
Le script Python créé un fichier "latest_log.txt" contenant les informations de la dernière exécution du script.
Le résultat des tests E2E est répertorié dans le tableau ci-dessous.

## Résultats des Tests
Les tests ont été réalisés en local avec Selenium et avec le script Python pour ceux ne provoquant pas d'erreur de délais.

|Description du test|Date de la dernière exécution|Résultat|
|:-----------------:|:---------------------------:|:------:|
|Connexion|21/11/2019|Réussi|
|Deconnexion|21/11/2019|Réussi|
|Ajout d'issue|21/11/2019|Réussi|
|Suppression d'issue|21/11/2019|Réussi|
|Ajout de membre|21/11/2019|Réussi|
|Suppression de membre|21/11/2019|Réussi|
|Ajout de release|21/11/2019|Réussi|
|Modification de release|21/11/2019|Réussi|
|Suppression de release|21/11/2019|Réussi|
|Redirection vers la release en cas de clique sur le lien|21/11/2019|Réussi|
|Ajout de sprint|21/11/2019|Réussi|
|Modification de sprint|21/11/2019|Réussi|
|Suppression de sprint|21/11/2019|Réussi|