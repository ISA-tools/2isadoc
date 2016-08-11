Installation
============


mzml2isa is available on PyPI, so if ``pip`` is installed on your
machine, installing mzml2isa should be quite straightforward, without
the need to worry about dependencies. It is also possible to install
mzml2isa development version directly from the `mzml2isa GitHub repository <https://github.com/althonos/mzml2isa>`__.


Dependencies
------------

- `pronto <https://pypi.python.org/pypi/pronto>`__
- `lxml <http://lxml.de>`__

.. warning::
   Without pip you'll have to install the dependencies yourself, otherwise running
   ``setup.py`` will fail when trying to import **mzml2isa** for the first time.


PyPI (stable version) |PyPI version|
------------------------------------

.. |PyPI version| image:: https://img.shields.io/pypi/v/mzml2isa.svg?style=flat&maxAge=2592000
   :target: https://pypi.python.org/pypi/mzml2isa/


With `pip`
''''''''''''

Just run one of the following commands in a terminal:

.. code:: bash

   pip install mzml2isa        # install on the machine, needs super-user rights
   pip install mzml2isa --user # install only for the current user, no rights needed


Without `pip`
'''''''''''''

This requires the python ``setuptools`` module to be installed, as well as the dependencies listed above. Download the latest stable release
from the:
`PyPI repository mzML2ISA <https://pypi.python.org/pypi/mzml2isa>`__ ,
`PyPI repository nmrML2ISA <https://pypi.python.org/pypi/nmrml2isa>`__
, unpack it and install it by running the following commands:

.. code:: bash

   tar xf mzml2isa-xx.yy.zz.tar.gz # replace with whatever version you downloaded
   cd mzml2isa-xx.yy.zz.tar.gz
   python setup.py install         # will require super-user rights



GitHub (development version) |Build Status|
-------------------------------------------

.. warning::
   Please check the current version of the program passes the Travis CI validation beforehand,
   or you could be installing a non-functional version of the program ! The program is working
   if the badge above displays |Passing build|.


With `pip`
''''''''''

.. code:: bash

   pip install git+git://github.com/althonos/mzml2isa


Without `pip`
'''''''''''''

.. code:: bash

   git clone https://github.com/althonos/mzml2isa
   cd mzml2isa
   python setup.py install


.. |Build Status| image:: https://img.shields.io/travis/althonos/mzml2isa.svg?style=flat&maxAge=2592000
   :target: https://travis-ci.org/althonos/mzml2isa

.. |Passing build| image:: https://img.shields.io/badge/build-passing-brightgreen.svg

