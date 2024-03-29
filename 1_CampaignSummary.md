# UAS Campaign Summary Metadata Guide

This page provides description of the variables included in the Campaign Summary metadata. Use this to guide completion of the [Campaign Summary metadata template](https://github.com/ess-dive-community/essdive-uas/tree/main/templates). 

---  
## Campaign Summary Metadata Content - Click links below for full description
[Project](#Project) |
[Contact](#Contact) |
[Pilot in Command](#Pilot-in-Command) |
[Location description](#Location-description) |
[Location identifier](#Location-identifier) |
[Start date](#Start-date) |
[End date](#End-date) |
[Total number of flights](#Total-number-of-flights) |
[Average flight time](#Average-flight-time) |
[Total flight time](#Total-flight-time) |
[Permits and waivers](#Permits-and-waivers) |
[Base station](#Base-station) |
[Geospatial reference](#Geospatial-reference) |

### Project
|**Variable Name**|project|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|controlled list (ESS-DIVE) or free text|
|**Description**|Project name|
|**Example**|Next-Generation Ecosystem Experiments (NGEE) Tropics|

### Contact
|**Variable Name**|contact|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|free text|
|**Description**|List the person who should be contacted by users seeking further information for the data. Only one contact is allowed. Including the ORCID of this individual is strongly encouraged.|
|**Example**|First name, Last name, Organization, Email, ORCID|

### Pilot in Command
|**Variable Name**|pilot|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`recommended`|
|**Unit or format**|free text|
|**Description**|List the name and contact details of the Pilot in Command (PIC). Include FAA pilot license number if applicable.|
|**Example**|First name, Last name, Organization, Email, FAA license number|

### Location description
|**Variable Name**|location_description|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|free text|
|**Description**|Geographic place name, including Place, State, Country|
|**Example**|Seward Peninsula, AK, USA|

### Location identifier
|**Variable Name**|location_id|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|free text|
|**Description**|Identifiers of any sites or plots within flight area|
|**Example**|Plot 4, Intensive site 1|

### Start date
|**Variable Name**|date_start|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|yyyy-mm-dd|
|**Description**|Date of first flight in data package|
|**Example**|2022-02-02|

### End Date
|**Variable Name**|date_end|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|yyyy-mm-dd|
|**Description**|Date of last flight in data package|
|**Example**|2022-02-04|

### Total number of flights
|**Variable Name**|num_flights|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|integer|
|**Description**|Total number of flights for which data included|
|**Example**|5|

### Average flight time
|**Variable Name**|flight_time_avg|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|minutes|
|**Description**|Average flight time of missions|
|**Example**|21|

### Total flight time
|**Variable Name**|flight_time_total|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`optional`|
|**Unit or format**|minutes|
|**Description**|Total flight time of missions (alternative to using numFlights and flightTimeAvg)|
|**Example**|600|

### Permits and waivers
|**Variable Name**|permits|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`recommended`|
|**Unit or format**|free text|
|**Description**|List land permits, waivers and Certificates of Waiver or Authorization (COA). Can include documents in the data package.|
|**Example**|permit.pdf|

### Base station
|**Variable Name**|base_station|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`recommended`|
|**Unit or format**|free text|
|**Description**|Base station GPS coordinates, model and type of GNSS data collected. Self-deployed vs CORS network station. If CORS record ID of CORS station(s) (e.g. AB11) and provide raw base station data in data submission.|
|**Example**|Lat 70.123456 Lon -100.123456; Emlid RS2 collecting GPS, Beidou, Galileo and GLONASS data; CORS:AB11|

### Geospatial reference
|**Variable Name**|geo_ref|
|:----------------------------------------------------|:----------------------------------------------------|
|**Requirement level**|`required`|
|**Unit or format**|free text|
|**Description**|Geospatial reference system used|
|**Example**|WGS 84|
