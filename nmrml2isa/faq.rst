Frequently Asked Questions
==========================



What metadata does nmrml2isa extract from the .mzML files ?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
nmrml2isa extracts a lot more information than it actually writes to the
final ISA-Tab files. The following parameters are successfully extracted:

The program crashed when I used it on my files, what should I do ?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
As the **nmrML** file format is quite new, there is still issues to fix
concerning the standardization of the format. The converter might not
work as intended, there might be missing tags in the nmrML file you tried
to parse.

But most of the times those problems are not really complicated to mend,
and they help making nmrml2isa a more and more generic program.

In order to help the resolution of such problems, contact one of the author
of the program in the :doc:`/contact` page, and send him the following information
in your email:

  * what software and software version you used (you can know the version
    by running ``nmrml2isa --version`` in a terminal)
  * **the file that made the program crash** (without this, nothing can
    be done to analyze the issue)
  * any remark you might have on how you think your file is `not`
    generic (special instrument, multiple instruments, special parameters,
    etc.)

The development team will then have a glance at that file to try to understand
what made the program crash.



The parameter `xxxxx` does not get extracted / is not correct !
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
First of all: is it present in the source .nmrML file ? It could happen that
some parameters were not successfully written into the converted file when
the nmrML converter converted the Raw NMR files.
Also, nmrml2isa relies on **controlled vocabulary terms** to extract those
parameters from the source nmrML, so if the parameters are present but
not labeled, there are large chances those parameters won't be extracted
from the nmrML file.
