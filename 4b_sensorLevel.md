|**Metadata element**|**Variable name**|**Optical RGB camera**|**Thermal camera**|**Point spectrometer**|**Imaging spectrometer**|**LiDAR**|
|:------|:------|:------|:------|:------|:------|:------||
|Sensor type|sensorType|required|required|required|required|required|
|Manufacturer and model|makeModel|required|required|required|required|required|
|Serial number|serialNum|optional|required|required|required|required|
|Calibration date|calibrationDate|x|recommended|recommended|recommended|recommended|
|Foreoptic|Foreoptic|required|required|required|required|x|
|Image area and size|imageSize|optional|optional|x|x|x|
|Shutter speed|shutterSpeed|required|x|x|x|x|
|Focal length|focalLength|required|required|x|x|x|
|FOV|FOV|recommended|recommended|recommended|recommended|required|
|ISO|ISO|required|x|x|x|x|
|Focus|focus|optional|optional|x|optional|x|
|White balance|whiteBalance|optional|x|x|x|x|
|Quantization|quant|optional|optional|optional|optional|x|
|File format|fileFormat|required|required|required|required|required|
|Sensor measurement units|sensorUnits|optional|required|required|required|optional|
|Accuracy|accuracy|x|required|required|required|required|
|Precision|precision|x|required|required|required|required|
|Sensitivity|sensitivity|optional|required|required|required|optional|
|Collection frame rate|frameRate|optional|required|x|required|required|
|Sensor spectral response functions|spectralResponseFunction|x|optional|optional|optional|x|
|Integration time|integrationTime|x|x|optional|optional|x|
|Spectral range|spectralRange|x|x|optional|optional|x|
|Spectral resolution|spectralRes|x|x|optional|optional|x|
|Navigation|navSystem|x|x|optional|required|required|
|Spatial pixels|spatialPixels|x|required|x|required|x|
|F-number|Fnumber|required|required|x|optional|x|
|weight|weight|optional|optional|optional|optional|recommended|
|Lidar wavelength|lidarWavelength|x|x|x|x|required|
|Lidar channels|lidarChannels|x|x|x|x|required|
|Lidar range|lidarMeasurementRange|x|x|x|x|recommended|
|Minimum angular Resolution|minAngRes|x|x|x|x|recommended|
|Angular resolution|angRes|x|x|x|x|recommended|
