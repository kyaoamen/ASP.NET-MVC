# Binôme : AYARMA Lacpili & KOTOKOU Yao Amen

### Description ###

Bibliotheca est une application de gestion des livres dans une bibliothèque électronique.

### Dépendances et Pré-requis ###
1. Base de données.
La solution de base de données est nommée "bd_biblio" et se trouve à la racine du projet de développement.
Les DDL(0 et 1) répresentent les fichiers de définition (Utilisateur, Base de données et tables).
Le DML contient les requêtes de manipulation de données afin d'avoir un jeu d'enregistrement.

2. Dépendances
Avec la console d'installation de packages Nuget, installer les éléments suivants :
- EntityFramework : Install-Package EntityFramework -Version 6.4.4
- PagedList.MVC : Install-Package PagedList.Mvc -Version 4.5.0
- JQuery UI Combined : Install-Package jQuery.UI.Combined -Version 1.12.1

### Exécution ###
La BD étant créée et les packages installés, le projet peut donc être déployé.


### Améliorations futures ###
- Les interfaces d'authentification ont été implémentées, testées mais pas intégrées au flux normal.
Au démarrage, l'utilisateur est dirigé vers l'administration qui est composée de différents menus relatifs à une bibliothèque
- La lecture d'un livre dans un nouvel onglet n'est pas encore implémentée.
- Le rafraîchissment partiel a été implémenté au niveau de la recherche de livres. Les tests ne ^donnant pas encore le résultat escompté, nous avons décidé de le retirer pour une prochaine mise-à-jour.
