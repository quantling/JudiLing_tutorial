# Readme

This repository contains preliminary code and data from the book

Heitmeier, Chuang and Baayen (in preparation): The Discriminative Lexicon: Theory, Implementation in the Julia package JudiLing, and Applications.

## Installing Julia

You need to use at least version 1.11.
Installation instructions for all operating systems can be found [here](https://julialang.org/downloads/).

## Using Julia in Jupyter Notebook

We provide the code as Jupyter Notebooks. If you are entirely new to python and jupyter notebook, a good place to start might be [this tutorial](https://www.dataquest.io/blog/jupyter-notebook-tutorial/).

If you are already familiar with python: If you have a Mac or Linux OS and python installed, you can simply install jupyter notebook as explained on this website: https://jupyter.org/install
If you have Windows, you can install Jupyter Notebook from your Anaconda environment (get it here, if you don't have it already: https://docs.anaconda.com/anaconda/install/windows/).

Now you have to add Julia to Jupyter Notebook. Instructions on how this is done can be found for example here: https://datatofish.com/add-julia-to-jupyter/ (Note that in our experience, you may have to run Pkg.build("IJulia") after installing it before it works in Jupyter.)

## Installing JudiLing and other required packages

Once you have Julia installed, you can open the the Julia REPL by opening a terminal and typing

```bash
% julia
```

Next, type the following commands, which first make Julia's package manager available and then install all required packages:

```julia
using Pkg
Pkg.add("DataFrames")
Pkg.add("JudiLing")
```

You can also run the notebook in `notebooks/00_julia_fundamentals.ipynb` which gives an introduction to julia and installs all required packages along the way.

## JudiLing Cheatsheet

A JudiLing cheatsheet can be found in `doc`.

## Data

All datasets can be found at *link to OSF project* or links for downloading them are provided in the main manuscript. Please see attributions for all datasets at *link to OSF project*.

## Helpful links

* Learning programming in Julia: https://julialang.org/learning/
* Working directory in Julia: https://www.youtube.com/watch?v=taHJwZy_3O8&ab_channel=JCharisTech