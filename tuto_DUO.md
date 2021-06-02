---
title: Tutoriel Jupyter DUO
author: Pierre Poulain
license: Creative Commons Attribution-ShareAlike (CC BY-SA 4.0)
---

# Tutoriel DUO

## 1. Connection 
Ouvrez une session sur le Jupyter Hub de l'IFB. Pour cela :

- Ouvrez une page de votre navigateur web à l'adresse https://jupyterhub.cluster.france-bioinformatique.fr/
- Idendifiez-vous avec votre login et mot-de-passe IFB.
- Sur la page *Server Options*, choississez un profile *Small (1 cpu, 1GB RAM, 12h)*. Votre instance Jupyter disposera donc d'un processeur et de 1 Go de RAM, et ce sera active 12 h (après ce laps de temps, elle sera détruite).
- Patientez quelques instants le temps que votre serveur Jupyter s'initialise.
- L'interface que vous avez en face de vous s'appelle Jupyter Lab.

## 2. Orientation et préparation des données

Vous trouverez sur la gauche un explorateur de fichier qui vous permet de naviguer graphiquement 🥳 dans l'arborescence du serveur.

Votre répertoire utilisateur se trouve dans `/shared/home/USERNAME` où `USERNAME` est votre nom d'utilisateur.

Votre répertoire de projet se trouve dans `/shared/projects/uparis_duo_2020/USERNAME` où `USERNAME` est votre nom d'utilisateur. Je vous rappelle que c'est dans ce répertoire que vous devez travailler.

Dans la partie droite de votre navigateur, vous avez le *Launcher* qui, comment son nom l'indique, permet de *lancer* (créer) des notebooks Jupyter (Python, Bash ou R), RStudio, un terminal et plein d'autres choses.

En bas de la page, dans la rubrique *Other*, cliquez sur l'icône *Terminal* qui va lancer un terminal Unix dans Jupyter Lab.


## 3. Préparation des données

Depuis un terminal lancé dans le Jupyter Lab, déplacez vous dans votre répertoire de travail avec la commande :
```bash
cd /shared/projects/uparis_duo_2020/USERNAME
```
où `USERNAME` est votre nom d'utilisateur.

Exécutez ensuite la commande suivante : 
```
git clone https://github.com/pierrepo/intro-jupyter
```

Vérifiez en ligne de commande, dans votre terminal, que le répertoire `intro-jupyter` a bien été créé.

Vérifiez aussi graphiquement, en utilisant l'explorateur de fichiers à gauche, que ce répertoire existe bien.

Pour la suite, vous trouverez les notebooks d'exercice dans le répertoire `intro-jupyter/notebooks`.


## Exercice 1 : `intro_R.ipynb`

Ouvrez le notebook `intro_R.ipynb` en double-cliquant sur son nom.

Suivez ensuite les instructions dans le notebook.


## Exercice 2 : `markdown.ipynb`

Ouvrez le notebook `markdown.ipynb` dans Jupyter en double-cliquant sur son nom. 

Suivez ensuite les instructions dans le notebook.


## Exercice 3 : `matplotlib.ipynb`

Ouvrez le notebook `matplotlib.ipynb` dans Jupyter en double-cliquant sur son nom. 

Suivez ensuite les instructions dans le notebook.

