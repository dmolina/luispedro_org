title: Mahotas
url: software/mahotas
categories: software python
..

.. raw:: html

    <a href="http://github.com/luispedro/mahotas">
        <img style="position: absolute; top: 0; right: 0; border: 0;" src="http://s3.amazonaws.com/github/ribbons/forkme_right_darkblue_121621.png" alt="Fork me on GitHub" />
    </a>

Mahotas: Image Processing in Python
===================================

Mahotas is a set of functions for image processing in Python.

It is completely based on numpy arrays as its datatype. It has its heavy
routines implemented in clean C++ in a way that is both very clean, type
independent (using templates), and fast.

All of the code is self contained and it has no other dependencies than numpy
and scipy.ndimage (for certain algorithms). Freeimage is an optional dependency
if you want to use the ``imread`` and ``imsave`` functions.

The code is well documented (**all** public functions are extensively
documented) and well tested (100% test coverage of all but 2 modules---working
on those last two). It has **no known bugs**.

Algorithms
----------

- watershed
- thresholding
- convex hull computation
- polygon drawing
- feature computation: Haralick textures, local binary patterns, and Zernike
  moment
- distance transform
- freeimage interface
- ...

Install
-------

You can get the code from `pypi <http://pypi.python.org/pypi/mahotas>`_ or the
cutting edge from `github <http://www.github.com/luispedro/mahotas>`_.
Instalation should be possible using:::

    pip install mahotas

or::

    easy_install mahotas

You can also find Windows packages `here
<http://www.lfd.uci.edu/~gohlke/pythonlibs/>`_ by Christoph Gohlke at UCI. He
also has other useful Python packages.

For FreeBSD, mahotas is available in `the ports section
<http://www.freshports.org/graphics/mahotas>`__.

Support
-------

The official forum for discussion of mahotas issues is the `pythonvision
mailing list <http://groups.google.com/group/pythonvision>`_. Also, check out
`pythonvision.org <http://pythonvision.org>`_ while you're at it.

For bug reports, `mail me <mailto:lpc@cmu.edu>`_. If you report a bug, I will
try to fix it. If it has a unit test, I **promise** to fix it.

Currently, **there are no known bugs**.

