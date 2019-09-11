---
title: Tutoriel Jupyter
author: Pierre Poulain
license: Creative Commons Attribution-ShareAlike (CC BY-SA 4.0)
---

# Tutoriel

## Lancer JupyterLab

Clonez le dépôt <https://github.com/pierrepo/intro-jupyter/>

Chargez l'environnement conda `ppoulain-jupyter-2019`.

Lancez JupyterLab.

Explorez et modifiez les différents notebooks.


## Installer JupyterLab

En utilisant le fichier yaml `environment.yml`, créez votre propre environnement.

Chargez ce nouvel environnement, puis activez ensuite les widgets pour Jupyter Lab avec la commande :
```
$ jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

Lancez enfin Jupyter Lab :
```
$ jupyter lab
```

Vérifiez que les notebooks précédants fonctionnent.

Vous pouvez également tester l'interface Jupyter classique avec la commande :

```
$ jupyter notebook
```


## Créer un notebook

Créez votre propre notebook pour votre projet.

Enregistrez-le dans un dépôt git puis visualisez-le depuis GitHub (en statique).

Si vous avez le temps, essayez avec Binder (utilisez l'exemple du cours).




