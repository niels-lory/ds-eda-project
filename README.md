# Welcome to the exploratory data analysis!

I analyzed house sales data in King County, Seattle, WA for a fictional buyer Erin Robinson.
Erin Robinson: Buyer - Invest in poor neighborhood, buying & selling, costs back + little profit, socially responsible  

The [Jupyter lab file]("EDA_notebook.ipynb") in the main directory of this repository contains the code and results of the EDA.

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.

```
brew update
brew install postgresql
```

In order to install the environment you can use the following commands:

```
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

