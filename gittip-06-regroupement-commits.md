# Le regroupement de commits

Mon historique est rempli de commits non nécessaires. Mais comment faire pour
rendre le tout plus lisible? C'est ce que nous allons voir dans ce tout nouvel
épisode sur git.

Le regroupement de commits ou plus communément appelé squash est une technique
très simple qui vous permettra de passer de ça à ça. L'outil utilisé pour faire
le squash est nommé rebase. Même si cet outil peut nous permettre bien plus que
les squashs, nous allons seulement nous concentrer sur le squash pour cet épisode.

Allons-y.

Avant de lancer la commande, assurez-vous de savoir le nombre de commits que vous
voulez regrouper. Pour avoir cette information, utilisez la commande git log afin
de visualiser les commits les plus récents. À toute fin pratique, imaginons que notre historique nous montre
les commits c,b, et a. Si a est le commit le plus récent, nous assumons que
le nombre de commits à donner en paramètres à la commande est 3.

Voici donc la commande: git rebase -i HEAD~3. Une fois la commande lancée, un éditeur de texte
va apparaître. Dans le haut de la page, nous avons la liste des 3 commits
ainsi qu'une commande à leur gauche. Comme indiqué par la documentation en bas,
nous voulons spécifier la commande squash aux commits que nous voulons regrouger.
Dans notre exemple, nous voulons regrouper b et c dans le commit a, nous allons
spécifier la commande squash à b et c.

Par la suite, sauvegarder le fichier. Vous allez être de nouveau présenté par
votre éditeur de texte. Cette fois-ci, il s'agit de regrouper les messages de
commits pour refléter le regroupement de commits. Puisque nous regroupons les
commits a,b et c, appelons notre message: Regroupement de a,b,c.

En sauvegardant de nouveau, vous obtenez un commit regroupé. Pour vérifier que
tout s'est bien passé, utilisez la commande git log pour voir si le commit le plus
récent est bel et bien celui que vous avez indiqué.

C'est tout pour tout de suite. Dans de futures vidéos, nous allons approfondir les
usages de la commande git rebase car cet outil est très utile, voir même essentiel
pour la maintenance d'un projet libre. Dans la prochaine vidéo,nous allons rassembler nos connaissances des dépôts distants.

J'espère que cette vidéo vous a été utile. N'hésitez pas à laisser des commentaires
pour m'indiquer ce que vous aimeriez voir dans les prochaines vidéos.

Merci de votre attention et à la prochaine vidéo.
