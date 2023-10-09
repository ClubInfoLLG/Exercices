# Choix complexe
## Club Info 2023 - Niveau Débutant

### Énoncé :

Léane, Jade, Hubert, Arthur, Yoon, et Céline souhaitent organiser une soirée cinéma chez l'un d'entre eux.
Mais pour ce faire, ils doivent commencer par choisir quel film ou série ils vont regarder.
Après quelques discussions, ils n'arrivèrent toujours pas à se mettre d'accord.
C'est alors que Jade propose que chaque personne écrive le titre du film ou de la série qu'il voudrait voir et un autre titre qu'il ne voudrait absolument pas regarder.
Après quelques minutes de réflexion et après avoir récolté les deux titres des six amis, les films et les séries ont été regroupés dans une liste `adore` et une liste `deteste`.

Vous devez, à partir de deux listes `adore` et `deteste`, afficher le nombre de films et de séries que les six jeunes peuvent regarder.
On considère que les jeunes peuvent regarder un film si et seulement si au moins une personne adore le film, et que personne ne le déteste.

### Entrée :
- Sur la première ligne, le nombre d'invités présents.
- Sur les lignes suivantes, une liste des noms du film adoré de chaque personne. 
- Sur les lignes suivantes, une liste des noms du film détesté de chaque personne.

### Sortie :
Afficher, sur une ligne, le nombre de films qu’ils peuvent regarder ainsi que la liste de ces films.

### Exemples d'entrée/sortie :
```
6

Planet Wars
Le roi des bagues
Pinky Muters
i3lock Holmes
Nurse Whom
Belluaire

Le roi des bagues
La Raison a ses raisons
Captain France
Belluaire
Edification
Angers Patrouille Judiciaire


>>> 4 ["Planet Wars", "Pinky Muters", "i3lock Holmes", "Nurse Whom"]
```

