# Niveau 1

Cloner ce repo et exécuter le script `main.py`.
Aucune erreur ne doit être affichée.

## Mise en oeuvre

Pour exécuter le script `main.py`, il faut installer les dépendances nécessaires au projet.
Pour cela, il faut installer `numpy` dans son environnement Python.
Il faut donc s'assurer que `pip` est bien présent dans son environnement Python.

```bash
# Installation de pip
python -m ensurepip --default-pip
```

Ensuite, il faut installer `numpy` dans son environnement Python.

```bash
# Installation de numpy
pip install numpy
```

Enfin, il faut exécuter le script `main.py`.

```bash
# Exécution du script
python main.py
```

# Niveau 2

Installer une dépendance supplémentaire (`pandas`) et afficher sa version (de la même façon que pour `numpy`).

# Niveau 3

Trouver un moyen **d'isoler les dépendances** de mon projet. Autrement dit, je ne veux pas installer les dépendance
nécessaires au projet dans mon environnement global, mais dans un environnement spécifique au projet.

# Niveau 4

Trouver un moyen de décrire les dépendances de mon projet et de les installer automatiquement.
Cela s'avère très utile lorsque l'on souhaite partager son projet avec d'autres personnes (par exemple, sur GitHub).
