# UAS Sensor Specification Requirement Levels

This table indicates the requirement level of each [Sensor Specification metadata variable](https://github.com/ess-dive-community/essdive-uas/blob/main/4a_SensorSpecs.md) for each sensor type. 
### Metadata variables are:
- required (closed circle, &#9679;)
- recommended (shaded circle, &#9677;) 
- optional (open circle, &#9675;) 
- not applicable (**x**)

Use this to guide completion of the [Sensor Specification metadata template](https://github.com/ess-dive-community/essdive-uas/tree/main/templates) for each sensor type. 

|**Metadata element**|**Variable name**|**Optical RGB camera**|**Thermal camera**|**Point spectrometer**|**Imaging spectrometer**|**LiDAR**|
|:------|:------:|:------:|:------:|:------:|:------:|:------:|
|Sensor type|sensor_type|&#9679;|&#9679;|&#9679;|&#9679;|&#9679;|
|Manufacturer and model|make_model|&#9679;|&#9679;|&#9679;|&#9679;|&#9679;|
|Serial number|instrument_serial_num|&#9675;|&#9679;|&#9679;|&#9679;|&#9679;|
|Calibration date|calibration_date|**x**|&#9677;|&#9677;|&#9677;|&#9677;|
|Foreoptic|foreoptic|&#9679;|&#9679;|&#9679;|&#9679;|**x**|
|Image area and size|image_size|&#9675;|&#9675;|**x**|**x**|**x**|
|Shutter speed|shutter_speed|&#9679;|**x**|**x**|**x**|**x**|
|Focal length|focal_length|&#9679;|&#9679;|**x**|**x**|**x**|
|FOV|fov|&#9677;|&#9677;|&#9677;|&#9677;|&#9679;|
|ISO|iso|&#9679;|**x**|**x**|**x**|**x**|
|Focus|focus|&#9675;|&#9675;|**x**|&#9675;|**x**|
|White balance|white_balance|&#9675;|**x**|**x**|**x**|**x**|
|Quantization|quant|&#9675;|&#9675;|&#9675;|&#9675;|**x**|
|File format|file_format|&#9679;|&#9679;|&#9679;|&#9679;|&#9679;|
|Sensor measurement units|sensor_units|&#9675;|&#9679;|&#9679;|&#9679;|&#9675;|
|Accuracy|accuracy|**x**|&#9679;|&#9679;|&#9679;|&#9679;|
|Precision|precision|**x**|&#9679;|&#9679;|&#9679;|&#9679;|
|Sensitivity|sensitivity|&#9675;|&#9679;|&#9679;|&#9679;|&#9675;|
|Collection frame rate|frame_rate|&#9675;|&#9679;|**x**|&#9679;|&#9679;|
|Sensor spectral response functions|spectral_response_function|**x**|&#9675;|&#9675;|&#9675;|**x**|
|Integration time|integration_time|**x**|**x**|&#9675;|&#9675;|**x**|
|Spectral range|spectral_range|**x**|**x**|&#9675;|&#9675;|**x**|
|Spectral resolution|spectral_res|**x**|**x**|&#9675;|&#9675;|**x**|
|Navigation|nav_system|**x**|**x**|&#9675;|&#9679;|&#9679;|
|Spatial pixels|spatial_pixels|**x**|&#9679;|**x**|&#9679;|**x**|
|F-number|f_number|&#9679;|&#9679;|**x**|&#9675;|**x**|
|weight|weight|&#9675;|&#9675;|&#9675;|&#9675;|&#9677;|
|LiDAR wavelength|lidar_wavelength|**x**|**x**|**x**|**x**|&#9679;|
|LiDAR channels|lidar_channels|**x**|**x**|**x**|**x**|&#9679;|
|LiDAR range|lidar_measurement_range|**x**|**x**|**x**|**x**|&#9677;|
|Minimum angular Resolution|min_ang_res|**x**|**x**|**x**|**x**|&#9677;|
|Angular resolution|ang_res|**x**|**x**|**x**|**x**|&#9677;|
