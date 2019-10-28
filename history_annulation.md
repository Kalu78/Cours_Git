•git config --local user.name Tony
•git config --local user.email tony@tony.fr
Mettre son pseudo

•git --no-pager log --oneline
Affiche les logs et sort de la commande

•git --no-pager log -3 --oneline
3 commits seulement

•git log --author "Antoine07"
Consulter les commits d’un auteur en particulier

•git log calzone.txt
Consulter l’historique d’un fichier uniquement

•git log -p calzone.txt
Visualiser les modifications au sein d’un fichier ou de l’ensemble / d’un ensemble des fichier(s)

•git log -p
Visualiser les modifications dans l'ensemble des commits

•git log --stat calzone.txt
Visualiser les statistiques des modifications des fichiers

•git log -E -i --grep='Pizza'
Permet de rechercher des logs : E expression pour rechercher les occurences et i pour insensible à la casse majuscule/minuscule

•git blame calzone.tx
Pour savoir qui a fait une/des modification(s) lorsqu’on travaille à plusieurs sur un même projet

•git diff
Visualiser les modifications d'un fichier avant de l'indexer

•git diff --cached
Affiche les différences entre le dernier commit et l’index

•git diff HEAD~1
Pour voir les modifications un commit en arrière

•git diff HEAD~3 HEAD
Pour visualiser les différences entre le HEAD et un état antérieur du dépôt (3 commits avant)

•git log --oneline
Voir les modifications entre deux commits

•git diff --stat
Faire des stat sur les différences opérées dans les fichiers

•git restore
Remet le dépôt dans l’état dans lequel il se trouvait juste avant une modification

•git restore --staged
Remet le dépôt dans l’état dans lequel il se trouvait avant une modification ajouté dans l’index

•git reset HEAD~1
Annule le dernier commit et met tout dans le WD sans perte (revient au commit précédent)

•git reset --soft HEAD~1
Annule le dernier commit et met tout dans la staging area sans perte

•git reset --hard HEAD~1
Annule le dernier commit et supprime les modifications

•git revert
La méthode revert annule un commit en créant un commit d’annulation