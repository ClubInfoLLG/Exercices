# Papi grincheux

## Club Info 2023 – Niveau Intermédiaire

### Énoncé :

Lors d’une partie de Scrabble avec votre Papi Albus, celui-ci critique vigoureusement votre choix de spécialité NSI. Il affirme que l’informatique ne sert à rien et qu’il sera toujours plus fort qu’un ordinateur. Vous le laissez parler tout en vous disant qu’il est bien présomptueux pour un octogénaire. Vous remarquez cependant qu’il met du temps a compter les points de son jeu préféré. Vous y voyez alors une occasion parfaite pour lui apprendre à respecter votre matière favorite.

Vous affirmez donc que vous êtes capables de faire un programme python qui compte plus vite les points au Scrabble que votre Papi. Vous devez donc avoir un programme qui renvoie la valeur d’un mot (sans prendre on compte les cases lettre triple, lettre double...) qui est donné en entrée.

#### Valeurs des lettres au Scrabble français :

| Lettres             | Valeur    |
| ------------------- | --------- |
| A,E,I,L,N,O,R,S,T,U | 1 point   |
| D,G,M               | 2 points  |
| B,C,P               | 3 points  |
| F,H,V               | 4 points  |
| J,Q                 | 8 points  |
| K,W,X,Y,Z           | 10 points |

### Entrée :

L’entrée contiendra le mot dont on souhaite connaître la valeur (peut contenir des majuscules ou des minuscules de manière aléatoire).

`BanAnE`

### Sortie :

Le programme renvoie le nombre de points dans une phrase rédigée comme suit :

`>>> Le mot "xylophone" a une valeur de 32 points au Scrabble.` (Le mot est affiché en minuscule)

#### Exemples d’entrée/sortie :

```
xylophone

>>> Le mot "xylophone" a une valeur de 32 points au Scrabble.
```

```
BanAnE

>>> Le mot "banane" a une valeur de 8 points au Scrabble.
```

## Extension 1 :

Votre Papi ne semble pas si impressionné. Votre maman Fleur vous suggère de modifier votre programme afin de pouvoir prendre plusieurs mots en même temps.

### Entrée :

L’entrée contiendra :

- Le nombre de mots soumis au programme sur la première ligne.
- Les mots en question, chacun sur une ligne, dont on souhaite connaître la valeur.

#### Exemples d’entrée/sortie :

```
3
Xylophone
BanAne
Coubeh

>>> Le mot 'xylophone' a une valeur de 32 points au Scrabble.
>>> Le mot 'banane' a une valeur de 8 points au Scrabble.
>>> Le mot 'coubeh' a une valeur de 12 points au Scrabble.
```

## Extension 2 :

Albus est (très) pointilleux et affirme que votre programme ne tient pas la route car il ne prend pas en compte le nombre de jetons dans le jeu du Scrabble.

En effet il a testé le mot `concomitance` sur votre programme (19 points) hors ce mot n’est pas écrivable dans le jeu du Scrabble car ce dernier ne comprend que 2 jetons `c`.

Votre père Drago vous propose donc de modifier votre code pour que celui-ci renvoie l’écrivabilité du mot avec les jetons du scrabble en plus du nombre de points.

#### Nombres de jetons au Scrabble :

| Lettre        | Occurences |
| ------------- | ---------- |
| E             | 10         |
| A             | 9          |
| I             | 8          |
| N,O,R,S,T,U   | 6          |
| L             | 5          |
| D,M           | 3          |
| F,H,G,B,C,P,V | 2          |
| J,Q,K,W,X,Y,Z | 1          |

### Entrée :

L’entrée contiendra :

- Le nombre de mot soumis au programme sur la première ligne.
- Les mots en question chacun sur une ligne dont on souhaite connaître la valeur.

### Sortie :

Le programme renvoie le nombre de points de chaque mot sur une ligne, suivi d’une autre phrase donnant l’écrivabilité ou non du mot :

```
>>> Le mot "xylophone" a une valeur de 32 points au Scrabble. Il est possible de former ce mot.
```

#### Exemples d’entrée/sortie :

```
3
Xylophone
BanAne
concomitance

>>> Le mot "xylophone" a une valeur de 32 points au Scrabble. Il est possible de former ce mot.
>>> Le mot "banane" a une valeur de 8 points au Scrabble. Il est possible de former ce mot.
>>> Le mot "concomitance" a une valeur de 19 points au Scrabble. Il est impossible de former ce mot.
```

## Conclusion :

Votre grand-père a admit l’utilité de votre spécialité et vous considère maintenant comme le prochain Elon Musk.
