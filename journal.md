#Journal de bord PPE1

##26/09/2024

Pour l'exercice 1 de PPE, j'ai eu du mal pour trouver la commande qui supprime un dossier (c'est mvdir) et pour déplacer des fichiers dans un autre dossier (c'est mv #nom du fichier ../).
J'ai trouvé par hasard comment renommer un fichier (c'est mv #nom du fichier actuel #nouveau nom).
J'ai testé les quelques commandes comme file, cat, hear, tail et less. Je n'arrivais pas à sortir de l'affichage de texte de la commande less (c'est q).
J'ai compris qu'il fallait toujours se repositionner dans le dossier où l'on veut agir.

Vous trouverez le fichier zip de l'historique de mon terminal pour l'exercice 1.

----

##03/10/2024

Pour l'exercice sur Git, je rencontre le problème suivant : quand je fais "git status", mon terminal affiche toujours que je suis à jour même si je ne le suis pas. Quand je "git pull", les nouveaux fichiers s'affichent quand même, mais si j'en croyais le "git status", il n'y avait pas de nouveauté...
Néanmoins, dans l'autre sens, quand j'ai fait des modifications sur ma machine et que je fais "git status", là le terminal me dit que le git est en retard d'un push de ma part...

Je me demande si nous devons rédiger le journal de bord en "format md" ?
Pour le reste de l'exercice, tout a bien fonctionné, les git pull et git push, le journal se retrouve à sa dernière version sur le git !
Je rencontre un difficulté, un texte que je ne comprends pas s'affiche quand je commit sans message (quand je fais "commit -m tout va bien)...
J'ai aussi eu du mal à faire un tag, mais j'ai compris que l'on pouvait juste écrire "git tag ..." et ça suffisait à l'ajouter au dernier commit. La commande "git tag -a <tagname> -m "message"" c'est juste pour ajouter un message au tag.
J'ai découvert les commandes "git tag -n" pour voir la liste des tags, "git tag -d" pour effacer un tag et enfin "git diff <tag1>..<tag2>" pour voir la différence entre deux versions de commit tagées.