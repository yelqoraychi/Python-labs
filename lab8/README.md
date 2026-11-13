# LAB-8

## Étape 0 : Création du dossier de travail

<img width="698" alt="LAB 8 E0" src="images/LAB%208%20E0.png">

## Étape 1 : Création du module `utils.py`

Création du fichier `utils.py` et implémentation des fonctions nécessaires à utiliser dans le script principal.

<img width="698" alt="LAB 8 E1" src="images/LAB%208%20E1.png">

## Étape 2 : Utilisation du module `utils.py`

Utilisation du module `utils.py` dans le script `app.py` et vérification de la validité de l'import à l'aide d'un test d'exécution.

<img width="698" alt="LAB 8 E2" src="images/lab%208%20E2.png">

## Étape 3 : Vérification depuis le terminal

Vérification et exécution du programme depuis le terminal.

<img width="698" alt="LAB 8 E3" src="images/LAB8%20E3.png">

## Étape 4 : Avantages des modules

- **Clarté :** `utils.py` ne contient que des fonctions utilitaires (aucune logique interactive).
- **Réutilisation :** un autre script (ex. `main.py`) pourrait importer `utils` sans copier le code.
- **Tests :** on peut tester `utils` indépendamment (via un framework comme `unittest` ou `pytest`).
- **Organisation :** dans un projet plus grand, on organise les modules en sous-dossiers (package).
- **Docstring :** un `help(utils)` montrera la documentation minimale que tu as mise en commentaire.
