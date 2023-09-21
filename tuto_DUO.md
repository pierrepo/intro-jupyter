---
title: Tutoriel Jupyter DUO
author: Pierre Poulain
license: Creative Commons Attribution-ShareAlike (CC BY-SA 4.0)
---

# Tutoriel DUO

## 1. Connection 
Ouvrez une session sur le Jupyter Hub de l'IFB. Pour cela :

- Ouvrez une page de votre navigateur web à l'adresse <https://jupyterhub.cluster.france-bioinformatique.fr/>
- Idendifiez-vous avec votre login et mot de passe IFB.
- Sur la page *Server Options*, choississez :
    + Reservation: No reservation
    + Account: **202304_duo**
    + Partition: fast
    + CPU(s): 4
    + Memory (in GB): 10
    + GPU(s): 0

    Votre instance Jupyter disposera donc de 4 processeurs, de 10 Go de RAM, et sera active 12 h (après ce laps de temps, elle sera détruite).
- Cliquez sur le bouton *Start* puis patientez quelques instants le temps que votre serveur Jupyter s'initialise.


## 2. Orientation

Vous êtes déjà familiers de l'interface JupyterLab, mais voici quelques rappels :

- Vous trouverez sur la gauche un explorateur de fichier qui vous permet de naviguer graphiquement dans l'arborescence du serveur.
    + Votre répertoire utilisateur se trouve dans `/shared/home/USERNAME` où `USERNAME` est votre nom d'utilisateur.
    + Votre répertoire de projet se trouve dans `/shared/projects/202304_duo/USERNAME` où `USERNAME` est votre nom d'utilisateur. Je vous rappelle que c'est **dans ce répertoire** que vous devez travailler.
- Sur la partie droite de l'inteface JupyterLab, vous avez le *Launcher* qui, comment son nom l'indique, permet de *lancer* (créer) des notebooks Jupyter dans plusieurs langages (Python, Bash ou R), RStudio, un terminal et plein d'autres choses.

En bas de la page, dans la rubrique *Other*, cliquez sur l'icône *Terminal* qui va lancer un terminal Unix dans JupyterLab.


## 3. Préparation des données

Depuis un terminal lancé dans JupyterLab, déplacez-vous dans votre répertoire de travail avec la commande :

```bash
$ cd /shared/projects/202304_duo/$USER
```

Exécutez ensuite la commande suivante :

```bash
$ git clone https://github.com/pierrepo/intro-jupyter
```

Vérifiez en ligne de commande, dans votre terminal, que le répertoire `intro-jupyter` a bien été créé.

Vérifiez aussi graphiquement, en utilisant l'explorateur de fichiers à gauche, que ce répertoire existe bien.

Pour la suite, vous trouverez les notebooks d'exercice dans le répertoire `intro-jupyter/notebooks`.


## 4. Exercice 1 : premier notebook

Ouvrez le notebook `intro_R.ipynb` en double-cliquant sur son nom depuis l'explorateur de fichiers (à gauche).

Si on vous le demande, sélectionnez si besoin un kernel R >= 4.

Suivez ensuite les instructions dans le notebook.


## 5. Exercice 2 : Markdown

Ouvrez le notebook `markdown.ipynb` dans JupyterLab en double-cliquant sur son nom. 

Suivez ensuite les instructions dans le notebook.


## 6. Exercice 3 : DESeq2

Créez un nouveau notebook Jupyter avec un **noyau R** (>= 4). Pour cela :

- Cliquez sur le gros bouton bleu "+" en haut à gauche de l'interface JupyterLab.
- Dans la section *Notebook*, cliquez sur l'icone *R* (normalement R 4.0.3).

Renommez ce nouveau notebook `analyse_DESeq2.ipynb` (clic droit sur le nom du notebook puis *Rename Notebook...*).

Téléchargez depuis Moodle le script R `Utilisation_DESeq2.R` sur votre machine locale.

Transférez ensuite ce script vers votre espace de travail sur JupyterLab en cliquant sur l'icone ⬆️ *Upload Files* (à gauche, au dessus de l'explorateur de fichiers).

Une fois téléchargé dans JupyterLab, double-cliquez sur le nom du script pour l'ouvrir dans l'éditeur de texte de JupyterLab.

Transformez ce script en notebook Jupyter en reportant les commandes R dans des cellules de code. Utilisez des cellules Markdown pour ajouter des commentaires sur les cellules de code et refléter la structure du script initial. Dans la barre d'outils au dessus du notebook, un menu permet de changer le type de cellule (Code ou Markdown).

N'oubliez pas d'exécuter votre notebook pour vérifier que celui fonctionne correctement.

**Remarques :** 

1. Le chargement des bibliothèques R avec la commande `library()` peut afficher de nombreux messages sur fond rose. C'est tout à fait normal.
1. Certains traitements peuvent prendre du temps, soyez patient.

À la fin de votre notebook, affichez la liste des bibliothèques utilisées avec leurs versions.

Exportez ensuite votre notebook au format HTML. Consultez pour cela les instructions à la fin du notebook `intro_R.ipynb`.

Enfin, partagez votre notebook au format .html sur le canal Slack de la promo.

