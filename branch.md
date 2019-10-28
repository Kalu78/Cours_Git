•git init
Git crée automatiquement la branchemaster

•git branch dev
Pour créer une branche

•git branch
Affiche l’ensemble des branches se trouvant sur votre dépôt

•git checkout dev
Pour se déplacer sur la branche dev

•git checkout -b feature_header
Pour créer une branche et se déplacer dessus en une seule commande

•git branch -d [nom de votre branche]
Supprime une branche

•git branch -D [nom de votre branche]
Force la suppression d’une branche

•git merge dev
Pour merger dev dans master

•git merge dev --no-ff
Pour faire un commit de merge même si on est dans une situation sans divergence de branche

•git branch --no-merged
Lister toutes les branches non mergées

•git stash
Met de coté le code non terminé

•git stash list
Liste sur la branche les stash

•git stash apply
Recupère ce qui était dans la stash
Et l'applique => récupération de son code modifié

•git stash drop
Supprime ce qui se trouve dans la remise

•git stash apply --index
Essaye de remettre ce qui était dans l'index

•git tag -a v1.0 -m 
Tag annoté

•git tag
Liste les tags

•git tag -l
Recherche des tags particuliers

•gitshow v8.2
Voir un tag annoté

•git --bare init
Création du server Git

•gitremote add [alias] [chemin_du_serveur_distant]
Ajouter un dépôt distant

•git push origin master
Push la branche master dans votre dépôt dans le serveur origin

•git remote
Liste les dépôts distants

•git remote rm [alias]
Supprimer ou renommer un dépôt distant

•git fetch origin
Fetch récupére la branche distante localement sans fusion avec sa branche master

•git log master..origin/master
Compare les différences entre master local et distant (après un fetch)

•git push [nom-distant] [nom-de-branche]
Permet de publier une branche distante

•git remote show origin
Inspecter un dépôt distant