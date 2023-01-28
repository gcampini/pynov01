# Niveau 1

Cloner ce repo et exécuter le script `main.py`.
Aucune erreur ne doit être affichée.

# Niveau 2

Installer une dépendance supplémentaire (`pandas`) et afficher sa version (de la même façon que pour `numpy`).

# Niveau 3

Trouver un moyen **d'isoler les dépendances** de mon projet. Autrement dit, je ne veux pas installer les dépendance
nécessaires au projet dans mon environnement global, mais dans un environnement spécifique au projet.

## Mise en oeuvre

La première étape consiste à créer un environnement virtuel. Pour cela, il faut installer `venv` (si ce n'est pas déjà
fait) et exécuter la commande suivante :

```bash
python -m venv venv
```

Cette commande va créer un dossier `venv` dans lequel se trouve un environnement virtuel. Pour l'activer, il faut
exécuter la commande suivante :

### Linux

```bash
source venv/bin/activate
```

### Windows

```bash
venv\Scripts\activate.bat
```

---
Pour désactiver l'environnement virtuel, il suffit d'exécuter la commande suivante :

```bash
deactivate
```

N.B. : Ne surtout pas oublier d'inclure le dossier `venv` dans le `.gitignore` !

# Niveau 4

Trouver un moyen de décrire les dépendances de mon projet et de les installer automatiquement.
Cela s'avère très utile lorsque l'on souhaite partager son projet avec d'autres personnes (par exemple, sur GitHub).
