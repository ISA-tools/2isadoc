Installation
============


Dependencies
------------

  This package relies on:
    - |pronto|_ to parse ontology files
    - |lxml|_ to parse .mzML files

  .. warning::
     Without pip you'll have to install the dependencies yourself, or else running 
     ``setup.py`` will fail when trying to import **mzml2isa** for the first time.



  .. |pronto| replace:: ``pronto``
  .. _pronto: https://pypi.python.org/pypi/pronto

  .. |lxml| replace:: ``lxml``
  .. _lxml: http://lxml.de



PyPI (stable version)
---------------------

  Current version: |PyPI version|

  * With ``pip``


    mzml2isa is available on PyPI, so if ``pip`` is installed on your
    machine installing mzml2isa should be quite straightforward, without
    the need to worry about dependencies.

    To install mzml2isa, run one the following commands in a terminal:

    .. code:: bash

       pip install mzml2isa        # install on the machine, needs super-user rights
       pip install mzml2isa --user # install only for the current user, no rights needed


  * Without ``pip``


    If however `pip` is not installed (you should install it!), then it is still possible
    to install mzml2isa from the distributed source package. Go on the Pypi page
    and download `mzml2isa-x.y.z.tar.gz` (the latest sdist archive available). This
    method requires the ``setuptools`` python module.

    Unpack it and install it by running the following commands

    |mzml2isa pypi code|
 

.. |PyPI version| image:: https://img.shields.io/pypi/v/mzml2isa.svg?style=flat&maxAge=2592000
   :target: https://pypi.python.org/pypi/mzml2isa/




GitHub (development version)
----------------------------

  Current status: |Build Status|

  .. warning::
     Please check the current version of the program passes the Travis CI validation beforehand, 
     or else you'll install a non-functioning version of the program ! The program is working
     if the badge above looks like |Passing build|.


  * With ``pip``

    .. code:: bash

       pip install git+git://github.com/althonos/mzml2isa


  * Without ```pip```

    .. code:: bash
    
       git clone https://github.com/althonos/mzml2isa
       cd mzml2isa
       python setup.py install


.. |Build Status| image:: https://img.shields.io/travis/althonos/mzml2isa.svg?style=flat&maxAge=2592000
   :target: https://travis-ci.org/althonos/mzml2isa

.. |Passing build| image:: https://img.shields.io/badge/build-passing-brightgreen.svg

