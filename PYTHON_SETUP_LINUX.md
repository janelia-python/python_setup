#Python Setup Linux

##Setup Git

<https://github.com/janelia-idf/git_setup>

##Setup Python

The latest versions of many Linux distributions come with Python 2.7
and 3.x out of the box.

Install virtualenv:

<https://virtualenv.pypa.io/en/stable/installation/>

Example:

```shell
sudo apt-get install virtualenv
```

Make a directory to store virtual environments:

```shell
mkdir ~/virtualenvs
```

Create and activate a virtual environment for either Python 3 or 2:

<https://virtualenv.pypa.io/en/stable/userguide/>

Example using Python 3:

```shell
virtualenv -p python3 ~/virtualenvs/example_env
source ~/virtualenvs/example_env/bin/activate
```

Example using Python 2:

```shell
virtualenv ~/virtualenvs/example_env
source ~/virtualenvs/example_env/bin/activate
```

In an activated virtual environment, install ipython:

```shell
pip install ipython
```
