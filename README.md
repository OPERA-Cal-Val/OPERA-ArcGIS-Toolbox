# OPERA-ArcGIS-Toolbox
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
## Overview
The toolbox contains three geoprocessing tools.   
(a)	OPERA Granule Download  
(b)	OPERA Granule Filter  
(c)	OPERA Granule Mosaic  
(d) OPERA Zonal Statistics

These tools perform the following actions:  
(a)	Download OPERA DSWx-HLS granules from PO.DAAC.  
    Download OPERA DIST-ALERT granules from LP DAAC.  
    Download OPERA RTC-S1 granules from ASF DAAC.  
(b)	Filter OPERA DSWx-HLS granules from (a) a previously downloaded stack of granules based on a user-provided date range and Area of Interest (AOI)  
or (b) granules currently existing on the ArcGIS Pro contents pane.   
(c)	Composite and mosaic OPERA DSWx-HLS granules based on user-provided land cover priorities (The mosaic operator will choose the prioritized land cover class in areas where granules overlap).  
(d) Calculate three different types of Zonal Statistics (i.e., number of pixels, area, percentage area) of each land cover class/product category class in granule(s) within a user-provided AOI.   

The contents of the toolbox are as follows: 
-	This readme file
-	Toolbox Documentation (Documentation_OPERAArcGISProToolbox_V1_2.pdf)
-	The OPERA ArcGIS Pro Toolbox  
-	a ‘Dependency’ folder with a .RTX file that contains stretch parameters for the visualization of RTC-S1 product and color ramp files (colorramp_dswx.clr and colorramp_dist.clr) to preserve original OPERA DSWX-HLS and DIST-ALERT color ramp information during geoprocessing.  
NOTE: The dependency folder is required to successfully run the tools. Please refrain from deleting/changing the folder path relative to its current location.  

Video turorials for the toolbox are available here https://www.youtube.com/playlist?list=PLKWlaxzCh8uLAtuqFMQtjbZxqhKI_9fPR. Note* these tutorials were made for the first version of the toolbox that did not include DIST-ALERT or RTC products.

## Installation
To install and access this toolbox in ArcGIS Pro, first download the OPERA-ArcGIS-Toolbox folder and unzip downloaded file. Next, open ArcGIS Pro and navigate to the unpacked location to work with the toolbox.
