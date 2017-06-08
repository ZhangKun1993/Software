# Software
Introduction
===
	This program is used to test the efficiency of four drawing methods including direct drawing method ,texture-based method,glyph-  
	based method and the method we proposed. In this case, the earthquake dataset and GPS trajectory datasets were chosen as the test data.  
	We select five symbols varying on geometric complexities  to compare four different symbol drawing methods.  

[System Requirements]
===  
Make sure that your system meets the minimum requirements to run this Demo.  
.	2.5 Gigahertz or faster processor   
.	Windows 7 (64 bit);  Windows 10 (64 bit)    
.	2 GB of installed RAM with 4G MB recommended    
.	60 GB of available hard disk space    
.	1,600 x 900 screen resolution  
[Folders]
===
bin folder
---
	The bin directory contains the working version. ＜/br＞
	It contains executable program(DataRender.exe), supporting symbol libraries, font files, and dependency dynamic libraries.＜/br＞
	
data folder
---
	The data file contains two folders: earthquake data and GPS trajectory data.＜/br＞
	The earthquake data folder contains earthquake dataset(.shp) and background image(NE1_50M_SR_W.tif).＜/br＞
	The GPS trajectory data folder contains GPS trajectory data(.plt) and background image(bei jing.tif).＜/br＞

src folder
---
	The src folder contains the testing code for the program. It was compiled by Visual Studio 2013 and contains two VS solutions: -DataRender and gisRender.＜/br＞
	DataRender is a test project. While the three comparing methods are implemented in gisRender, our method is encapsulated in gisRender_2.dll.＜/br＞
	
/////////////////////////////////////////////////////////////////////////////

[Perform the tests]
===
case 1:
---
	1.Execute the DataRender.exe＜/br＞
	2.Load background image(NE1_50M_SR_W.tif) and load earthquake dataset(EarthquakeDataset1990-2013.shp)＜/br＞
	3.Loading symbol library (Default Marker.MSD) in the bin folder, the default symbol is circle 1. ＜/br＞
	The testing symbol can be specified though a GUI (symbol viewer). ＜/br＞
	4.Choose a drawing method to render the data.＜/br＞
	5.The performance results are output as a text file in the working folder.＜/br＞

case 2:
---
	1.Execute the DataRender.exe＜/br＞
	2.Load background image(bei jing.tif) and load GPS trajectory dataset.You Can Use "Crtl + A" to select all files in GPS trajectory dataset folder .＜/br＞
	3. Loading symbol library (Default Marker.MSD) in the bin folder, the default symbol is circle 1. The testing symbol can be specified though a GUI (symbol viewer). ＜/br＞
	4.Choose a drawing method to render the data.＜/br＞
	5.The performance results are output as a text file in the working folder.＜/br＞
	
/////////////////////////////////////////////////////////////////////////////
[Dependent library]
===
FreeImage.dll＜/br＞
gdal18.dll＜/br＞
geos_x64.dll＜/br＞
gisRender.dll＜/br＞
gisRender_1.dll＜/br＞
gisRender_2.dll＜/br＞
libcairo-2.dll＜/br＞
libfontconfig-1.dll＜/br＞
libfreetype-6.dll＜/br＞
libiconv-2.dll＜/br＞
liblzma-5.dll＜/br＞＜/br＞
libpixman-1-0.dll＜/br＞
libpng16-16.dll＜/br＞
libxml2-2.dll＜/br＞
mfc120u.dll＜/br＞
mfcm120u.dll＜/br＞
msvcp120.dll＜/br＞
msvcr120.dll＜/br＞
vcomp120.dll＜/br＞
SymbolViewer.dll＜/br＞
zlib1.dll＜/br＞

/////////////////////////////////////////////////////////////////////////////
  
