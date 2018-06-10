# LOCIE NOTEBOOK

This is a repository with some useful snippets, tutorial or explaination linked to computation in python.

Broad topics will be talked about (and the repo is under construction).

## Installation of dependencies

Deps can be installed with [`pipenv`](https://docs.pipenv.org/) with `pipenv sync` in the root folder. Jupyter will be then launched with

`pipenv run jupyter notebook`

or

`pipenv run jupyter lab`

## Table of Contents:

### [Python, the language](./base_python)

Useful tutorial or snippets about the python language itself : data structure, useful libraries not directly related to numerical computation.

- [Unlock the power of your computer with multiprocessing computation (en)](./base_python/multiprocessing.ipynb)
- !DRAFT [functools and functional programming (en)](./base_python/functools_funct_program-en.ipynb)
- !DRAFT [functools et la programmation fonctionnelle (fr)](./base_python/functools_funct_program-fr.ipynb)
- !DRAFT [Classy iterable with itertools (en)](base_python/itertools-en.ipynb)
- !DRAFT [Itérer avec classe avec itertools (fr)](base_python/itertools-fr.ipynb)


### [Numpy](./numpy)

Numpy is the main brick of the computation in python. It's based on C routines which allow fast computation without have to sacrifice the ease of use.

### [Scipy](./scipy)

Scipy is a higher level brick than numpy and contain a lot of powerful routines to deal with almost all numerical analysis cases : interpolation, signal analysis, integration, linear algebra, statistic analysis and so on.

### [Pandas](./pandas)

Pandas is the dedicated tool to deal with tabular data. It's the excel on steroid for python. It allows easy manipulation and complex request on the data, statistic analysis, a broad range of I/O tool that allows to import a lot of different file formats. (.csv, .xls/x, .hdf, SQL databases, for multiple files, remote data...).

### [Vizualisation](./vizualisation)

Regroup all the viz tools: the classic matplotlib, but also seaborn (statistic based vizualisation), bokeh and holoviews that allow rich and interactive vizualisation.

### [Machine Learning and optimization](./ml)

Is a set of quick tutorial that introduce to machine learning via the sklearn library or to the optimization tool we use at LOCIE.

- [SVM regression example using Scikit-learn (en)](./ml/mapping_function_SVM.ipynb)
- [NSGA2 optimization using DEAP explained (en)](./ml/multiobjective_optimization.ipynb)

### [Misc](./misc)

Other topic that does not fit into other folders.
