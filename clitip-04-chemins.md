# Les chemins relatifs et absolus

Bonjour à tous et bienvenue dans ce tout nouvel épisode sur la ligne de commande
en linux.

Même si nous avons appris comment utiliser en pratique les chemins en linux, il est très important de comprendre la théorie en arrière. Que ce soit
pour se retrouver dans ses dossiers ou simplement pour spécifier un chemin à
une commande, il est essentiel de pouvoir faire la différence entre les deux afin
de choisir le chemin le plus efficace.

Commencons donc par les chemins relatifs. Un chemin relatif est un chemin qui est
par rapport au dossier courant. Par exemple, si j'ai l'arborescence suivante et que je me situe dans dossier1. J'aimerais me rendre au dossier dossier2 en utilisant uniquement un chemin relatif. Je vais donc spécifier la commande: cd ../dossier2. Si vous vous rappelez des anciens épisodes de la série, le .. signifie d'aller dans un dossier plus haut.

Au contraire, le chemin absolu est un chemin par rapport à la racine. La racine étant
le dossier le plus haut dans l'arborescence dans linux. Si on cherche à utiliser un
chemin absolu, il faudra spécifier le chemin à partir de la racine et descendre jusqu'au dossier ou fichier approprié. Si on reprend notre exemple, je pourrais me
rendre au dossier dossier2 en utilisant le chemin suivant: /home/fxleblanc/exemple/dossier1. Je commence le chemin par la racine qui est le caractère / et je redescend toute l'arborescence jusqu'au dossier dossier1.

Savoir choisir entre un chemin relatif et absolu dépend essentiellement de votre position dans l'arborescence et de la commande que vous utilisez. Avec de la pratique,
vous allez tout de suite savoir le chemin le plus efficace à partir de votre position.

C'est tout pour cette vidéo. Même si cette capsule a été un peu plus théorique que
les autres, elle n'en est pas moins importante. N'hésitez pas à poser des questions dans les commentaires si vous avez des interrogations ou des incompréhensions.

N'hésitez pas à me dire ce que vous voulez voir dans les prochaines vidéos.

Merci de votre attention et à la prochaine vidéo.
