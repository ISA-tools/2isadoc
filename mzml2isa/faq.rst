Frequently Asked Questions
==========================





What metadata does mzml2isa extract from the .mzML files ?
----------------------------------------------------------




The program crashed when I used it on my files, what should I do ?
------------------------------------------------------------------

While the **mzML** file format is supposed to be a standard, it so
happens that depending on what hardware and software were used to
generate .mzML files after a Mass Spectrometry study, some tags may
not be named the same, and that some metadata may be absent or
elsewhere than expected in the final .mzML file.

Even though the example files used to test mzml2isa are thought to be
comprehensive, it might happen that the files you use are one of the
special cases we did not consider.

In order to help the resolution of such problems, contact one of the author
of the program in the :ref:`contacts` page, and send him the following information
in your email:

  * what software and software version you used (you can know the version
    by running ``mzml2isa --version`` in a terminal)
  * **the file that made the program crash** (without this, nothing can
    be done to analyze the issue)
  * any remark you might have on how you think your file is `not`
    generic (special instrument, multiple instruments, special parameters,
    etc.)

The development team will then have a glance at that file to try to understand
what made the program crash.



