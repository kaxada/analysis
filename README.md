To setup your python environment:
```bash
python3 -m venv ../../virtualenvs/phds
source ../../virtualenvs/phds/bin/activate
pip install -r requirements.txt
pip install --upgrade pip
pip install -r requirements.txt
```

To start the notebooks, after activating your virtual environment and loading the libraries, enter `jupyter lab` at the command line. 

You can see what python versions and library versions you ended up with using these commands:
```bash
pip freeze
python --version
```
