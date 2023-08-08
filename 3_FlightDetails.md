### Flight name
|**Variable name**|flightIdentifier|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|free text|
|**Description**|Individual flight identifier|
|**Example**|KG014|

### Site
|**Variable name**|siteIdentifier|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|free text|
|**Description**|Site name|
|**Example**|Kougarok Road MM64|

### Start date time
|**Variable name**|DateTime_Start|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|YYYY-MM-DD HH:MM:SS|
|**Description**|Start of flight date and time|
|**Example**|2018-07-26 03:27:56 UTC|

### End date time
|**Variable name**|DateTime_End|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|YYYY-MM-DD HH:MM:SS|
|**Description**|End of flight date and time|
|**Example**|2018-07-26 03:32:51 UTC|

### Flight boundary
|**Variable name**|flightBound|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|free text|
|**Description**|Boundary of flight area|
|**Example**|See kmz file|

### Flight height
|**Variable name**|flightHeight|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|m|
|**Description**|Flight height program setting, indicate AGL (above ground level) or AMSL (height above average mean sea level)|
|**Example**|40 AGL|

### Forward overlap
|**Variable name**|forwardOverlap|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|percentage|
|**Description**|Forward overlap program setting|
|**Example**|85|

### Side overlap
|**Variable name**|sideOverlap|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|percentage|
|**Description**|Side overlap program setting|
|**Example**|85|

### Flight speed
|**Variable name**|flightSpeed|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|m/s|
|**Description**|Flight speed program setting|
|**Example**|5|

### Weather conditions
|**Variable name**|weatherCondition|
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
|**Variable name**|lightType|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text or controlled vocabulary: direct/diffuse/variable|
|**Description**|Descriptor of light type during flight|
|**Example**|direct|
### Cloud cover
|**Variable name**|cloudCover|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|percentage|
|**Description**|Estimate of percentage cloud cover during flight|
|**Example**|50|

### Cloud type
|**Variable name**|cloudType|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Dominant cloud cover type during flight|
|**Example**|cirrus|

### Surface wetness
|**Variable name**|surfaceWetness|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text or controlled vocabulary: dry/moist/wet|
|**Description**|Descriptor of surface moisture conditions|
|**Example**|dry|

### Days since last rain event
|**Variable name**|lastRain|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|numeric|
|**Description**|Days since last rain event|
|**Example**|10|
