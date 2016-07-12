.. 2isa documentation master file, created by
   sphinx-quickstart on Fri Jul  8 18:41:53 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

2isa suite
==========

The 2isa suite is a collection of programs that can extract metadata out of various metabolomics file formats and write them to ISA-Tab files, creating the backbone for an ISA-Tab study that can then be shared on databases such as `MetaboLights <http://metabolights.org>`__. Right now the following source files are supported:

  .mzML
    XML-like files containing derived spectral data of mass spectrometry scans

  .imzML
    XML-like files containing metadata about imaging mass spectrometry scans

  .nmrML
    XML-like files containing derived spectral data of nuclear magnetic resonance scans


Documentation
-------------

.. toctree::
   :maxdepth: 2

   mzml2isa  <mzml2isa/index.rst>
   nmrml2isa <nmrml2isa/index.rst>


About
-----

.. toctree::

   Contacts  <contacts.rst>


Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

