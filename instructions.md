# Reporting format for Unoccupied Aerial System (UAS) data and metadata instructions

A data package containing UAS data should include the following: 

1. Campaign metadata table (csv). 

2. UAS platform metadata table (csv).
   
3. Flight details metadata table (csv), or equivalent output from mission control software.  

4. A sensor metadata table (csv) for each sensor used.

5. Data products identified by processing level. Data from one or more processing levels may be included.

6. For submission to ESS-DIVE, data packages should include the csv data decription file (found [here](https://github.com/ess-dive-community/essdive-uas/blob/main/templates/UAS_CSV_dd.csv) in Templates), and a [file-level metadata file (FLMD)](https://github.com/ess-dive-community/essdive-file-level-metadata). Within the FLMD file, the _standard_ for each reporting format file should be **"ESS-DIVE UAS v1."** ESS-DIVE dataset submissions also require a keyword in the dataset metadata to identify the reporting format. Please add the keyword **"ESS-DIVE Unoccupied Aerial Systems (UAS) Reporting Format"** to this field. 

See the individual pages for each metadata type for variable names, requirement levels (i.e. required, recommended, optional) and full descriptions. Templates are provided for each metadata category. 

## Additional information
UAS platform and sensor technologies are rapidly evolving. Inclusion of additional platform and sensor metadata, such as manufacture specification sheets, is encouraged. 

## Use of this format with established spatial data conventions
The content of this UAS data and metadata reporting format is limited to guidance specific to UAS data, platforms and sensors. It is recommend that data be prepared following recommendations from [EPSG](https://spatialreference.org/ref/epsg/) for spatial reference systems and [ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html) for dates and times. 

## Use of this format with other ESS-DIVE reporting formats
The [ESS-DIVE collection of reporting formats](https://github.com/ess-dive-community) includes formats for different measurement types and also for file and metadata structures. The collection is designed to be modular, so use of multiple reporting formats will be required to correctly format a data package. 

Refer to the [ESS-DIVE Community Space](https://github.com/ess-dive-community) for a complete list of available reporting formats. 

## Example data package
Here is an example data package that follows an early version of these reporting format guidelines. This will be updated when a data package following the completed guidelines becomes available.

Shawn Serbin, Dedi Yang, Andrew McMahon. 2021. Landscape-scale Characterization of Arctic Tundra Vegetation Composition, Structure, and Function with a Multi-sensor Unoccupied Aerial System: Supporting Data. *Next Generation Ecosystem Experiments Arctic Data Collection*, Oak Ridge National Laboratory, U.S. Department of Energy, Oak Ridge, Tennessee, USA. [doi.org/10.5440/1778212](https://doi.org/10.5440/1778212).
