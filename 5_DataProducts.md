# UAS Data data product types and processing levels

A scheme of data Levels allows data users to clearly identify the types of data products within a UAS data package. 

The following tables describe data levels, giving examples of data types and file formats. With ‘File name convention’, the *** represents a prefix for a flight or campaign. This prefix should represent on the study site, acquisition date, and/or flight identification as appropriate.

---
## Level 0 (L0): raw data collected with the platform
[Flight mission telemetry and trigger records](#Flight-mission-telemetry-and-trigger-records)|
[Spectral reflectance json files](#Spectral-reflectance-json-files)|
[Optical RGB photos](#Optical-RGB-photos)|
[Spectral datacube image](#Spectral-datacube-image)|
[Multispectral image](#Multispectral-image)|
[Multispectral calibration image](#Multispectral-calibration-image)|
[Calibration panel reflectance reference](#Calibration-panel-reflectance-reference)|
[Thermal IR images](#Thermal-IR-images)|
[Ground station](#Ground-station)|

## Level 1 (L1): data products after basic post-processing
[Optical RGB orthomosaic](#Optical-RGB-orthomosaic)|
[Digital surface model](#Digital-surface-model)|
[Thermal IR orthomosaic](#Thermal-IR-orthomosaic)|
[At-surface spectral reflectance](#At-surface-spectral-reflectance)|
[At-surface spectral reflectance orthomosaic](#At-surface-spectral-reflectance-orthomosaic)|
[Point clouds](#Point-clouds)|

## Level 2 (L2): higher-level processed data products
[Georeferenced optical RGB orthomosaic](#Georeferenced-optical-RGB-orthomosaic)|
[Georeferenced thermal IR orthomosaic](#Georeferenced-thermal-IR-orthomosaic)|
[Georeferenced optical spectral orthomosaic](#Georeferenced-optical-spectral-orthomosaic)|
[Canopy height model](#Canopy-height-model)|
[Digital elevation model](#Digital-elevation-model)|

## Level 3 (L3): higher-level derived data products
[Plant functional type (PFT) map](#Plant-functional-type-(PFT)-map)|
[Foliar nitrogen](#Foliar-nitrogen)|![image](https://github.com/ess-dive-community/essdive-uas/assets/13078587/5334050d-648b-411f-9cea-067cbc45b32a)

### Flight mission telemetry and trigger records
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|kml, txt, json|
|**File name recommendation**|[date]_[flight number or record] ID]_[data_description]. e.g. 2018-07-26_flight1_camera_shutter_log.txt|
|**Comments**|Depending on the UAS platform there may be ancillary information required for data processing. These records, including GPS information, trigger points, and other telemetry can be saved as L0 mission information.|

### Spectral reflectance json files
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|json, txt, netcdf|
|**File name recommendation**|[date]_[flight number or record ID]_[spectral_reflectance].txt|
|**Comments**|If utilizing a point spectrometer system a flat text or other file will contain the spectral information by wavelength. L0 data should include the raw DN or radiance data and any in-flight or pre-flight calibration data needed for conversion to the measurement of interest (e.g. surface at-surface reflectance).|

### Optical RGB photos
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|jpg, tiff|
|**File name recommendation**|[prefix][number].jpg e.g.DSC0001.jpg|
|**Comments**|Report the naming convention and total number of files/raw images. The individual file naming convention is typically set by the UAS camera.|

### Spectral datacube image
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|dat, hdf5|
|**File name recommendation**|[date]_[flight number or record ID]_[DN or rad or ref]_img.tiff|
|**Comments**|Usually Digital Numbers (DN) swaths; file type is often in a proprietary or binary format. DN: digital number; rad: radiance image; ref: reflectance image.|

### Multispectral image
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff|
|**File name recommendation**|[date]_[flight number or record ID]_[DN or rad or ref]_img.tiff|
|**Comments**|Usually Digital Numbers (DN) swaths; file types are usually proprietary formats.|

### Multispectral calibration image
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff|
|**File name recommendation**|[date]_[flight number or record ID]_[DN or rad or ref]_img.tiff|
|**Comments**|Usually Digital Numbers (DN) swaths; file types are usually proprietary formats.|

### Calibration panel reflectance reference
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|Txt, csv|
|**File name recommendation**|[date]_[flight number or record ID]_[spectral_calibration].txt|
|**Comments**|The pre-/post-flight measurement of the spectral calibration panel in DN or radiance.|

### Thermal IR images
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|Binary, tiff, HDF5|
|**File name recommendation**|[date]_[flight number or record ID]_[DN or temperature].dat|
|**Comments**|Depending on the camera and image acquisition these data will be in a binary format or image format. Data should be provided with the information or assumptions necessary for converting raw radiance to brightness and surface temperatures.|

### Ground station
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|csv, tex, rinex binary|
|**File name recommendation**|[date]_[flight number or record ID]_[gps].txt|
|**Comments**|GNSS ground station raw and post-processed data.|

### Optical RGB orthomosaic
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff|
|**File name recommendation**|***_rgb.tiff|
|**Comments**|An orthomosaic image that has been georeferenced to the surface with a coordinate system and projection.|

### Digital surface model
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff|
|**File name recommendation**|***_dsm.tiff|
|**Comments**|An orthomosaic image that has been georeferenced to the surface with a coordinate system and projection. The DSM can either be derived from structure-from-motion or through the processing of LiDAR observations.|

### Thermal IR orthomosaic
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff, binary|
|**File name recommendation**|***_tir.tiff|
|**Comments**|An orthomosaic image that has been georeferenced to the surface with a coordinate system and projection. Typically provided as a physical measurement such as land-surface temperature in degrees C or Kelvin.|

### At-surface spectral reflectance
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|csv|
|**File name recommendation**|***_HDRF.csv|
|**Comments**|Includes spectral/atmospheric calibration information.|

### At-surface spectral reflectance orthomosaic
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff, binary, hdf5|
|**File name recommendation**|***_HDRF.dat|
|**Comments**|Calibrated and at-surface spectral reflectance image cube. If relevant, the data format should also be indicated in the metadata, e.g. band-sequential, BSQ or band interleaved by pixel, BIP.|

### Point clouds
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|laz|
|**File name recommendation**|***_CloudPoints.las OR ***_CloudPoints.laz|
|**Comments**|This should be the georeferenced, classified if possible, LiDAR or SfM cloud points.|

### Georeferenced optical RGB orthomosaic
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff|
|**File name recommendation**|***_GeoAligned_point01m.tiff|
|**Comments**|Improved geo-registration of the L1 data product using an authority reference.|

### Georeferenced thermal IR orthomosaic
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff, binary, hdf5|
|**File name recommendation**|***_ GeoAligned _TIR_point01m.tiff|
|**Comments**|Improved geo-registration of the L1 data product using an authority reference.|

### Georeferenced optical spectral orthomosaic
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff, binary, hdf5|
|**File name recommendation**|***_ GeoAligned _HDRF_point05m.tiff|
|**Comments**|Improved geo-registration of the L1 data product using an authority reference. If relevant, the data format should also be indicated in the metadata, e.g. band-sequential, BSQ or band interleaved by pixel, BIP|

### Canopy height model
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff|
|**File name recommendation**|***_ GeoAligned _CHM_point01m.tiff|
|**Comments**|The estimated canopy height is derived with the point cloud data from LiDAR or structure-from-motion and using an algorithm to detect the vegetation (if present).|

### Digital elevation model
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff|
|**File name recommendation**|***_ GeoAligned _DEM_point01m.tiff|
|**Comments**|The estimated surface or terrain elevation derived with the point cloud data from LiDAR or structure-from-motion and removing the vegetation (if present).|

### Plant functional type (PFT) map
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff|
|**File name recommendation**|***_pft.tiff|
|**Comments**|A map of plant functional types by pixel provided with an estimate of the error or uncertainty for each class.|

### Foliar nitrogen
|:----------------------------------------------------|:----------------------------------------------------|
|**File type examples**|tiff|
|**File name recommendation**|***_leafN.tiff|
|**Comments**|A map of estimated leaf nitrogen at the top of the canopy with an estimate of the error or uncertainty for each pixel or image.|
