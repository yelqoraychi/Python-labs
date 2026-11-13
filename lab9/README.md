# LAB 9 – Python et NumPy

## Étape 1 : Installation de NumPy

Installation de NumPy via le terminal et vérification de son installation.

<img width="787" alt="Lab9 E0" src="images/Lab9%20E0.png">

NumPy est bien installé et sa version est `2.2.4`.

## Étape 2 : Création des tableaux 1D et 2D

Implémentation des tableaux 1D et 2D et exploration des différentes fonctions disponibles dans le module NumPy, avec un test à la fin du tableau 1D (`+5`).

**Exemple d'exécution :**

<img width="471" alt="LAB 9 E1" src="images/LAB%209%20E1.png">

## Étape 3 : Exploration des propriétés des tableaux

Exploitation du tableau 2D de l'exemple précédent et test des différentes propriétés :

- `dtype` : type des éléments du tableau.
- `shape` : dimensions du tableau.
- `ndim` : nombre de dimensions.
- `size` : nombre total d'éléments.

<img width="471" alt="LAB 9 E2" src="images/LAB%209%20E2.png">

### Différence entre `dtype` et `type`

Création d'un nouveau tableau `A` et exploration de la différence entre `dtype` et `type`.

<img width="464" alt="LAB 9 E2 B" src="images/LAB%209%20E2%20B%20.png">

## Étape 4 : Utilisation de `reshape()`

Utilisation de `reshape()` pour modifier la forme d'un tableau sans effectuer de recopie lorsque cela est possible.

<img width="512" alt="LAB 9 E3" src="images/LAB%209%20E3%20.png">

## Étape 5 : Exploration supplémentaire

Exploration de quelques fonctions supplémentaires disponibles dans NumPy.

<img width="512" alt="LAB 9 E5" src="images/LAB%209%20E%205%20.png">

## Étape 6 : Différence entre une liste Python et `np.zeros()`

La différence entre `alist` et `np.zeros()` est que :

- `alist` est de type `list`.
- `np.zeros()` retourne un tableau de type `ndarray`.

La différence apparaît notamment dans les opérations arithmétiques :

- `alist + [1]` concatène les deux listes.
- `ndarray + 1` ajoute `1` à tous les éléments du tableau.

**Remarque :** une erreur sera produite car `4 × 3 > 9`.
