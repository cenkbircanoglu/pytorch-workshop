# Learning Deep Learning for Coders

Repo with the notebooks for the Learning Deep Learning Workshop.

## Run Jupyter Notebooks Locally

To run this notebook, you need to have these installed,

	1. Python3
	2. jupyter package
	3. torch package

You can make your environment ready to run notebook with following these instructions. 
There will several different ways to install Python3 and manage your Python packages.
Some of them are,

	1. pyenv
	2. conda


### Installation of pyenv

#### Dependencies

##### If you are using Ubuntu run these bash command

```bash	
sudo apt-get install -y make build-essential libssl-dev zlib1g-dev \
libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm \
libncurses5-dev libncursesw5-dev xz-utils tk-dev libffi-dev \
liblzma-dev python-openssl git
```

##### If you are using OS X run these bash command

```bash
brew install openssl readline sqlite3 xz zlib git
```

#### Install pyenv
```bash
curl -L https://github.com/pyenv/pyenv-installer/raw/master/bin/pyenv-installer \
| bash

export PATH="~/.pyenv/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

#### Verify pyenv

```bash
pyenv --version 
```

#### Install Python3.6.9
```bash
pyenv install 3.6.9
```
#### Create virtualenv
```bash
pyenv virtualenv 3.6.9 learn-pytorch
```

#### Activate virtualenv
```bash
pyenv activate learn-pytorch
```

#### Install Python packages
```bash
pip install torch jupyter
```
#### Start Jupyter Notebook
```bash
jupyter notebook
```


