# Introduction to Jupyter Notebooks

This repository contains a tutorial on how to use Python and [Jupyter
notebooks](https://jupyterlab.readthedocs.io/en/stable/user/notebook.html)
for interactive computing. 

## Prerequisites

In terms of
* knowledge: Nothing, really. Maybe some _basic_ Python
* software:
    - Python 3.8
    - `pipenv`

## How to Run the Notebooks

### Create Virtual Environment

The tutorial notebooks are intended to be run from within a Python virtual
environment. 

Open up a terminal **in the directory of this repository** and run

```
pipenv install
```

to automatically create a new virtual environment using the correct
Python version and install all package dependencies.

### Start JupyterLab

Start the JupyterLab server inside of your new virtual environment by running

```
pipenv run jupyter lab
```
still inside the directory of this repo.

A new instance of the Juypter server will be started and automatically open
up the JupyterLab start page in your browser. We will only be interacting
with the browser front-end from now on but you need to leave the server
running in the background.

Using the file browser in the left pane, navigate into the `notebooks/`
directory and open up the first `.ipynb` file.
