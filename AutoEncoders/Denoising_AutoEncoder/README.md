## Installation Guide
python 3.12 is required
Use Terminal in Projectfolder/Subfolder where pyproject.toml is located:


### Windows11 (recommended)
```code
pip install pdm 
pdm install 
```
A .venv will be created. We recommend to use the venv
### Linux (recommended)
```code
python -m venv .venv
source .venv/bin/activate
python -m ensurepip --upgrade
python -m pip install --upgrade pip setuptools
pip install pdm
pdm install
```
A .venv will be created. We recommend to use the venv

### Alternative Installation
Use Terminal in Projectfolder/Subfolder where requirements.txt is located:
```code 
pip install -r requirements.txt
```