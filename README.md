[![PythonDevopsMiscroservicesCD](https://github.com/Serafiel/PythonDevOpsMIcroservicesCD/actions/workflows/devops.yml/badge.svg)](https://github.com/Serafiel/PythonDevOpsMIcroservicesCD/actions/workflows/devops.yml)

# PythonDevOpsMicroservicesCD

# Scaffold

![scaffold](https://user-images.githubusercontent.com/47248860/213919476-5204ec8d-d8f1-4fe1-ae6e-564100e5ff88.png)

## Steps:

### Step 1: Create a Python Virtual Environment `python -m venv ~/.venv` or `virtualenv ~/.venv`

### Step 2:  Create empty files (e.g. via bash): `Makefile`, `requirements.txt`, `Dockerfile`, `main.py` (to run microservice), `mylib/__init__.py`

### Step 3: Populate `Makefile`

### Step 4: Set up Continuous Integration, i.e. check code for issues like lint errors
![lint failure](https://user-images.githubusercontent.com/47248860/213938422-5d9af99b-2abd-4959-8259-5f17906782bc.png)

### Step 5: Build cli using Python Fire library `./cli-fire.py --help` to test logic

1:07:11 Pinning FastAPI version number
