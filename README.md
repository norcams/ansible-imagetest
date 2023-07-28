# Ansible imagetest

## Requirements

* Python 3.9+
* Python virtualenv

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
ansible-playbooks plays/<test>.yaml
```

