# Packgenlite - Python package builder

Python script to create Python packages templates with preconfigured setup, tests and CI/CD.

Forked from https://github.com/krokrob/packgenlite in order to use the PEP518/PEP621 compliant `pyproject.toml` dependencies/setup file instead of old `requirements.txt` and `setup.py`.


## Install `packgenlite`

With pip:
```bash
pip install git+https://github.com/bolinocroustibat/packgenlite.git
```

or with Poetry:
```bash
poetry add git+https://github.com/bolinocroustibat/packgenlite.git
```


## Create a `newpkgname` package

Use `packgenlite` to create a new python package:

```bash
packgenlite newpkgname
```

Check that the package has been created:

```bash
cd newpkgname
tree
.
├── MANIFEST.in
├── Makefile
├── README.md
├── newpkgname
│   ├── __init__.py
│   └── data
├── notebooks
├── raw_data
├── pyproject.toml
├── scripts
│   └── newpkgname-run
├── setup.py
└── tests
    └── __init__.py

6 directories, 8 files
```
