JSON metadata
===========

This for advanced users only.

All additional metadata can be added in a JSON format. A format that is easily interchangeable with python dictionaries.

This is to allow the parsing tools to be added into existing bioinformatic/computational workflows that may already have collected this information.

Example format:

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

Run either of the following 

.. highlight:: bash

.. code:: bash

   python3 -m mzml2isa_qt.usermeta
   python3 -m imzml2isa_qt.usermeta
   python3 -m nmrml2isa_qt.usermeta

Add any metadata through the GUI and then click apply. The terminal will then spit out the JSON text.

See the following link for full `example of json. http://codebeautify.org/jsonviewer/cba2a5c8`__   




