# Chicago-Crime-Data
## Subtitle describing the analysis 

**Author**: Sami Imran

### Business problem:

Study and answer some stakeholders question's about crimes that happend in chicago from 2001-2023

### Data:
[Data Source ](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data). Below data dictionary:

| **Variable Name**                                | **Description**              |**Data Type**|
| :---:                           |        :---    |               :---: |
| `ID`               | Unique identifier for the record.           | `Number`|
| `Date`                   | 	Date when the incident occurred. this is sometimes a best estimate.|  `datetime` |
| `Primary Type`              | The primary description of the IUCR code.| `Text` |
| `Description`               | 	The secondary description of the IUCR code, a subcategory of the primary description.| `Text`|
| `Location Description`   | Description of the location where the incident occurred.                                                          | `Text` |
| `Arrest`                      | Indicates whether an arrest was made.                                              | `bool` |
| `Domestic`             |Indicates whether the incident was domestic-related as defined by the Illinois Domestic Violence Act.       | `bool` |
| `Beat`     |Indicates the beat where the incident occurred. A beat is the smallest police geographic area – each beat has a dedicated police beat car. Three to five beats make up a police sector, and three sectors make up a police district. The Chicago Police Department has 22 police districts. See the beats at https://data.cityofchicago.org/d/aerh-rz74.| `Text`|
| `District`                   | 	Indicates the police district where the incident occurred.                                            | `Text`|
| `Ward`          | The ward (City Council district) where the incident occurred. See the wards at https://data.cityofchicago.org/d/sp34-6z76.| `Number`|
| `Latitude`          | The latitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block| `Number`|
| `Longitude`          |The longitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.| `Number`|
