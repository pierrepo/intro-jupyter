---
title: Tutoriel Jupyter M2 BI
author: Pierre Poulain
license: Creative Commons Attribution-ShareAlike (CC BY-SA 4.0)
---

Tutoriel M2 BI

# Préparation de l'environnement local

Dans un environnement Unix, clonez ce dépôt GitHub :
```bash
$ git clone https://github.com/pierrepo/intro-jupyter.git
```

Entrez dans le répertoire `intro-jupyter` ainsi créé :
```bash
$ cd intro-jupyter
```

Créez ensuite l'environnement nécessaire avec conda :
```bash
$ conda env create -f binder/environment.yml
```
ou avec mamba si celui-ci est installé :
```bash
$ mamba env create -f binder/environment.yml
```

Activez le nouvel environnement :
```bash
$ conda activate jupyter-demo
```

Enfin, lancez Jupyter Lab :
```bash
$ jupyter-lab
```

Cette commande lance un mini-serveur web sur votre machine et ouvre normalement votre navigateur sur l'interface Jupyter Lab.


### Cas de Windows Subsystem for Linux (WSL) dans Windows

Si vous utilisez WSL dans Windows, l'interface Jupyter n'apparaitra pas dans le navigateur. Par contre, dans le terminal depuis lequel vous avez lancé Jupyter, vous trouverez deux lignes qui ressemblent à :
```
http://localhost:8888/?token=cd78adf4af2c800a16cc958e2303bc4c97c1194d86ebde04
http://127.0.0.1:8888/?token=cd78adf4af2c800a16cc958e2303bc4c97c1194d86ebde04
```
Copiez une de ces lignes et collez-la dans votre navigateur. L'interface Jupyter Lab devrait alors apparaître.


### Stopper Jupyter Lab

Pour arrêter Jupyter Lab, pressez **deux** fois de suites les touches <kbd>Ctrl</kbd>+<kbd>C</kbd> dans le terminal depuis lequel vous avez lancé Jupyter.

Remarque : fermer l'onglet de votre navigateur n'arrête pas le mini-serveur Jupyter.


# Exercices

Les notebooks Jupyter se trouvent dans le répertoire `notebooks`.

Ouvrez dans l'ordre les notebooks en double-cliquant sur leur nom. 

- `intro_Python.ipynb`
- `intro_R.ipynb`
- `markdown.ipynb`
- `matplotlib.ipynb`
  
Suivez les instructions indiquées dans chaque notebook.


# Jupyter en ligne

Si Jupyter n'est pas installé localement sur votre machine, vous pouvez utiliser une version en ligne. Cette version peut prendre plusieurs minutes à charger, soyez patients et profitez-en pour vous préparer un thé en attendant.

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pierrepo/intro-jupyter/master?urlpath=lab)

Les notebooks sont directement accessibles dans le répertoire `notebooks`.
