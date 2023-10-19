# UAS Flight Detail Metadata Guide

This page provides description of the variables included in the Flight Detail metadata. Use this to guide completion of the [Flight Detail metadata template](https://github.com/ess-dive-community/essdive-uas/tree/main/templates). 

---  
## Platform Description Metadata Content - Click links below for full description
[Flight name](#Flight-name) |
[Site](#Site) |
[Start date time](#Start-date-time) |
[End date time](#End-date-time) |
[Flight boundary](#Flight-boundary) |
[Flight height](#Flight-height) |
[Forward overlap](#Forward-overlap) |
[Side overlap](#Side-overlap) |
[Flight speed](#Flight-speed) |
[Weather conditions](#Weather-conditions) |
[Brightness](#Brightness) |
[Light type](#Light-type) |
[Cloud cover](#Cloud-cover) |
[Cloud type](#Cloud-type) |
[Surface wetness](#Surface-wetness) |
[Days since last rain event](#Days-since-last-rain-event) |

### Flight name
|**Variable name**|flight_identifier|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|free text|
|**Description**|Individual flight identifier|
|**Example**|KG014|

### Site
|**Variable name**|site_identifier|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|free text|
|**Description**|Site name|
|**Example**|Kougarok Road MM64|

### Start date time
|**Variable name**|date_time_start|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|YYYY-MM-DD HH:MM:SS|
|**Description**|Start of flight date and time|
|**Example**|2018-07-26 03:27:56 UTC|

### End date time
|**Variable name**|date_time_end|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|YYYY-MM-DD HH:MM:SS|
|**Description**|End of flight date and time|
|**Example**|2018-07-26 03:32:51 UTC|

### Flight boundary
|**Variable name**|flight_bound|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|free text|
|**Description**|Boundary of flight area|
|**Example**|See kmz file|

### Flight height
|**Variable name**|flight_height|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|m|
|**Description**|Flight height program setting, indicate AGL (above ground level) or AMSL (height above average mean sea level)|
|**Example**|40 AGL|

### Forward overlap
|**Variable name**|forward_overlap|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|percentage|
|**Description**|Forward overlap program setting|
|**Example**|85|

### Side overlap
|**Variable name**|side_overlap|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|percentage|
|**Description**|Side overlap program setting|
|**Example**|85|

### Flight speed
|**Variable name**|flight_speed|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|m/s|
|**Description**|Flight speed program setting|
|**Example**|5|

### Weather conditions
|**Variable name**|weather_condition|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Summary of wind speed, temperature, cloud cover|
|**Example**|5 mph, 25 ¡C, 10% cloud|

### Brightness
|**Variable name**|brightness|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text or controlled vocabulary: bright/dim/dark|
|**Description**|Descriptor of light quality during flight|
|**Example**|bright|

### Light type
|**Variable name**|light_type|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text or controlled vocabulary: direct/diffuse/variable|
|**Description**|Descriptor of light type during flight|
|**Example**|direct|
### Cloud cover
|**Variable name**|cloud_cover|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|percentage|
|**Description**|Estimate of percentage cloud cover during flight|
|**Example**|50|

### Cloud type
|**Variable name**|cloud_type|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Dominant cloud cover type during flight|
|**Example**|cirrus|

### Surface wetness
|**Variable name**|surface_wetness|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text or controlled vocabulary: dry/moist/wet|
|**Description**|Descriptor of surface moisture conditions|
|**Example**|dry|

### Days since last rain event
|**Variable name**|last_rain|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|numeric|
|**Description**|Days since last rain event|
|**Example**|10|
