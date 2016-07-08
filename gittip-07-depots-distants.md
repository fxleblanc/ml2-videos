# Les dépôts distants

La compréhension du fonctionnement des dépôts distants est essentielle afin de
contribuer et maintenir un projet libre. C'est pourquoi nous allons consolider
les notions reliées aux dépôts distants dans ce tout nouvel épisode de la maison
du logiciel libre.

Pour commencer, il est important de savoir comment nos dépôts sont structurés. Pour
avoir une liste des dépôts de notre projet, utilisons la commande git remote. La liste
imprimée nous donne la liste des noms des dépôts distants.

Pour obtenir plus d'informations concernant un dépôt distant en particulier, utilisons
la commande git remote show [le nom de votre dépôt distant]. Le résultat de cette
commande donne un vue très détaillé du dépôt distant. À des fins de simplicité, concentrons-nous uniquement sur Fetch URL et Push URL. Cette url est très importante car c'est avec celle-ci que nous allons interagir lorsque nous voulons push et pull nos
commits.

Pour ajouter un dépôt distant, il suffit d'utiliser la commande git remote add [nom du dépôt] [url du dépôt distant].

Par la suite, si vous voulez modifier les dépôts distants, voici deux trucs très
simples qui vont vous servir dans le cadre du développement de logiciel libre.

Le premier truc est de pouvoir renommer le nom de votre dépôt distant. Pour ce faire,
utilisons la commande git remote rename [vieux nom] [nouveau nom].

Le deuxième truc vise à nous permettre de changer l'url de votre dépôt distant. Très
utile lorsqu'on se trompe d'url ou que l'on veut réorganiser son projet. Pour changer l'url, utilisons la commande git remote set-url [nom du dépôt distant] [nouvelle url].

C'est tout pour cette vidéo. J'espère que les notions apprises vous serviront autant qu'elle m'ont servi.

Dans la prochaine vidéo, nous allons approfondir nos connaissances sur le merge.

N'hésitez pas à laisser des commentaires pour me dire ce que vous aimeriez voir dans les prochaines vidéos.

Encore une fois, merci de votre attention et à la prochaine vidéo.
