# OPERA-ArcGIS-Toolbox
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
## Overview
The toolbox contains three geoprocessing tools.   
(a)	OPERA Granule Download  
(b)	OPERA Granule Filter  
(c)	OPERA Raster Mosaic

These tools perform the following actions:  
(a)	Download OPERA DSWx-HLS granules from PO.DAAC.  
    Download OPERA DIST-ALERT granules from LP DAAC.  
    Download OPERA RTC-S1 granules from ASF DAAC.  
(b)	Filter OPERA DSWx-HLS granules from the downloaded stack in (a) or from a previously downloaded stack based on a user-provided date range and Area of Interest (AOI). Optional functionality copies subsets of granules into a separate folder based on filter parameters.  
(c)	Composite and mosaic OPERA DSWx-HLS granules based on user-provided land cover priorities (The mosaic operator will choose the prioritized land cover class in areas where granules overlap). 

The contents of the toolbox are as follows: 
-	This readme file
-	The OPERA ArcGIS Pro Toolbox
-	a folder with the Global MGRS (Military Grid Reference System) shapefile (mgrs_region.shp): This grid is used to query OPERA granules on PO.DAAC based on the user-provided AOI. 
-	a color ramp file (colorramp.clr): This is used to preserve original OPERA color ramp information during geoprocessing.
NOTE: The MGRS grid shapefile and the colorramp.clr file are required to successfully run the tools. Please refrain from deleting/moving outside of its current location.

Video turorials for the toolbox are available here https://www.youtube.com/playlist?list=PLKWlaxzCh8uLAtuqFMQtjbZxqhKI_9fPR. Note* these tutorials were made for the first version of the toolbox that did not include DIST-ALERT or RTC products.

## Installation
To install this toolbox, first download the included zip folder and extract. Next, open ArcGIS Pro, navigate to "Toolboxes" in the catalog. Right click on Toolboxes, select "add toolbox", and select the .atbx file in the unpacked location.
