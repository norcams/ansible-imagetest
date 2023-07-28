# Ansible imagetest

## Requirements

* Python 3.9+
* Python virtualenv
* (recommended) ansible inventory from [tf-imagetest](https://github.com/norcams/tf-imagetest)

## Setup 

``` bash
git clone <repo> <dir>
cd <dir>
python3.9 -m venv .
source bin/activate
pip install --upgrade pip
pip install -r requirements.txt
ansible-galaxy install -r requirements.yaml
```

## Run tests

``` bash
source bin/activate
ansible-playbooks -i <inventory> plays/<test>.yaml
```

