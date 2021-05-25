# Packgenlite - Python package builder

This package is a meta-package that provide Python libs for projects
and mainly `packgenlite` script.

`packgenlite` create a Python package template.


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
