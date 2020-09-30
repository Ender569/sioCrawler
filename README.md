# Projet sioCrawler #

Le but de ce projet est de réaliser un jeu de rôle contenant plusieurs classes de personnages avec des attributs différents. Ce projet a pour but de permettre aux étudiants du BTS SIO d'améliorer leurs compétences en développement.

## Les outils mis en oeuvre ##

* Git
* VisualStudio
* mysql
* apache

Le développement tourne autour de 3 grandes parties.

1. L'inscription en ligne
2. Développement du jeu en lui même permettant l'exploration d'un labyrinthe.
3. La sauvegarde des personnages et du contexte du jeu.

| Développement | Langages | Technique de programmation |
| ------------- | ---------- | ----------- |
| Inscription en ligne | php, MySQL | Développement web avec Code Igniter |
| Sio Crawler du jeu | C# | Programmation objet, test unitaires |
| Sauvegarde du contexte | C#, MySQL | Programmation procédurale stockées en mysql |

# L'inscription en ligne #

Site web permettant à un joueur de s'inscrire en ligne, le projet prévoit le principe suivant pour l'inscription en ligne.

![acteurFluxInscription.png](/Image/acteurFluxInscription.png)

# Sio Crawler le jeu #

![useCasePersonnage.png](/Image/useCasePersonnage.png)

Les classes développées.

![diagrammeClassePersonnage.png](/Image/diagrammeClassePersonnage.png)

# Sauvegarde du contexte #

La sauvegarde du contexte se fera dans la base de données.

![mcdSauvegarde.png](/Image/mcdSauvegarde.png)
