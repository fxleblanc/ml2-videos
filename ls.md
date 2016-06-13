# Ligne de commande 101: Lister des fichiers

Bonjour à tous et bienvenue dans ce deuxième épisode sur la ligne de commande en linux.

Dans cet épisode, j'aimerais appronfondir la façon dont on liste des fichiers. Si vous vous souvenez bien du premier épisode, la commande ls sans paramètres nous permet d'avoir une liste des fichiers du dossier courant. De plus, la commande ls -l nous permet d'avoir cette même liste mais sous une présentation beaucoup plus détaillée.

Analysons donc un peu l'information que cette commande nous donne. Partant de la gauche, le premier caractère nous indique s'il s'agit d'un dossier ou d'un fichier. d pour dossier et tiret pour fichier.

Par la suite, les 9 caractères suivants indiquent les permissions des différents utilisateurs sur le fichier ou dossier. Ici, r signifie read ou lecture, w signfie write ou écriture, x signifie execution ou exécution et - signifie que la permission n'est pas accordée. Le premier groupe de 3 lettres indique les permissions pour l'utilisateur propriétaire du fichier. Le deuxième indique les permissions pour le groupe propriétaire du fichier. Finalement, le troisième groupe indique les permissions pour les autres utilisateurs.

Continous avec la prochaine colonne. Le caractère de cette colonne est un nombre qui indique le nombre total de liens vers ce fichier. Ici, un lien est un fichier ou un dossier contenu dans le dossier listé. À noter que ce lien peut être directement sous le dossier listé ou être dans un sous-dossier du dossier listé.

Ensuite, les deux prochaines colonnes indiquent le nom ainsi que le groupe propriétaire du fichier.

La prochaine colonne indique la taille du fichier en octets. Si vous voulez voir la taile du fichier de manière plus lisible, ajoutez l'argument h à la commande.

Par la suite, les trois prochaines colonnes indiquent la date et l'heure de la dernière modification.

Pour finir, la dernière colonne nous donne le nom du fichier.

Maintenant, qu'en est-il des fichiers cachées? Pour lister les fichiers cachés en plus des fichiers réguliers, ajoutez l'argument a dans la commande. Remarquez que pour qu'un fichier soit caché dans linux, il suffit de mettre un point au début du nom de fichier.

C'est tout pour cette vidéo, j'espère que vous en avez appris plus sur comment utiliser la ligne de commande.

N'hésitez pas à laisser des commentaires pour m'indiquer ce que vous aimeriez voir dans les prochaines vidéos.

Encore une fois, merci de votre attention et à la prochaine vidéo
