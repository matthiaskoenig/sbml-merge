# sbml-merg
Merging SBML files with python libsbml bindings.

## Installation
### clone repository
```
git clone https://github.com/matthiaskoenig/sbml-merge.git
```

### setup virtual environment
```
cd sbml-merge
mkvirtualenv sbml-merge
(sbml-merge) pip install -r requirements.txt
```

### install python kernel
(sbml-merge) python -m ipykernel install --user --name=sbml-merge

### start jupyter notebook with kernel
```
(sbml-merge) jupyter notebook model_merging.ipynb
```
Select kernel
```
Kernel -> Select Kernel -> sbml-merge
```
Run notebook
