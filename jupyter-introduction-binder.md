# Data and Project Organisation
[Data & Project Organisation](https://reproducible-science-curriculum.github.io/organization-RR-Jupyter/01-introduction/)

[project organisation slides](https://reproducible-science-curriculum.github.io/organization-RR-Jupyter/slides/02_slideshow_organization.slides.html)

# Jupyter Notebook

* [Intro to Jupyter Notebook](https://github.com/Reproducible-Science-Curriculum/introduction-RR-Jupyter/blob/gh-pages/notebooks/Jupyter_Intro_Background.ipynb)

* [Navigating Notebook](https://github.com/Reproducible-Science-Curriculum/introduction-RR-Jupyter/blob/gh-pages/notebooks/Navigating%20the%20notebook%20-%20instructor%20script.ipynb)

## magics

* timeit

```py
%time x = range(10000)
%timeit x = range(10000)
```

* using variables between notebooks

```py
#notebook1
a = "from notebook 1"
%store a

#notebook2
%store -r
print(a)
```

* [Exporting Jupyter Notebook](https://reproducible-science-curriculum.github.io/publication-RR-Jupyter/02-exporting_the_notebook/index.html)

* [Sharing](https://reproducible-science-curriculum.github.io/sharing-RR-Jupyter/)

## Diffing Notebooks

```sh
pip install nbdime

nbdiff notebook_1.ipynb notebook_2.ipynb

nbdiff-web notebook_1.ipynb notebook_2.ipynb

nbdime config-git --enable --global
```

# MyBinder
[From Zero to Binder](https://github.com/Build-a-binder/build-a-binder.github.io/blob/master/workshop/10-zero-to-binder.md)
