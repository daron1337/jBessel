This cython module computes bessel functions of the first kind (J) for integers order n (0,1,2).
Once it has been compiled, you can import it as a standard python module.
Bessel functions for python are only supported by SciPy package.
Windows users: please download and install Scipy package.

INSTALLATION REQUIREMENTS

Operating systems: Linux or MacOsX
Cython (http://cython.org/#download)

INSTALLATION HOW TO

Compiling cython code using distutils:
(http://docs.cython.org/src/quickstart/build.html)

To build, run:
python setup.py build_ext --inplace. 
Then simply start a Python session and do:
from Bessel import jBessel