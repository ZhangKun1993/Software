# Software
Introduction
===
	This program is used to test the efficiency of four drawing methods including direct drawing method ,texture-based method,glyph-based method and the method we proposed. In this case, the earthquake dataset and GPS trajectory datasets were chosen as the test data. We select five symbols varying on geometric complexities  to compare four different symbol drawing methods.

[System Requirements]
===
	-Make sure that your system meets the minimum requirements to run this Demo.
.	-2.5 Gigahertz or faster processor
.	-Windows 7 (64 bit);  Windows 10 (64 bit)
.	-2 GB of installed RAM with 4G MB recommended
.	-60 GB of available hard disk space
.	-1,600 x 900 screen resolution
=[Folders]

bin folder
	The bin directory contains the working version. 
	It contains executable program(DataRender.exe), supporting symbol libraries, font files, and dependency dynamic libraries.
	
data folder
	The data file contains two folders: earthquake data and GPS trajectory data.
	The earthquake data folder contains earthquake dataset(.shp) and background image(NE1_50M_SR_W.tif).
	The GPS trajectory data folder contains GPS trajectory data(.plt) and background image(bei jing.tif).

src folder
	The src folder contains the testing code for the program. It was compiled by Visual Studio 2013 and contains two VS solutions: -DataRender and gisRender.
	DataRender is a test project. While the three comparing methods are implemented in gisRender, our method is encapsulated in gisRender_2.dll.
	
/////////////////////////////////////////////////////////////////////////////

[Perform the tests]
case 1:
	1.Execute the DataRender.exe
	2.Load background image(NE1_50M_SR_W.tif) and load earthquake dataset(EarthquakeDataset1990-2013.shp)
	3.Loading symbol library (Default Marker.MSD) in the bin folder, the default symbol is circle 1. The testing symbol can be specified though a GUI (symbol viewer). 
	4.Choose a drawing method to render the data.
	5.The performance results are output as a text file in the working folder.

case 2:
	1.Execute the DataRender.exe
	2.Load background image(bei jing.tif) and load GPS trajectory dataset.You Can Use "Crtl + A" to select all files in GPS trajectory dataset folder .
	3. Loading symbol library (Default Marker.MSD) in the bin folder, the default symbol is circle 1. The testing symbol can be specified though a GUI (symbol viewer). 
	4.Choose a drawing method to render the data.
	5.The performance results are output as a text file in the working folder.
	
/////////////////////////////////////////////////////////////////////////////
[Dependent library]
FreeImage.dll
gdal18.dll
geos_x64.dll
gisRender.dll
gisRender_1.dll
gisRender_2.dll
libcairo-2.dll
libfontconfig-1.dll
libfreetype-6.dll
libiconv-2.dll
liblzma-5.dll
libpixman-1-0.dll
libpng16-16.dll
libxml2-2.dll
mfc120u.dll
mfcm120u.dll
msvcp120.dll
msvcr120.dll
vcomp120.dll
SymbolViewer.dll
zlib1.dll

/////////////////////////////////////////////////////////////////////////////
  
