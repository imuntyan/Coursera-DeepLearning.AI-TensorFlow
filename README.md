#SETUP

## Python

Pyrhon version >= 3.5 required

### pyenv

Install https://github.com/pyenv/pyenv

```shell script
pyenv local 3.8.2
```
assuming python version 3.8.2 is installed, otherwise:

```shell script
pyenv install
```

### Virtual environment

```shell script
mkdir ~/venv/coursera
python -m venv ~/venv/coursera
source ~/venv/coursera/bin/activate
```

To deactivate virtual environment later:

```shell script
deactivate
```

### Install Libraries

In active virtual environment:

```shell script
pip install -r requirements.txt
```


### Jupyter problems

```shell script
pip install --upgrade ipykernel ipython
```

## Course repository

https://github.com/lmoroney/dlaicourse
