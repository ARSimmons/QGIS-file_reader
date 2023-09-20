# file_reader.py

## Team Members
***

* Arielle Simmons-Steffen

# Libraries
***

qgis.PyQT.QTCore
qgis.PyQT.QTGui
qgis.PyQT.QTWidgets

## Project Summary
***
 
'file_reader' is a sample QGIS plugin that was built using the 'QGIS Plugin Builder' (background: http://g-sherman.github.io/Qgis-Plugin-Builder/).

Code iterates through .adf (ESRI Raster Grid component file), .mdb (ESRI personal GeoDatabases), .jpg, .jp2, and coverage files to create a 'output.csv' of file names, created/modified/and last accessed dates, and (if available) projection information.


## How To Use
***

To use this script you need to download this WHOLE folder and then zip it. Then:

1. Open the QGIS software (this script was developed and tested using QGIS Desktop 3.30.1)
2. In the top ribbon, locate and click on the 'Plugins' menu.
3. From the drop-down menu, select “Manage and Install Plugins”. This will open the QGIS Plugin Manager, where you can browse, install, and manage various plugins.

![Screenshot](https://github.com/ARSimmons/QGIS-file_reader/blob/main/picture1.JPG)

4. Next, choose the "Install from ZIPs" option to bring in the plugin's zip file.
5. Locate the plugin zip file by searching through your directory and import it.

![Screenshot](https://github.com/ARSimmons/QGIS-file_reader/blob/main/picture2.JPG)

6. Afterward, simply select "Install Plugin".
7. When a security warning appears, click "Yes" to successfully install the plugin.
8. The plugin tool will become visible in the top ribbon.
9. Double-click the plugin icon and import the input and output folders to retrieve ancillary information from the stored files.

![Screenshot](https://github.com/ARSimmons/QGIS-file_reader/blob/main/picture3.JPG)


## Parameters
***

User puts in a root input folder directory in the 'input' option, and then selects an 'output' location where the 'output.csv' will be stored. Depending on your file sizes, types, and quantities - this script can take some time to run.
