# Python3 Virtual Environment

In order to avoid conflicting versions of python and any modules or packages, we build a virtual environment  for the project.

The venv/ file is in the .gitignore, so it isn't tracked. Instead we have a [requirements.txt](../requirements.txt) file for you to build your own virtual environment.

## Setup

```bash
user@computer:~/path/to/mass-aquaponics$ python3 -m venv venv
(venv) user@computer:~/path/to/mass-aquaponics$ source env/bin/activate
(venv) user@computer:~/path/to/mass-aquaponics$ pip3 install -r requirements.txt
```

## Updating requirements

```bash
(venv) user@computer:~/path/to/mass-aquaponics$ pip3 freeze > requirements.txt
```

## Deactivating Virtual Environment

```bash
(venv) user@computer:~/path/to/mass-aquaponics$ deactivate
```