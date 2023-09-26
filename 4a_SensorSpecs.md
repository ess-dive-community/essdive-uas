# UAS Sensor Specification Metadata Guide

This page provides description of the variables included in the Sensor Specification metadata. Use this to guide completion of a Sensor Specification metadata [template](https://github.com/ess-dive-community/essdive-uas/tree/main/templates) for each sensor. Refer to the [Sensor metadata requirement level](https://github.com/ess-dive-community/essdive-uas/blob/main/4b_SensorReqLevel.md) for guidance on which variables are required, recommended, optional or not applicable for different sensor types. 

---  
## Sensor Specification Metadata Content - Click links below for full description. 
See [Sensor metadata requirement level](https://github.com/ess-dive-community/essdive-uas/blob/main/4b_SensorReqLevel.md) for requirement levels for each sensor type. 
[Sensor type](#Sensor-type) |
[Manufacturer and model](#Manufacturer-and-model) |
[Serial number](#Serial-number) |
[Calibration date](#Calibration-date) |
[Foreoptic](#Foreoptic) |
[Image area and size](#Image-area-and-size) |
[Shutter speed](#Shutter-speed) |
[Focal length](#Focal-length) |
[FOV](#FOV) |
[ISO](#ISO) |
[Focus](#Focus) |
[White balance](#White-balance) |
[Quantization](#Quantization) |
[File format](#File-format) |
[Sensor measurement units](#Sensor-measurement-units) |
[Accuracy](#Accuracy) |
[Precision](#Precision) |
[Sensitivity](#Sensitivity) |
[Collection Frame Rate](#Collection-Frame-Rate) |
[Sensor spectral response functions](#Sensor-spectral-response-functions) |
[Integration time](#Integration-time) |
[Spectral range](#Spectral-range) |
[Spectral resolution](#Spectral-resolution) |
[Navigation](#Navigation) |
[Spatial pixels](#Spatial-pixels) |
[F-number](#F-number) |
[weight](#weight) |
[LiDAR wavelength](#LiDAR-wavelength) |
[LiDAR channels](#LiDAR-channels) |
[LiDAR range](#LiDAR-range) |
[Minimum angular Resolution](#Minimum-angular-Resolution) |
[Angular resolution](#Angular-resolution) |

### Sensor type
|**Variable name**|sensorType|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Type of sensing system|
|**Example**|Thermal camera|

### Manufacturer and model
|**Variable name**|makeModel|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Manufacturer and model of sensor|
|**Example**|Canon EOS M6|

### Serial number
|**Variable name**|serialNum|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Instrument serial number|
|**Example**|6001194|

### Calibration date
|**Variable name**|calibrationDate|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|YYYY-MM-DD|
|**Description**|Date of last calibration|
|**Example**|2022-10-04|

### Foreoptic
|**Variable name**|foreoptic|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Specifications of the foreoptic used for data collection. A foreoptic could be an optical lens, a fiber optic, a combined fiber optic+lens, etc. Include serial numbers if applicable.|
|**Example**|Canon Zoom Lens EF-M 15-45 mm with a neutral density filter; Fiber optic cable with a variable FOV optical lens; None|

### Image area and size
|**Variable name**|imageSize|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Image size in pixels|
|**Example**|DX 6000 _ 4000 = 24 megapixel|

### Shutter speed
|**Variable name**|shutterSpeed|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|s|
|**Description**|Camera shutter speed. Can be fixed for all flights or a range of values if variable.|
|**Example**|1/200|

### Focal length
|**Variable name**|focalLength|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|numeric|
|**Description**|Instrument focal length|
|**Example**|35mm, 18-55mm|

### FOV
|**Variable name**|FOV|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|degrees|
|**Description**|The instrument field of view. For LiDAR specify horizontal and vertical FOV|
|**Example**|360, 40|

### ISO
|**Variable name**|ISO|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|numeric|
|**Description**|ISO light sensitivity setting. Can be fixed for all flights or a range of values if variable.|
|**Example**|100|

### Focus
|**Variable name**|focus|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Camera focus setting. List all that were used|
|**Example**|auto, infinity|

### White balance
|**Variable name**|whiteBalance|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Camera white balance settings used. List all settings used during campaign.|
|**Example**|sunlight|

### Quantization
|**Variable name**|quant|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Image bit depth|
|**Example**|12-bit|

### File format
|**Variable name**|fileFormat|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Sensor output file format|
|**Example**|jpg|

### Sensor measurement units
|**Variable name**|sensorUnits|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|The measurement units output by the sensor|
|**Example**|Digital Number; Radiance; brightness temperature; degrees Celsius|

### Accuracy
|**Variable name**|accuracy|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Instrument/sensor measurement accuracy as per manufacturer specifications|
|**Example**|+/- 1 degree|

### Precision
|**Variable name**|precision|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Instrument/sensor measurement precision as per manufacturer specifications|
|**Example**|+/- 1 meters|

### Sensitivity
|**Variable name**|sensitivity|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Instrument sensitivity as per manufacturer specifications. The smallest difference between two features that is detectable by the sensor.|
|**Example**|0.1 degrees|

### Collection Frame Rate
|**Variable name**|frameRate|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|Hz|
|**Description**|Measurement frame rate or speed|
|**Example**|30|

### Sensor spectral response functions
|**Variable name**|spectralResponseFunction|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|defined vocabulary: yes, no|
|**Description**|Indicate if spectral response functions are included in data package|
|**Example**|Table of band number, wavelength, and intensity|

### Integration time
|**Variable name**|integrationTime|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Measurement integration time. Can be fixed value or range.|
|**Example**|1 - 2 s|

### Spectral range
|**Variable name**|spectralRange|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Instrument measurement wavelength range. Can be more than one if a co-aligned instrument|
|**Example**|350 ~ 1000 nm|

### Spectral resolution
|**Variable name**|spectralRes|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Instrument measurement resolution. Can be more than one if a co-aligned instrument|
|**Example**|1.5 nm|

### Navigation
|**Variable name**|navSystem|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|free text|
|**Description**|Make/Model of GNSS Inertial Measurement Unit used with the sensing system|
|**Example**|Trimble APX-15L w/ AV18 antenna|

### Spatial pixels
|**Variable name**|spatialPixels|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|numeric|
|**Description**|For each sensor plus combined|
|**Example**|1240|

### F-number
|**Variable name**|Fnumber|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|numeric|
|**Description**|The fixed or selected aperture size for the data collection|
|**Example**|F/4|

### weight
|**Variable name**|weight|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|grams|
|**Description**|Weight of sensor|
|**Example**|925|

### LiDAR wavelength
|**Variable name**|LiDARWavelength|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|nanometers|
|**Description**|LiDAR beam wavelength|
|**Example**|903|

### LiDAR channels
|**Variable name**|LiDARChannels|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|integer|
|**Description**|The total number of LiDAR channels (laser beams) used for data collection|
|**Example**|32|

### LiDAR range
|**Variable name**|LiDARMeasurementRange|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|meters|
|**Description**|Max measurement distance|
|**Example**|200|

### Minimum angular Resolution
|**Variable name**|minAngRes|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|degrees|
|**Description**|Angular resolution of LiDAR system (Vertical)|
|**Example**|0.33|

### Angular Resolution
|**Variable name**|angRes|
|:----------------------------------------------------|:----------------------------------------------------|
|**Unit or format**|degrees|
|**Description**|Angular Resolution (Horizontal/Azimuth):|
|**Example**|0.1 to 0.4|
