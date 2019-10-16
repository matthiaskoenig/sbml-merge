# sbml-merge
Merging SBML files with python 3 libsbml. This project is deprecated, and now part of the functionality of [`sbmlutils`](https://github.com/matthiaskoenig/sbmlutils).

## Installation
### clone repository
```
git clone https://github.com/matthiaskoenig/sbml-merge.git
```

### setup virtual environment
```
cd sbml-merge
mkvirtualenv sbml-merge --python=python3
(sbml-merge) pip install -r requirements.txt
(sbml-merge) pip install jupyter jupyterlab
```

### install python kernel
```
(sbml-merge) python -m ipykernel install --user --name=sbml-merge
```

### start jupyter lab with kernel
```
(sbml-merge) jupyter lab model_merging.ipynb
```
Select kernel
```
Kernel -> Select Kernel -> sbml-merge
```
Run notebook
```
Kernel -> Restart & Run all
```

&copy; 2017 Matthias König.