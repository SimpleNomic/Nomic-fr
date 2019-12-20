# Règles

1. Les présentes règles doivent être suivies par tous les joueurs.
1. Points de règle
    1. Un point de règle est défini par les éléments suivant qui doivent être présents dans l'ordre indiqué :
        1. Un nombre suivi par un point. Dans le code, chaque nombre est " 1 ", mais le point de règle est identifié dans la version affichable des règles.
        1. Un texte décrivant le point de règle en détail. Si des sous-points sont présents, ce texte peut être un titre.
        1. Optionellement une ou plusieurs sous-points qui suivent le même schéma que le point de règle.
    1. Un nouveau point de règle est ajouté après le dernier présent.
    1. Si un point de règle est en conflit avec un autre, celui dont le numéro est le plus bas prévaut. Si l'un ou l'autre est un sous-point, la comparaison se fait d'abord au niveau des points de la règle principale. Par exemple, la règle *1.iii.d.* prévaut sur la règle *2.*.
1. Les joueurs jouent dans l'ordre décrit dans le fichier [joueurs.md](../joueurs.md).
1. À son tour de jeu, un joueur peut faire une ou plusieurs propositions traitées comme une seule.
    1. Est considérée une proposition l'une des suivantes :
        1. Une proposition de création d'un nouveau point de règle.
        1. Une proposition de modification d'un point de règle existant.
        1. Une proposition de suppression d'un point de règle existant.
        1. Une proposition de déplacement d'un point de règle ou sous-point de règle à un autre endroit des règles.
1. Une proposition est soumise sous la forme d'un *pull request*.
1. Après qu'une proposition soit faite, tous les joueurs doivent voter soit *OUI*, soit *NON*, soit *BLANC* dans les commentaires du *pull request*.
    1. Si tous les joueurs ont voté et que le nombre de voix pour le *OUI* est strictement supérieur au nombre de voix pour le *NON*, alors la proposition est acceptée et devient partie intégrante des règles.
    1. Les joueurs n'ayant pas voté sept jours après la proposition votent *BLANC*.
1. Le tour de jeu d'un joueur prend fin au maximum sept jours après le début de celui-ci.
1. Un utilisateur de GitHub peut rejoindre ou quitter la partie en inscrivant, respectivement retirant son nom dans le fichier [joueurs.md](../joueurs.md). L'hôte décidera si un nouveau joueur est accepté ou non.
    1. S'il y a moins de trois joueurs, la partie fait une pause jusqu'à ce que le nombre de joueurs soit acceptable.
1. Le joueur qui vent la princesse a gagné la partie.
