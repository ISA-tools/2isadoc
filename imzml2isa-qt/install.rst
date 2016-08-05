Installation
============


imzml2isa-qt is available on PyPI, so if ``pip`` is installed on your
machine, installing mzml2isa should be quite straightforward, without
the need to worry about dependencies. It is also possible to install
mzml2isa development version directly from the `imzml2isa-qt GitHub repository <https://github.com/althonos/imzml2isa-qt>`__.

.. warning::
   imzml2isa-qt is a **Python3 program only !**


Dependencies
------------

- `mzml2isa <https://pypi.python.org/pypi/mzml2isa>`__
- `PyQt5 <https://pypi.python.org/pypi/PyQt5/5.6>`__


PyPI (stable version) |PyPI version|
------------------------------------

.. |PyPI version| image:: https://img.shields.io/pypi/v/imzml2isa-qt.svg?style=flat&maxAge=2592000
   :target: https://pypi.python.org/pypi/imzml2isa-qt/


With `pip`
''''''''''''

Just run one of the following commands in a terminal:

.. code:: bash

   pip install imzml2isa-qt        # install on the machine, needs super-user rights
   pip install imzml2isa-qt --user # install only for the current user, no rights needed


Without `pip`
'''''''''''''

This requires the python ``setuptools`` module to be installed, as well as the dependencies listed above. Download the latest stable release
from the `PyPI repository <https://pypi.python.org/pypi/imzml2isa-qt>`__, unpack it and install it
by running the following commands:

.. code:: bash

   tar xf imzml2isa-qt-xx.yy.zz.tar.gz # replace with whatever version you downloaded
   cd imzml2isa-qt-xx.yy.zz.tar.gz
   python setup.py install             # will require super-user rights



GitHub (development version)
----------------------------

With `pip`
''''''''''

.. code:: bash

   pip install git+git://github.com/althonos/imzml2isa-qt


Without `pip`
'''''''''''''

.. code:: bash

   git clone https://github.com/althonos/imzml2isa-qt
   cd imzml2isa-qt
   python setup.py install

