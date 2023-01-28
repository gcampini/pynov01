# Niveau 1
Cloner ce repo et exécuter le script `main.py`.
Aucune erreur ne doit être affichée.

# Niveau 2
Installer une dépendance supplémentaire (`pandas`) et afficher sa version (de la même façon que pour `numpy`).

# Niveau 3
Trouver un moyen **d'isoler les dépendances** de mon projet. Autrement dit, je ne veux pas installer les dépendance nécessaires au projet dans mon environnement global, mais dans un environnement spécifique au projet.

# Niveau 4
Trouver un moyen de décrire les dépendances de mon projet et de les installer automatiquement.
Cela s'avère très utile lorsque l'on souhaite partager son projet avec d'autres personnes (par exemple, sur GitHub).

## Mise en oeuvre
Lister les dépendances **déjà installées** dans votre environnement :
```bash
pip freeze
```

Afin de décrire les dépenances de votre projet, la convention veut que l'on crée un fichier `requirements.txt` contenant une liste de dépendances, une par ligne. Par exemple, pour notre cas :
```txt
numpy==1.24.1
pandas==1.5.3
python-dateutil==2.8.2
pytz==2022.7.1
six==1.16.0
```

Pour installer les dépendances décrites dans ce fichier, il suffit de lancer la commande suivante :
```bash
pip install -r requirements.txt
```
