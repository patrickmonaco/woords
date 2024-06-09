# woords
Merging Office Word documents with ORDS REST

Merging Office Word document with Data from ORDS service

cf https:// gpmfactory.com/woords for details

Instructions for setup:

	0. Unzip woords 1.0 in a directory
 	1. check the settings.xml file and enter the endpoints for OAUTH et REST
	2. Create a REST module or import the sample module (setup\ORDS_REST_DEMO_gpm.demo.sales.sql)
	3. Create an OAUTH client for authorization
	4. Add a trusted location for templates/Macros in Office WORD 
	5. In a command line, enter: bin\woords -?
