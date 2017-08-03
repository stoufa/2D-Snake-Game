# Jeu-Snake-2D-SDL
Jeu Snake en 2D développée en C avec la librairie SDL

Malheureusement, je n'ai plus le code source de l'application ! je n'ai trouvé que l'exécutable
c'est un projet que j'ai fait pendant l'été de l'année 2013
le jeu est écrit en C à l'aide de la librairie SDL
Si vous êtes intéressés, je peux réécrire le code source de l'application, toute aide sera appréciée :)
Le principe du jeu est simple : collectionner tous les fruits tout en évitant les obstacles
- vous contrôlez le serpent en utilisant les flèches
- l'appui sur 'p' permet de mettre le jeu en pause
- le jeu contient 3 niveaux de difficulté et 6 stages différents stockés chacune dans un fichier dans le dossier `niveaux/`
- chaque niveau est décrit par un fichier texte `snakeX.dat` avec X le numéro du niveau ( de 1 à 6 )
  `0` représente le vide, `1` représente un obstacle, `2` représente la position initiale du joueur
- `icone.bmp` est l'icône du jeu
- `cS.gif` est l'image du corps du serpent
- `tSX.gif` est l'image de la tête du serpent dans la position X, X peut être `H` ( Haut ), `B` ( Bas ), `D` ( Droite ) ou `G` ( Gauche )
- `mur.gif` est l'image du mur
- `eat.wav` est le son entendu quand le serpent mange un fruit
- `win.mp3` est le son entendu quand vous gagnez
- `lose.wav` est le son entendu quand vous perdez ( c-à-d quand vous touchez le mur ou alors le corps du serpent )
- `angelina.TTF` est le fichier de la police du texte utilisé dans le jeu
- les fichiers \*.dll sont nécessaires pour le bon fonctionnement du jeu ( graphique, son, ... )

![screenshot](https://raw.githubusercontent.com/stoufa/Jeu-Snake-2D-SDL/master/screenshots/06.png)
