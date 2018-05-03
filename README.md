# Dcop python

pyDCOP is a python librarire for Distributed Constraints Optimization.
It contains implementations of several standard DCOP algorithms (MaxSum, DSA,
DPOP, etc.) and allows you to develop your own algorithms.

PyDCOP runs on python >= 3.5.

## Installation

Using pip is recommended, on ubuntu :

    sudo apt-get install python3-setuptools
    sudo apt-get install python3-pip


I also recommend installing pyDCOP in a virtualenv, in order to avoid any
conflict with other applications you might have:

     python3 -m venv ~/.pydcop
     source ~/.pydcop/bin/activate

For now, installation is only from source :

    cd pydcop
    pip install .

Or without pip, simply use :

    python3 setup.py install
    
When developing on DCOP-python, one would rather use the following command,
which installs pydcop in development mode and test dependencies:

    pip install -e .[test]

To generate documentation, you need to install the corresponding dependencies:

    pip install -e .[doc]

