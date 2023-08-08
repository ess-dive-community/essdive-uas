# UAS Sensor Specification Requirement Levels

This table indicates the requirement level of each Sensor Specification metadata variable for each sensor type. 
### Metadata variables are:
- required (closed circle, &#9679;)
- recommended (shaded circle, &#9677;) 
- optional (open circle, &#9675;) 
- not applicable (**x**)

Use this to guide completion of the [Sensor Specification metadata template](https://github.com/ess-dive-community/essdive-uas/tree/main/templates) for each sensor type. 

|**Metadata element**|**Variable name**|**Optical RGB camera**|**Thermal camera**|**Point spectrometer**|**Imaging spectrometer**|**LiDAR**|
|:------|:------:|:------:|:------:|:------:|:------:|:------:|
|Sensor type|sensorType|&#9679;|&#9679;|&#9679;|&#9679;|&#9679;|
|Manufacturer and model|makeModel|&#9679;|&#9679;|&#9679;|&#9679;|&#9679;|
|Serial number|serialNum|&#9675;|&#9679;|&#9679;|&#9679;|&#9679;|
|Calibration date|calibrationDate|**x**|&#9677;|&#9677;|&#9677;|&#9677;|
|Foreoptic|Foreoptic|&#9679;|&#9679;|&#9679;|&#9679;|**x**|
|Image area and size|imageSize|&#9675;|&#9675;|**x**|**x**|**x**|
|Shutter speed|shutterSpeed|&#9679;|**x**|**x**|**x**|**x**|
|Focal length|focalLength|&#9679;|&#9679;|**x**|**x**|**x**|
|FOV|FOV|&#9677;|&#9677;|&#9677;|&#9677;|&#9679;|
|ISO|ISO|&#9679;|**x**|**x**|**x**|**x**|
|Focus|focus|&#9675;|&#9675;|**x**|&#9675;|**x**|
|White balance|whiteBalance|&#9675;|**x**|**x**|**x**|**x**|
|Quantization|quant|&#9675;|&#9675;|&#9675;|&#9675;|**x**|
|File format|fileFormat|&#9679;|&#9679;|&#9679;|&#9679;|&#9679;|
|Sensor measurement units|sensorUnits|&#9675;|&#9679;|&#9679;|&#9679;|&#9675;|
|Accuracy|accuracy|**x**|&#9679;|&#9679;|&#9679;|&#9679;|
|Precision|precision|**x**|&#9679;|&#9679;|&#9679;|&#9679;|
|Sensitivity|sensitivity|&#9675;|&#9679;|&#9679;|&#9679;|&#9675;|
|Collection frame rate|frameRate|&#9675;|&#9679;|**x**|&#9679;|&#9679;|
|Sensor spectral response functions|spectralResponseFunction|**x**|&#9675;|&#9675;|&#9675;|**x**|
|Integration time|integrationTime|**x**|**x**|&#9675;|&#9675;|**x**|
|Spectral range|spectralRange|**x**|**x**|&#9675;|&#9675;|**x**|
|Spectral resolution|spectralRes|**x**|**x**|&#9675;|&#9675;|**x**|
|Navigation|navSystem|**x**|**x**|&#9675;|&#9679;|&#9679;|
|Spatial pixels|spatialPixels|**x**|&#9679;|**x**|&#9679;|**x**|
|F-number|Fnumber|&#9679;|&#9679;|**x**|&#9675;|**x**|
|weight|weight|&#9675;|&#9675;|&#9675;|&#9675;|&#9677;|
|Lidar wavelength|lidarWavelength|**x**|**x**|**x**|**x**|&#9679;|
|Lidar channels|lidarChannels|**x**|**x**|**x**|**x**|&#9679;|
|Lidar range|lidarMeasurementRange|**x**|**x**|**x**|**x**|&#9677;|
|Minimum angular Resolution|minAngRes|**x**|**x**|**x**|**x**|&#9677;|
|Angular resolution|angRes|**x**|**x**|**x**|**x**|&#9677;|
