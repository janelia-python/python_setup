#Python Setup Mac OS X

##Setup Python

Download and install XCode:

<https://developer.apple.com/xcode/>

Install Homebrew:

```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Insert Homebrew directory at the top of the PATH by adding the
following line to the bottom of your ~/.profile file (create it if it
does not exist):

```shell
export PATH=/usr/local/bin:/usr/local/sbin:$PATH
```

Open a new terminal to complete the PATH modification or run:

```shell
source ~/.profile
```

Update brew:

```shell
sudo chown -R $(whoami):admin /usr/local
brew update
```

##Setup Git

```shell
brew install git
```

Or install Python 3.x

```shell
brew install python3
```

Or install Python 2.7

```shell
brew install python
```

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
