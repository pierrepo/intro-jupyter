# Introduction à Jupyter DUBii 2020

[Diapo](https://pierrepo.github.io/intro-jupyter-dubii/slides/)


## Préparation de l'environnement local

Sur vos machines locales (= **pas sur le cluster**), chargez l'environnement conda qui contient Jupyter :
```
$ conda activate pfuchs-dubii-2020
```
Rappel : le caractère `$` en début de ligne représente l'invite de commande. Il n'est pas à taper.

Vérifiez que Jupyter est bien installé avec la commande
```
$ jupyter lab --version
```

Vous devriez obtenir `2.0.0` ou une valeur supérieure.

Créez dans votre répertoire personnel le répertoire `dubii/python/jupyter` :
```
$ mkdir -p ~/dubii/python/jupyter
```
Rappel : l'option `-p` de la commande `mkdir` permet de créer un répertoire sans que la commande ne plante si le répertoire existe déjà. Elle permet aussi (et surtout) de créer une succession de répertoires imbriqués (ici le répertoire `jupyter` dans le répertoire `python` dans le répertoire `dubii`).

Dirigez-vous ensuite dans ce répertoire :
```
$ cd ~/dubii/python/jupyter
```

Puis, lancez Jupyter. Soit l'inteface classique :
```
$ jupyter notebook
```

soit l'interface Jupyter Lab, plus récente et plus évoluée :
```
$ jupyter lab
```

Ces deux commandes lancent un mini-serveur web sur votre machine et ouvre normalement votre navigateur sur l'interface Jupyter choisie.

Pour arrêter Jupyter, pressez **deux** fois de suites les touches <kbd>Ctrl</kbd>+<kbd>C</kbd> dans le terminal depuis lequel vous avez lancé Jupyter.

Remarque : fermer l'onglet de votre navigateur n'arrête pas le mini-serveur Jupyter.



## Exercices 

### Exercice 1 : intro

Suivez les instructions de la section précédentes pour préparer votre environnement (répertoire + conda).

Dans le répertoire `~/dubii/python/jupyter`, téléchargez ensuite le notebook d'intro :
```
$ curl https://raw.githubusercontent.com/pierrepo/intro-jupyter-dubii/master/notebooks/intro.ipynb -o intro.ipynb
```

Lancez Jupyter puis ouvrez le notebook `intro.ipynb` en double-cliquant sur son nom. 

Suivez ensuite les instructions dans le notebook.


### Exercice 2 : markdown

Toujours dans le répertoire `~/dubii/python/jupyter`, téléchargez le notebook `markdown.ipynb` et l'image `logo.png` :

```
$ curl https://raw.githubusercontent.com/pierrepo/intro-jupyter-dubii/master/notebooks/markdown.ipynb -o markdown.ipynb
$ curl https://raw.githubusercontent.com/pierrepo/intro-jupyter-dubii/master/notebooks/logo.png -o logo.png
```

Ouvrez le notebook `markdown.ipynb` dans Jupyter en double-cliquant sur son nom. 

Suivez ensuite les instructions dans le notebook.


### Exercice 3 : matplotlib

Toujours dans le répertoire `~/dubii/python/jupyter`, téléchargez le notebook `matplotlib.ipynb` :

```
$ curl https://raw.githubusercontent.com/pierrepo/intro-jupyter-dubii/master/notebooks/matplotlib.ipynb -o matplotlib.ipynb
```

Ouvrez le notebook `matplotlib.ipynb` dans Jupyter en double-cliquant sur son nom. 

Suivez ensuite les instructions dans le notebook.



## Jupyter en ligne

Si Jupyter n'est pas installé localement sur votre machine, vous pouvez utiliser une version en ligne. Cette version peut prendre quelques minutes à charger, soyez patients et profitez-en pour vous préparer un thé en attendant.

Interface classique :

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pierrepo/intro-jupyter-dubii/master)

Interface Jupyter Lab (recommandée) :

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pierrepo/intro-jupyter-dubii/master?urlpath=lab)

Les notebooks sont directement accessibles dans le répertoire `notebooks`.