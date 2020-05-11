# D-Lab Visualization with Python workshop

This repository contains materials for the Visualization with Python workshop at the UC Berkeley D-Lab.

### 1. Software for the workshop

The best learning experience happens when you can edit and run code. So, please have Python Anaconda Distribution 3.7, seaborn, matplotlib, numpy, and jupyter installed before the start of the workshop. Follow the steps below to setup your environment: 

1. [Click here to download Python Anaconda 3.7 Distribution](https://www.anaconda.com/products/individual), although 3.6 is also okay if you already have it installed. Scroll down to the "Anaconda Installers" section and click the "Graphical Installer" option that corresponds to your operating system. 

2. If you are using Terminal (Mac) or GitBash (PC), you can pip install the necessary packages by typing: 

`$ pip install seaborn pandas matplotlib numpy jupyter`

> Windows users only - if you wish to emulate the Bash programming language found in Mac users' "Terminal" application, [click here to download GitBash](https://git-scm.com/downloads), a Unix command-line environment for Windows users. 

Alternatively, you can install these packages by adding a cell to the top of your Jupyter Notebook and typing: 

`!pip install seaborn pandas matplotlib numpy jupyter`

### 2. Files for the workshop

Once the software is installed, download the necessary files for the workshops which are contained in this repository. Get them by doing the following:

1. Click the green "Clone or Download" button
2. Click "Download Zip"
3. Extract this .zip file someplace familiar, such as your Desktop. 

Or, if you are a Git user you can simply clone this repository

`$ git clone git@github.com:dlab-berkeley/visualization-with-python.git`

### 3. Open a Jupyter Notebook

1. Open the "Anaconda Navigator" application and click "Launch" under Jupyter Notebook

or

Navigate to the respository using Terminal or Gitbash and type

`$ cd visualization-with-python`

then

`$ jupyter notebook` or `python3 -m notebook`

This will open a blank notebook for you to use as a scratch space is you desire. Open the file "visualization-with-python.ipynb" to access the tutorial.

### 4. Outline

For this workshop, we'll provide an introduction to visualization with Python. We'll cover visualization theory and plotting with Matplotlib and Seaborn, working through examples in a Jupyter (formerly IPython) notebook. The following plot types will be covered:

* line
* bar
* scatter
* boxplot

We'll also learn about styles and customizing plots.

Throughout the workshop, we'll discuss the plot types best suited for particular kinds of data.

Basic familiarity with Python *is* assumed.

### 5. Resources

[Pyplot tutorial](https://matplotlib.org/tutorials/introductory/pyplot.html)

[Matplotlib tutorial](https://matplotlib.org/3.2.1/tutorials/index.html)

[Seaborn tutorial](https://seaborn.pydata.org/tutorial.html)

### 6. Launch binder

If you have trouble installing the software or can otherwise not get the Jupyter Notebook to open, click this "launch binder" badge to start this session [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/visualization-with-python/master)
