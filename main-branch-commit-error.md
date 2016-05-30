# Conseils git: Commit par erreur sur la branche principale

Bonjour à tous et bienvenue dans ce tout nouvel épisode sur les conseils git. Dans cette vidéo, nous allons explorer ce qui se passe lorsque nous faisons un commit par erreur dans la branche principale.

Il m'est personnellement arrivé plusieurs fois de faire cet erreur et il existe probablement plusieurs solutions pour se sortir de cette situation.

Dans ce tutoriel, je vais vous montrer comment transférer vos commits de la branche principale vers une branche de fonctionnalité.

De cette façon, vous aurez une branche principale avec un historique propre et vous ne perdrez pas votre travail car il sera dans la nouvelle branche de travail.

Sans plus tarder, allons-y.

La première étape consiste à créer la branche de fonctionnalité à partir de la branche principale. Pour se faire, assurez-vous d'être dans la branche principale et utilisez la commande git checkout -b branche. Nous avons maintenant deux branches ayant exactement le même historique.

Ensuite, revenons dans la branche principale avec la commande git checkout le nom de votre branche principale. Dans mon cas, il s'agit de master.

La dernière étape va nous permettre d'enlever le ou les commits mis par erreur dans notre branche principale. Faites bien attention avant d'utiliser cette commande car elle va supprimer des commits de notre historique. C'est d'ailleurs pourquoi nous avons préalablement créé une autre branche avant de faire cette manoeuvre.

Voici donc la commande: git reset --hard HEAD~1. Ici, 1 représente le nombre de commits que vous voulez supprimer à partir du plus récent. Pour confirmer que la commande a bien fonctionnée, tapez la commande git log pour voir si le commit que vous avez mis par erreur n'existe plus.

Super. Vous avez maintenant réglé votre problème et êtes prêts à recommencer votre travail sans affecter la branche principale. De plus, vous n'avez pas perdu votre travail puisqu'il a été transféré dans une branche de travail.

Dans la prochaine vidéo, nous allons apprendre comment regrouper nos commits en un seul en utilisant la technique du squash.

N'hésitez pas à laisser des commentaires pour m'indiquer ce que vous voulez voir dans les prochaines vidéos et également ce qui vous a plus ou déplu dans cette vidéo.

Merci de votre attention et à la prochaine vidéo.
