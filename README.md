# 2D-Snake-Game
:us: 2D Snake Game developed in C with the SDL library  
Unfortunately, I no longer have the source code! I only found the executable.  
It's a project I did during the summer of 2013.  
The game is written in C using the SDL library.  
If you are interested, I can rewrite the source code of the application, any help will be appreciated :)  
The principle of the game is simple: collect all the fruits while avoiding obstacles  
  
:fr: Jeu Snake en 2D développé en C avec la librairie SDL  
Malheureusement, je n'ai plus le code source! je n'ai trouvé que l'exécutable.  
C'est un projet que j'ai fait pendant l'été de l'année 2013.  
Le jeu est écrit en C à l'aide de la librairie SDL.  
Si vous êtes intéressés, je peux réécrire le code source de l'application, toute aide sera appréciée :)  
Le principe du jeu est simple : collectionner tous les fruits tout en évitant les obstacles  

<p align="center">
  <img src="https://raw.githubusercontent.com/stoufa/Jeu-Snake-2D-SDL/master/snake.gif" alt="Jeu-Snake-2D-SDL-Preview"/>
</p>

| :us: | :fr: |
|------|------|
| - you control the snake using the arrows | - vous contrôlez le serpent en utilisant les flèches |
| - pressing `p` allows you to pause the game | - l'appui sur `p` permet de mettre le jeu en pause |
| - the game contains 3 levels of difficulty and 6 different maps, each stored in a file in the `niveaux/` folder | - le jeu contient 3 niveaux de difficulté et 6 stages différents,  stockés chacun dans un fichier dans le dossier `niveaux/` |
| - each level is described by a text file `snakeX.dat` with X the number of the map (from 1 to 6) `0` represents the void, `1` represents an obstacle, `2` represents the initial position of the player | - chaque niveau est décrit par un fichier texte `snakeX.dat` avec X le numéro du stage (de 1 à 6) `0` représente le vide, `1` représente un obstacle, `2` représente la position initiale du joueur |
| - `icone.bmp` is the game icon | - `icone.bmp` est l'icône du jeu |
| - `cS.gif` is the image of the snake's body | - `cS.gif` est l'image du corps du serpent |
| - `tSX.gif` is the image of the snake's head in position X, X can be `H` (Top), `B` (Bottom), `D` (Right) or `G` (Left) | - `tSX.gif` est l'image de la tête du serpent dans la position X, X peut être `H` (Haut), `B` (Bas), `D` (Droite) ou `G` (Gauche) |
| - `mur.gif` is the image of the wall | - `mur.gif` est l'image du mur |
| - `eat.wav` is the sound heard when the snake eats a fruit | - `eat.wav` est le son entendu quand le serpent mange un fruit |
| - `win.mp3` is the sound heard when you win | - `win.mp3` est le son entendu quand vous gagnez |
| - `lose.wav` is the sound heard when you lose (i.e. when you touch the wall or the body of the snake) | - `lose.wav` est le son entendu quand vous perdez (c-à-d quand vous touchez le mur ou alors le corps du serpent) |
| - `angelina.TTF` is the font file of the text used in the game | - `angelina.TTF` est le fichier de la police du texte utilisé dans le jeu |
| - the `*.dll` files are necessary for the game to work properly (graphic, sound, ...) | - les fichiers `*.dll` sont nécessaires pour le bon fonctionnement du jeu (graphique, son, ...) |
| - the components of the snake's body are stored in a linked list, each of its nodes contains information about its current position (line number, column number), assuming that the snake's head is stored at the beginning of the list, the list is updated as follows: at each moment, each cell takes the position of the cell that comes next and the snake's head is updated according to the current direction. | - les composantes du corps du serpent sont stockées dans une liste chaînée, chacun de ses noeuds contient des informations sur sa position actuelle (numéro ligne, numéro colonne), en supposant que la tête du serpent est stockée au début de la liste, cette dernière se met à jour de la façon suivante: à chaque instant, toute cellule prend la position de la cellule qui vient juste après et la tête du serpent se met à jour en fonction de la direction en cours. |

<p align="center">
  <img src="https://raw.githubusercontent.com/stoufa/Jeu-Snake-2D-SDL/master/screenshots/06.png" alt="Jeu-Snake-2D-SDL-Preview"/>
</p>
