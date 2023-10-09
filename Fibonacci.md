# La suite de Fibonacci

## Club Info 2023 – Niveau Intermédiaire

### Contexte :

En mathématiques, la suite de Fibonacci est une suite de nombres entiers dans laquelle chaque nombre est la somme des deux nombres qui le précèdent.

Elle commence par les nombres 0 et 1 puis se poursuit avec 1 (0+1), 2 (1+1), 3 (1+2), 5 (2+3), 8 (3+5), etc.

Les termes de cette suite, c’est-à-dire les nombres qui apparaissant dans cette suite, sont appelés nombres de Fibonacci.

Vous avez pour objectif d’afficher une liste contenant les n premiers termes de la suite de Fibonacci.

Pour se faire, on donne le programme suivant:

```
n <- entrer un chiffre
fibo <- liste composée de n 0
fibo[0] <- 0
fibo[1] <- 1
Pour i allant de 2 à n faire :
    fibo[i] <- fibo[i-1] + fibo[i-2]
afficher fibo
```
### Énoncé :

Réalisez ce programme et modifiez le pour obtenir une fonction `fibonacci` qui prend en paramètre un nombre `n` et qui renvoie une liste qui contient les n premiers termes de la suite.
