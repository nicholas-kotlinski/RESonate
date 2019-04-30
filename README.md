# RESonate
RESonate (Riverine Ecosystem Synthesis) geoprocessing methodology for rapid analysis and categorization of river systems based on hydrogeomorphic variables using ArcPy based scripts for use in ArcGIS.

The RESonate Tool is a semi-automated GIS-based process designed for ArcGIS that enables the rapid collection and processing of GIS data sources and geomorphic variable extraction. These variables embody fundamental geologic, climatic, and topographic characteristics of riverine landscapes, that can be quantified using freely available geospatial datasets, and are thought to be an ideal minimum set of variables to identify distinct river valley scale differences within a watershed.

Read more about RESonate at **[ESRI ArcNews](https://www.esri.com/esri-news/arcnews/spring17articles/comparing-distant-river-systems-to-assess-the-effects-of-climate-change)**

Learn more about the methodology from my **GIS in the Rockies [Presentation](https://www.slideshare.net/GISITR/2016-conservation-track-automated-river-classification-using-gis-delineated-functional-process-zones-by-nicholas-kotlinski)**

All of the files should be downloaded for use. The **"RESonate_Arcpy_Untouched.tbx"** should be used in place of the toolbox included in the zipped folder. For everything else, please follow the directions provided.

The **"RESonate_Support_Package.tbx"** is a suite of supplemental processing tools can be used to automate the creation and management of GIS data inputs for the RESonate tool.

It includes batch projection, clipping, generalization, and mosaic functions for vector and raster data (i.e., DEM, PRISM, Geology). It also includes models to expedite the editing of vector streamlines, which was previously performed manually. A **Single Variable Extraction** tool, which is a simplified version of the RESonate tool that can extract and organize additional variables (vector) not included in the original tool (i.e., land-cover).
