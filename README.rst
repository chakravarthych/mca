===============================
mca
===============================

.. image:: https://badge.fury.io/py/mca.png
    :target: http://badge.fury.io/py/mca
    
.. image:: https://travis-ci.org/esafak/mca.png?branch=master
    :target: https://travis-ci.org/esafak/mca

mca is a `Multiple Correspondence Analysis <http://en.wikipedia.org/wiki/Multiple_correspondence_analysis>`_ (MCA) package for python, intended to be used with `pandas <http://pandas.pydata.org/>`_. MCA is a `feature extraction <http://en.wikipedia.org/wiki/Feature_extraction>`_ method; essentially `PCA <http://en.wikipedia.org/wiki/Principal_component_analysis>`_ for `categorical variables <http://en.wikipedia.org/wiki/Categorical_variable>`_. You can use it, for example, to address `multicollinearity <http://en.wikipedia.org/wiki/Multicollinearity>`_ or the `curse of dimensionality <http://en.wikipedia.org/wiki/Curse_of_dimensionality>`_ with big categorical variables.

Installation
------------

.. code :: bash

	pip install --user mca

Usage
------------------

Please refer to the `usage notes <https://github.com/esafak/mca/blob/master/docs/usage.rst>`_ and `this illustrated ipython notebook <http://nbviewer.ipython.org/github/esafak/mca/blob/master/docs/mca-BurgundiesExample.ipynb>`_.

Reference
---------

Michael Greenacre, Jörg Blasius (2006). `Multiple Correspondence Analysis and Related Methods <http://www.crcpress.com/product/isbn/9781584886280>`_, CRC Press. ISBN 1584886285.
