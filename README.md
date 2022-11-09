# AnanseScanpy: implementation of scANANSE for Scanpy objects in Python
[![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/anansescanpy/README.html)
[![Anaconda-Server Badge](https://anaconda.org/bioconda/anansescanpy/badges/version.svg)](https://anaconda.org/bioconda/anansescanpy)
[![Anaconda-Server Badge](https://anaconda.org/bioconda/anansescanpy/badges/downloads.svg)](https://anaconda.org/bioconda/anansescanpy)

## Installation

The most straightforward way to install AnanseScanpy is via conda using pypi.

### Install package through Conda
If you have not used Bioconda before, first set up the necessary channels (in this order!). 
You only have to do this once.
```
$ conda config --add channels defaults
$ conda config --add channels bioconda
$ conda config --add channels conda-forge
```

Then install AnanseScanpy with:
```
$ conda install anansescanpy
```

### Install package through PyPI
```
$ pip install anansescanpy
```

### Install package through GitHub
```
git clone https://github.com/Arts-of-coding/AnanseScanpy.git
cd AnanseScanpy
conda env create -f requirements.yaml
conda activate AnanseScanpy
pip install -e .
```

## Start using the package

### Run the package either in the console
```
$ python3
```

### Or run the package in jupyter notebook
```
$ jupyter notebook
```

For extended documentation see our ipynb vignette with PBMC sample data

