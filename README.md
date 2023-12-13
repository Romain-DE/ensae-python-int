# Mise en place du poste de travail
Pour utiliser le repo dans le cadre cette formation:
1. Installer VSCode : https://code.visualstudio.com/download
2. Installer Python 3
    - Sous Windows : https://www.python.org/downloads/ ou Microsoft Store
    - Sous Mac : `brew install python3`
3. Ouvrir VSCode et son terminal, choisir le dossier de travailet s'y rendre. Par exemple : `User/Formations/ENSAE/Python_int`, avec la commande suivante : `cd User/Formations/ENSAE/Python_int`
4. Cloner le répertoire git dans ce dossier : `git clone https://github.com/Romain-DE/ensae-python-int.git`
5. Créer un environnement virtuel : `python3 -m venv python_int_env`
6. Activer l'environnement virtuel :
    - Sous Windows : `python_int_env\Scripts\activate`
    - Sous Mac : `source python_int_env/bin/activate`
7. Installer les dépendances nécessaires : `pip install requirements.txt`