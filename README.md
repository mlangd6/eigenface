# Projet de mathématiques - Eigenface

Ce travail nous est demandé dans le cadre de l'UE : [Projet de Mathématique](https://moodlesupd.script.univ-paris-diderot.fr/course/view.php?id=7066)
au deuxième semestre de L2.

## Sujet
Le sujet (libre) doit partir d'une application pratique et concrète et des mathématiques pas trop triviales doivent intervenir dans la solution. Bien relire le document de présentation de l'UE.

## Rendu
L'évaluation se faisait uniquement sur un oral suivi de questions, une version texte n'était pas demandé.

- [Version texte pdf](eigenface-text.pdf).
- [Slides de présentation](presentation.pdf).


## Implémentation
L'implémentation de la reconnaissance facial que nous avons faites peut se trouver
[ici](src/algo/eigenfaces.py)

### Utilisation
Lancer `python3 eigenfaces.py yale_testset/s[n].pgm` en remmplacant `[n]` par un entier entre 1 et 39 inclus (sauf 15). Le programme devrait reconnaître de quelle individus il s'agit grâce à la [base de données des visages](src/algo/yale_dataset/).

### Dépendances
- numpy    
- cv2
- colorama
