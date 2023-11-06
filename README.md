# Force Dimension Core Python Bindings Documentation

This is a GitHub repository dedicated to the [Force Dimension Core Python Bindings](https://github.com/EmDash00/forcedimension_core-python) documentation.

If you're looking for the documentation please go to:

https://force-dimension-core-python-documentation.readthedocs.io


## Install dependencies

```
poetry -C ../forcedimension_core-python install --with docs --extras numpy
```

## Building the Documentation

In the docs folder:

```
poetry -C ../forcedimension_core-python run make html
```
