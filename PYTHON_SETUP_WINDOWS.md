#Python Setup Windows

##Setup Git and Git Bash

<https://github.com/janelia-idf/git_setup>

##Setup Python

Download Python 3.X Windows Installer from:

<https://www.python.org/download>

Or download Python 2.7.X Windows Installer from:

<https://www.python.org/download>

Install all features, including pip and adding python.exe to Path.

Restart computer.

Open git bash terminal:

Upgrade pip:

```shell
pip install --upgrade pip
```

Install virtualenv:

```shell
pip install virtualenv --upgrade
```

Make a directory to store virtual environments:

```shell
mkdir ~/virtualenvs
```

Create and activate a virtual environment:

<https://virtualenv.pypa.io/en/stable/userguide/>

Example:

```shell
virtualenv ~/virtualenvs/example_env
source ~/virtualenvs/example_env/bin/activate
```

In an activated virtual environment, install ipython:

```shell
pip install ipython
```
