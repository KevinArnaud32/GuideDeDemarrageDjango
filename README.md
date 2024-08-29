# GuideDeDemarrageDjango
Explication de la structure d'un projet django 
Dans un premier temps creer un dossier dans lequel va se trouver notre projet Django
Ensuite creer un environnment virtuel dans le projet Django à l'aide de la commande python -m venv <nom_environnement>
ex: python -m venv env """env ici est mon environnement virtuel"""
Et dans l'environnement virtuel installer le framework django grace à la commande pip install django
"""pip""" est le mpt clé qui permet d'installer des bibliothèque
Après l'installation nous pouvons enregistrer l'environnement, cela se fait grace à la commande pip freeze > < ficher_txt >
ex: pip freeze > requirements.txt """Ici notre fichier requirements.txt contient contient les informations de nôtre environnement << env >> créé
Bien ! avant de commencer par creer notre projet Django, il est nécéssaire d'activer notre environnement virtuel
Cela se fait grace à la commande .\env\Scripts\activate. Afin que l'environnement nécessaire de se trouver à la racine du dossier crée au préalable
Après avoir préparer l'environnement, commençons par creer un projet Django
django-admin startproject est la commande qui va nous permettre de creer un nouveau projet django sans oublier le nom du projet à la fin de la commande
Cette commande est utilisé comme suit: django-admin startproject MonProjet """Ici < MonProjet > est le nom de notre projet Django
Notre projet sera représenté par un dossier 'MonProjet' dans lequel se trouvera un autre dossier du même nom que le nom du projet dans notre cas 'MonProjet' crée par Django lui-même qui contiendra l'ensemble des paramètre de notre application
Ensuite se trouvant dans notre projet Djano 'MonProjet' nous pouvons maintenant creer nos applications django.
La creation d'une application Django se fait grace la commande django-admin startapp < nom_application >
Ex: django-admin startapp MonApp """MonApp est le nom de mon application crée dans le projet Django
Dans les paramètres de notre projet Django se trouve un fichier seetings.py dans lequel se trouve l'ensemble des application nous allons ajouter notre application django
