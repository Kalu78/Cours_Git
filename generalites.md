•git init

Pour initialiser un projet Git il faut en premier lieu taper cette ligne de commande

•git status
Donne l’état du dépôt à un instant t et également des informations complémentaires

•git add calzone.txt
Pour ajouter le fichier dans la zone d’index

•git rm --cached calzone.txt
Pour ne plus suivre le fichier calzone.txt

•git log
Pour voir les clés de hachages ainsi que des informations relatives à chaque commit

•git log --oneline
Verifier que le commit a bien été fait

•git shortlog
Une autre commande équivalente

•git add .
Ajoute un ensemble de fichiers/dossiers ou modifs

•git log master..origin/master
Voir les différences entre deux branches

•git log --stat
Stat sur les modifs par commits

•git log --since=2.weeks
Voir les commits réaliser depuis deux semaines

•git blame -L 40,60 readme.md
Rechercher qui a fait les modifs par ligne -L

•git blame --since=3.weeks -- readme.md
Depuis 3 semaines avec auteurs des modifications

•git mv mon_ancien_fichier mon_nouveau_fichier
Pour renommer un fichier dans Git

•git commit -am "un message court"
Modifier un fichier connu par Git

•git rm mon_fichier
Supprimer un fichier

•git ls-files
Pour voir tous les fichiers suivis
