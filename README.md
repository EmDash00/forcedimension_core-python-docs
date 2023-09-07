# Force Dimension Core Python Bindings Documentation

![build](https://img.shields.io/readthedocs/forcedimension_core-python-documentation)

This is a GitHub repository dedicated to the [Force Dimension Core Python Bindings](https://github.com/EmDash00/forcedimension_core-python) documentation.

If you're looking for the documentation please go to:

https://forcedimension_core-python-documentation.readthedocs.io/en/latest/

## Install required dependencies


```
python3 -m pip install pipenv  # if you don't already have it
pipenv install
```


## Building the Documentation


```
pipenv run sphinx-build -b html source/ build/
```
