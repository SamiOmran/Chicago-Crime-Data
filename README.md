# Chicago-Crime-Data
## Subtitle describing the analysis 

**Author**: Sami Imran

### Business problem:

Study and answer some stakeholders question's about crimes that happend in chicago from 2001-2023

### Data:
[Data Source ](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data). Below data dictionary:

| **Variable Name**               | **Description**                                                                                    |
| :---:                           |    :---                                                                                            |
| `ID`               | Unique identifier for the record.                                                                                         |
| `Date`                   | 	Date when the incident occurred. this is sometimes a best estimate.                                                                     |
| `Primary Type`              | The primary description of the IUCR code.                                                          |
| `Description`               | 	The secondary description of the IUCR code, a subcategory of the primary description.|
| `Location Description`   | Description of the location where the incident occurred.                                                          |
| `Arrest`                      | Indicates whether an arrest was made.                                              |
| `Domestic`             |Indicates whether the incident was domestic-related as defined by the Illinois Domestic Violence Act.       |
| `Beat`     |Indicates the beat where the incident occurred. A beat is the smallest police geographic area – each beat has a dedicated police beat car. Three to five beats make up a police sector, and three sectors make up a police district. The Chicago Police Department has 22 police districts. See the beats at https://data.cityofchicago.org/d/aerh-rz74.|
| `District`                   | 	Indicates the police district where the incident occurred.                                            |
| `Ward`          | The ward (City Council district) where the incident occurred. See the wards at https://data.cityofchicago.org/d/sp34-6z76.                                                    |
| `Outlet_Type`                   | Whether the outlet is a grocery store or some sort of supermarket                                  |
| `Item_Outlet_Sales`             | Sales of the product in the particular store. This is the target variable to be predicted.         |
