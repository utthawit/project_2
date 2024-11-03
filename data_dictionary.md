### Data Dictionary

#### Housing Dataset

Here is the table of data dictionary:

| Column                    | Data Type     | Description                                                                       |
|---------------------------|---------------|-----------------------------------------------------------------------------------|
| id                        | int           | ID of selling item                                                                |
| province                  | string        | province name: this dataset only includes Bangkok, Samut Prakan and Nonthaburi    |
| district                  | string        | district name                                                                     |
| subdistrict               | string        | subdtistrict name                                                                 |
| address                   | string        | address e.g. street name, area name, soi number                                   |
| property_type             | string        | type of the house: Condo, Townhouse, or Detached House                            |
| total_units               | float         | the number of rooms/houses that the condo/village has                             |
| bedrooms                  | int           | the number of bedrooms                                                            |
| baths                     | int           | the number of baths                                                               |
| floor_area                | float         | total area of inside floor                                                        |
| floor_level               | int           | floor level of the room                                                           |
| land_area                 | float         | total area of the land                                                            |
| latitude                  | float         | latitude of the house                                                             |
| longitude                 | float         | longitude of the house                                                            |
| nearby_stations           | int           | the number of nearby stations (within 1km)                                        |
| nearby_station_distance   | list          | list of (station name, distance[m]).                                              |
| nearby_bus_stops          | int           | the number of nearby bus stops                                                    |
| nearby_supermarkets       | int           | the number of nearby supermarkets                                                 |
| nearby_shops              | int           | the number of nearby shops                                                        |
| year_built                | int           | year built                                                                        |
| month_built               | string        | month built: January-December                                                     |
| price                     | float         | selling price                                                                     |

---

#### 7-Elevent Dataset

Here is the table of data dictionary:

| Column                    | Data Type     | Description                                                                       |
|---------------------------|---------------|-----------------------------------------------------------------------------------|
| store_code                | int           | ID of store                                                                       |
| district_en               | string        | district name                                                                     |
| sub_district_en           | string        | subdistrict name                                                                  |
| province_en               | string        | province name: this dataset only includes Bangkok                                 |
| latitude                  | float         | latitude of the store                                                             |
| longitude                 | float         | latitude of the store                                                             |

---
