# se-hw2-fall22

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7113804.svg)](https://doi.org/10.5281/zenodo.7113804)
![MIT license](https://img.shields.io/badge/License-MIT-green.svg)
![GitHub](https://img.shields.io/badge/Language-Python-blue.svg)
![Build](https://github.com/ekanshsinghal/se-hw2-fall22/actions/workflows/build.yml/badge.svg)
![Test](https://github.com/ekanshsinghal/se-hw2-fall22/actions/workflows/test.yml/badge.svg)
[![Code Coverage](https://img.shields.io/badge/Code%20Coverage-95%25-brightgreen)](https://github.com/ekanshsinghal/se-hw2-fall22/blob/main/coverage_report.txt)

## About the project

This project is python implementation of a lua script. It contains the following classes:
1. Num.py
2. Sym.py
3. Cols.py
4. Row.py
5. Data.py

## Installation
This project requires:
 - Python 3.6 or greater
 - pip (or) pip3
 
 To install the packages used by this project, run ```pip install -r requirements.txt``` in the command line. Alternatively, you could run ```pip install .``` in the command line. You may need to use pip3 depending on how it has been set up in your system.
 
 ## Directory structure
    .
    |   .coverage
    |   .gitignore
    |   CITATION.cff
    |   CODE-OF-CONDUCT.md
    |   CONTRIBUTING.md
    |   coverage.svg
    |   coverage_report.txt
    |   directory_tree.txt
    |   LICENSE
    |   README.md
    |   requirements.txt
    |   
    +---.github
    |   \---workflows
    |           build.yml
    |           test.yml
    |           
    +---code
    |   |   Cols.py
    |   |   csv_reader.py
    |   |   Data.py
    |   |   Func.py
    |   |   main.py
    |   |   Num.py
    |   |   Row.py
    |   |   Sym.py
    |   |   __init__.py
    |   |
    +---data
    |   |   help.py
    |   |   hw2-csv.csv
    |   |         
    +---docs
    |   |   code.rst
    |   |   conf.py
    |   |   index.rst
    |   |   Makefile
    |   |   modules.rst
    |   |   
    |   \---_build
    |       +---doctrees
    |       |       code.doctree
    |       |       environment.pickle
    |       |       index.doctree
    |       |       modules.doctree
    |       |       
    |       \---html
    |           |   .buildinfo
    |           |   code.html
    |           |   genindex.html
    |           |   index.html
    |           |   modules.html
    |           |   objects.inv
    |           |   py-modindex.html
    |           |   search.html
    |           |   searchindex.js
    |           |   
    |           +---_sources
    |           |       code.rst.txt
    |           |       index.rst.txt
    |           |       modules.rst.txt
    |           |       
    |           \---_static
    |                   alabaster.css
    |                   basic.css
    |                   custom.css
    |                   doctools.js
    |                   documentation_options.js
    |                   file.png
    |                   jquery.js
    |                   language_data.js
    |                   minus.png
    |                   plus.png
    |                   pygments.css
    |                   searchtools.js
    |                   underscore.js
    |                   
    \---test
        |   TestCode.py
        |   __init__.py


## Testing
Run ```python -m code.main -e all``` in the command line to run the tests under the test folder.

## Contributing to this project
Read the Contributing.md to find out how you can help contribute to this project.




