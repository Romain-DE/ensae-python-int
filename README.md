# Mise en place de l'environnement de travail
Prérequis : 
- Installer VSCode : https://code.visualstudio.com/download
- Installer Python 3
    - Sous Windows : https://www.python.org/downloads/ ou Microsoft Store
    - Sous Mac : `brew install python3`
- Optionnel : installer git
    - sous Windows : https://git-scm.com/download/win
    - sous Mac : https://git-scm.com/download/mac


Pour utiliser le repo dans le cadre cette formation:

1. Ouvrir VSCode et son terminal, et choisir un dossier de travail. Par exemple : `User/Formations/ENSAE/Python`.
S'y rendre avec la commande suivante : 
`cd User/Formations/ENSAE/Python`

2. Placer le répertoire dans ce dossier :
    - avec git : `git clone https://github.com/Romain-DE/ensae-python-int.git`
    - manuellement, en téléchargeant le zip

3. Se placer dans le dossier avec la commande : `cd ensae-python-int`
4. Créer un environnement virtuel : `python3 -m venv python_int_env`. Il sera créé dans l'emplacement actuel : `User/Formations/ENSAE/Python/ensae-python-int`.
5. Activer l'environnement virtuel :
    - Sous Windows : `python_int_env\Scripts\activate`
    - Sous Mac : `source python_int_env/bin/activate`
6. Installer les dépendances nécessaires : `pip install -r requirements.txt`