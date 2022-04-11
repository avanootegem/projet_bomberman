# Projet JavaScript du style "Bomberman like"

Jeu Bomberman codé entièrment en Js.

## But du jeu
Éliminer tous les monstres avec votre personnage. Vous avez 3 vies.
Déplacement avec les flèches directionnelles, pose des bombes avec la touche Espace.
Une bombe à la fois.
Déplacement aléatoire des monstres. (fonction randomMove())
Passage secret à gauche et à droite du plateau.


## Explication de la variable Plateau
Chaques tableaux correspondent à une ligne du plateau de jeu.
Et chaques éléments de ses tableaux correspondent à une case.

* 0 --> Contour du plateau
* 1 --> Cases accessibles par toutes unités
* 2 et 3 --> Cases accessibles uniquement par le joueur
* 4 --> Cases accessibles uniquement par les monstres
* 5 --> Valeur des cases bombes (Sélectionné aléatoirement dans la fonction random_stone())
* 8 --> Mur intérieur
* 9 --> Cases en dehors du jeu