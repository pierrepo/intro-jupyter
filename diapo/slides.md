class: center, middle

# Introduction à Jupyter

## M2BI 2019-2020


<br /><br /><br /><br /><br /><br />

.leftcol[
<img src="img/Universite_Paris_logo_horizontal_2000px.png"
	 height="100px" style="vertical-align:top;">
 </img>
]

.righcol.right[
<br /><br />
Pierre Poulain <br />
pierre.poulain@univ-paris-diderot.fr <br />
@pierrepo
]

.footer[
Ce contenu est mis à disposition selon les termes de la licence Creative Commons BY-SA 4.0
]

---

layout: true
name: title
class: center, middle
.footer[
Poulain 2019 CC BY-SA
]

---

layout: true
name: contentleft
class: top, left
.footer[
Poulain 2019 CC BY-SA
]

---

layout: true
name: contentcenter
class: top, center
.footer[
Poulain 2019 CC BY-SA
]

---

template: contentleft

# Objectifs d'apprentissage

--

- Décrire l'écosystème Jupyter.

- Installer Jupyter Lab.

- Créer un notebook Jupyter.

- Utiliser les bonnes pratiques pour construire un notebok.

---
template: contentleft

# Jupyter

<https://jupyter.org/>

IPython, 2014... (Brian Granger & Fernando Perez)

--

.center[
    <img src="img/20180624_prix_ACM_Jupyter_SylvainCorlay_1010945292877754368.png"
         height="400px">

]
---
template: contentleft

## Jupyter Notebook

- Python dans le navigateur

--

- Mais aussi **Ju**lia, **Py**thon, **R**, C++...

--

- Analyse de données : code + graphiques + explications + formules mathématiques... 

--

- Export : py, html, pdf

--

<br />
<br />
Intro : [Jupyter: Tools for the Life Cycle of a Computational Idea](https://sinews.siam.org/Details-Page/jupyter-tools-for-the-life-cycle-of-a-computational-idea)


---
template: contentleft

# Jupyter Notebook

.center[
    <img src="img/Lorentz.jpg" height="500px" />
]

---
template: contentleft

# Jupyter Notebook

5,2 millions notebooks sur GitHub (07/09/2019) ! <br />
[Estimate of Public Jupyter Notebooks on GitHub](http://nbviewer.jupyter.org/github/parente/nbestimate/blob/master/estimate.ipynb)
<br />
<br />

--

Utilisé en 1re année à Berkekey (1800 étudiants) : <br />
[The course of the future – and the technology behind it](https://data.berkeley.edu/news/coursefuture)
<br />
<br />

--

Utilisé chez Google, Microsoft, IBM, Bloomberg, Nasa, SoundCloud, NetFlix, La banque mondiale [...](https://jupyter.org/)


---
template: contentleft

# Exemples

- [A gallery of interesting Jupyter Notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)  
- [Bioinformatics with Python Cookbook](https://github.com/tiagoantao/bioinf-python/blob/master/notebooks/Welcome.ipynb) ([FastQ files](https://github.com/tiagoantao/bioinf-python/blob/f2e05df2d7baa54f9fbbc246b2526ee57d8b451c/notebooks/01_NGS/Working_with_FASTQ.ipynb)) ([PDB files](https://github.com/tiagoantao/bioinf-python/blob/f2e05df2d7baa54f9fbbc246b2526ee57d8b451c/notebooks/06_Prot/Stats.ipynb))
- [An open RNA-Seq data analysis pipeline tutorial with an example of reprocessing data from a recent Zika virus study](http://nbviewer.jupyter.org/github/maayanlab/Zika-RNAseq-Pipeline/blob/master/Zika.ipynb)


---
template: contentleft

## Jupyter**Lab**

- Environnement de développement et d'analyse.
- 1.0 été 2019.

--

Installation dans un environnement conda
```
$ conda install -c conda-forge jupyterlab
```

--

Lancement 
```
$ jupyter lab
```
(pour les notebooks classiques : `$ jupyter notebook`)

--

Intro :

- vidéo : [JupyterLab: The Next-Generation Jupyter Frontend](https://www.youtube.com/watch?v=w7jq4XgwLJQ) (Brian Granger, 2017)
- article : [JupyterLab is Ready for Users](https://blog.jupyter.org/jupyterlab-is-ready-for-users-5a6f039b8906)
- vidéo : [Sea change: What happens when Jupyter becomes pervasive at a university?](https://www.oreilly.com/ideas/sea-change-what-happens-when-jupyter-becomes-pervasive-at-a-university) (Fernando Perez, 2018)


---
template: contentleft

# Pour aller plus loin

[Ten simple rules for writing and sharing computational analyses in Jupyter Notebooks](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007007),   
Rule *et al.*, PLOS Comput. Biol., 2019.  
[> exemples de notebooks](https://github.com/jupyter-guide/ten-rules-jupyter)

<br />

[The Scientific Paper Is Obsolete](https://www.theatlantic.com/science/archive/2018/04/the-scientific-paper-is-obsolete/556676/),  
Somers, The Atlantic, 2018.

<br />

Dashboarding avec Voila :
- [vidéo](https://www.youtube.com/watch?v=VtchVpoSdoQ), M. Breddels et M. Renou, SciPy 2019.
- [demo](https://github.com/maartenbreddels/scipy-voila-demo)
  
---
template: contentleft

background-color: #cccccc

# C'est parti ! 🚀

## 💻 Tutoriel


