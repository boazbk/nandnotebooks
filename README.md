# The NAND programming languages

This is a collection of Jupyter Notebooks for the NAND family of programming languages that accompany the upcoming book [Introduction to Theoretical Computer Science](http://introtcs.org).

You can launch all the notebooks live using either [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/boazbk/nandnotebooks/master) or [Azure notebooks](https://notebooks.azure.com/boazbk/libraries/introtcs).

However, if you want to play with them more extensively you'd probably want to download them to your own machine. You can do so by _(1)_ clone/download (using the ![this button](githubbutton.png) button on the top right corner) all of the files to a local folder,   _(2)_ install [anaconda](https://www.anaconda.com/download/), and then install [Jupyter Lab](https://github.com/jupyterlab/jupyterlab) by opening up a command prompt (or maybe "anaconda prompt", in windows) and type `conda install -c conda-forge jupyterlab`. You then change directory to the folder containing these notebooks and type `jupyter lab`.  For visualizing circuits you will need to also install  [graphviz](https://graphviz.gitlab.io/download/), which I believe can be done by typing `conda install -c anaconda graphviz `

The main notebooks contained in this repository are:

1. [The NAND Programming Language](https://github.com/boazbk/nandnotebooks/blob/master/NAND%20programming%20language.ipynb)  (   [live version on binder](https://mybinder.org/v2/gh/boazbk/nandnotebooks/master?filepath=NAND%20programming%20language.ipynb) [version on google collab](https://colab.research.google.com/github/boazbk/nandnotebooks/blob/master/NAND%20programming%20language.ipynb) ): Definition of the NAND programming language, relation to Boolean circuits, syntactic sugar, computing every function, and representing it as list of triples



3. [Blog post about the course](https://github.com/boazbk/nandnotebooks/blob/master/blog.ipynb) ([live version](https://mybinder.org/v2/gh/boazbk/nandnotebooks/master?filepath=blog.ipynb) [version on google collab](https://colab.research.google.com/github/boazbk/nandnotebooks/blob/master/blog.ipynb) ) : High level overview of the main results in the course.

3. [NAND++ programming language](https://github.com/boazbk/nandnotebooks/blob/master/NANDpp_language.ipynb) ( [live version](https://mybinder.org/v2/gh/boazbk/nandnotebooks/master?filepath=NANDpp_language.ipynb) [version on google collab](https://colab.research.google.com/github/boazbk/nandnotebooks/blob/master/NANDpp_language.ipynb) ): Overview of the NAND++ programming lanaguage.





4. [The Cook Levin Theorem](https://github.com/boazbk/nandnotebooks/blob/master/Cook_Levin.ipynb) ([live version](https://mybinder.org/v2/gh/boazbk/nandnotebooks/master?filepath=Cook_Levin.ipynb) [version on google collab](https://colab.research.google.com/github/boazbk/nandnotebooks/blob/master/Cook_Levin.ipynb)  ): Overview of the Cook Levin Theorem.

5. [Lambda calculus](https://github.com/boazbk/nandnotebooks/blob/master/lambda.ipynb)   ( [live version](https://mybinder.org/v2/gh/boazbk/nandnotebooks/master?filepath=lambda.ipynb) [version on google collab](https://colab.research.google.com/github/boazbk/nandnotebooks/blob/master/lambda.ipynb) ): Some notes on the lambda calculus and the Y combinator.

__Note:__ As of Summer 2018 I am changing a bit the syntax of the languages, and hence some notebooks use the older syntax `foo := bar NAND blah` and some use the newer syntax `foo = NAND(bar,blah)`
