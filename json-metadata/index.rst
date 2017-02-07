Adding additional metadata via JSON file
===========

.. warning::
   *For advanced use only* 

All additional metadata can be added in a JSON format. A format that is easily interchangeable with python dictionaries.

This is to allow the parsing tools to be added into existing bioinformatic/computational workflows that may already have collected this information.

Example format:

.. highlight:: json

.. code:: json

   {
	"characteristics": {
		"organism": {
			"name": "",
			"accession": "",
			"ref": ""
		},
		"organism_variant": {
			"name": "",
			"accession": "",
			"ref": ""
		},
		"organism_part": {
			"name": "",
			"accession": "",
			"ref": ""
		}
	} ....


   }

Example templates for the metadata json can be extracted from either mzml2isa-qt, imzml2isa-qt or nmrml2isa-qt.

Run either of the following:

.. highlight:: bash

.. code:: bash

   python3 -m mzml2isa_qt.usermeta
   python3 -m imzml2isa_qt.usermeta
   python3 -m nmrml2isa_qt.usermeta

Add any metadata through the GUI and then click apply. The terminal will then spit out the JSON text.

See the following link for full `example of json. <http://codebeautify.org/jsonviewer/cba2a5c8>`__   

GUI
-----------
This metadata is added direcly via via the GUI using via the usermeta dialog. 

CLI
-----------
For the CLI simply use the ``-m`` option and direct to the json file. 

.. highlight:: bash
.. code:: bash

   mzml2isa -i /path/to/mzml/folder -o /path/to/out_folder -s STUDYID -m metadata.json
   nmrml2isa -i /path/to/mzml/folder -o /path/to/out_folder -s STUDYID -m metadata.json

API
-----------
For the API the ``usermeta`` paramater can be used to pass the JSON metadata as a python dictionary to the ISA_Tab class. See the following API documentation for class `mzml2isa.isa.ISA_Tab <http://2isa.readthedocs.io/en/latest/mzml2isa/api/isatab.html>`__  and class `nmrml2isa.isa.ISA_Tab <http://2isa.readthedocs.io/en/latest/nmrml2isa/api/isatab.html>`__ 

Galaxy
-----------
This metadata can be added manually via the dropdown options or via a prepared JSON file using the ``Additional user metadata in json`` option.


