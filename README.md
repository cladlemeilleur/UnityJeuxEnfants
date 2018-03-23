# UnityJeuxEnfants

Le projet est de créer un jeu mobile pour enfants qui contiendra plusieurs mini jeux.

Le premier mini jeux sera Simon, un jeu de mémoire.

# Simon
But du jeu : Recopier la séquence qui s'afficher au joueur.

Dans un premier temps l'écran comportera 4 couleurs.
Pendant la 1er sequence : Chaque changement de couleurs aura 1 seconde de décallage.
sequence + 1 : Chaque changement de couleurs aura 0.01 seconde en moins de la séquence précédente de décallage.
Max durée séquénce : 1
Min durée séquence :0.5

Pour chaque clique, vérifier que cela corresponds à la séquence originale.
Si oui on continue sinon on GAME OVER.

Un meilleur score sera afficher a l'écran et symbolisé par une icone.
Se score sera conserver dans un fichier de config appellé PlayerPref pour commencer.
