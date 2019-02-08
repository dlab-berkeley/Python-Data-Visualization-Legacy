# Visualization with Python

Materials for teaching the visualization workshop at UC Berkeley's D-Lab.

## Outline

For this workshop, we'll provide an introduction to visualization with Python. We'll cover visualization theory and plotting with Matplotlib and Seaborn, working through examples in a Jupyter (formerly IPython) notebook. The following plot types will be covered:

* line
* bar
* scatter
* boxplot

We'll also learn about styles and customizing plots.

Throughout the workshop, we'll discuss the plot types best suited for particular kinds of data.

Basic familiarity with Python *is* assumed.

## Set Up

For this workshop we'll be using a Jupyter notebook. (An IPython notebook will be provided for attendees who are not yet on IPython 3.0.0 or above.)

The best learning experience happens when you can edit and run code. So, please have Matplotlib, Seaborn, and Jupyter or IPython (and the notebooks) installed. There are several options for getting your environment set up.

1. [BCE Summer 2015](http://bce.berkeley.edu/install.html)
2. [Anaconda](http://continuum.io/downloads)
3. A package manager such as [pip](https://pip.pypa.io/en/stable/installing.html)

Both BCE and the Anaconda distribution will install everything you need for this workshop. If you decide to use `pip`, you can do the following:

```
$ pip install matplotlib seaborn

$ pip install --upgrade jupyter
```

Once those are installed, you can get the necessary files for this workshop by doing the following:

```
# clone the repository
$ git clone https://github.com/dlab-berkeley/visualization-with-python.git

# navigate to the repo
$ cd visualization-with-python

# start the interactive session
$ jupyter notebook

# alternatively
$ ipython notebook
```


