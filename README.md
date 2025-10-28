# Projet Pac-Man en Python


## Introduction

Pac-Man est un jeu vidéo d'arcade classique où le joueur contrôle Pac-Man, un personnage qui se déplace dans un labyrinthe pour manger des pastilles tout en évitant les fantômes. Dans ce projet, nous allons réaliser une version simplifiée de Pac-Man en utilisant le langage Python et la bibliothèque Pygame. Le jeu sera contrôlé à l'aide des flèches du clavier pour déplacer Pac-Man dans le labyrinthe.

Pour une version plus complète de Pac-Man, vous pouvez consulter [ce lien](https://freepacman.org/).

## Structure du Projet

```plaintext
pacman/
├── main.py
├── game.py
├── pacman.py
├── ghost.py
├── helper.py
├── home.py
├── end.py
├── config.py
└── assets/
    └── images/
```

#### Détails des fichiers :

- **main.py**  
  Le fichier principal qui lance le jeu. Il contient le point d'entrée du programme et initialise les différentes parties du jeu, y compris la gestion des événements et l'affichage. C'est ce fichier qui doit être exécuté pour démarrer le jeu, à l'aide de la commande suivante : ```python main.py``` ou directement dans votre IDE.

- **game.py**  
  Gère la logique principale du jeu, y compris le contrôle des niveaux, des mouvements des personnages (Pac-Man et les fantômes), et la progression générale du jeu. Il orchestre le déroulement du jeu.

- **pacman.py**  
  Définit le comportement du Pac-Man.

- **ghost.py**  
  Gère le comportement des fantômes ennemis.

- **helper.py**  
  Fournit des fonctions utilitaires et du code réutilisable pour le projet.

- **home.py**  
  Ce fichier gère l’affichage de l’écran d’accueil où le joueur peut démarrer le jeu. Il permet ainsi au joueur de débuter la partie.

- **end.py**  
  Gère l’écran de fin de partie. Ce fichier affiche le résultat de la partie (victoire ou défaite) avec une image de fond et un message en français au centre de l’écran.

- **config.py**  
  Contient les paramètres de configuration du jeu, comme la taille de l'écran, la vitesse des personnages, et d'autres constantes utilisées pour ajuster le gameplay.

- **assets/images/**  
  Ce dossier contient les ressources graphiques du jeu, telles que les images des personnages, des éléments de décor, et les icônes.

