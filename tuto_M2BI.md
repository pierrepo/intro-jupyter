---
title: Tutoriel Jupyter M2 BI
author: Pierre Poulain
license: Creative Commons Attribution-ShareAlike (CC BY-SA 4.0)
---

# Préparation de l'environnement local

Dans un environnement Unix, clonez ce dépôt GitHub :
```
$ git clone https://github.com/pierrepo/intro-jupyter.git
```

Etrez dans le répertoire `intro-jupyter` ainsi créé :
```
$ cd intro-jupyter
```

Créez ensuite l'environnement nécessaire avec conda :
```
$ conda env create -f binder/environment.yml
```

Activez le nouvel environnement ainsi créé :
```
$ conda activate jupyter-demo
```

Installez certaines extensions pour Jupyter Lab avec la commande :
```
$ bash binder/postBuild
```

Enfin, lancez Jupyter. Soit l'inteface classique :
```
$ jupyter notebook
```

soit l'interface Jupyter Lab, plus récente et plus évoluée (recommandée) :
```
$ jupyter lab
```

Ces deux commandes lancent un mini-serveur web sur votre machine et ouvre normalement votre navigateur sur l'interface Jupyter choisie.

Pour arrêter Jupyter, pressez **deux** fois de suites les touches <kbd>Ctrl</kbd>+<kbd>C</kbd> dans le terminal depuis lequel vous avez lancé Jupyter.

Remarque : fermer l'onglet de votre navigateur n'arrête pas le mini-serveur Jupyter.


# Exercices

Les notebooks Jupyter se trouvent dans le répertoire `notebooks`.

Ouvrez dans l'ordre les notebooks en double-cliquant sur leur nom. 

- `intro.ipynb`
- `markdown.ipynb`
- `matplotlib.ipynb`
- `demo-R.ipynb`
- `ipywidgets.ipynb`
  
Suivez les instructions dans chaque notebook.


# Jupyter en ligne

Si Jupyter n'est pas installé localement sur votre machine, vous pouvez utiliser une version en ligne. Cette version peut prendre quelques minutes à charger, soyez patients et profitez-en pour vous préparer un thé en attendant.

Interface classique :

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pierrepo/intro-jupyter/master)

Interface Jupyter Lab (recommandée) :

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pierrepo/intro-jupyter/master?urlpath=lab)

Les notebooks sont directement accessibles dans le répertoire `notebooks`.
