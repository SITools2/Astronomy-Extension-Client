![](workspace/client-public/res/images/logo_01_petiteTaille.png)
# SITools2 client extensions
## Description
SITools2 is a new CNES generic tool performed by a joint effort between CNES and scientific laboratories. The aim of SITools is to provide a self-manageable data access layer deployed on already existing scientific laboratory databases.

This repository contains usefull extensions for the client part

For more information : [http://sourceforge.net/projects/sitools2/](http://sourceforge.net/projects/sitools2/ "SITools2 Web Site")

Release notes : [README.txt](workspace/sitools-build/files/README.txt)

## Installing the extensions

Copy js and resources directories to the client-extension-3.0 directory of your SITools2 installation

	cp -r js/ <sitools_install>/workspace/client-extension-3.0/js
	cp -r resources/ <sitools_install>/workspace/client-extension-3.0/resources 

Copy the data/ directory to the data directory of your SITools2 installation

	cp -r data/ <sitools_install>/data