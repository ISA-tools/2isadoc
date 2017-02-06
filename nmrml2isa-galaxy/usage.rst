Usage
=====

See the python package documentation for `detailed explanation http://2isa.readthedocs.io/en/latest/nmrml2isa/index.html`__  


Folder structure
----------------

nmrml2isa only requires that you put all you nmrML and zipped raw files
in the same folder, and parsing should work fine. Note that reference to
RAW files is extracted from the mzML files, so if you plan to create an
ISA archive after mzml2isa creates ISA files, don't forget to include
those as well.

Example structure::

   /
   └ home/
     └ metabolomics/
       └ nmrML_study1/     # the name of the folder doesn't matter
         ├ Sample1.nmrML  # the name of the file must correspond to the sample name
         ├ Sample2.zip    # the raw files should be zipped and called exactly like the nmrML
         ├ Sample2.nmrML
         ├ Sample2.zip
         └ ...
       └ nmrML_study2/    
         ├ Sample1.nmrML 
         ├ Sample2.zip    
         ├ Sample2.nmrML
         ├ Sample2.zip
         └ ...

The folders need to be zipped before adding to galaxy e.g. nmrML_study1.zip. The zipped folders are then added 1 at a time through the GetData interface of Galaxy.
