# UAS Platform Description Metadata Guide

This page provides description of the variables included in the Platform Description metadata. Use this to guide completion of the [Platform Description metadata template](https://github.com/ess-dive-community/essdive-uas/tree/main/templates). 

---  
## Platform Description Metadata Content - Click links below for full description

[Manufacturer and model](#Manufacturer-and-model) |
[Airframe type](#Airframe-type) |
[Maximum takeoff gross weight](#Maximum-takeoff-gross-weight) |
[Serial number](#Serial-number) |
[Registration](#Registration) |
[Motor type](#Motor-type) |
[Propellor type](#Propellor-type) |
[Flight controller](#Flight-controller) |
[Battery type](#Battery-type) |
[Gimbal type](#Gimbal-Type) |
[Navigation](#Navigation) |
[IMU](#IMU) |
[Radio and telemetry](#Radio-and-telemetry) |
[Handheld remote control](#Handheld-remote-control) |
[Platform images available ](#Platform-images-available) |

### Manufacturer and model
|**Variable name**|makeModel|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|free text|
|**Description**|Manufacturer and model of airframe|
|**Example**|CarbonCore Cortex X8 Heavy-Lift airframe|


### Airframe type
|**Variable name**|airframeType|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|free text|
|**Description**|Type of airframe|
|**Example**|fixed wing, quadcopter, octocopter|


### Maximum takeoff gross weight
|**Variable name**|maxWeight|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|kilograms|
|**Description**|Maximum takeoff gross weight of system including airframe|
|**Example**|12.8|


### Serial number
|**Variable name**|serialNum|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`recommended`|
|**Unit or format**|free text|
|**Description**|Platform serial number|
|**Example**|ABC123456|


### Registration
|**Variable name**|registration|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`recommended`|
|**Unit or format**|free text|
|**Description**|Platform registration details, e.g. FAA registration number|
|**Example**|ABC-123|


### Motor type
|**Variable name**|motorType|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Manufacturer and model of motor types|
|**Example**|T-Motor Tiger motor|


### Propellor type
|**Variable name**|propellorType|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Manufacturer and model of propellor types|
|**Example**|T-Motor carbon fiber propellers|


### Flight controller
|**Variable name**|flightController|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Manufacturer and model of flight controller|
|**Example**|3DR PixelHawk PX4|


### Battery type
|**Variable name**|batteryType|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Battery type (cells, peak voltage, connectors)|
|**Example**|LiPo (or Li-ion), 12 cell, 50.4V, XT-90|


### Gimbal type
|**Variable name**|gimbalType|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Manufacturer and model of gimbal types|
|**Example**|Gremsy H3 gimbal|


### Navigation
|**Variable name**|navigation|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|GPS make/model and supported GNSS modes|
|**Example**|3DR. GPS/Glonass|


### IMU
|**Variable name**|imu|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Inertial Measurement Unit model|
|**Example**|SBG Pulse-40 High Range|


### Radio and telemetry
|**Variable name**|radioModel|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Manufacturer and model of radios|
|**Example**|FRXPro 915 Mhz x 2|


### Handheld remote control
|**Variable name**|controlModel|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Manufacturer and model of handheld remote control|
|**Example**|Futaba 14-channel computer radio system|


### Platform images available
|**Variable name**|platformImages|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Indicate if photos or diagrams showing the platform and payload configuration are included in the data package.|
|**Example**|included|
