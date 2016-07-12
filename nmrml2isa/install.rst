Installation
============


nmrml2isa is available on PyPI, so if `pip` is installed on your
machine installing nmrml2isa should be quite straightforward, without
the need to worry about dependencies. It is also possible to install
nmrml2isa development version from its `GitHub repository <https://github.com/althonos/nmrml2isa>`__.
Please note that the GitHub version of the program may fix bugs but
also introduce new bugs, and that it might not work on your files.


Dependencies
------------

- `pronto <https://pypi.python.org/pypi/pronto>`__

.. warning::
   Without pip you'll have to install the dependencies yourself, or else running
   ``setup.py`` will fail when trying to import **nmrml2isa** for the first time.


PyPI (stable version) |PyPI version|
------------------------------------

.. |PyPI version| image:: https://img.shields.io/pypi/v/nmrml2isa.svg?style=flat&maxAge=2592000
   :target: https://pypi.python.org/pypi/nmrml2isa/
   :align: middle


With `pip`
''''''''''

Just run one the following commands in a terminal:

.. code:: bash

   pip install nmrml2isa        # install for all users, needs super-user rights
   pip install nmrml2isa --user # install only for the current user, no rights needed


Without `pip`
'''''''''''''

This requires the python ``setuptools`` module to be installed, as well as the dependencies listed above. Download the latest stable release
from the `PyPI repository <https://pypi.python.org/pypi/nmrml2isa>`__, unpack it and install it
by running the following commands:

.. code:: bash

   tar xf nmrml2isa-xx.yy.zz.tar.gz # replace with whatever version you downloaded
   cd nmrml2isa-xx.yy.zz.tar.gz
   python setup.py install          # will require super-user rights



GitHub (development version) |Build Status|
-------------------------------------------

.. warning::
   Please check the current version of the program passes the Travis CI validation beforehand,
   or else you're likely to install a non-functioning version of the program ! The program
   is working if the badge above displays |Passing build|.


With `pip`
''''''''''

.. code:: bash

   pip install git+git://github.com/althonos/nmrml2isa


Without `pip`
'''''''''''''

.. code:: bash

   git clone https://github.com/althonos/nmrml2isa
   cd nmrml2isa
   python setup.py install


.. |Build Status| image:: https://img.shields.io/travis/althonos/nmrml2isa.svg?style=flat&maxAge=2592000
   :target: https://travis-ci.org/althonos/nmrml2isa
   :align: middle

.. |Passing build| image:: https://img.shields.io/badge/build-passing-brightgreen.svg

