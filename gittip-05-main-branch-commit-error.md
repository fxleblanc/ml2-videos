# Conseils git: Commit par erreur sur la branche principale

Bonjour à tous et bienvenue dans ce tout nouvel épisode sur les conseils git. Dans cette vidéo, nous allons explorer ce qui se passe lorsque nous faisons un commit par erreur dans la branche principale. À toute fin pratique, la branche principale se nommera master.

Imaginons que nous avons les commits a,b et c dans la branche master. Maintenant, imaginez que vous faites par erreur un commit nommé D. Le commit D devrait idéalement être dans une branche séparée mais comment fait-on pour le transférer de master à une nouvelle branche?

Dans ce tutoriel, je vais vous montrer exactement cela.

Allons-y.

La première étape consiste à créer la branche de fonctionnalité à partir de master. Pour se faire, assurez-vous d'être dans la branche master et utilisez la commande git checkout -b branche.

Nous avons maintenant deux branches ayant exactement le même historique.

Ensuite, revenons dans la branche principale avec la commande git checkout master. Cette commande est très importante car la prochaine manipulation demande à ce que nous soyons dans la branche master.

La dernière étape va nous permettre d'enlever le ou les commits mis par erreur dans notre branche principale. Faites bien attention avant d'utiliser cette commande car elle va supprimer des commits de notre historique.

Voici donc la commande: git reset --hard HEAD~1. Ici, 1 représente le nombre de commits que vous voulez supprimer à partir du plus commit le plus récent.

Super. Vous avez maintenant réglé votre problème et êtes prêts à recommencer votre travail sans affecter la branche principale.

Dans la prochaine vidéo, nous allons apprendre comment regrouper nos commits en un seul en utilisant la technique du squash.

N'hésitez pas à laisser des commentaires pour m'indiquer ce que vous voulez voir dans les prochaines vidéos et également ce qui vous a plus ou déplu dans cette vidéo.

Merci de votre attention et à la prochaine vidéo.
