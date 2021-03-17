# Pony Club

Ce lab est un exercice du cours "Débuter avec Git et Github" dispensé par Nicolas Bauwens ([nbwns](https://github.com/nbwns)) à Bruxelles Formation Cepegra.

## Pour commencer

1. Télécharger et installer Git
2. Récupérer ce projet en local en téléchargeant le zip et en mettant son contenu dans un répertoire 
3. Lancer la console :)

## Les bases

1. Configurer Git avec son nom et e-mail
2. Se placer dans le répertoire et faire `git init`
3. Faire un `git status`
4. Faire un `git add`
5. Refaire un `git status`
6. Faire un `git commit`
7. Refaire un `git status`
8. Faire une modification dans un des fichiers
9. Refaire un `git status`
10. Faire un `git diff`
11. Faire un `git add` et `git commit`
12. Faire un `git log`

## Les branches

1. Créer une branche
2. Faire un `git branch`
3. Faire un `git checkout` sur la nouvelle branche
4. Faire des modifications, par exemple rajouter le poney Pimkie Pie à la liste (image ici http://mycouponlady.com/wp-content/uploads/2013/02/pinkiepie.png)
5. Faire un `git status`
6. Faire un `git diff`
7. Faire un `git add` et `git commit` et regarder la page
8. Refaire un `git status`
9. Faire un `git checkout` sur master et regarder la page
10. Faire un `git diff master..<branche>`

## Merge d'une branche sur master

1. Faire un `git checkout` sur master
2. Faire une modification dans le même fichier que celui édité dans la branche, mais pas au même endroit.
3. Faire un `git diff`
4. Faire un `git add` et `git commit` et regarder la page
5. Faire un `git checkout` sur la branche et regarder la page.
6. Le merge doit se faire depuis master. Retourner sur master avec un `git checkout`.
7. Faire un `git merge` de la branche
8. Regarder la page
6. Effacer la branche

## Merge d'une branche sur master... avec un conflit !

1. Créer une nouvelle branche
2. Faire des modifications
3. Faire un `git add` et `git commit` et regarder la page
4. Faire un `git checkout` sur master
5. Y faire des modifications aux mêmes endroits
6. Faire un `git add` et `git commit`
7. Faire un `git merge` de la branche
8. Ouille ! Conflit x_x Il faut choisir manuellement le contenu à conserver
9. Faire un `git add` et `git commit` et regarder la page
10. Effacer la branche

## Pousser vers un remote repository

1. Créer un remote repository sur Github
2. Configurer le remote avec `git remote add`
3. Regarder si un remote est configuré 
4. Faire un `git push`
5. Aller voir le projet sur Github

## Récupérer le code d'un remote repository existant

1. Trouver un projet sur Github (celui-ci peut-être ?)
2. Se placer dans le répertoire qui contient les projets
3. Faire un `git clone` pour initialiser un nouveau repository à partir d'un projet existant

## Activer les Github Pages

1. Créer une branche **gh-pages**
2. Se placer sur cette branche
3. Faire un `git push` de cette branche
4. Le site est en ligne, pour le voir il faut visiter http://*username*.github.io/*remote_repository*

**Félicitations, vous avez acquis les bases de Git et Github !** 

## Si vous êtes bloqués, voici quelques ressources

Débuter avec Git et Github (Le Wagon)
https://www.youtube.com/watch?v=V6Zo68uQPqE 

Gérer vos codes sources avec Git (OpenClassRooms)
https://openclassrooms.com/courses/gerez-vos-codes-source-avec-git 

Git – petit guide
http://rogerdudler.github.io/git-guide/index.fr.html 

Git Beginner’s Guide for Dummies
https://backlogtool.com/git-guide/en/ 

Learn Git (CodeCademy)
https://www.codecademy.com/learn/learn-git 

Try Git (CodeSchool)
https://www.codeschool.com/courses/try-git 

La doc Github
https://git-scm.com/docs 

Tutoriel de démarrage
https://guides.github.com/activities/hello-world/ 
