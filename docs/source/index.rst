.. ForceDimension Python Bindings documentation master file, created by
   sphinx-quickstart on Tue Jul 19 13:59:28 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to the Python Force Dimension Bindings Documentation!
===============================================================

The ForceDimension API published by Force Dimension allows users to control
supported haptic devices using C++.

Force Dimension Python an unofficial attempt to provide a open source, performant, and
Pythonic interface for interacting with the original C++ API so that libraries such as
NumPy may be used to render haptics. It was created by Ember Chow during her work at both the
Rothlab and Trusting AI projects at IU: Bloomington for use in scientific experiments
involving haptics using the Novint Falcon. This project is continuing to be used as a part of
her research at University of Washington - Seattle.

It consists of two parts: low-level bindings and high level wrappers.

The low-level bindings mimic the original ForceDimension C++ API closely; however, some
liberties were taken to make the calls more Pythonic. For example, many calls ask for
pointers to be passed in. In the low-level bindings, a list is asked for instead. If no
list is provided, a new one is created.


The high level wrappers create an object oriented interface for the ForceDimension API. They
introduce context management and a custom daemon that polls for the device state in background
threads.

This library is currently in alpha; however, low-level bindings should be largely stable.
High-level wrappers may introduce breaking changes until release v1.0.0. An official release will only
be considered after Force Dimension runs tests on the API.


Copyright
=========
The ForceDimension API and documentation is property of Force Dimension, all rights reserved.
This code does **not** involve any reverse engineering or distribution of proprietary code.
Users are encouraged to download the ForceDimension API through publicly available download
links provided by Force Dimension. Documentation was generated using Sphinx. Many parts are
copied from the original C++ API with the express permission of Force Dimension.

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   modules.rst

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
